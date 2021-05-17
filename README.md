# Factorial-n

p=100001
 s=[0]*p
def fact():
 s[0]=1

 po=(10**9)+7

for i in range(1,p):

 s[i]=(s[i-1]*i)%po


 

 fact()
t=int(input())

 for i in range(0,t):

inp=int(input())

 print(s[inp])
