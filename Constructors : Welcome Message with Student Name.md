# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program
```
# Get user input
name = input("Enter student name: ")

# Define the class
class Student:
    # Default constructor
    def __init__(self):
        self.a = name   # assign input to instance variable

    # Method to display message
    def show(self):
        print("This is non-parameterized constructor")
        print("Welcome", self.a)

# Create object
s = Student()

# Call method
s.show()
```


## Output
<img width="691" height="359" alt="image" src="https://github.com/user-attachments/assets/1df0ce4c-939a-471f-96aa-3d7ef7a90fef" />

## Result
The program was executed successfully. A Student class with a default (non-parameterized) constructor was created, and it correctly displayed a welcome message using the user-provided name.
