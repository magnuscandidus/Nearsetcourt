# cook your dish here
t=int(input())
while t:
    x,y=map(int,input().split())
    z=(x+y)//2
    value=max(abs(x-z),abs(y-z))
    print(value)
    t-=1
