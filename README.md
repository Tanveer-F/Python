# Python
Python common Errors
A collection of common Python errors and their solutions, aimed at helping developers quickly identify and resolve issues in their code.

print("hello") # SyntaxError.

x = int("hello") # ValueError.


var = "name"

y = 10

print(var/y) # TypeError.


a = int(input("Enter first number:"))
b = int(input("Enter second number:"))
c = a/b

print("result", c) # 40/0 ZeroDivisionError.

a = 12
print(b) # NameError.

x = [1, 2, 3]
print(x[4]) # IndexError.

x = {1: "b" , 2: "c"}
print(x[3]) # KeyError.


with open ("file.txt", "r") as f:
    book = f.read()
    print(book) # FileNotFoundError.
