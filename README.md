<html>

<head>

<title>MP calculator</title>

</head>



<body>

<h2 align="center">

Check out my python coded advanced calculator!

</h2>

<br>

<p align="center">

Clik <a href="https://repl.it/languages/python3">here </a>to see the code and run it.

<br>

Copy in this code: <br>

# Calculator.

def cal():

  print("This is a calculator.")

  print("You choose a number, then a sign and then the last number. The signs can be plus, minus, times, **, division and modulos.")

  

  num1 = int(input("Number 1 --> "))

  sign = input("Sign --> ")

  num2 = int(input("Last number --> "))

  

  if sign == "+" or sign == "-" or sign == "*" or sign == "/":

    print("You want to calculate %s%s%s." % (num1, sign, num2))

  

  if sign == "+":

      result = int(num1) + int(num2)

      print("The result is %s." % (result))

      

  elif sign == "-":

        result = int(num1) - int(num2)

        print("The result is %s." % (result))

        

  elif sign == "*":

    result = num1 * num2

    print("The result is %s." % (result))

             

  elif sign == "/":

               result = num1 / num2

               print("The result is %s." % (result))

             

  elif sign == "**":

               result = num1**num2

               print("The result is %s." % (result))

 

  elif sign == "%":

               result = num1 % num2

               print("The result is %s." % (result))

 

  else:

               print("Something went wrong.")

 

 

# Square root function.

def sqr():

  from math import sqrt

  answer = input("Enter a number you want to find the square root of: ")

  def cals():

    result = sqrt(int(answer))

    print("The result is %s." % (result))

 

  print("We will now find the square root of you number.")

 

  if len(answer) > 0 and answer.isnumeric:

    cals()

  

  elif answer.isalpha:

    print("You can only use numbers.")

 

  elif len(answer) == 0:

    print("You must write something.")

  

  else:

    print("Something went wrong.")

 

# Vector length.

def length_vector():

  print("Enter the length of the x coordinate and the length of the y coodinate.")

  x, y = input("x and y coordinate: ").split()

  print("Your vector is (%s, %s)" % (x, y))

  

  from math import sqrt

  length = sqrt(int(x)**2) + sqrt(int(y)**2)

  print("The length of the vector is %s." % (length))

 

# if funkction.

def t_if():

  if choice == "calculator":

    cal()

 

  elif choice == "square root":

    sqr()

 

  elif choice == "vector length":

    length_vector()

 

  elif choice == "line slope":

    calc()

 

  else:

    print("Something went wrong. Make sure you spelled correctly.")

 

# Line slope

def calc():

  x, y = input("Enter x and y coordinates: ").split()

  x2, y2 = input("Enter the second x and y coordinates: ").split()

  ys = int(y2) - int(y)

  xs = int(x2) - int(x)

  result = int(ys) / int(xs)

  print("The line slope er %s." % (result))

 

print("Enter what type of calculations you want.")

print("You can choose 'Square root', 'Vector length', 'Calculator' and 'Line slope'.")

 

choice = input("Enter here: ").lower()

 

if len(choice) > 0:

  t_if()

 

else:

  print("Something went wrong. Make sure you spelled it correct.")

</p>

</body>

</html># MP-calculator
This is a python coded advanced calculator. Check it out by following the instructions by running the HTML code.
