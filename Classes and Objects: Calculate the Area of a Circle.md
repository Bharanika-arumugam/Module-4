# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `pen` and a method `stationary` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `pen`.
3. **Define the method**: Inside the class, define the method `stationary` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
``` python
import math
class pen:
    def stationary(self,r):
        return math.pi*r*r
r=int(input())
h=pen()
print("Area of circle:",round(h.stationary(r),2))
```

## Output
![image](https://github.com/user-attachments/assets/84e29a69-13e8-401b-8d27-358159c8b247)

## Result
Thus Python program that calculates the **area of a circle** is executed successfully.
