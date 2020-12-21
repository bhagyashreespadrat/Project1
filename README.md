# Project1
#Simple Calculator Program
# Label program
# author:Bhagyashree
# Location:Pune
# Date:14/11/2020
#Simple calculator game in python
# menus

print("Calculator")
print("1.Add")
print("2.Substract")
print("3.Multiply")
print("4.Divide")

# input choice
ch=int(input("Enter Choice(1-4): "))

if ch==1:
    a=int(input("Enter A:"))
    b=int(input("Enter B:"))
    c=a+b
    print("Sum = ",c)
elif ch==2:
    a=int(input("Enter A:"))
    b=int(input("Enter B:"))
    c=a-b
    print("Difference = ",c)
elif  ch==3:
    a=int(input("Enter A:"))
    b=int(input("Enter B:"))
    c=a*b
    print("Product = ",c)
elif ch==4:
    a=int(input("Enter A:"))
    b=int(input("Enter B:"))
    c=a/b
    print("Quotient = ",c)
else:
    print("Invalid Choice")

'''#OUTPUT:
Calculator
1.Add
2.Substract
3.Multiply
4.Divide
Enter Choice(1-4): 1
Enter A:10
Enter B:20
Sum =  30
Enter Choice(1-4): 2
Enter A:40
Enter B:29
Difference =  11
Enter Choice(1-4): 3
Enter A:12
Enter B:14
Product =  168
Enter Choice(1-4): 4
Enter A:12
Enter B:4
Quotient =  3.0

'''
