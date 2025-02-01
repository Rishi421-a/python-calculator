# python-calculator
made calculator using python 
def add(num1,num2,num3):
    return num1 + num2 + num3

def sub(num1,num2,num3):
    return num1 - num2 - num3

def mul(num1,num2,num3):
    return num1 * num2 * num3

def div(num1,num2,num3):
    return num1/num2/num3

print("please select a operation \n" "1. Addition\n" "2. Subtraction\n" "3. Multiplication\n" "4. Division")

select = int(input("Select a operation from 1,2,3,4,:"))

number1 = int(input("Enter the first number :"))
number2 = int(input("Enter the second number :"))
number3 = int(input("Enter the third number :"))

if select == 1:
    print(number1, "+", number2, "+", number3, "=",\
        add(number1,number2,number3))
    
elif select ==2:
    print(number1, "-", number2, "-", number3,"=", \
          sub(number1,number2,number3))

elif select ==3:
    print(number1, "*", number2, "*", number3,"=", \
          mul(number1,number2,number3))

elif select ==4:
    print(number1, "/", number2, "/", number3,"=", \
          div(number1,number2,number3)) 
    
else :
    print("invalid opeartion")
