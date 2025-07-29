## Find the output of the following pseudocode

### Pseudocode:

```
Integer p, q, r
Set p = 1, q = 4, r = 2
if (p ^ q > p & q)
    r = p & q
Else
    r = p ^ q
End if
if (q > r && r > p)
    p = q
End if
Print p - q + r - 2
```

---

### Python Code:

```python
p, q, r = 1, 4, 2

if (p ^ q > p & q):
    r = p & q
else:
    r = p ^ q

if (q > r and r > p):
    p = q

print(p - q + r - 2)
```

---

- Initial values: `p = 1`, `q = 4`, `r = 2`

- Final values: `p = 1`, `q = 4`, `r = 0`

---

### Final Output: **`-5`**
