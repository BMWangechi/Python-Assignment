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
    num1 =  int(input("5: "))
    num2 = int(input("10: "))
    operation = input("Enter operation (+): ")
    result = calculate(num1, num2, operation)
    print(f"{num1} {operation} {num2} = {result}")
    # Python-Assignment
