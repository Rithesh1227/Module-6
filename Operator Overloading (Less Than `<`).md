# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```

class Beans(): 
     def type(self): 
       print("Vegetable") 
     def color(self):
       print("Green") 
class Mango(): 
     def type(self): 
       print("Fruit") 
     def color(self): 
       print("Yellow")      
def func(obj): 
       obj.type()
       obj.color()
obj_beans = Beans() 
obj_mango = Mango() 
func(obj_beans) 
func(obj_mango)

```
## Output
<img width="561" height="123" alt="image" src="https://github.com/user-attachments/assets/c4b39e8a-4089-4c5d-9409-75598c6b86d2" />
e1b" />

## Result
