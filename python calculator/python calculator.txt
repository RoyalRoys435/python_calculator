num1 = int(input("enter first number : "))
num2 = int(input("enter second number : "))

print("enter which operation you would like to perfom")
ch = input("enter any of these characters for specific operations +, -, *, /: ")

result =0
if ch == '*':
  result = num1 * num2
elif ch == '/':
  result = num1 / num2
elif ch =='+':
  result = num1 + num2
elif ch == '-':
  result = num1 - num2
else:
  print("input character is not recognised!!")
print(num1, ch, num2, ":", result)