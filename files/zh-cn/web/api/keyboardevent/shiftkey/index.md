---
title: KeyboardEvent.shiftKey
slug: Web/API/KeyboardEvent/shiftKey
---

{{APIRef("DOM Events")}}

**`KeyboardEvent.shiftKey`** 只读属性返回一个 {{jsxref("Boolean")}} 值，表示事件触发时 <kbd>shift</kbd> 键是 (`true`) 否 (`false`) 按下。

## 语法

```
var shiftKeyPressed = instanceOfKeyboardEvent.shiftKey
```

### 返回值

布尔值

## 示例

```js
<html>
<head>
<title>shiftKey example</title>

<script type="text/javascript">

function showChar(e){
  alert(
    "Key Pressed: " + String.fromCharCode(e.charCode) + "\n"
    + "charCode: " + e.charCode + "\n"
    + "SHIFT key pressed: " + e.shiftKey + "\n"
    + "ALT key pressed: " + e.altKey + "\n"
  );
}

</script>
</head>

<body onkeypress="showChar(event);">
<p>Press any character key, with or without holding down
 the SHIFT key.<br />
You can also use the SHIFT key together with the ALT key.</p>
</body>
</html>
```

## 规范

{{Specifications}}

## 浏览器兼容性

{{Compat("api.KeyboardEvent.shiftKey")}}

## 参考

- {{ domxref("KeyboardEvent") }}
