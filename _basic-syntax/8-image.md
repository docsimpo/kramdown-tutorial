---
title: 图片
---

在 Markdown 中，插入图片有以下几种方式：

1. [行内一体式](#行内一体式)
2. [脚注式](#脚注式)

# 行内一体式

## 语法描述

插入图片的方法如下：

1. 输入感叹号（`!`）。
2. 输入图片的替换文本（`alt` 属性值），并用方括号（`[]`）括起来。
3. 输入圆括号。
4. 在圆括号内输入图片的网址或路径。
5. 如果需要，在圆括号中图片网址或路径的后面输入图片标题（`title` 属性值），并用引号引起来。网址或路径 与图片标题之间使用空格分隔。

## 示例

```markdown
![印度尼西亚萨母巴岛上的红树林](https://img.peapix.com/f0b899e247da4e6da5a7ac7938f3dc05_480.jpg "漂亮的红树林")
```

```html
<p>
  <img src="https://img.peapix.com/f0b899e247da4e6da5a7ac7938f3dc05_480.jpg" alt="印度尼西亚萨母巴岛上的红树林" title="漂亮的红树林">
</p>
```

<div class='exmp'>
  <div class='exmp-container'>
    <p>
      <img src="https://img.peapix.com/f0b899e247da4e6da5a7ac7938f3dc05_480.jpg" alt="印度尼西亚萨母巴岛上的红树林" title="漂亮的红树林">
    </p>
  </div>
</div>

# 脚注式

## 语法描述

插入图片的脚注式写法与链接的脚注式写法大体相同，只是需要使用插入图片的语法。

## 示例

```markdown
![印度尼西亚萨母巴岛上的红树林][红树林]

[红树林]: https://img.peapix.com/f0b899e247da4e6da5a7ac7938f3dc05_480.jpg "漂亮的红树林"
```

编译后的 HTML 以及输出效果，与上面的图片完全相同。
