# Min
#To find the minimum of three numbers:
n1=int(input("Enter num1:"))
n2=int(input("Enter num2:"))
n3=int(input("Enter num3:"))
if n1<n3 and n1<n2:
    print(n1,"is minimum")
elif n2<n1 and n2<n3:
    print(n2,"is minimum")
else:
    print(n3,"is minimum")
