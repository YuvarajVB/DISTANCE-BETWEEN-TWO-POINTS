# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import the math module using import math.
### Step 2: 
Assign values to variables x1, y1, x2, and y2 representing coordinates.
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Print the calculated distance with two decimal places using print("{:.2f}".format(d))

## PROGRAM:
```
#Program to find the distance between two points.
#Developed by: yuvaraj.v
#RegisterNumber:23013769
import math
x1=10
y1=6
x2=4
y2=2
d=math.sqrt((x2-x1)**2+(y2-y1)**2)
print("{:.2f}".format(d))

```  


## OUTPUT:

![output](/distance.png)

### RESULT:
Thus finding the distance between two points is successfully executed
