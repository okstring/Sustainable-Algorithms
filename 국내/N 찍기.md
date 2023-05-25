https://www.acmicpc.net/problem/2741

```python
for n in range(1, int(input()) + 1): print(n)
```



### another

range마다 \n로 join하기

```python
# 2741 N 찍기
N = int(input())
print("\n".join(map(str, range(1, N + 1))))
```

