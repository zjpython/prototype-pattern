# prototype-pattern
原型模式 
当需要根据现有对象复制出新的对象并对其修改，可以考虑使用“原型模式”
```python
# classics
point6 = copy.deepcopy(point5)
point6.x = 4
point6.y = 6

# more elegant, without copy
point7 = point5.__class__(4, 7)
```

