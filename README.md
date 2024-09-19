# Function to perform basic operations
def calculate(num1, num2, operation):
    if operation == '+':
        return num1 + num2
    elif operation == '-':
        return num1 - num2
    elif operation == '*':
        return num1 * num2
    elif operation == '/':
        if num2 != 0:
            return num1 / num2
        else:
            return "Error: Division by zero!"
    else:
        return "Invalid operation!"

# Main program
def main():
    try:
        # Input from the user
        num1 = float(input("Enter the first number: "))
        num2 = float(input("Enter the second number: "))
        operation = input("Choose an operation (+, -, *, /): ")

        # Perform the operation and display the result
        result = calculate(num1, num2, operation)
        print(f"Result: {result}")

    except ValueError:
        print("Error: Please enter valid numbers.")

# Run the calculator
if __name__ == "__main__":
    main()

<!---
Diksha200512/Diksha200512 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
