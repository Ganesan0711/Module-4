
# Dictionary: Python Program to Sort a Dictionary by Keys and Values

## 🎯 Aim
To write a Python program to sort a dictionary alphabetically by keys and values.

## 🧠 Algorithm
1. Start the program.
2. Define a dictionary with key-value pairs.
3. Sort the dictionary by keys using `sorted(dictionary.items())`.
4. Convert the sorted items into a dictionary using `dict()`.
5. Sort the dictionary by values using `sorted()` with a lambda function.
6. Convert the sorted items into a dictionary.
7. Display the original and sorted dictionaries.
8. End the program.

## 🧪 Program

```python
dictionary = {
    'b': 'banana',
    'a': 'apple',
    'd': 'orange',
    'c': 'cherry'
}

# Sort dictionary by keys
sorted_by_keys = dict(sorted(dictionary.items()))

# Sort dictionary by values
sorted_by_values = dict(
    sorted(dictionary.items(), key=lambda item: item[1])
)

print("Original Dictionary:", dictionary)
print("Dictionary sorted by keys:", sorted_by_keys)
print("Dictionary sorted by values:", sorted_by_values)
```

## 💻 Sample Output

```text
Original Dictionary: {'b': 'banana', 'a': 'apple', 'd': 'orange', 'c': 'cherry'}

Dictionary sorted by keys: {'a': 'apple', 'b': 'banana', 'c': 'cherry', 'd': 'orange'}

Dictionary sorted by values: {'a': 'apple', 'b': 'banana', 'c': 'cherry', 'd': 'orange'}
```

## ✅ Result
Thus, the Python program to sort a dictionary alphabetically by keys and values was executed successfully.
