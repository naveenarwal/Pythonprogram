Program to find the factorial of any number in python

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
num = int(input("Enter a number to find its factorial: "))
print("Factorial of", num, "is", factorial(num))
