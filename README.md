# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :import the numpy module to use the bulit-in-functionsfor calculation
Step 2:prepare the lists from each linear equations and assign in np.array()
Step 3:Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Step 4:End the program
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
![alt text](<Screenshot 2024-12-26 133928-1.png>)
![alt text](<Screenshot 2024-12-26 133940.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
