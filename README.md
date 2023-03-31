# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner.

## Algorithm:
### Step1 : Import numpy as np
### Step 2: Assign in np.array() in eigen values and eigen vectors of matrix.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the Program.

## Program:
```
import numpy as np
A=np.array([[2,2],[1,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:
![Screenshot (110)](https://user-images.githubusercontent.com/107488929/229110242-34f04896-a44f-421b-86e7-fb70ce5d7ae0.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
