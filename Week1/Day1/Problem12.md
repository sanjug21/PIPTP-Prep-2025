## Find the output of the following pseudocode

### Pseudocode:

```
Integer pp, qq, rr
Set pp = 7, qq = 2, rr = 2
pp = ((pp + pp) ^ ((pp + pp) mod pp)) ^ (pp + pp)
if (pp && qq)
    pp = pp ^ pp
    qq = qq + qq
End if
Print pp + qq + rr
```

---

### Python Code:

```python
pp, qq, rr = 7, 7, 2

pp = ((pp + pp) ^ ((pp + pp) % pp)) ^ (pp + pp)

if pp and qq:
    pp = pp ^ pp
    qq = qq + qq

print(pp + qq + rr)
```

---
- Initial values: `pp = 7`, `qq = 7`, `rr = 2`
- Final values: `pp = 0`, `qq = 7`, `rr = 2`  

---

### Final Output: **`9`**
