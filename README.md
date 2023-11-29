# Find the square root of a number
NAME: SHYAM S
REF.NO: 23012478
## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: SHYAM S
RegisterNumber: 23012478
def sqr_root():
    x=int(input())
    y=int(x)
    for i in range(100):
        x=0.5*(x+y/x)
    print("Square root of the number:",x)
sqr_root()
```

## Output:
![Alt text](<Screenshot 2023-11-29 141704.png>)

![Alt text](<Screenshot 2023-11-29 141037.png>)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
