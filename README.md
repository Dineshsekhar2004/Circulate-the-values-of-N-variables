# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
import numpy 
### Step 2: 
assign the values
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the values
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: s.dinesh
#RegisterNumber:212222230033
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)

```
## Output:
![Screenshot from 2023-03-22 09-46-17](https://user-images.githubusercontent.com/119405916/226801479-b733482e-89f0-434f-9f3a-f3b4f5fb7ed4.png)
## Result:
The program is executed sucessfully!
