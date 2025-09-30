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
```Python
# Register No: 212224230009
# Developed By: AHAMADH SULAIMAN M
# 1-Norm of a Matrix


import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,1)
print("{:2f}".format(norm))


# 2-Norm of a Matrix


import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix


import numpy as np
matrix = eval(input())
arr = np.array(matrix)
norm = np.linalg.norm(arr,np.inf)
print("{:2f}".format(norm))


```
## Output:
### 1-Norm of a Matrix


<img width="1220" height="345" alt="image" src="https://github.com/user-attachments/assets/6709d6b3-adbe-458e-8749-568abab69133" />


### 2-Norm of a Matrix


<img width="1231" height="392" alt="image" src="https://github.com/user-attachments/assets/6be34c83-7faf-4f3d-8a7a-b9fdf53f01de" />


### Infinity Norm of a Matrix


<img width="1240" height="347" alt="image" src="https://github.com/user-attachments/assets/65234727-e198-42f0-a8ab-20a2f4b5dff3" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
