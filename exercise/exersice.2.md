# Exersice 2

### Prime Number or Odd number
```py
import math


def is_prime(number):
    if number <= 1:
        return False  
    if number == 2:
        return True   
    if number % 2 == 0:
        return False  

    limit = int(math.sqrt(number)) + 1
    for i in range(3, limit, 2):
        if number % i == 0:
            return False
    return True


while True:
    value = input("Enter a integer to check if it's prime: ")
    try:
        num = int(value)
        if num <= 0:
            print("Enter a integer greater than zero.")
            continue
        break
    except ValueError:
        print("Invalid input. Please enter a valid integer.")


if is_prime(num):
    print(f"{num} is a prime number.")
else:
    print(f"{num} is not a prime number.")





```