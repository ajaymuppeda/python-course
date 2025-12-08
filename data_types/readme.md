# Data Types 


Data types are used to define the type of data that a variable can hold.
Common data types in Python include:
Integers (int): Whole numbers without a decimal point.
Floating-point numbers (float): Numbers with a decimal point.
Strings (str): Sequence of characters enclosed in quotes.
Lists (list): Ordered collection of items enclosed in square brackets [].
Tuples (tuple): Ordered collection of items enclosed in parentheses ().
Dictionaries (dict): Collection of key-value pairs enclosed in curly braces {}.
Booleans (bool): Represents either True or False values.

We Are have some more data types in Python are

- None
- Numeric
- List
- Tuples
- Sets
- String
- Range
- Dictionaries

Now we going to expalin one by one 
### 1. None 
None is a special data type in Python that represents the absence of a value or a null value.
It is often used to indicate that a variable has no value assigned to it or to signify the end of a function that
does not return anything.

### Example of None data type
```py
x = None
if x is None:
    print("x has no value assigned to it")      

```

### 2. Numeric
Numerice are muliple type now we are going to study about 4 types. 
1. int 
2. Float
3. Complex
4. bool

```py 
# Float 
num = 2.5
print(type(num))

# Int 

num = 2
print(type(num))

# Complex
num = 2+6j
print(type(num))


# Float to int

a = 5.6 
b = int(a)
print(type(b))
print (b)

k = 6
c = complex(b,k)
print(c)

# Boolen 

k = 6
b = 5
print(k>b)
#output True

print(k<b)
# Output False

# Range 

print(range(10))
# Output: range(0,10)
print(list(range(10)))
# Output : [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]




