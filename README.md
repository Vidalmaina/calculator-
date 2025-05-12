num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter the operation (+, -, *, /): ")

# Performing the calculation based on the operation
if operation == '+':
    result = num1 + num2
    print(f"{num1:g} + {num2:g} = {result:g}")
elif operation == '-':
    result = num1 - num2
    print(f"{num1:g} - {num2:g} = {result:g}")
elif operation == '*':
    result = num1 * num2
    print(f"{num1:g} * {num2:g} = {result:g}")
elif operation == '/':
    if num2 != 0:
        result = num1 / num2
        print(f"{num1:g} / {num2:g} = {result:g}")
    else:
        print("Error: Division by zero is not allowed")
else:
    print("Error: Invalid operation")# calculator-
