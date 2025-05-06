# Exp.No:29  
## Encapsulation

---

### AIM  
To create an Employee class by defining employee attributes such as name and salary as an instance variable and implementing behavior using work() and show() instance methods.

---

### ALGORITHM

1.Start

2.Define the Employee class

3.Inside the class:

4.Define the constructor method __init__(self, name, salary)

5.Assign name to an instance variable self.name

6.Assign salary to an instance variable self.salary

7.Define a method work(self)

8.Display or return a message indicating that the employee is working

9.Define a method show(self)

10.Display or return the employee's name and salary

11.End

---

### PROGRAM

```

class emp:

    def __init__(self,name,salary):

        self.name=name

        self.salary=salary

    def work(self):

        self.wor="NLP"

    def show(self):

        print(f"Name:  {self.name} Salary: {self.salary}")

        print(f"{self.name} is working on {self.wor}")

e=emp("Jessa",8000)

e.work()

e.show()


```

### OUTPUT

![image](https://github.com/user-attachments/assets/2287c421-c8dd-48e4-838c-862e59e740dd)


### RESULT

Thus the python program to create an Employee class by defining employee attributes such as name and salary as an instance variable and implementing behavior using work() and show() instance methods was created and executed successfully.
