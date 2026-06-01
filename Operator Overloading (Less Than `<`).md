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
~~~~~~~~~~~~~~~~~~
class A:
    def __init__(self,a):
        self.a=a
    def __gt__(self,other):
        return self.a > other.a
        
ob1=A(20)
ob2=A(3)

if ob1>ob2:
    print("ob2 is less than ob1")
else:
    print("ob1 is less than or equal to ob2")
~~~~~~~~~~~~~~~~~~~~~~~~~~
## Output
<img width="545" height="141" alt="WhatsApp Image 2026-05-28 at 9 31 48 PM" src="https://github.com/user-attachments/assets/ac1e2d53-461a-484f-8a8e-9342ab68070e" />

## Result
the output is verified
