## Find the output of the following pseudocode

### Pseudocode:

```
Integer a, b, c
Set a = 2, b = 3
for (each c from 4 to 6)
    a = a + b
    if (a > 4)
        a = 0
    End if
    if (a + 2) 
        b = a + 10
    Else
        Jump out of the loop
    End if
    b = a + 1
End for
Print a + b
```

---

### Python Code:

```python
a, b = 2, 3

for c in range(4, 7):
    a = a + b
    if a > 4:
        a = 0
    if a + 2:
        b = a + 10
    else:
        break
    b = a + 1

print(a + b)
```

---

#### Initial values: `a = 2`, `b = 3`

---

#### Final values: `a = 3`, `b = 4`

---

### Final Output: **`7`**
