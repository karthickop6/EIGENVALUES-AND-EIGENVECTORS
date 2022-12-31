# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1:
 import numpy as np 

### Step 2: 
arrange the given matrix in np.array command
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
run the program and get the output
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Karthick p
#RegisterNumber:22000995
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```

## Output:

![0utput](./Screenshot%202022-12-31%20at%2020-58-16%20Exp%2004%20-%20Eigen%20values%20and%20Eigen%20vectors%20Attempt%20review.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
