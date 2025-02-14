---
title: HTMLMediaElement.loop
slug: Web/API/HTMLMediaElement/loop
---

{{APIRef("HTML DOM")}}**`HTMLMediaElement.loop`** 属性是 HTML 标签 {{htmlattrxref("loop", "video")}} 属性的映射，它决定了媒体元素播放结束时是否重新开始。

> **备注：** 原文：The **`HTMLMediaElement.loop`** property reflects the {{htmlattrxref("loop", "video")}} HTML attribute, which controls whether the media element should start over when it reaches the end.

## 语法

```js
var loop = video.loop;
audio.loop = true;
```

### 返回值

一个布尔值 {{domxref("Boolean")}}.

## 示例

```js
var obj = document.createElement('video');
obj.loop = true; // true
```

## 规范

{{Specifications}}

## 浏览器兼容性

{{Compat("api.HTMLMediaElement.loop")}}

## 相关链接

- The interface defining it, {{domxref("HTMLMediaElement")}}.
