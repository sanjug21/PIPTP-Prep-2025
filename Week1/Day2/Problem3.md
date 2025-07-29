## Find the output of the following pseudocode

### Pseudocode:

```
Integer pp, qq, rr
Set pp=0, qq = 6 rr = 7
pp=rr+pp
pp=(rr&4)^rr
if((qq&pp&rr)<(rr&qq))
if((qq^pp)<(rr+qq))
rr = (3 + 1) ^ pp
End if
End if
Print pp+qq+rr
End
```

---

### Python Code:

```python
pp = 0
qq = 6
rr = 7
pp = rr + pp
pp = (rr & 4) ^ rr
if ((qq & pp & rr) < (rr & qq)):
    if ((qq ^ pp) < (rr + qq)):
        rr = (3 + 1) ^ pp
print(pp + qq + rr)


```

---

### Input:

- Initial values `pp = 0, qq = 6, rr = 7`

---
### Output:



- Ouput **16**
