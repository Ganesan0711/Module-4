
# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program to calculate the area of a circle using a class named `cse` and a method named `mech`.

## 🧠 Algorithm
1. Get the radius of the circle from the user.
2. Define a class named `cse`.
3. Define a method named `mech` to calculate the area.
4. Calculate the area using the formula A = π × r × r.
5. Create an object of the class.
6. Call the method and display the result.

## 🧾 Program

```python
import math

class cse:
    def mech(self, r):
        area = math.pi * r * r
        print("Area of the circle:", area)

radius = float(input("Enter the radius: "))

obj = cse()
obj.mech(radius)
```

## 💻 Output

```text
Enter the radius: 5
Area of the circle: 78.53981633974483
```

## ✅ Result
Thus, the Python program to calculate the area of a circle using classes and objects was executed successfully.
