### CSS 笔记
  * 语法
  * CSS 规则由两个主要的部分构成：选择器，以及一条或多条声明:
  * id 和 class 选择器
  * 外部样式表、内部样式表、内联样式
  * 多重样式（继承、优先级）
  * 优先级别：内联样式）Inline style > （内部样式）Internal style sheet >（外部样式）External style sheet > 浏览器默认样式
  * 背景的四个属性： background-color、background-image、background-repeat、background-attachment、background-position
  * 文本：文本格式、文本颜色、本的对齐方式、文本修饰、文本转换、文本缩进（文本缩进属性是用来指定文本的第一行的缩进。）
  * 字体： 字型、字体系列、字体样式、字体大小（16px=1em）、设置字体大小像素、用em来设置字体大小
  * 链接： a:link - 正常，未访问过的链接、a:visited - 用户已访问过的链接、
    a:hover - 当用户鼠标放在链接上时、a:active - 链接被点击的那一刻（先后顺序，L、V、H、A）
    文本修饰、背景颜色
  * 列表: 无序列表、有序列表；不同的列表项标记、作为列表项标记的图像；list-style-type、list-style-position、list-style-image
  * 表格：表格边框（border）、 折叠边框（border-collapse）、 表格宽度和高度、表格文字对齐、表格填充、表格颜色
  * 盒子模型：Margin(外边距)、Border(边框)、Padding(内边距)、Content(内容)、元素的宽度和高度（边框及边距）
  * 边框：边框属性、边框样式（border-style:dotted solid double dashed;）；边框-简写属性、border-width、border-style (required)、border-color
  * 轮廓（outline）：outline-color、outline-style、outline-width、inherit
  * Margin(外边距)
  * Padding（填充）
  * CSS 分组 和 嵌套 选择器
  * Display(显示) 与 Visibility（可见性）；visibility:hidden可以隐藏某个元素，
    但隐藏的元素仍需占用与未隐藏之前一样的空间。也就是说，该元素虽然被隐藏了，但仍然会影响布局。
    display:none可以隐藏某个元素，且隐藏的元素不会占用任何空间。也就是说，该元素不但被隐藏了，
    而且该元素原本占用的空间也会从页面布局中消失。
  * Display - 块和内联元素 （可以设置 display 改变）
  * Positioning(定位): static、 relative（相对定位元素的定位是相对其正常位置。）、fixed、
    absolute（绝对定位的元素的位置相对于最近的已定位父元素，如果元素没有已定位的父元素，那么它的位置相对于<html>:）
  * 重叠的元素： z-index属性指定了一个元素的堆叠顺序（哪个元素应该放在前面，或后面）
  * Float(浮动)：元素怎样浮动，彼此相邻的浮动元素
  * 清除浮动 - 使用 clear
  * 布局 - 水平 & 垂直对齐；元素居中对齐（Margin: auto;）; 文本居中对齐(text-align: center;); 图片居中对齐(margin: auto;)
    左右对齐 - 使用定位方式(position: absolute;); 左右对齐 - 使用 float 方式;
    垂直居中对齐 - 使用 padding(如果要水平和垂直都居中，可以使用 padding 和 text-align: center:)
    垂直居中 - 使用 line-height;(vertical-align: middle;);
  * 垂直居中 - 使用 position 和 transform 这个是超有用 http://www.runoob.com/try/try.php?filename=trycss_align_transform
  * 组合选择符：后代选取器(以空格分隔)、子元素选择器(以大于号分隔）、相邻兄弟选择器（以加号分隔）、普通兄弟选择器（以破折号分隔）
  * 伪类(Pseudo-classes)：a:link、a:visited、a:hover、a:active 、:first - child伪类；
  * 伪元素：:first-line 伪元素， :first-letter 伪元素， :before 伪元素， :after 伪元素。
  * 导航栏：http://www.runoob.com/css/css-navbar.html
  * 下拉菜单：http://www.runoob.com/css/css-dropdowns.html
  * 提示工具(Tooltip)：http://www.runoob.com/css/css-tooltip.html
  * 图片廊：http://www.runoob.com/css/css-image-gallery.html
  * 图像透明/不透明：http://www.runoob.com/css/css-image-transparency.html
  * 图像拼合技术：http://www.runoob.com/css/css-image-sprites.html
  * 媒体类型：http://www.runoob.com/css/css-mediatypes.html
  * 属性 选择器：http://www.runoob.com/css/css-attribute-selectors.html
  * 布局实例： http://www.runoob.com/css/css-examples.html
