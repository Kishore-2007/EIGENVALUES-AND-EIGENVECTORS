# EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors


## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner


## Algorithm:
### Step1 : import numpy library
### Step 2: numpy array has been declared using a 3 x 3 matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:

```python
#Program to find the eigen values and eigen vectors.
#Developed by: KISHORE.S
#RegisterNumber: 24900594

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```

## Output:

![Screenshot 2024-12-04 112541](https://github.com/user-attachments/assets/904665ae-8002-4357-b9b1-b4394e6fed0f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
