Define a function which can generate a dictionary where the keys are 
numbers between 1 and 20 (both included) and the values are square of 
keys. The function should just print the keys only.

def printDict():
    dict = {i: i**2 for i in range(1, 21)}
    print(dict.keys())      # print keys of a dictionary

printDict()
