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
Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: 
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:gowtham u 
#RegisterNumber:212225040099
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
x=np.linalg.inv(a)
print(x)
```
## Output:
<img width="936" height="197" alt="image" src="https://github.com/user-attachments/assets/f64abdc3-236e-48df-860a-5809fa1b4ed4" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

