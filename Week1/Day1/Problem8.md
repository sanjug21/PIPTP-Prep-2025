## Find the output of the following pseudocode

### Pseudocode:

```
Integer a, b, c
Set a = 2, b = 4, c = 2
if (b - a)
    b = a ^ b
    a = c
    if (b)
        a = a ^ b
    End if
    b = b - 1
End if
if (c)
    a = b
End if
Print a + b + c
```

---

### Python Code:

```python
a, b, c = 2, 4, 2

if b - a:
    b = a ^ b
    a = c
    if b:
        a = a ^ b
    b = b - 1

if c:
    a = b

print(a + b + c)
```

---

 Initial: `a = 2`, `b = 4`, `c = 2`

 Final values: `a = 5`, `b = 5`, `c = 2`  

---

### Final Output: **`12`**
