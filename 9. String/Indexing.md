### Code

```python
# Indexing

name = "Priyam"

# Characters:
# P   r   i   y   a   m
# 0   1   2   3   4   5
#-6  -5  -4  -3  -2  -1

# print(name[0])
# print(name[1])
# print(name[2])
# print(name[3])
# print(name[4])
# print(name[5])

print(name[-1])
print(name[-2])
print(name[-3])
print(name[-4])  # name[-4 + 6] = name[2]
print(name[-5])
```

### Output

```text
m
a
y
i
r
```

### Note

- **Indexing** is used to access individual characters of a string.
- Python supports two types of indexing:
  - **Positive indexing** starts from the beginning (`0`).
  - **Negative indexing** starts from the end (`-1`).

#### String Index

```text
String:      P   r   i   y   a   m
Positive:    0   1   2   3   4   5
Negative:   -6  -5  -4  -3  -2  -1
```

#### Explanation

| Expression | Character |
|------------|-----------|
| `name[-1]` | `m` |
| `name[-2]` | `a` |
| `name[-3]` | `y` |
| `name[-4]` | `i` |
| `name[-5]` | `r` |

**Note:** Negative index `-n` is equivalent to `len(name) - n`.

For example:

```python
name[-4] = name[-4 + 6] = name[2] = 'i'
```
