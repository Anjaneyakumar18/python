15. Use a list comprehension to square each odd number in a list. The list is 
input by a sequence of comma-separated numbers. Suppose the following 
input is supplied to the program:
1,2,3,4,5,6,7,8,9
Then, the output should be:
1,9,25,49,81


seq = input().split(',') 
lst = [int(i) for i in seq]
def flt(i):                                           
    return i % 2 != 0
result_l = [str(i * i) for i in filter(flt,lst)]      
print(",".join(result_l))
