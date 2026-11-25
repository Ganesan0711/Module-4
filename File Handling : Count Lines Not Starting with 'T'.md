
# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program to count the number of lines in a text file that do not start with the alphabet 'T'.

## 🧠 Algorithm
1. Create a list containing some text lines.
2. Initialize a counter variable `count` to zero.
3. Iterate through each line using a `for` loop.
4. Check whether the line starts with the letter 'T'.
5. If the line does not start with 'T', increment the counter by 1.
6. Print the total number of lines that do not start with 'T'.

## 🧾 Program

```python
story = [ "The sun is shining.","Python is easy.","This is a story.","Hello everyone.","Today is Monday."]

count = 0

for line in story:
    if not line.startswith('T'):
        count += 1

print("Number of lines not starting with T:", count)
```

## 💻 Output

```text
Number of lines not starting with T: 2
```

## ✅ Result
Thus, the Python program to count the number of lines that do not start with the letter 'T' was executed successfully.
