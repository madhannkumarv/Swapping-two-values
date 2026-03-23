# Swapping-two-values
## AIM:
To write a python program for swapping of two values
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable 
### Step 3: 
Assign the value of the first variable to the second variable.
### Step 4:  
Assign the value in temporary variable to the first variable
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## PROGRAM:
```
try:
    a = int(input())
    b = int(input())

    temp = a
    a = b
    b = temp

    print("Swapped values are:", a, b)

except EOFError:
    pass
```

## OUTPUT:
<img width="1026" height="487" alt="image" src="https://github.com/user-attachments/assets/be825e30-9a8b-440a-864a-2ffd0e5eaeae" />



## RESULT:
Thus the swapping of two values are successfully executed



