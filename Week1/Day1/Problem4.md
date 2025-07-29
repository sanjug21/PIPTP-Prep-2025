## Find the output of the following pseudocode

### Pseudocode:

```
Integer a, b
Set a = 3, b = 3
a = b
if (1 ^ 1)
    a = 1
Else
    b = 2
End if
Print a + b
```

---

### Python Code:

```python
a, b = 3, 3
a = b
if 1 ^ 1:
    a = 1
else:
    b = 2
print(a + b)
```

---

### Output:

`1 ^ 1` is bitwise XOR → result is `0`, so the `else` block runs.  
- `a = 3`, `b = 2`  
So the result of `a + b` is:  **`5`**