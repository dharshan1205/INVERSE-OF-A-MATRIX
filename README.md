# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: End the program

## Program:
```
import numpy as np
A = np.array([
    [1, 0, 3],
    [-1, 2, -2],
    [2, 3, -1]
])

A_inv = np.linalg.inv(A)

print(A_inv)
```

## Output:
<img width="1290" height="901" alt="image" src="https://github.com/user-attachments/assets/0f13ab96-77eb-4a38-902a-3fad4e0580d9" />
<img width="1293" height="338" alt="image" src="https://github.com/user-attachments/assets/56d8d0f8-c853-4e3f-95ac-80c701f37fe1" />
## Result:
Thus the inverse of given matrix is successfully solved using python program

