# Pset 0
#### A Very Simple Program: Raising a number to a power and taking a logarithm

Write a program that does the following in order:

1. Asks the user to enter a number “x”
2. Asks the user to enter a number “y”
3. Prints out number “x”, raised to the power “y”.
4. Prints out the log (base 2) of “x”.

```python
import numpy  

x = int(input("Enter number x: "))
y = int(input("Enter number y: "))
  
power = x**y
log_base2 = numpy.log2(x) 

print("x**y =", power)
print("log(x) =", log_base2)
```