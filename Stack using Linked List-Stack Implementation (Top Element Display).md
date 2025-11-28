# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
```
stack = []  
for i in range(3):
    element = input()
    stack.append(element)
if stack:
    print("Top element:", stack[-1])
else:
    print("Stack is empty")
```
## Output
<img width="450" height="285" alt="image" src="https://github.com/user-attachments/assets/594607e1-f4f3-4216-8a2c-a3480a62ad3a" />

## Result
Thus, the program is successfully executed.
