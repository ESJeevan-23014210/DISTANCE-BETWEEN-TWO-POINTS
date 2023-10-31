# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Start the program
### Step 2: 
Import the math module to use the built-in functions for calculation
### Step 3: 
 Represent the values as x1,y1,x2,y2
### Step 4: 
Substitute the values in the distance formula ![formula](/formula.JPG)
### Step 5: 
End the program
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: Jeevan E S 
#RegisterNumber: 23014210
import math
x_1,y_1=4,2
x_2,y_2=10,6
d=math.sqrt((x_2-x_1)**2+(y_2-y_1)**2)
print(f"{d:.2f}")
```


### OUTPUT:
![output](/distanceoutput.png)

### RESULT:
Thus distance between two points are calculated successfully using python program