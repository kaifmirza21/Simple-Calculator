'''SIMPLE CALCULATOR'''

ch=input("enter the operator(+,-,*,/,%,!) : ")

if ch=="+":

    n1=int(input("enter the 1st operand : "))
    n2=int(input("enter the 2nd operand : "))
    print("sum of ",n1,"and ",n2," is",n1+n2)

elif ch=="-":
    
    n1=int(input("enter the 1st operand : "))
    n2=int(input("enter the 2nd operand : "))
    print("difference of ",n1,"and",n2,"is",n1-n2)

elif ch=="*":

    n1=int(input("enter the 1st operand : "))
    n2=int(input("enter the 2nd operand : "))
    print("multiplication of ",n1,"and",n2,"is",n1*n2)

elif ch=="/":
    
    n1=int(input("enter the 1st operand : "))
    n2=int(input("enter the 2nd operand : "))
    if n2==0:
        print("error, you cannot divide a number by zero")
    else:
        print("division of ",n1,"by",n2,"is",n1/n2)

elif ch=="%":

    n1=int(input("enter the 1st operand : "))
    n2=int(input("enter the 2nd operand : "))
    if n2==0:
        print("error, you cannot divide a number by zero")
    else:
        print("modulus of",n1,"by",n2,"is",n1%n2)

elif ch=="!":
    n=int(input("Enter a number: "))
    factorial = 1
    if n < 0:
        print(" Factorial does not exist for negative numbers")
    elif n == 0:
        print("The factorial of 0 is 1")
    else:
        for i in range(1,n + 1):
            factorial = factorial*i
    print("The factorial of",n,"is",factorial)

else:
    print("sorry, you select wrong operator.")
