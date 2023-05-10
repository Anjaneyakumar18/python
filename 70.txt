The Fibonacci Sequence is computed based on the following formula:

f(n)=0 if n=0
f(n)=1 if n=1
f(n)=f(n-1)+f(n-2) if n>1


def f(n):
    if n < 2:
        fibo[n] = n
        return fibo[n]
    fibo[n] = f(n-1) + f(n-2)
    return fibo[n]

n = int(input())
fibo = [0]*(n+1)  # initialize a list of size (n+1)
f(n)              # call once and it will set value to fibo[0-n]
fibo = [str(i) for i in fibo]   # converting integer data to string type
ans = ",".join(fibo)    # joining all string element of fibo with ',' character
print(ans)
