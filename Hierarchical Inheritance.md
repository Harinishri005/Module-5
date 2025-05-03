# Exp.No:25  
## Hierarchical Inheritance


### AIM  
To write A Python Program to Calculated Addition using Inheritance.

### ALGORITHM

1.Define a base class Details with private attributes id, name, and gender. 

2.Include methods to set and display these details.

3.Create a subclass Employee that inherits from Details, with additional attributes company and department. 

4.Add methods to set and display employee data.

5.Create another subclass Doctor that also inherits from Details, with added attributes hospital and department. 

6.Add methods to set and display doctor data.

7.Take input from the user for employee and doctor details (ID, name, gender, and specific fields).

8.Create objects of Employee and Doctor, use their respective methods to set and display full information.

9.Display the output for both objects using appropriate method calls.



### PROGRAM
# REG NO:212223090008
# NAME:Harinishri S
```
class Details:
    def __init__(self):
        self.__id="<No Id>"
        self.__name="<No Name>"
        self.__gender="<No Gender>"
    def setData(self,id,name,gender):
        self.__id=id
        self.__name=name
        self.__gender=gender
    def showData(self):
        print("Id: ",self.__id)
        print("Name: ", self.__name)
        print("Gender: ",self.__gender)
        
class Employee(Details):
    def __init__(self):
        self.__company="<No Company>"
        self.__dept="<No Dept>"
    def setEmployee(self,id,name,gender,comp,dept):
        self.setData(id,name,gender)
        self.__company=comp
        self.__dept=dept
    def showEmployee(self):
        self.showData()
        print("Company: ", self.__company)
        print("Department: ",self.__dept)
    
class Doctor(Details):
    def __init__(self):
        self.__hospital="<No Hospital>"
        self.__dept="<No Dept>"
    def setEmployee(self,id,name,gender,hos,dept):
        self.setData(id,name,gender)
        self.__hospital=hos
        self.__dept=dept
    def showEmployee(self):
        self.showData()
        print("Hospital: ", self.__hospital)
        print("Department: ", self.__dept)

id=int(input())
name=input()
gender=input()
comp=input()
dept=input()
id1=int(input())
nam=input()
gen=input()
hosp=input()
dep=input()

print("Employee Object")
e=Employee()
e.setEmployee(id,name,gender,comp,dept)
e.showEmployee()
print("\nDoctor Object")
d=Doctor()
d.setEmployee(id1, nam, gen, hosp, dep)
d.showEmployee()
        
        


```

### OUTPUT  

![image](https://github.com/user-attachments/assets/41115d4b-a290-48a9-abea-841e6592566f)



### RESULT
The program illustrates inheritance and encapsulation in Python using a common base class for shared attributes. Subclasses extend the base with role-specific details and behaviors for employees and doctors.









