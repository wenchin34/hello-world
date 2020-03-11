# hello-world
It's my 1st homework!

```python
def hanoi(n, A="A", B="B", C="C"):
    if n > 0:
        hanoi(n-1, A, C, B)
        print("Move a Disc from %s to %s" % (A, C))
        hanoi(n-1, B, A, C)

hanoi(4)
```
