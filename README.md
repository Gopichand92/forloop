# forloop
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
