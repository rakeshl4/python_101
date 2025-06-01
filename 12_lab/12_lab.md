# How to Create and Run a Python (.py) File in VS Code! 🐍💻

Welcome, coding superstar! 🌟 Today, you'll learn how to make your very own Python files and run them in VS Code. Let's make it fun and easy, step by step!

---

## 1. What is a `.py` File? 📄
A `.py` file is just a file where you write your Python code. It's like your magic spellbook for coding! 🧙‍♂️✨

---

## 2. How to Create a `.py` File in VS Code 📝
1. **Open VS Code** (the blue icon with angle brackets).
2. **Go to your folder** (like `12_lab`).
3. **Right-click** in the folder area and choose **New File**.
4. Name your file something fun, like `hello.py` or `my_magic_code.py`.
5. Press **Enter**. You just made a Python file! 🎉

---

## 3. Write Some Python Code! ✍️
Here are some fun examples you can try:

```python
# hello.py
print("Hello, world! 🌍")
```

```python
# animals.py
print("🐶 Woof! 🐱 Meow! 🐸 Ribbit!")
```

```python
# add_numbers.py
num1 = 5
num2 = 7
print("The sum is:", num1 + num2)
```

```python
# joke.py
print("Why did the computer go to the doctor? Because it had a virus! 🤒💻")
```

---

## 4. How to Run Your `.py` File in VS Code 🚀
1. **Click on your `.py` file** to open it in the editor.
2. **Right-click** anywhere in your code and choose **Run Python File in Terminal**. (Or click the green play button ▶️ at the top right!)
3. Look at the **Terminal** at the bottom. That's where your code's output appears!

**Example:**
- If you run `hello.py`, you'll see:
  ```
  Hello, world! 🌍
  ```
- If you run `animals.py`, you'll see:
  ```
  🐶 Woof! 🐱 Meow! 🐸 Ribbit!
  ```

---

## 5. More Fun Examples to Try! 🎲

```python
# multiply.py
print("3 x 4 =", 3 * 4)
```

```python
# emoji_party.py
print("🎉🎈🥳 Welcome to the emoji party! 🥳🎈🎉")
```

```python
# ask_name.py
name = input("What's your name? ")
print("Hi, " + name + "! 👋")
```

---

## 6. Tips & Tricks 💡
- You can make as many `.py` files as you want!
- Try changing the code and running it again to see what happens.
- If you see an error, don't worry! Check your spelling and try again. Mistakes help you learn! 🤗

---

## 8. Using Two Python Files with Imports! 🗂️➡️📄

You can split your code into different files and use `import` to share code between them. It's like having two magic spellbooks and using spells from both!

### Example 1: Importing a Function from Another File

Suppose you have two files in your folder:

**greetings.py**
```python
def say_hello():
    print("Hello from greetings.py! 👋")
```

**main.py**
```python
from greetings import say_hello

say_hello()  # This will print: Hello from greetings.py! 👋
```

### Example 2: Importing the Whole File as a Module

**math_magic.py**
```python
def add(a, b):
    return a + b
```

**main.py**
```python
import math_magic

result = math_magic.add(3, 4)
print("The magic sum is:", result)
```

### Example 3: Using Aliases with Imports

**animals.py**
```python
def sound():
    print("Woof! 🐶")
```

**main.py**
```python
import animals as pet

pet.sound()  # Woof! 🐶
```

### Example 4: Importing Multiple Functions from a File

Suppose you have a file with several functions:

#### math_tricks.py

```python
# math_tricks.py
def double(x):
    return x * 2

def triple(x):
    return x * 3
```

#### main.py

```python
from math_tricks import double, triple

print("Double of 5 is:", double(5))   # 10
print("Triple of 5 is:", triple(5))   # 15
```

---

### Example 5: Importing Everything from a File (Not Recommended for Big Projects)

#### greetings.py

```python
def hello():
    print("Hello! 👋")
def bye():
    print("Goodbye! 👋")
```

#### main.py

```python
from greetings import *

hello()
bye()
```

---

### Example 6: Using Variables from Another File

#### facts.py

```python
# facts.py
favorite_color = "blue"
number_of_pets = 2
```

#### main.py

```python
import facts

print("My favorite color is:", facts.favorite_color)
print("I have", facts.number_of_pets, "pets!")
```

---

### Example 7: Calling Functions from a File Inside a Folder

Suppose you have a folder called `helpers` with a file `math_helpers.py`:

#### helpers/math_helpers.py

```python
def square(x):
    return x * x
```

#### main.py

```python
from helpers.math_helpers import square

print("The square of 6 is:", square(6))
```

---

Try making your own creative examples! You can even make a file with jokes and import them into your main program for a laugh! 😂

---

Happy coding, Python wizard! 🐍🪄
