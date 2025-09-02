# simple calculator 
this is code 
print("wellcome to my calculator")
a = '''First you can enter a first number then enter the sign chose (+,-,*,/,%) 
then enter the second nuber to get the result then press enter 
get the result then your answer will be shown'''
print(a )


# importing side
import math # importing math module

# taking input side
a = int(input("enter one number1:")) # input taking to  th user number 1
b = input("enter your sign chose anyone (+,-,*,/,%):")  # input taking to the user sign
c = int(input("enter one number2:"))# input taking to the user number 2

# printing input side
print("your first number",a)# printing the first number
print("you chose the sign",b)# prting the sign
if b != '+'and b != '-'and b != '*'and b != '/'and b != '%': # chaking the input is correct or not
    print("your sign is wrong please enter the correct sign")
print("your second number",c)# printing the second number

# chaking mathord
if b == '+':# chaking mathord
    print("mathord plus (+)")
if b == '/':# chaking mathord
    print(" mathord  divide (/) ")
if b == '*':# chaking mathord
    print(" mathord multiply (*) ")  
if b == '-':# chaking mathord
    print(" mathord minus (_)")
if b == '%':# chaking mathord
    print(" mathord modulas (%)")


# printing the result side


if b == '+':# chaking printing the result
   print("the sum of ",a,"and",c)
   print("sum of two number",a+c)
if b == '-':# chaking printing the result
   print("the subtration of ",a,"and",c)
   print("subtration of two number",a-c)
if b == '*':# chaking printing the result
    print("the Multiplication of ",a,"and",c)
    print("multiplication of two number",a*c)
if b == '/':# chaking printing the result
    print("that divison of ",a,"and",c)
    print("divison of two number",a/c)
if b == '%':# chaking printing the result
    print("the modulas of ",a,"and",c)
    print("moduls of two mumber",a%c)

def infirmation():
    print("thank you for using my calculator")
    print("if you to suggest any thing pleas tell me")
    print("have a nice day")                                       
    print("my mail is :alideals933@gmail.com")
def e():
    print("OK!")   
q = input("do you want to get more information yes/no y for yess n foor no :")
if q == 'y':
    print(infirmation())
if q == 'n':
    print(e())
