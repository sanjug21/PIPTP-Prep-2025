## Find the output of the following pseudocode

### Pseudocode:

```
Integer p,q,r
Set p = 9 , q = 6 , r = 10
if((q^p^r)>(r^q)) r = (11&12) + q
End if
if ((q ^ (6 ^ 8)) > (p ^ 4)) p= (r + 3) \&r
End if
Print p+q+r
```

---

### Python Code:

```python
p = 9
q = 6
r = 10

if((q^p^r)>(r^q)):
    r = (11&12) + q
if ((q ^ (6 ^ 8)) > (p ^ 4)):
    p= (r + 3) & r
print(p+q+r)


```

---

### Input:

- Initial values `p = 9 , q = 6 , r = 10`


---
### Output:



- Ouput **25**
