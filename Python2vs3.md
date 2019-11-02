# Python:

In Python3, Strings are by default unicode and non local variable declaration.
Python3 uses print() with parentheses.
Python2 , uses without parentheses.
Python3, used only input() both number and string
python2, used only raw_input() fort string and input() used for intger , if string passes then it will throw errors.

# Error Handling
   In Python 3, we need to use as keyword in except clause while
checking error, whereas as keyword is not required in Python 2.

# Literal Constants
   Numeric literals are 5, 2.85 and  string literals are I am a string

# Numbers
   Numbers are 2 types (Integer and Float)
   
   e Refers to Power 
   
   There is no long/double

# strings
  Python Strings supports both ASCII and Unicode.
  
  Strings are immutable - This means once we have created a string we cannot
change it
  
# Python as a Calculator
print("Hello World")

# Addition
print(5+3)

# Subtraction
print(5-3)

# Multiplication
print(5*3)

# Division
print(5/3)

# Modulo
print(5%3)

# integer Division operator
print(5//3)

# Composite Expression
print (3 + 2 + 1 - 5 + 4 % 2 - 1 / 4 + 6)

# Brackets  two operands called binary operators
(5 + 3) * (3 - 4)

# Negation 
- (5 + 3)

# Floating
5.0*3

# Floating Point Exponential
36 ** 0.5

# type is inbuilt function
type(5.0)

# To Know Types
int(5.9)
type(int(5.9))
round(5.9)
a=float(5)
print(a)
print(type(float(5)))

# useful function is abs, which takes one numerical argument and returns its absolute value.
abs(-5)
print(abs(5))
print(abs(5.0))

# Scientfic Notation
5e1
5e-1
5e2

# Variable to hold value
month_name='January'
print(month_name)

Error  
month_name[0]='F'
'str' object does not support item assignment

# Concatenating two strings
print('January',',First month of Year')

# Concatenating a variable and string
stock_name='Aditya Birala'
print(stock_name + " is the stock name.")
#String Concatenation will be integer,Literals,Strings and Variables

# f-strings or formatted string literal.
#Use Variable in curly brackets{}
print(f'The Stock Name',stock_name)
print(f'{stock_name} is the stock name invested by Dinesh Sekaran')

# %-formatting strings
price=38.1
print("%s is currently trading at the price %.2f" %(stock_name,price))

#%s is used for specifying a string literal and %f is used to specify float literal.

# format() function used for printing and constructing string for output
stock_picker='Kotak'
price=50.25
print('i am intersted in {x},which is trading at {y}'.format(x=stock_picker,y=price))
print('i am intersted in {},which is trading at {}'.format(stock_picker,price))
print('i am intersted in {0},which is trading at {1}'.format(stock_picker,price))
print('The stock trading at {1},which is {0}'.format(stock_picker,price))

# Escape Sequence
print("That's  Pretty easy task")
print('That\'s  Pretty easy task')    #\ (backslash character
#character to indicate that it is a part of the string

# \n To Break into multiple lines
print('This is Pretty Easy Task.\n Yes, it\'s easy compartively to other task')

# \t tab escape sequence
print('Dinesh\tSekaran')

# single \ at the end of the line, it indicates that the string is continued in the next line
print('AAPL is the ticker for Apple Inc.\
...: It is a technology company.')

#More Escape Sequence Which is found.

# Indentation
Whitespaces are important in Python. Whitespace at the start of a line is called indentation.
We either use four spaces or tab space for indentation.

#We use %.2f to limit two digits after the decimal point.
