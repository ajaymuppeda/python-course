# Dictionary
Dictionary is a collection of key-value pairs.
Dictionary are enclosed in curly braces {}. 
Dictionary keys are unique and immutable.

# Example of Dictionary
```py

data = {"Name": "Ajay", "Age": 25, "Gender": "Male"}

print(data)
# Output : {'Name': 'Ajay', 'Age': 25, 'Gender': 'Male'}

print(data["Name"])
# The data["Name"] will only print the name of the person like
# Output : Ajay 
print(data.get("Name"))
# Get is also same like above fucntion it will only show the name. 

print(data.get("City"))
# If we enter the "City" in the place of "Name" then it will show none. 
print(data.get("City", "Not Found"))
# It will print the "Not found " because it's fixed the key word as Not Found 
# For example when we open a site if it is not there then instard for showing blanck it will show "Not Found"
# Output : Not Found

Names = ['Ajay','Anvesh','Muppeda']
Age = ['20','28','Family']
data = dict(zip(Names,Age))
print(data)

# Output : {'Ajay': '20', 'Anvesh': '28', 'Muppeda': 'Family'}
#   dict is  a fuction used to join two data are any thing from the above we know that "Ajay" age is "20" and "Anvesh" age is "28" 

print(data["Ajay"])

# Output : 20 


```