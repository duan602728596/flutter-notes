## Container

### 设置宽高

```
Container(
  constraints: BoxConstraints(
    minHeight: 50.0,
    maxHeight: 400.0
  )
);

```

### 边框

```
decoration: BoxDecoration(
  border: Border.all(color: Colors.blueAccent)
)

BoxDecoration(
  border: Border(
    left: BorderSide(
      color: Colors.black,
      width: 3.0,
    ),
    top: BorderSide(
      color: Colors.black,
      width: 3.0,
    ),
  ),
);
```

### 设置形状

> https://juejin.cn/post/6844903812264640519