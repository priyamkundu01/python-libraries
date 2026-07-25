### Code

```python
# Slicing

name = "Harry0123456789"

# print(name[0:2])   # Goes from index 0 to 2-1 (0 to 1)

# print(name[2:-1])  # From index 2 to the last character (excluding the last)

# print(name[0:10:n])  # Skip n-1 characters

print(name[0:10:1])  # Skip 0 characters (step = 1)
print(name[0:10:3])  # Skip 2 characters (step = 3)

print(name[:4])      # Same as name[0:4]
print(name[1:])      # Same as name[1:len(name)]
```

### Output

```text
Harry01234
Hr03
Harr
arry0123456789
```

### Note

#### String Index

```text
String:    H  a  r  r  y  0  1  2  3  4  5  6  7  8  9
Index:     0  1  2  3  4  5  6  7  8  9 10 11 12 13 14
```

### String Slicing Syntax

```python
string[start : stop : step]
```

- **start** → Starting index (inclusive)
- **stop** → Ending index (exclusive)
- **step** → Number of positions to move each time

### Explanation

| Expression | Result | Explanation |
|------------|--------|-------------|
| `name[0:10:1]` | `Harry01234` | Starts at index `0`, ends before `10`, takes every character. |
| `name[0:10:3]` | `Hr03` | Starts at `0`, ends before `10`, takes every 3rd character (`0, 3, 6, 9`). |
| `name[:4]` | `Harr` | Omits the start index, so Python assumes `0`. |
| `name[1:]` | `arry0123456789` | Omits the stop index, so Python goes to the end of the string. |

### Key Points

- The **start index is included**.
- The **stop index is excluded**.
- The **step** determines how many positions to move after each character.
- If the **start** is omitted, Python uses `0`.
- If the **stop** is omitted, Python uses the length of the string.
- The default value of **step** is `1`.