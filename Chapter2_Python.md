# Variables
In Python, variables need NOT be declared or defined in advance, as is the case in many other programming languages. In fact, Python has no command for declaring a variable. To create a variable, we assign a value to it and start using it.

A variable is created the moment we assign the first value to it.

# Creating a variable
price = 226      # Intializing the variable

print(price)

price=230          # Assigning New Value to variable

print(price)

# chain assignment operation to variables in Python
x=y=z=100

print(x,y,z)

y=101

print(x,y,z)


# Variable Naming Conventions
## variable name must start with a letter or the underscore character

stock ='AXIS'

_name='HDFC'

print(stock,_name)

##  variable name cannot start with a number.

1stock='axis'

print(stock)

## A variable name can only contain alpha-numeric characters(A-Z, a-z,0-9) and underscores( _ ).
## It is a combination of a capital letter, alphabets and a number.

stock='HDFC'

Stock_name='HDFC'

stock_1='HDFC'

Stock_price_1=52

print(stock,Stock_name,stock_1,Stock_price_1)

## Variable names are case-sensitive
## STOCK, stock and Stock all three are different variable names.
STOCK='AXIS'

Stock='DHFL'

stock='KVB'

print(STOCK,Stock,stock)

## Python keywords cannot be used as a variable name.

is and for are not valid for variable. They are Reserved Words.

is ='a'

print(is)

for ='FOR'

print(for)

# de facto method of creating variables

Stock_Name


# Data Types
Primitive Data types of Python are
Integer

Float

String

Boolean


# Data Types Integer
total_months=12

# FLoat
Price=22.5

# Boolean
Buy=True

print(Buy)

# Equality Operator
1==1

1==-1

1>-1

## Boolean should written as True and False and not in Quotes.


# String

Sample_String='Nothing something'

print(Sample_String)

price_value='1.1'

price_value_1=1.2

print('The value is '+price_value)

-------------------------------------

# + operator works only on a string concatenation
print('The value is '+price_value_1)

Error can only concatenate str (not "float") to str

# * operator with a string literal to produce the same string multiple times.

Var_String='Python '

print(Var_String*3)


# Subtring/Slice/Inexing
Var_String[0]

Var_String[1]

Var_String[0:3]


# Operations on String
