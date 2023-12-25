# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Define a function.
## Step 2:
Assign number_iters = 100 in the function to perform 100 iteratios.
## Step 3:
 Set i = 0.
## Step 4:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
## Step 5:
Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: Priyadharshini.P
RegisterNumber: 23013604

def square_root_newton_method(number):
    x=number/2.0
    while True:
        new_x=0.5*(x+number/x)
        if abs(new_x-x)<1e-10:
            return new_x
        x=new_x
input_number=float(input())
result=square_root_newton_method(input_number)
print(f"Square root of the number: {result}")
```

## Output:
![image](https://github.com/priyadharshini210/Square-root-of-a-number/assets/148514638/17c935d3-63da-41d1-bd17-a20e63b7fd95)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
