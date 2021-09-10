## GestureDetector

> https://api.flutter.dev/flutter/widgets/GestureDetector-class.html

### 取消input的焦点

```
GestureDetector(
  behavior: HitTestBehavior.translucent,
  onTap: () {
    // 触摸收起键盘
    FocusScope.of(context).requestFocus(FocusNode());
  },
  child: Text('')
);
```