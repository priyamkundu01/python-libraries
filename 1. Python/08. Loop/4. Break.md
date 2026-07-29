### Code

```python
for i in range(0, 21):
    print(i)
    if i == 11:
        break  # Cancel the execution of this loop now
```

### Output

```text
0
1
2
3
4
5
6
7
8
9
10
11
```

### Note

- `break` is used to **immediately terminate** the loop.
- The loop starts printing numbers from `0` to `20`.
- When `i` becomes `11`, the `break` statement is executed.
- As a result, the loop stops, and numbers `12` to `20` are **not printed**.