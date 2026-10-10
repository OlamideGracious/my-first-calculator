# my-first-calculator
My first Python calculator built with Python 3 on phone - WAEC 2027 Software engineering aspirant from Nigeria 
# My First Calculator - by Oziegbe Gracious
print("=== MY CALCULATOR ===")

# Ask user for numbers
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

# Show options
print("\nChoose operation:")
print("1 = Add (+)")
print("2 = Subtract (-)")
print("3 = Multiply (*)")
print("4 = Divide (/)")

choice = input("Enter 1,2,3 or 4: ")

# Do the calculation
if choice == "1":
    result = num1 + num2
    print(f"Answer: {num1} + {num2} = {result}")
elif choice == "2":
    result = num1 - num2
    print(f"Answer: {num1} - {num2} = {result}")
elif choice == "3":
    result = num1 * num2
    print(f"Answer: {num1} * {num2} = {result}")
elif choice == "4":
    if num2 != 0:
        result = num1 / num2
        print(f"Answer: {num1} / {num2} = {result}")
    else:
        print("Error: Cannot divide by zero!")
else:
    print("Invalid choice!")

print("\nThanks for using my calculator!")
