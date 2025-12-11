# Variables

A variable is a named location used to store data in the memory.
Variables are created when you assign a value to them.
variables can hold different data types such as integers, floats, strings, lists, etc.
Variables are case-sensitive and must start with a letter or an underscore.
Variable names should be descriptive and follow naming conventions.
Variables can be reassigned to different values or data types.
Variables can be used in expressions and calculations.
Variables can be printed or displayed using the print() function.
Variables can be used as function arguments and return values.
Variables can be global or local in scope.


# Example of Variables

```py
x = 10
y = 5
sum = x + y
print("The sum of", x, "and", y, "is", sum)


# Print will print the The sum of x and y 
# We can change the values of the x,y

```



### Swap in variables

Swap is a technique used to exchange the values of two variables.
swap are of two types:
1. Using a temporary variable
2. Without using a temporary variable
# Using a temporary variable
```py
a=int(input("Enter first number:")) # a = 2
b=int(input("Enter second number:")) # b = 4
temp=a # if a = 2 in temp a value will 2 only 
a=b. # a will be the b value 
b=temp # b will be the temp value the value of first a will remain
print("After swapping:")        
print("First number:",a) # a  will be 4 
print("Second number:",b) # b will be 2
 
```
# Without using a temporary variable

```py
x=int(input("Enter first number:")) # x = 5
y=int(input("Enter second number:")) # y= 12
x=x+y # x = 5 ; y= 12; now x+y is 17 than x value wll be 17
y=x-y # x =17; y= 12 ; now x-y is 5 than y value will be 5 
x=x-y # x = 17 ; y= 5 ; now x-y is 12 than x value will be 12
print("After swapping:")        
print("First number:",x) # x : 12
print("Second number:",y) # y : 5

```
