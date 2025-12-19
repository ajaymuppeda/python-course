# Exercise 1
 
```py
# Nested Loop

for i in range(4):
    for j in range(4-i):
        print("#",end="")

    print()

# Output:
# # # # 
# # # 
# # 
# 


# If we want in reverse order we have use 

for i in range(4):
    for j in range(i+1):
        print("#",end=" ")

    print()
# Output:
#
# #
# # #
# # # #


for i in range(4):
    for j in range(4):
        print("#",end=" ")
    
    print()
# Output:
# # # # 
# # # # 
# # # # 
# # # # 


```
