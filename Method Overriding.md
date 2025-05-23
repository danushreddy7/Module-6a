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
great_white = Shark()

print("Calling type() from Fish instance:")
generic_fish.type()

print("\nCalling type() from Shark instance:")
great_white.type()
```
## OUTPUT:
```
Calling type() from Fish instance:
I am a fish.

Calling type() from Shark instance:
I am a shark, a type of fish.
```
## RESULT:
The program was successful.
