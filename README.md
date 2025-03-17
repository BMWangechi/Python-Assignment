def calculate(num1, num2, operation):
    if operation == "+":   
        return num1 + num2
    elif operation == "-":
        return num1 - num2
    elif operation == "*":
        return num1 * num2
    elif operation == "/":
        return num1 / num2
    else:
        return "Invalid operation"
num1 =  int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
operation = input("Enter the mathematical operation (+, -, *, /): ")
result = calculate(num1, num2, operation)
print(f"{num1} {operation} {num2} = {result}")
