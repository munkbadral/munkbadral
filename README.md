def subtract(num1, num2):
    return num1 - num2

def multiply(num1, num2):
    return num1 * num2

def divide(num1, num2):
    return num1 / num2

print("зорилгоо сонго уу:")
print("1. үгсийн сангийн дайралт")
print("2. шууд шаах")
print("3. арын хаалга")
print("4. хортой холбоос")

choice = int(input("Enter choice (1-4): "))

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

if choice == 1:
    result = add(num1, num2)
    print("The result is:", result)
elif choice == 2:
    result = subtract(num1, num2)
    print("The result is:", result)
elif choice == 3:
    result = multiply(num1, num2)
    print("The result is:", result)
elif choice == 4:
    result = divide(num1, num2)
    print("The result is:", result)
else:
    print("Invalid choice")
