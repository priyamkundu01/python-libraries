### Code

```python
# String Methods

s = "hello world"  # Strings are immutable

# s[0] = "R"  # ❌ You cannot modify a string directly

a = len(s)
# print(a)
# print(s.upper(), s)
# print(s.lower())
# print(s.capitalize())
# print(s.title())

# text = " \nhello world "
# print(text.strip())    # Output: "hello world"
# print(text.lstrip())   # Output: "hello world "
# print(text.rstrip())   # Output: " hello world"

# text = "Python is fun and fun and fun"
# print(text.find("is"))            # Output: 7 (Index of first occurrence)
# print(text.replace("fun", "awesome"))

# text = "Apples,Bananas,Pineapples"
# print(text.split(","))
# print(",".join(['Apples', 'Bananas', 'Pineapples']))

text = "Python123"

print(text.isalpha())   # Output: False
print(text.isdigit())   # Output: False
print(text.isalnum())   # Output: True
print(text.isspace())   # Output: False
```

### Output

```text
False
False
True
False
```

### Note

Python strings are **immutable**, which means their characters **cannot be changed** after the string is created.

Example:

```python
s = "hello"
# s[0] = "H"   ❌ TypeError
```

Instead, create a new string:

```python
s = "Hello"
```

### Common String Methods

| Method | Description | Example | Output |
|--------|-------------|---------|--------|
| `len(s)` | Returns the length of the string | `len("hello")` | `5` |
| `upper()` | Converts all letters to uppercase | `"hello".upper()` | `"HELLO"` |
| `lower()` | Converts all letters to lowercase | `"HELLO".lower()` | `"hello"` |
| `capitalize()` | Capitalizes the first letter | `"hello world".capitalize()` | `"Hello world"` |
| `title()` | Capitalizes the first letter of each word | `"hello world".title()` | `"Hello World"` |
| `strip()` | Removes leading and trailing whitespace | `" hello ".strip()` | `"hello"` |
| `lstrip()` | Removes leading whitespace | `" hello".lstrip()` | `"hello"` |
| `rstrip()` | Removes trailing whitespace | `"hello ".rstrip()` | `"hello"` |
| `find()` | Returns the index of the first occurrence of a substring | `"Python".find("th")` | `2` |
| `replace()` | Replaces occurrences of a substring | `"I like Python".replace("Python","Java")` | `"I like Java"` |
| `split()` | Splits a string into a list | `"A,B,C".split(",")` | `['A', 'B', 'C']` |
| `join()` | Joins list elements into a string | `",".join(["A","B","C"])` | `"A,B,C"` |

### String Checking Methods

For the string:

```python
text = "Python123"
```

| Method | Result | Explanation |
|--------|--------|-------------|
| `text.isalpha()` | `False` | Contains both letters and numbers. |
| `text.isdigit()` | `False` | Contains letters, so it is not made of only digits. |
| `text.isalnum()` | `True` | Contains only letters and digits (no spaces or symbols). |
| `text.isspace()` | `False` | Contains letters and numbers, not only whitespace. |

### Summary

- Strings are **immutable**.
- String methods return **new strings**; they do not modify the original string.
- Methods like `upper()`, `lower()`, `replace()`, and `strip()` are commonly used to manipulate strings.
- Methods like `isalpha()`, `isdigit()`, `isalnum()`, and `isspace()` are used to check the contents of a string.