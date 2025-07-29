## Find the output of the following pseudocode for `a = 4`, `b = 3`

### Pseudocode:

```
Integer fun(Integer a, Integer b)
    if (a > 0)
        return fun(a - 2, a + b) + fun(a - 3, a + b) + fun(a - 4, a + b)
    Else
        a = b
        b = a
        return a + b
    End if
End function fun()
```

---

### Python Code:

```python
def fun(a, b):
    if a > 0:
        return fun(a - 2, a + b) + fun(a - 3, a + b) + fun(a - 4, a + b)
    else:
        a = b
        b = a
        return a + b
```

---

Given: `a = 4`, `b = 3`

---

### Final Output: **`116`**