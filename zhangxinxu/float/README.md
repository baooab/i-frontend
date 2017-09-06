## float

### 原本作用

`float` 原本的作用是 [实现文字环绕][1]。

### 浮动特性

包裹和破坏。

#### 包裹

包裹的表现：

1. 元素宽高由内容撑开。大约等于内容的宽和高。
2. 隔绝。BFC，浮动元素内部内容不干扰外部元素。

其它具有包裹性的属性：

1. `display: inline-block` 和 `display: table-cell`。
2. `position: absolute`（float 近亲）、`position: fixed` 和 `position: sticky`。
3. `overflow: hidden` 和 `overflow: scroll`。

#### 破坏

浮动元素的父元素的高度塌陷。

其它具有破坏性的属性：

1. `display: none`。
2. `position: absolute`（float 近亲）、`position: fixed` 和 `position: sticky`。

### float 元素让父级元素高度塌陷



[1]: https://codepen.io/zhangbao/full/mMBaRQ
