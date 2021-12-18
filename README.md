# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
~~~
Program to find the gcd of two number using function.
Developed by:G.Pavithra
RegisterNumber:21500148
```
def GCD(x,y):
    rem = x%y
    if (rem == 0):
        return y
    else:
        return GCD(y,rem)
        
n=int(input())
m=int(input())
print("The GCD of number is", GCD(n,m))
~~~
## Output:
![Github logo](gcdpython.png)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
