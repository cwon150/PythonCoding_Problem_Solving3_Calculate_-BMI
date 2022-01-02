# PythonCoding_Problem_Solving3_Calculate_BMI
# Write a program that calculates the Body Mass Index (BMI) from a user's weight and height.  The BMI is a measure of some's weight taking into account their height. e.g. If a tall person and a short person both weigh the same amount, the short person is usually more overweight.  The BMI is calculated by dividing a person's weight (in kg) by the square of their height (in m)

height = input("enter your height in m: ")

weight = input("enter your weight in kg: ")

# 🚨 Don't change the code above 👆

# Write your code below this line 👇

# print(type(height)) - <class 'str'>

# print(type(weight)). - <class 'str'>

person_weight = float(weight)

height_power_of_2 = float(height) ** 2

bmi_result = person_weight / height_power_of_2

print(int(bmi_result))

# Alternatively, you can write the codes as following:

height = input("enter your height in m: ")

weight = input("enter your weight in kg: ")

bmi = float (weight) / float (height) ** 2

bmi_as_int = int(bmi)

print(bmi_as_int)
