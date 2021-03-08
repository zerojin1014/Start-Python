# Start-Python

```python
def GuGu(n):
    result = []
    i = 1
    while i < 10:
        result.append(n*i)
        i = i +1
    # result.append(n*1)
    # result.append(n*2)
    # result.append(n*3)
    # result.append(n*4)
    # result.append(n*5)
    # result.append(n*6)
    # result.append(n*7)
    # result.append(n*8)
    # result.append(n*9)    
    return result
    
n= int(input("구구단 몇단을 외울까요?"))
print(GuGu(n))
```

a,b = input().split()
a=int(a)
b=int(b)
print(a+b)