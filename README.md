# ratation
n=int(input())
while n:
    if n%2==0:
        n=n//2
    elif n%2!=0:
        n=3*n+1
    if n==1:
        break
    print(n)

