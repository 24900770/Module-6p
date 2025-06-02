# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:

```
class Fish:
    def type(self):
        print("I am a fish.")
class Shark(Fish):
    def type(self):
        print("I am a shark, a type of fish.")
generic_fish = Fish()
specific_shark = Shark()
generic_fish.type()
specific_shark.type() 
```

## OUTPUT
![442485140-82cce579-79ae-4a31-9f76-8e8cc30db95f](https://github.com/user-attachments/assets/77725628-69ab-4f71-ad9e-9d1f158e856a)

## RESULT
Thus the program has been executed successfully.
