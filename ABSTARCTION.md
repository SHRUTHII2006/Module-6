# Exp.No:28  
## Abstraction

---

### AIM  
To Create a abstract class type_shape   Which  is inherited from the ABC class. define an abstract method area inside the class type_shape: The implementation of an abstract class is done in the sub-classes, which will inherit the class type_shape. defined four classes Rectangle,Square,Circle,Triangle that inherit the abstract class type_shape.

### ALGORITHM

1. **Start the Program.**
2. **Import the ABC class** from the `abc` module to implement abstraction.
3. **Define the abstract base class Polygon**:
   - Inherit from `ABC` (Abstract Base Class).
   - Define an abstract method `sides()` with no implementation.
4. **Define the Triangle class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Triangle has 3 sides"`.
5. **Define the Pentagon class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Pentagon has 5 sides"`.
6. **Define the Hexagon class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"Hexagon has 6 sides"`.
7. **Define the Square class** that inherits from `Polygon`:
   - Implement the `sides()` method to print `"I have 4 sides"`.
8. **Create an object `t` of the Triangle class** and call the `sides()` method to print the number of sides.
9. **Create an object `s` of the Square class** and call the `sides()` method to print the number of sides.
10. **Create an object `p` of the Pentagon class** and call the `sides()` method to print the number of sides.
11. **Create an object `k` of the Hexagon class** and call the `sides()` method to print the number of sides.
12. **End the Program.**

---

### PROGRAM

```
from abc import ABC
class Shape(ABC):
    def calculate_area(self):
        pass
class Rectangle(Shape):
    length = 6
    breadth =4
    def calculate_area(self):
        return self.length*self.breadth
class Square(Shape):
    length = 4
    def calculate_area(self):
        return self.length * self.length
class Circle(Shape):
  radius = 6.99
  def calculate_area(self):
        return 153.86
class Triangle:
    length = 4
    breadth =5 
    def calculate_area(self):
        return 0.5*self.length * self.breadth
 


r = Rectangle()
r.calculate_area()

p = Circle()
p.calculate_area()

m=Square()
m.calculate_area()

t=Triangle()
t.calculate_area()

print("Area of a rectangle:", r.calculate_area()) #call to 'calculate_area' method defined inside the class 'Rectangle'
print("Area of a circle:", p.calculate_area()) #cal
print("Area of a square:", m.calculate_area()) 
print("Area of a triangle:", t.calculate_area()) # call to 'area' method defined inside the class.
```

### OUTPUT

![image](https://github.com/user-attachments/assets/2a8d9e38-74cc-4c50-bfa8-afc30cfd3a76)


### RESULT

Thus a abstract class type_shape   Which  is inherited from the ABC class. define an abstract method area inside the class type_shape: The implementation of an abstract class is done in the sub-classes, which will inherit the class type_shape. defined four classes Rectangle,Square,Circle,Triangle that inherit the abstract class type_shape was created and verified successfully.
