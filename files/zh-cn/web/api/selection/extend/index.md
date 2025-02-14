---
title: Selection.extend()
slug: Web/API/Selection/extend
---

{{ ApiRef("DOM") }}{{SeeCompatTable}}

**`Selection.extend()`** 方法移动选中区的焦点到指定的点。选中区的锚点不会移动。选中区将从锚点开始到新的焦点，不管方向。

## 语法

```
sel.extend(node, offset)
```

### 参数

- _node_
  - : 焦点会被移至此节点内。
- _offset_ {{optional_inline}}
  - : 焦点会被移至 `node` 内的偏移位置。如果没有指定，使用 `0` 作为默认值。

## 规范

{{Specifications}}

## 浏览器兼容性

{{Compat("api.Selection.extend")}}

## 相关链接

- {{domxref("Selection")}}, 此方法所属接口。
