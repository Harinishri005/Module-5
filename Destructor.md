# Exp.No:22  
## Destructor-Create  a  Python Class Student with a destructor.



### AIM  
To create a Python class `Student` with a destructor.


### ALGORITHM

1.Start the program.

2.Define a class Student with a constructor method __init__() that prints object initialization messages.

3.Define a destructor method __del__() that prints object destruction messages.

4.Create an object obj of the Student class to automatically call the constructor.

5.Delete the object using del obj, which calls the destructor.

6.End the program.


### PROGRAM
# REG NO:212223090008
# NAME:Harinishri S
```
class Student():
    def __init__(self):
        print("Inside Constructor\nObject initialized\nHello, my name is Emma")
    def __del__(self):
        print("Inside destructor")
        print("Object destroyed")
obj=Student()
del obj

```

### OUTPUT

![image](https://github.com/user-attachments/assets/b9cd1111-a6e7-4316-990c-c2aa4d6aaa9d)



### RESULT
This program demonstrates how constructors and destructors work in Python classes. The constructor runs at object creation, and the destructor runs when the object is explicitly deleted or goes out of scope.









