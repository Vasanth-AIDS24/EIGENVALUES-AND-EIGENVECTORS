# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : imort numpy as np
### Step 2: give input in te array format
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the eigen values and eigen vectors of the matix

## Program:
```
developed by:Vasanth P
registerationNumber:24900136
import numpy as np
A=np.array([[2,2],[1,3]])
result1,result2=np.linalg.eig(A)
print(f"Eigen values are {result1} and Eigen Vectors are {result2}")
```

## Output:
![Screenshot from 2024-12-02 20-26-02](https://github.com/user-attachments/assets/637e7bdc-268a-4978-a589-58c8f0b0ec42)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
