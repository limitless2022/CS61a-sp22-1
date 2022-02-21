

### for 语句中的序列解包

```python
pairs = [[1, 2], [2, 2], [3, 2], [4, 4]]
same_count = 0

for x, y in pairs:
    if x == y:
        same_count = same_count + 1
```

### range

如果只有一个参数，范围从 0 开始并在它之前结束：

```
📄for num in range(6):
    print(num)       # 0, 1, 2, 3, 4, 5
```

如果有两个参数，范围从第一个开始并在第二个之前结束：

```
📄for num in range(1, 6):
    print(num)       # 1, 2, 3, 4, 5
```