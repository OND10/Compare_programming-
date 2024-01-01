# Compare_programming-
# Assignment number three

class MyClass:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display_info(self):
        print(f"Name: {self.name}, Age: {self.age}")

    @staticmethod
    def welcome():
        print("Welcome to the MyClass!")

# Creating an instance of the class
obj = MyClass(name="John", age=25)

# Calling the instance method
obj.display_info()

# Calling the static method
MyClass.welcome()
