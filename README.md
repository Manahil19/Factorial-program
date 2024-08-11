# Factorial-program
fact=1
a=1
num=int(input("enter any number : "))
while a<=num:
    fact+=fact*a
    a+=1
    print("factorial of",num,"=",fact)
