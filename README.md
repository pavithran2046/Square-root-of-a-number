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
``` python
#Program to find the square root for the given number(newton's method)
#developed by:s.pavithran
#register number:23001643
x=int(input())
aprox=0.5*x
for i in range(1,10):
    b=0.5*(aprox+x/aprox)
    aprox=b
print("Square root of the number:",b) 
```

## Output:
![gcd of two number](/Screenshot%202023-07-26%20092104.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
