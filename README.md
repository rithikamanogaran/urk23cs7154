def get_number(prompt):
    while True:
        try:
            return float(input(prompt))
        except ValueError:
            print("Invalid input. Please enter a numeric value.")

num1 = get_number("Enter the first number: ")
num2 = get_number("Enter the second number: ")
result = num1 + num2
print("The sum is:", result)


















