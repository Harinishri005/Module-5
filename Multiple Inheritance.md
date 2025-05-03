# Exp.No:23  
## Multiple Inheritance

### AIM  
To write a Python program to Get the name, age and salary of a person and display using Multilevel inheritance.

### ALGORITHM

1.Start the program and define a class Fun with an __init__ method taking three parameters.

2.Inside __init__, assign the input values to instance variables self.a, self.b, and self.c.

3.Define a method get() to display the values of a, b, and c.

4.Take user input for a (string), b (int), and c (int).

5.Create an object of the Fun class using the inputs.

6.Call the get() method to print the stored values.

### PROGRAM
# REG NO:212223090008
# NAME:Harinishri

```
class fun:
    def _init_(self,a,b,c):
        self.a=a
        self.b=b
        self.c=c
    def get(self):
        print(f"{self.a} {self.b} {self.c}")
a=input()
b=int(input())
c=int(input())
obj=fun()
print(f"{a} {b} {c}")


```

### OUTPUT

![image](https://github.com/user-attachments/assets/7b0417cd-593b-43ff-b7ce-44cebb1ba1b8)


### RESULT
This program demonstrates multilevel inheritance in Python by collecting and displaying a person's name, age, and salary across three linked classes.














