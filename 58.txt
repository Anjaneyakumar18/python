Write a function to compute 5/0 and use try/except to catch the exceptions.

def divide():
    return 5/0

try:
    divide()
except ZeroDivisionError as ze:
    print(" you are dividing a number by ZERO!!")
except:
    print("Any other exception")
