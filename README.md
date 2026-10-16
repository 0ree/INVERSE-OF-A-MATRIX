# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
### Step 2: 

import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
### Step 3:

r=np.linalg.inv(A)

### Step 4: 

print(r)

## Program:
<img width="1282" height="853" alt="image" src="https://github.com/user-attachments/assets/067f0485-252b-4571-abb2-aac4766fb4f3" />

## Output:
<img width="1242" height="202" alt="image" src="https://github.com/user-attachments/assets/cadd5a39-aff0-480a-a1c3-af1d279ff1f4" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

