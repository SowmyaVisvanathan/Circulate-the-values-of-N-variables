# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Get the values to be circulated from the user
### Step 2: 
Get the value from the user for the number of rotation
### Step 3: 
Using the slicing concept rotate the list
### Step 4: 
Print the circulated values using print statement
### Step 5: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: SOWMYA V
#RegisterNumber:22005551
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![output](/res1.png)

## Result:
Thus the program to circulate values of n variables is successfully executed
