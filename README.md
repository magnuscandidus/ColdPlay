# ColdPlay
# cook your dish here
t=int(input())
while t:
    m,s=map(int,input().split())
    if(m>=s):
        print(m//s)
    else:
        print("0")
    t-=1
