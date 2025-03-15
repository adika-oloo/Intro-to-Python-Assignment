# Intro-to-Python-Assignment
# Get input from the user
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

# Display operation options
print("\nSelect operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")

# Get user's choice
choice = input("Enter choice (1/2/3): ")

# Perform calculation based on choice
if choice == '1':
    result = num1 + num2
    print(f"\nResult: {num1} + {num2} = {result}")
elif choice == '2':
    result = num1 - num2
    print(f"\nResult: {num1} - {num2} = {result}")
elif choice == '3':
    result = num1 * num2
    print(f"\nResult: {num1} × {num2} = {result}")
else:
    print("Invalid input! Please select 1, 2, or 3.")

