# Intro-to-Python-Assignment
def basic_calculator():
    
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    operation = input("Choose an operation (+, -, *, /): ").strip()

    
    if operation == "+":
        result = num1 + num2
    elif operation == "-":
        result = num1 - num2
    elif operation == "*":
        result = num1 * num2
    elif operation == "/":
        if num2 == 0:
            print("Error! Division by zero is not allowed.")
            return  
        result = num1 / num2
    else:
        print("Invalid operation. Please enter +, -, *, or /.")
        return  

   
    print(f"{num1} {operation} {num2} = {result}")


basic_calculator()

