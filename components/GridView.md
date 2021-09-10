## GridView

> https://api.flutter.dev/flutter/widgets/GridView-class.html

网格。

### api

* { bool } shrinkWrap: 该属性表示是否根据子组件的总长度来设置ListView的长度，默认值为false 。默认情况下，ListView的会在滚动方向尽可能多的占用空间。当ListView在一个无边界(滚动方向上)的容器中时，shrinkWrap必须为true。
* physics: NeverScrollableScrollPhysics()。禁止滑动。
* controller: ScrollController(keepScrollOffset: false)。禁止回弹效果。

### 例子

```
GridView(
  gridDelegate: SliverGridDelegateWithFixedCrossAxisCount(
    crossAxisCount: 3,    //横轴三个子widget
    childAspectRatio: 1.0 //宽高比为1时，子widget
  ),
  children:<Widget>[
    Icon(Icons.ac_unit),
    Icon(Icons.airport_shuttle),
    Icon(Icons.all_inclusive),
    Icon(Icons.beach_access),
    Icon(Icons.cake),
    Icon(Icons.free_breakfast)
  ]
);
```