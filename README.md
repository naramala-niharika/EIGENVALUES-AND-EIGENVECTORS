# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
start the program
### Step 2: 
import numpy as np and insert values
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
#Program to find the eigen values and eigen vectors.

#Developed by:N.Niharika

#RegisterNumber:21500912

import numpy as np

A=np.array([[2,2],[1,3]])

values,vectors = np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
![output](https://github.com/naramala-niharika/EIGENVALUES-AND-EIGENVECTORS/blob/main/Screenshot%20(26).png?raw=true)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
