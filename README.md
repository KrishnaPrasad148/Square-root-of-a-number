# Find the square root of a number

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

Developed by: Krishna Prasad.S
RegisterNumber: 212223230108
```
```
b = int(input("Enter the number : "))
x = b
while (1):
    root = 0.5 * (x + (b / x))
    if (abs(root - x) < 0.00000001):
        break
    x = root
print("Square root of the number:",root)
```

## Output:
![Screenshot 2024-05-08 064042](https://github.com/KrishnaPrasad148/Square-root-of-a-number/assets/147332763/41c773e1-38bf-47b4-99a1-07ab0a4e7de2)




## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
