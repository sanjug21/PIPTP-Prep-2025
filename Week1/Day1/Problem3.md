## Find the output of the following pseudocode for `a = 8`, `b = 8`

### Pseudocode:

```
Integer fun(Integer a, Integer b) 
    if (a && b && a+b > 0)
        return a + fun(a-2, b-2) + b
    End if
    return a ^ b
End function fun()

Note: && is Logical And, ^ is Bitwise Or
```

---

### Python Code:

```python
def fun(a, b):
    if a and b and (a + b > 0):
        return a + fun(a - 2, b - 2) + b
    return a ^ b
```

---

### Output:

Here, `a = 8` and `b = 8`.  
`fun(8, 8)` returns:  **`40`**