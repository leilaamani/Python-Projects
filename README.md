# Python-Projects
# get x and read 5 numbers from inpute then specify how many numbers are less than x and how meny numbers are bigger than it.
# get x and read 5 numbers from inpute then specify how many numbers are less than x and how meny numbers are bigger than it.
# # First approche
# print("----------------------------------")
# x= int(input("please enter a number:"))
# number1= int(input("please enter number1:"))
# number2= int(input("please enter number2:"))
# number3= int(input("please enter number3:"))
# number4= int(input("please enter number4:"))
# number5= int(input("please enter number5:"))
# count= 0
# if number1>= x:
#     count +=1
# if number2>= x:
#     count +=1
# if number3>=x:
#     count +=1
# if number4>=x:
#     count +=1
# if number5 >=x:
#     count +=1
# print(f"{count} numbers are bigger than {x} and {5-count} numbers ara less than {x}")
# print("Thank you for contribution")

# Second approche
print("----------------------------------")
x, number1, number2, number3, number4, number5= map(int, input("please enter six numbers as x and other numbers:").split())
count=0
count+= number1>=x
count+= number2>=x
count+= number3>=x
count+= number4>=x
count+= number5>=x
print(f"{count} numbers are bigger than {x} and {5-count} numbers ara less than {x}")
print("Thank you for contribution")
