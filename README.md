# Python
Practice
#Syntax for printing
print("GIan Panopio")
print("BSIT")

#Printing variables
x = 10 # x is an integer
y = "Gian" # y is a string
print(x)
print(y)

#Different type of casting
x = str(5)  # x will be '5'
y = int(11)  # y will be 11
z = float(9)  # z will be 9.0

#different cases of variable
#camel case
myVariableName = "gian"
#pascal case
MyVariableName = "gian"
#snake case
my_variable_name = "gian"

#Multiple Variables
x, y = "gian", "louis" 
print(x)
print(y)

#values can be variables
feels = ["envy", "pity", "jealous"]
x, y, z = feels
print(x)
print(y)
print(z)

#printing output variables
x= "yo"
y= "bo"
z= "seyo"
print(x, y, z)

#this operator "+" can be used in output variables
x= yo
y= bo
z= seyo
print(x + y + z)

#for numbers this operator "+" is used for mathematical operator
x= 10
y= 56
z= 30
print(x + y + z)

#Global variables are variables that is outside of the function
x = "anime"

def myfunc():
  print("I love " + x)

myfunc()

#in this code there is a global and local variable
x = "anime"

def myfunc():
  x = "so good"
  print("anime is " + x)

myfunc()

print("I love " + x)
#the output shows that the local vairable is printed first
output:
anime is so good
I love anime
