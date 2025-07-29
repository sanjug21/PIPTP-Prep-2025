## Find the output of the following pseudocode

### Pseudocode:

```
Integer funn (Integer a, Integer b, Integer c)
b = 7 + a
a=(a+c)+a
b=(b+b)+c
c = 1 + b
return a+b+c
End function funn()
```

---

### Python Code:

```python
def funn(a, b, c):
    b = 7 + a
    a = (a + c) + a
    b = (b + b) + c
    c = 1 + b
    return a + b + c
```

---

### Input:

- Input values `a=1`,`b=2`,`c=3`

---
### Output:



- Ouput **59**
