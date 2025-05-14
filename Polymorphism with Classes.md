# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program:
```

class PlantItem:
    def get_type(self):
        pass

    def get_color(self):
        pass

class Beans:
    def get_type(self):
        return "Vegetable"

    def get_color(self):
        return "Green"

class Mango:
    def get_type(self):
        return "Fruit"

    def get_color(self):
        return "Yellow"

def describe_item(item):
    print("Type:", item.get_type())
    print("Color:", item.get_color())

# Create objects
b = Beans()
m = Mango()

print("Describing Beans:")
describe_item(b)

print("\nDescribing Mango:")
describe_item(m)
```
## Output:
```
Describing Beans:
Type: Vegetable
Color: Green

Describing Mango:
Type: Fruit
Color: Yellow
```
## Result:
The program was successful.
