# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy library: import numpy as np
### Step 2:
Create a 3x3 numpy array A with the given values: A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Print the values of evalues and evector using the print() function: print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: HARISH RAGAV S
#RegisterNumber: 212222110013

import numpy as np
A= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues , evector = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```


## Output:
![image](https://user-images.githubusercontent.com/119345345/226253885-41f03dbd-c08f-485e-8baa-d5f093cc3cd7.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
