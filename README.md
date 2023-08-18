# PYTHON_STDY_1
"""
#PYTHON ÇALIŞMASI 
x = y = z = 'Root Beer Float'
print(x)
print(y)
print(z)

x = 130000 
y =(x*0.025+x)
print(y) 

a = y
b = (a*0.025+a)
print (b)

x = 'Ice Cream'
y = 2
print(x,y)
a = 'Hello World!'
print(a[1:7]) 
 if (25 < 10) or (1 < 3):
    print('It worked!')
    if 10 > 5:
        print('This nested if statement worked!')
elif 25 < 20:
    print('elif worked!')
elif 25 < 21:
    print('elif 2 worked!')
elif 25 < 40:
    print('elif 3 worked!')
elif 25 < 50:
    print('elif 4 worked!')
else:
    print('It did not work...')

if (25 < 10) or (1 < 3) :
    print('IT WORKED!')
elif 25 < 20:
    print('elif worked!')
elif 25 < 21:
    print('elif 2 worked!')
elif 25 < 40:
    print('elif 3 worked!')
elif 25 < 50: 
    print('elif 4 worked!')
else: 
    print('It did not worked ... ')

flavors = ['Vanilla', 'Chocolate', 'Cookie Dough']
toppings = ['Hot Fudge', 'Oreos', 'Marshmallows']
for one in flavors:
    for two in toppings:
        print(one, 'topped with', two)

integers = [1,2,3,4,5]
for number in integers:
    print(number) 
ice_cream_dict = {'name': 'Alex Freberg', 'weekly intake': 5, 'favorite ice creams': ['MCC', 'Chocolate']}
for cream in ice_cream_dict.values():
    print(cream)

number = 0

while number < 5:
    print(number)
    if number == 3:
        break
    number = number + 1
def number_squared(number):
    print(number**2)
number_squared(5)

name = input("Enter you name: ")

weight = int(input("Enter your weight in pounds: "))

height = int(input("Enter your height in inches: "))

BMI = (weight * 703) / (height * height)

print(BMI)

if BMI>0:
    if(BMI<18.5):
        print(name +", you are underwight.")
    elif (BMI<=24.9):
        print(name +", you are normal weight.")
    elif (BMI<29.9):
        print(name +", you are overweight. You need to exercise more and stop sitting and writing so many python tutorials.")
    elif (BMI<34.9):
        print(name +", you are obese.")
    elif (BMI<39.9):
        print(name +", you are severely obese.")
    else:
        print(name +", you are morbidly obese.")
else:
    print("Enter valid input")

# Python code to demonstrate Type conversion
# using  tuple(), set(), list()
  
# initializing string
s = 'geeks'
  
# printing string converting to tuple
c = tuple(s)
print ("After converting string to tuple : ",end="")
print (c)
  
# printing string converting to set
c = set(s)
print ("After converting string to set : ",end="")
print (c)
  
# printing string converting to list
c = list(s)
print ("After converting string to list : ",end="")
print (c)

# Python code to demonstrate Type conversion
# using  dict(), complex(), str()
  
# initializing integers
a = 1
b = 2
  
# initializing tuple
tup = (('a', 1) ,('f', 2), ('g', 3))
  
# printing integer converting to complex number
c = complex(1,2)
print ("After converting integer to complex number : ",end="")
print (c)
  
# printing integer converting to string
c = str(a)
print ("After converting integer to string : ",end="")
print (c)
  
# printing tuple converting to expression dictionary
c = dict(tup)
print ("After converting tuple to dictionary : ",end="")
print (c)

# Python program to illustrate if-elif-else ladder
#!/usr/bin/python
 
i = 20
if (i == 10):
    print("i is 10")
elif (i == 15):
    print("i is 15")
elif (i == 20):
    print("i is 20") 
else:
    print("i is not present")
"""

