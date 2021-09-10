## AppBar

> https://api.flutter.dev/flutter/material/AppBar-class.html

应用栏目。

### api

* elevation: 阴影。
* backgroundColor: 背景颜色。
* shape: 下边框。
  
  ```
  Border(bottom: BorderSide(color: Color(0xfff1f2f3), width: 1))
  ```
  
* title: 导航标题。
* actions: 右侧小组件。
* leading: 左侧导航配置。

  ```
  leading: IconButton(
    icon: Icon(Icons.arrow_back_ios_new),
    onPressed: () {}
  )
  ```