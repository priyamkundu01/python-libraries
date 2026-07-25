### Code

```python
for i in range(1, 20):
    if i == 10:
        continue  # Continue to the next iteration
    print(i)
```

### Output

```text
1
2
3
4
5
6
7
8
9
11
12
13
14
15
16
17
18
19
```

### Note

- `continue` is used to **skip the rest of the current iteration** and move directly to the next iteration of the loop.
- When `i` becomes `10`, the `continue` statement is executed.
- Therefore, `print(i)` is **not executed** for `i = 10`.
- The loop continues with `i = 11` and prints the remaining numbers up to `19`.