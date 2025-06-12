 # sinmple calculater program

# take inpute from user and conver into floting             
num1 = float(input("enter frist number : "))     
num2 = float(input("enter second number: "))

#display option to user

print("chose your option:")
print("1. addition(+)")
print("2. subtraction(-)")
print("3. multiply(*)")
print("4. addition(/)")

#taking user choice

choice = input("enter choice(1)(2)(3)(4)")

if choice == '1':
    result = num1 + num2
    print(f"result: {num1} + {num2} = {result}")
elif choice == '2': 
    result = num1 - num2
    print(f"result {num1} - {num2} = {result}")
elif choice == '3':
    result = num1 * num2
    print(f"result {num1}* {num2}  = {result}")

elif  choice == '4':
    if num2 != 0:
        result = num1 / num2 
        print(f"result : {num1} / {num2} = {result}")
    else:
        print("error: division by zero is not allowed!")
else :
    print("Invalid choice")






