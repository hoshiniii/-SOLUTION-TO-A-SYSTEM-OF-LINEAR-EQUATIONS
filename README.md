# EXP 1 -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
## DATE: 02.03.2024
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#write a program to find the solution to a system of linear equations 5x-3y-10z=-9,2x+2y-3z=4,-3x+y+5z=-1

#prgram to find the solution for the given equation 
#devoleped by : HOSHINI S
#registerNumber:2305003006

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
b=np.array([-9,4,-1])
le=np.linalg.solve(a,b)
print("the solution for the given matrix is",le)
```
## Output:
![WhatsApp Image 2024-04-12 at 22 16 20](https://github.com/hoshiniii/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/166852545/dc4334e9-e0aa-4f94-aeb0-f5e3a68dc3d1)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

