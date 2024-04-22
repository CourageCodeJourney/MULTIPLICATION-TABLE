**Line 1:**

```python
num = int(input("Display multiplication table of? "))
```

- **`input("Display multiplication table of? ")`**: This part prompts the user to enter a number. The `input` function takes a string argument (the message to display) and returns whatever the user types in.
- **`int()`**: This converts the user's input, which is initially a string, into an integer. This is necessary because multiplication requires numerical operands.
- **`num = ...`**: Assigns the converted integer value (the number the user entered) to the variable `num`.

**Line 2-4:**

```python
# Iterate 10 times from i = 1 to 100
for i in range(1, 101):
```

- **`for i in range(1, 101):`**: This line defines a `for` loop that will iterate 100 times. Here's how it works:
    - `for`: This keyword indicates the start of a `for` loop.
    - `i`: This is a loop variable (often called a counter) that will take on different values during each iteration of the loop.
    - `in`: This keyword separates the loop variable from the iterable object used for the loop.
    - `range(1, 101)`: This is a built-in Python function that generates a sequence of numbers. Here, it creates a sequence from 1 (inclusive) to 100 (exclusive). So, the values of `i` will be 1, 2, 3, ..., 100 during each iteration.

**Line 5:**

```python
   print(num, 'x', i, '=', num*i)
```

- **`print(...)`**: This function is used to output something to the console.
- **`num, 'x', i, '=', num*i`**: This part is what's actually printed within the `print` function. It's a comma-separated sequence of items that are combined into a single string before being printed. Let's break it down:
    - `num`: The value entered by the user (the number for which the multiplication table is being generated).
    - `'x'` (enclosed in single quotes): This is a literal string, representing the multiplication symbol "x".
    - `i`: The current value of the loop counter (`i`), which represents the number being multiplied by `num`.
    - `=`: Another literal string, representing the equals sign.
    - `num*i`: This calculates the product of `num` and the current value of `i`.
