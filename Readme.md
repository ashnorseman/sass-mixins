# Sass mixin の 日常

- `clearfix`: 清除浮动
- `ellipsis`: 超长文字自动截断，加省略号
- `full-size($position: absolute)`: 占据父元素的全部空间，父元素需不为 `static`
- 模态框
    - `modal`: 相对于 viewport 居中显示（宽高不限），未打开状态
    - `modal-opened`: 打开状态，与 `modal` 叠加使用
    - `modal-mask`: backdrop 效果，打开模态框后，在 `body` 上添加（未指定颜色）
- `ratio($w, $h)`: 设置元素的宽高比
- `square($size)`: 正方形元素，内容为单行文字，水平、垂直居中
