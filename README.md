# python-internship-task_8

List down all the error types

1.)NameError

2.)ModuleNotFoundError

3.)IndexError

4.)ZeroDivisionError

5.)ValueError


try:
    raise NameError('python')
except NameError:
    print("The exception demolished")

#ModuleNotFoundError

try:
    import pandas
    
    print("Module found")
    
except:

    print("module not found")

#Indexerror

list_1=list(range(0,5))

try:

    print(list_![10])

except:

    print("Error handled")

#ZeroDivisionError

try:

    a=2/0
    
    print(a)
    
except:

    print("Cannot divide by zero")

#ValueError

try:
    
    x=int(input("Enter the number"))

except:
    
    print("It is not a number")

Excercise_2:Design a simple calculator app with try and except for all use cas-es

print("enter 1 for add,2 for subtraction,3 for multiply,4 for division")

try:

    choice=int(input("option:"))
    
    if choice==1:
    
        first=float(input("first number:"))
        
        second=float(input("second number:"))
        
        print(first+second)
        
    elif choice==2:
      
      first=float(input("first number:"))
      
      second=float(input("second number:"))
      
      print(first-second)
    elif choice==3:
      
      first=float(input("first number:"))
      
      second=float(input("second number:"))
      
      print(first*second)
    elif choice==4:
      
      first=float(input("first number:"))
      
      second=float(input("second number:"))
      
      print(first/second)
    else:
      
      print("enter a valid integer")
        
except NameError:

    print("Invalid input")
    
except SyntaxError:

    print("Invalid input")
    
except TypeError:

    print("Invalid input")
    
except AttributeError:

    print("Invalid input")
    
except ValueError:

    print("Invalid input")


Excercise_3:print one message if the try block raises a NameError and another for 

other errors

try:

    raise NameError("python")
    
except NameError:

  print("The Exception is handled")

Excercise_4:When try-except scenario is not required

#Answer:Whwenever there is no need for error to be handled or we can let the program to 

display the error,try-except scenario is not required.

Excercise_5:Try getting an input inside the try catch block

solution:

while True:

  try:

    num=int(input("Enter the integer"))

    print("The integer you have entered is",num)

    break

  except:

    print("Invalid integer")

print("You have entered an integer")
