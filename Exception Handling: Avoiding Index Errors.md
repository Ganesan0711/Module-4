
# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program to handle an `IndexError` when trying to access an element beyond the available range of a list using try-except blocks.

## 🧠 Algorithm
1. Define a list named `list1` with some integer elements.
2. Use a `try` block to access an element at an invalid index.
3. Use an `except` block to catch the `IndexError`.
4. Print the custom error message "You're out of list range".
5. Display the result.

## 🧾 Program

```python
list1 = [10, 20, 30, 40, 50]

try:
    print("Element:", list1[5])

except IndexError:
    print("You're out of list range")
```

## 💻 Output

```text
You're out of list range
```

## ✅ Result
Thus, the Python program to handle an `IndexError` using try-except blocks was executed successfully.
