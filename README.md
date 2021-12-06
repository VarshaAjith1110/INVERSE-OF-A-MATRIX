# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
importing numpy as np
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_inverse(), we can find the inverse of the given matrix
### Step 4: 
End program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Varsha Ajith
#RegisterNumber:21500246
import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
ans=np.linalg.inv(A)
print(ans)
```
## Output:
![output](.//m2.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

