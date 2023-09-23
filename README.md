# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step1 : 
import numpy as np.
### Step 2: 
Assign np.array() in eigen values and eigen vectors.
### Step 3: 
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors,then end the program.

## Program:
```py
#Program to find the eigen values and eigen vectors.
#Developed by: SUBALAKSHMI.S
#RegisterNumber: 212222100051
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:

![Screenshot (126)](https://github.com/Subalakshmisuresh/EIGENVALUES-AND-EIGENVECTORS/assets/121957896/ea8b387e-b5e7-4b84-bb52-64400b5b0216)


## Result:
Thus,the Eigenvalue and Eigenvector is successfully solved using python program.
