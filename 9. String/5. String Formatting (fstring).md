### Code

```python
# f-String (Formatted String)

# String formatting using format()

template = "Dear {}, You are awesome. Take this {}$ bag"

a = "John"
a1 = 10000
b = "Jack"
b1 = 1000
c = "Marie"
c2 = 300

# Using the format() method
s1 = template.format(a, a1)
print(s1)

# Using an f-string
print(f"{a} you are awesome and take this {a1}$ bag")
```

### Output

```text
Dear John, You are awesome. Take this 10000$ bag
John you are awesome and take this 10000$ bag
```

### Note

**f-strings (Formatted Strings)** provide a simple and readable way to insert variables and expressions directly into a string.

### 1. Using `format()`

```python
template = "Dear {}, You are awesome. Take this {}$ bag"

name = "John"
money = 10000

print(template.format(name, money))
```

**Output**

```text
Dear John, You are awesome. Take this 10000$ bag
```

- `{}` acts as a placeholder.
- The values passed to `format()` replace the placeholders in order.

### 2. Using f-strings (Recommended)

```python
name = "John"
money = 10000

print(f"{name} you are awesome and take this {money}$ bag")
```

**Output**

```text
John you are awesome and take this 10000$ bag
```

- Prefix the string with `f`.
- Place variables or expressions inside `{}`.
- Python automatically replaces them with their values.

### f-Strings Can Also Evaluate Expressions

```python
x = 10
y = 20

print(f"Sum = {x + y}")
print(f"Product = {x * y}")
```

**Output**

```text
Sum = 30
Product = 200
```

### Comparison

| Method | Example | Readability |
|---------|---------|-------------|
| Concatenation | `"Hello " + name` | Less readable |
| `format()` | `"Hello {}".format(name)` | Good |
| **f-string** | `f"Hello {name}"` | ⭐ Best (Python 3.6+) |

### Summary

- `format()` replaces placeholders `{}` with supplied values.
- **f-strings** are the modern and preferred way to format strings.
- They are easier to read, faster, and allow variables and expressions directly inside `{}`.
- Use **f-strings** whenever possible in Python 3.6 and later.