# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

### Step 1: Start the program
### Step 2:  Initialise the values in the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: slice the number of values required
### Step 6:  Then paste it at the back to circulate
## Program:
```
def circulate():
    lst = eval(input())
    n = int(input())

    result = lst[n:] + lst[:n]

    print("After circulating the values are:", result)
```
## Output:
<img width="1262" height="474" alt="image" src="https://github.com/user-attachments/assets/2fc4d31c-f726-43a6-a342-197cf44ee491" />

## Result:
