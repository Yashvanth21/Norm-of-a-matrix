# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```
Python
# Register No: Yashvanth K
# Developed By: 23011613
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-01-02 172143](https://github.com/Yashvanth21/Norm-of-a-matrix/assets/144979957/9d1f8576-a805-4876-9b37-2044d051f5c6)

### 2-Norm of a Matrix
![Screenshot 2024-01-02 172217](https://github.com/Yashvanth21/Norm-of-a-matrix/assets/144979957/3cac77e6-e1ba-453a-9259-d83b79bcf16a)


### Infinity Norm of a Matrix
![Screenshot 2024-01-02 172259](https://github.com/Yashvanth21/Norm-of-a-matrix/assets/144979957/a5491970-1298-4f9f-922c-487b0c63b4b8)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
