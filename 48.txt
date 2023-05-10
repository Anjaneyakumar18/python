Write a program which can map() to make a list whose elements are square of numbers between 1 and 20 (both included).

def sqr(x):
    return x*x

squaredNumbers = list(map(sqr, range(1,21)))
print (squaredNumbers)