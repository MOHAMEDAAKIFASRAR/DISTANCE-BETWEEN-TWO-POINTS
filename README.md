# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Clone the repository from github
### Step 2: 
Assign the function command in the program
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
print the round(d,2)
### Step 5: 
End the program
### PROGRAM:
  
```
#Program to find the distance between two points.
#Developed by: Mohamed Aakif Asrar S
#RegisterNumber:23003613

import math
def distance(x1,y1,x2,y2):
    dx=x2-x1
    dy=y2-y1
    d=math.sqrt(dx**2+dy**2)
    return d
x1=4
y1=2
x2=10
y2=6
d=distance(x1,y1,x2,y2)
print(round(d,2))


```


### OUTPUT:

![Screenshot 2024-01-05 094711](https://github.com/MOHAMEDAAKIFASRAR/DISTANCE-BETWEEN-TWO-POINTS/assets/148514683/f01768a8-32ba-4c0a-b3ee-b9ecd614db80)

### RESULT:

Thus the distance between two points is completed successfully
