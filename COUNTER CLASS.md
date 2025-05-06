# Exp.No:30  
## COUNTER CLASS

---

### AIM  
To write a python program to overload a comparison operator. 

class name : A

ob1 = A(2)

ob2 = A(3)

---

### ALGORITHM

1.Start

2.Define class A

3.Inside class A:

4.Define the constructor method __init__(self, value)

5.Assign value to an instance variable self.value

6.Define method __lt__(self, other) to overload the < operator

7.Compare self.value < other.value

8.Return the result of the comparison

9.Create two objects:

    ob1 = A(2)

    ob2 = A(3)

10.Use the overloaded < operator to compare ob1 < ob2

11.Print the result of the comparison

12.End

---

### PROGRAM

```
class A:

    def __init__(self, value):

        self.value = value
    
    def __gt__(self, other):

        if self.value > other.value:

            return True

        else:

            return False

ob1 = A(2)

ob2 = A(3)

if ob2 > ob1:

    print("ob2 is greater than ob1")

else:

    print("ob1 is greater than or equal to ob2")



```

### OUTPUT


![image](https://github.com/user-attachments/assets/d3c41db8-a2ee-4b4c-9bdb-a227d2151654)


### RESULT

Thus the python program to overload a comparison operator was successfully executed.
