# List.  
- List is a collection which is ordered and changeable.   
- In Python lists are written with square brackets.   
- List is used to store multiple items in a single variable.
- It can have many data types like int, float, string etc.  
Example for the List :

``` py
num = [25,12,32,45,3,43]
# print is used to print the num values 
print(num)
# Output : [25,12,32,45,3,43]
# it can be also print the values using the index value staring for 0,1,2,3,4......
#from top number we want 32 the index of 32 is 2 . Then we print the value by using
print(num[2])
# Output : 32
# If we want to print some numbers for example 32,45,3,43 by using index value
print(num[2:])
# Output : [32,45,3,43]

#- We have some lists like append,remove,insert,etc 

# Append
# Append is use to add element in the last of the list 
num.append(49)
print(num)
# Output :[25, 12, 32, 45, 3, 43, 49]

# INSERT
# Insert is use to add element in where ever you what we can insert the element 
num.insert(2,52)
# In insert we have two values : First one is index value and second is the the element that we want to insert 
print(num)
# Output :[25, 12, 52, 32, 45, 3, 43]

# REMOVE
# Remove is use to remove the element from the list 
num.remove(32)
print(num)
# Output : [25, 12, 52, 45, 3, 43]

# POP
# Pop is use to remove element using index number from the list 
num.pop(2)
print(num)
# Output: [25, 12, 32, 45, 43]

# Extend
# extend is use to add elements in the list 
# the elements which we are going to add that elements must be in the square brackets only.
num.extend([21,39,46])
print(num)
# Output : [25, 12, 32, 45, 3, 43, 21, 39, 46]

# Sort 
# sort is use to sort the elemnets in the list from low to high. 
num.sort()
print(num)
# Output : [3, 12, 25, 32, 43, 45]

# Minimum is use to show the minimum value in the list. 
min_num = min(num)
print(min_num)
# Output : 3
# MAX is use to show the maximum Value in the list 
max_num = max(num)
print(max_num)
# Output : 45
# Sum is use to Add all the elements in the list 
sum_num = sum(num)
print(sum_num)
# Output : 160





```


