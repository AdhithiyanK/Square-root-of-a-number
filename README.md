# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
~~~
#Program to to find the square root for the given number(newton's method) using function.
#Developed by: Adhithiyan k
#RegisterNumber: 22001999 
def sq(x):
    b=x
    for i in range(10):
        x=0.5*(x+b/x)
    print('Square root of the number: ',end="")
    print(x)    
x=int(input())
sq(x)
~~~

## Output:
![sqrt](
Screenshot_20230122_110836.png )

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
