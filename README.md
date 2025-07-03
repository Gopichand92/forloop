# forloop(ARMSTRONG)
num=int(input("Enter number"))
temp=num
n=len(str(num))
sum=0
while temp>0:
    digit=temp%10
    sum+=digit ** n
    temp//=10
    print("Latest value of sum:",sum)
    print("Latest value of temp:",temp)
if sum==num:
    print(num,"is a armtrong number")
else:
    print(temp,"is not a armstrong number")
OUTPUT:
       Enter number 9474
Latest value of sum: 256
Latest value of temp: 947
Latest value of sum: 2657
Latest value of temp: 94
Latest value of sum: 2913
Latest value of temp: 9
Latest value of sum: 9474
Latest value of temp: 0
9474 is a armtrong number
----------------------------------------------------------------------
(NIVENS NUMBER)
num=int(input("Enter number"))
temp=num
n=len(str(num))
sum=0
while temp>0:
    digit=temp%10
    sum+=digit
    temp//=10
print("Latest value of sum:",sum)
print("Latest value of temp:",temp)
if num%sum==0:
    print(num,"is a nivens number")
else:
    print(num,"is not a nivens number")
OUTPUT:
    Enter number 156
Latest value of sum: 12
Latest value of temp: 0
156 is a nivens number
-------------------------------------------------------------------------
 for i in range(10,0,-1):
        print(i, end=',')
  OUTPUT:
      10,9,8,7,6,5,4,3,2,1,
------------------------------------------------------------------------
for i in range(1,11):
    print(f"square of {i} is {i*i}")
OUTPUT:
    square of 1is 1
square of 2is 4
square of 3is 9
square of 4is 16
square of 5is 25
square of 6is 36
square of 7is 49
square of 8is 64
square of 9is 81
square of 10is 100
 --------------------------------------------------------------------- 
 m=int(input("enter a number:"))
for i in range(1,11):
    print(f"{m}*{i}={m*i}")
OUTPUT:
    enter a number: 10
10*1=10
10*2=20
10*3=30
10*4=40
10*5=50
10*6=60
10*7=70
10*8=80
10*9=90
10*10=100
-----------------------------------------------------------------------
num=int(input())
f=1
for i in range(num,0,-1):
    f*=i
print(f"factorial of{num}is{f}")
OUTPUT:
     4
factorial of 4 is 24
-----------------------------------------------------------------------
n=int(input("enter size:"))
for i in range(n):
    for j in range(n):
        print("*",end=" ")
    print()
OUTPUT:
       enter size: 4
* * * * 
* * * * 
* * * * 
* * * * 
-----------------------------------------------------------------------
n=int(input("enter size:"))
for i in range(n):
    for j in range(n):
        if i==0 or i==n-1 or j==0 or j==n-1:
            print("*",end=" ")
        else:
            print(" ",end=" ")
    print()
OUTPUT;
enter size: 5
* * * * * 
*       * 
*       * 
*       * 
* * * * * 
