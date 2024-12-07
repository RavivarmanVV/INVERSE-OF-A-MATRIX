# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
### Step 4: 

## Program:
    #Program to find the inverse of a matrix.
    #Developed by: RavivarmanVV
    #RegisterNumber:24006127
    import numpy as np
    A = np.array([[1, 0, 3],
                  [-1, 2, -2],
                  [2, 3, -1]])
    try:
        A_inv = np.linalg.inv(A)
        
        print(A_inv)
    except np.linalg.LinAlgError:
        print("The matrix is singular and cannot be inverted.")
## Output:
![image](https://github.com/user-attachments/assets/1354159b-7f0d-40ea-92d9-1d4b0ddff151)

## Result:
Thus the inverse of given matrix is successfully solved using python program

