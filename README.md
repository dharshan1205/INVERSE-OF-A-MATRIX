# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Create an augmented matrix by placing an $n \times n$ Identity matrix (1s on the diagonal, 0s elsewhere) to the right of your original matrix.for Gauss-Jordan elimination]
### Step 2: Select the first row and divide the entire row by its first element (the pivot) so that the first number becomes 1.
### Step 3: For all other rows, subtract a multiple of that first row from them so that every other number in the first column becomes 0.
### Step 4: Move to the next diagonal element (the second row, second column) and repeat Steps 2 and 3 until every diagonal element is 1 and all other elements in their columns are 0.
### Step 5: Once the left side of your augmented matrix is the Identity matrix, the right side is your Inverse.

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

