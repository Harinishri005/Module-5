# Exp.No:21  
## Constructors -Non-Parameterized Constructor

### AIM  
To write a python code to create a student class with  default constructor  and a user defined function to display the text "welcome" with student name given to the function.

### ALGORITHM

1.Start the program.

2.Define a class Student with a default constructor __init__() that does nothing (using pass).

3.Create a method display_welcome(self, name) that takes a name and prints "Welcome" with that name.

4.Create an object of the Student class.

5.Call the display_welcome() method using the object and pass a student name.

6.End.


### PROGRAM
# REG NO:212223090008
# NAME:Harinishri S

```
class Name:
    def __init__(self,name):
        self.name = name
        
    def display(self):
        print("Hello "+ self.name)

name = input()
s = Name(name)
print("This is non parametrized constructor")
s.display()

```

### OUTPUT


![constructor](https://github.com/user-attachments/assets/746dce0a-cb03-4bfa-b1fb-ebbbb9d3194f)


### RESULT
The program demonstrates how to define a class with a default constructor and a user-defined method. It successfully displays a personalized welcome message using the student’s name.









