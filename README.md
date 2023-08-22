# libraray-fine-charging-1
"""
no fine
1-5 0.5
0
5-10 1
10-30 5
>30 membership cancelled
"""
name=input("Enter the name :")
days=int(input("enter the number:"))
if days==0:
  print(name,"good no fine")
elif days>=1 and days<=5:
    print(name,"fine amount:",days*0.5)
elif days>=6 and days<11:
    print(name,"fine amount :",days*1)
elif days>=11 and days<=30:
    print(name,"fine amount :",days*5)
else:
      print(name,"membership cancelled")
