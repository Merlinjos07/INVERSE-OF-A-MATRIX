# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()


### Step 3: 
Using the np.linalg.inv(), we can find the inverse of the given matrix.


### Step 4: 
End the program


## Program:

```


import numpy as np
A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])
try:
    A_inv = np.linalg.inv(A)
    print(A_inv)
except np.linalg.LinAlgError:
    print("The matrix is singular and does not have an inverse.")

```
## Output:


<img width="971" height="793" alt="image" src="https://github.com/user-attachments/assets/3b598947-0da0-4a49-94f4-2d99667b6c2e" />



## Result
:
Thus the inverse of given matrix is successfully solved using python program

