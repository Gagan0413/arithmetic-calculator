print("WELCOME TO CALCULATOR \n")


num1 = float(input("Enter first number: "))
op = input("Enter operator (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if op == "+":
     result= num1 + num2
     print("results: ", result)
elif op == "-":
     result= num1 - num2
     print("results: ", result)
elif op == "*":
     result= num1 * num2
     print("results: ", result)
elif op == "/":
     result= num1 / num2
     print("results: ", result)
else:
    print("Invalid operator!")
