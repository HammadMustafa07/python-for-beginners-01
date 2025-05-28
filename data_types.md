# Python Data Types: What are They?

Welcome to Python! When you work with information in your programs, Python needs to know what *kind* of information it is. This "kind" is called a **data type**.

Think of it like sorting toys: you have blocks, cars, and dolls. Each is a different "type" of toy. Python does the same with data!

Python figures out the data type automatically, so you don't always have to tell it. But knowing the types helps you understand what you can do with your data.

Here are the most common data types you'll use:

---

## 1. Numbers

For working with mathematical values.

* **`int` (Integers):** Whole numbers, like counting numbers.
    * Examples: `5`, `-10`, `0`
    ```python
    apples = 3
    students = 25
    ```

* **`float` (Floating-Point Numbers):** Numbers with a decimal point.
    * Examples: `3.14`, `-0.5`, `99.99`
    ```python
    price = 19.99
    temperature = 23.5
    ```

---

## 2. Text

For storing words and sentences.

* **`str` (Strings):** Any sequence of characters (letters, numbers, symbols). You put them in single (`' '`) or double (`" "`) quotes.
    ```python
    name = "Alice"
    greeting = 'Hello there!'
    ```

---

## 3. True/False Values

For making decisions.

* **`bool` (Booleans):** Represents either `True` or `False`. Used for logic.
    ```python
    is_raining = True
    is_finished = False
    ```

---

## 4. Collections of Items

For holding multiple pieces of data.

* **`list` (Lists):** An ordered group of items. You put them in square brackets `[ ]`. You can change items in a list.
    ```python
    colors = ['red', 'green', 'blue']
    numbers = [1, 2, 3, 4]
    ```

* **`tuple` (Tuples):** An ordered group of items. You put them in parentheses `( )`. Once a tuple is made, you **cannot** change its items.
    ```python
    coordinates = (10, 20)
    days_of_week = ('Mon', 'Tue', 'Wed')
    ```

* **`dict` (Dictionaries):** A collection of items stored as `key: value` pairs. Think of it like a real dictionary where a word (key) has a definition (value). You put them in curly braces `{ }`.
    ```python
    person = {'name': 'Bob', 'age': 25}
    car = {'make': 'Toyota', 'model': 'Camry'}
    ```

* **`set` (Sets):** An unordered collection of *unique* items. Duplicates are automatically removed. You put them in curly braces `{ }`.
    ```python
    unique_numbers = {1, 2, 3, 2, 1} # This becomes {1, 2, 3}
    ```

---

## 5. No Value

* **`NoneType` (`None`):** This special type means "no value" or "nothing."
    ```python
    empty_result = None
    ```

---

## How to Check a Data Type

You can always find out a variable's data type using the `type()` function:

```python
age = 30
print(type(age))        # Output: <class 'int'>

city = "New York"
print(type(city))       # Output: <class 'str'>
```

---

That's it for the basic data types! Understanding these will give you a strong start in Python.