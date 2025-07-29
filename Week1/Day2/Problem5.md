## Find the output of the following pseudocode

### Pseudocode:

```
Integer pp,qq,rr
Set pp = 1 , qq = 2 , rr = 8
if( (5 + 8) <(7+ qq))
if((qq+pp)<(pp=qq))
    rr = (rr + 6) + rr
    rr=(qq+pp)+pp
End if
    rr=rr+pp
Else
if((pp+qq-rr)<(rr+pp))
pp=pp+rr
End if
rr=(pp&rr)+pp
End if
Print pp+qq+rr

```

---

### Python Code:

```python
pp,qq,rr=1,2,8
if((5+8)<(7+qq)):
    if((qq+pp)<(pp==qq)):
        rr=(rr+6)+rr
        rr=(qq+pp)+pp
    else:
        rr=rr
else:
    if((pp+qq-rr)<(rr+pp)):
        pp=pp+rr
    rr=(pp&rr)+pp
print(pp+qq+rr)



```

---

### Input:

- Initial values `pp=1,qq=2,rr=8`



---
### Output:



- Ouput **28**
