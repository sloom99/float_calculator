# float_calculator
basic floating point calculator in python3
# code
num1 = float(input("Enter a number: "))
num2 = float(input("Enter other number: "))
result = 0
choice = input('Enter 1 for sum, 2 for difference, 3 for product, 4 for quotient: ')
if choice == '1':
    result = num1 + num2
elif choice == '2':
    result = num1 - num2
elif choice == '3':
    result = num1*num2
elif choice == '4':
    result = num1 // num2
else:
    print("Please enter valid choice number")
print("The result is:", result)
