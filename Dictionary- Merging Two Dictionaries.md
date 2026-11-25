
# Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program to merge two dictionaries and combine their key-value pairs using the `**` unpacking operator.

## 🧠 Algorithm
1. Define two dictionaries named `dict1` and `dict2`.
2. Define a function named `merge()` to merge the dictionaries.
3. Use the `**` unpacking operator to combine both dictionaries.
4. If a key exists in both dictionaries, the value from `dict2` overwrites the value from `dict1`.
5. Call the `merge()` function.
6. Print the merged dictionary.

## 🧾 Program

```python
def merge(dict1, dict2):
    merged_dict = {**dict1, **dict2}
    return merged_dict

dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'c': 40, 'd': 50, 'e': 60}

result = merge(dict1, dict2)

print("Merged Dictionary:", result)
```

## 💻 Output

```text
Merged Dictionary: {'a': 10, 'b': 20, 'c': 40, 'd': 50, 'e': 60}
```

## ✅ Result
Thus, the Python program to merge two dictionaries using the `**` unpacking operator was executed successfully.
