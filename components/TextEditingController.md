## TextEditingController

> https://api.flutter.dev/flutter/widgets/TextEditingController-class.html

## 可以通过继承实现富文本

参考：https://juejin.cn/post/6844904017655496711

```
class RichTextEditingController extends TextEditingController {
  @override
  TextSpan buildTextSpan({
    required BuildContext context,
    TextStyle? style,
    required bool withComposing
  }) {
    print(text);

    return TextSpan(text: text);
  }
}
```