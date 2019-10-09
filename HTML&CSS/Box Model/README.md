The Box Model

When assigning values to the width and height properties, they actually stand for the content parts.
To maintain the desired values after adding paddings, borders, margins and so on, we could use:
box-sizing:border-box

border
--> border-radius
--> border-top-style

padding: ...
margin: ...

<!-- 在 CSS 中定义 width 和 height 时，它们其实指的是 content 部分的
所以，在定义了 width 和 height 之后，如果又定义了 paddings，borders， margin 等，
最终显示在网页上的 box 就不是想要的长宽比了

为此，可以使用：box-sizing: border-box -->
