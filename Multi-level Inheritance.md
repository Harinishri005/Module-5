# Exp.No:24  
## Multi-level Inheritance

### AIM  
To Write a Python program to get the name age and Id of a student and check they are valid student using multiple inheritance


### ALGORITHM

1.Start the program.

2.Read the student's name (a) as a string.

3.Read the student's ID or roll number (b) as an integer.

4.Read a numeric value (c), which could represent marks or fees.

5.Check if c > 21000:

6.If true, print the name, ID, and "Valid Student".

7.If false, print the name, ID, and "Invalid Student".

8.End the program.



### PROGRAM
# REG NO:212223090008
# NAME:Harinishri S

```
class Person:
    def get_details(self):
        self.name = input("Enter student name: ")
        self.age = int(input("Enter student age: "))
class StudentID:
    def get_id(self):
        self.student_id = int(input("Enter student ID: "))
class Student(Person, StudentID):
    def check_validity(self):
        if self.age >= 18 and self.student_id > 0:
            print("\nValid Student")
        else:
            print("\nInvalid Student")

    def show_details(self):
        print("\nStudent Details:")
        print("Name:", self.name)
        print("Age:", self.age)
        print("ID:", self.student_id)
s = Student()
s.get_details()
s.get_id()       
s.show_details()  
s.check_validity() 


```

### OUTPUT
![image](https://github.com/user-attachments/assets/b1b3accb-f7e2-49c8-8097-75255e55ba94)


### RESULT
Thus,Python program to get the name age and Id of a student and check they are valid student using multiple inheritance executed successfully
