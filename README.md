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
Using the np.linalg.solve(),we can find the solution

### Step 4: 
End the program

## Program:
```
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
result=np.linalg.inv(A)
print(result)``

```
## Output:
![Screenshot from 2022-12-28 09-52-48](https://user-images.githubusercontent.com/120550359/209757012-d7f40445-2f17-4724-85e4-3d3d7379ca01.png)


## Result:
Thus the inverse of given matrix is successfully solved using python program

