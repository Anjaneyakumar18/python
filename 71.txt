Please write a program using generator to print the even numbers between 0 and n in comma separated form while n is input by console.

Example: If the following n is given as input to the program:


n = int(input())
for i in range(0, n+1, 2):
  if i < n - 1:
    print(i, end = ',' )
  else:
    print(i)
