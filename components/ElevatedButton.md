## ElevatedButton

按钮。

### 例子

```
ElevatedButton(
  style: ButtonStyle(
    backgroundColor: MaterialStateProperty.all(Color.fromRGBO(245, 67, 67, 1)), // 颜色类型为AHEX
    shape: MaterialStateProperty.all( // 带有圆角的矩形边框
      RoundedRectangleBorder(borderRadius: BorderRadius.circular(5.0))
    ),
    side: MaterialStateProperty.all(BorderSide(color: Colors.purple, width: 3))
  ),
  child: Padding(
    child: Text('发表')
  ),
  onPressed: () {}
)
```

### ElevatedButton.icon

带图标的按钮。

```
ElevatedButton.icon(
  icon: Icon(Icons.g_mobiledata),
  label: Text('添加位置'),
  onPressed: () {},
);
```