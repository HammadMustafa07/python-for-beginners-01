
---

# Python Variables: A Simple Guide

Think of variables as containers or labels that hold information in your computer's memory. When you create a variable, you're essentially giving a name to a piece of data so you can use it later in your program.

## 1. Creating Variables (Assignment)

In Python, creating a variable is super easy. You just choose a name and use the equals sign (`=`) to assign a value to it.

**Syntax:**

```python
variable_name = value
```

**Examples:**

```python
age = 30           # 'age' is a variable holding the number 30
name = "Alice"     # 'name' is a variable holding the text "Alice"
is_student = True  # 'is_student' is a variable holding a true/false value
price = 19.99      # 'price' is a variable holding a decimal number
```

* Python automatically figures out the type of data you're storing (like a number, text, etc.). You don't need to explicitly tell it!

## 2. Naming Rules for Variables

There are a few simple rules for naming your variables:

* **Start with a letter or an underscore (`_`)**: You cannot start a variable name with a number.
    * `my_variable` (Good)
    * `_secret` (Good)
    * `1st_number` (Bad!)
* **Can contain letters, numbers, and underscores**:
    * `user_id_2` (Good)
    * `total_sum` (Good)
* **Case-sensitive**: `my_variable` is different from `My_Variable`. Python treats them as two completely separate variables.
* **Avoid Python keywords**: Don't use words that Python already uses for special purposes (like `if`, `for`, `while`, `print`, `True`, `False`, etc.). You'll get an error if you try.

**Good Naming Practices (for readability):**

* Use descriptive names: `student_name` is better than `sn`.
* Use `snake_case`: This is the most common convention in Python, where words are separated by underscores (e.g., `total_score`, `first_name`).

## 3. Using Variables

Once you've created a variable, you can use its name to access the value it holds.

**Examples:**

```python
greeting = "Hello"
person = "Bob"

message = greeting + ", " + person + "!" # We're using the values from 'greeting' and 'person'

print(message)  # This will print: Hello, Bob!

num1 = 10
num2 = 5

sum_result = num1 + num2 # Performing an operation using variable values
print(sum_result) # This will print: 15
```

## 4. Changing Variable Values (Reassignment)

You can change the value a variable holds at any point in your program. When you assign a new value to an existing variable, the old value is overwritten.

**Example:**

```python
score = 100
print(score)  # Prints: 100

score = 150   # Now 'score' holds a new value
print(score)  # Prints: 150

name = "Charlie"
print(name)   # Prints: Charlie

name = "David"
print(name)   # Prints: David
```

## 5. Multiple Assignment

You can assign the same value to multiple variables at once:

```python
x = y = z = 0
print(x) # Prints: 0
print(y) # Prints: 0
print(z) # Prints: 0
```

You can also assign different values to multiple variables on a single line:

```python
a, b, c = 1, 2, "hello"
print(a) # Prints: 1
print(b) # Prints: 2
print(c) # Prints: hello
```

---

And that's the basics of Python variables! They are fundamental building blocks for any program you write.