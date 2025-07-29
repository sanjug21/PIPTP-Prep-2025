## Find the output of the following pseudocode for `a = 7`, `b = 5`

### Pseudocode:

```
Integer fun(Integer a, Integer b)
    Integer c
    for (each c from 2 to 4)
        if (a mod 2 < b mod 3)
            a = 4 mod 3
        Else
            if (5 mod 3 > b)
                a = b
            End if
            b = 1
        End if
    End for
    return a + b
End function fun()
```

---

### Python Code:

```python
def fun(a, b):
    for c in range(2, 5):
        if a % 2 < b % 3:
            a = 4 % 3
        else:
            if 5 % 3 > b:
                a = b
            b = 1
    return a + b
```

---

Given: `a = 7`, `b = 5`

After loop: `a = 1`, `b = 5`

---

### Final Output: **`6`**