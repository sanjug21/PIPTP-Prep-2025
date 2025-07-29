## Find the output of the following pseudocode if `w = 40` and `x = 4`

### Pseudocode:

```
void fun(Integer w , Integer x )
    Integer y
    Set y = 0
    if (x mod w EQUALS 0 || w mod x EQUALS 0)
        Set y = y + 1
    Else
        Set y = y + 10
    End if
    Print y
End function fun()
```

---

### Python Code:

```python
def fun(w, x):
    y = 0
    if x % w == 0 or w % x == 0:
        y += 1
    else:
        y += 10
    print(y)
```

---

### Output:

Here when `w = 40`, `x = 4`.  
`fun(40, 4)` returns: **`1`**