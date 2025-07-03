num=int(input("enter the number"))
temp=num
sum=0
while temp>0:
    digit=temp%10
    sum+=digit
    temp//=10
print("latest value of sum",sum)
print("latest value of temp",temp)
if num%sum==0:
    print(num,"is nivens number")
else:
    print(num,"is not nivens number")
