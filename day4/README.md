# 2019/5/25 Day4 用时： 3H   学习背景设置和更复杂的选择器
* ```background-color``` 不能继承。默认值是 ```transparent```。一个元素如果没指定背景色，那么它就是透明的。
* ```background-repeat``` 可以设置图像是否重复，默认把整个元素的背景填满。常用值有： ```no-repeat、repeat-x``` 和 ```repeat-y```
* ```background-position``` 可以设置图像的位置，属性值可以使用关键字、长度值和百分数值。使用关键字可以最多使用两个。
* ```background-attachment```默认值为```scroll```，就是背景会随着文档滚动。设置```fixed```可以使图像一直固定在当前窗口。
* 因为```background-image```是出现在背景中，它本身并不是图片，只是一个装饰。如果想要在页面上包含一个图片，就需要使用```<img>```元素。
* ```background-image```可以设置渐变，属性为```linear-gradient()```。至少使用三个参数，分别为方向、起始颜色和结尾颜色。
* ```border```没有指定值时，默认使用文本的颜色，宽度为```3px```。
* ```border-radius``` 可以指定两个、三个或四个值。指定三个分别为 左上、右上左下和右下。
* ```list-style-position```可以设置项目符号的位置。
* 如果想在有序列表里从1以上的数字作为开始；可以设置 ```start="n"```； ```reversed```可以启动倒序；```value```可以在```li```里面指定序号。
* ```a:hover``` 必须位于 ```a:link``` 和 ```a:visited``` 之后；```a:active``` 必须位于```a:hover```之后。
*  伪类前面有一个```:``` ，而伪元素前面有两个```::```。
* 选择器
    * 子选择器	A > B	匹配B元素，满足条件：B是A的直接子节点；
    * 相邻兄弟选择器	A + B	匹配B元素，满足条件：B是A的下一个兄弟节点（AB有相同的父结点，并且B紧跟在A的后面；
    * 通用兄弟选择器	A ~ B	匹配B元素，满足条件：B是A之后的任意一个兄弟节点（AB有相同的父节点，B在A之后，但不一定是紧挨着A。
* 相互冲突的声明将按以下顺序适用，后一种将覆盖先前的声明：
    * 在用户代理样式表的声明 (例如：浏览器在没有其他声明的默认样式).
    * 用户样式表中的普通声明（由用户设置的自定义样式）。
    * 作者样式表中的普通声明（这是我们设置的样式，Web开发人员）。
    * 作者样式表中的重要声明
    * 用户样式表中的重要声明
* 如果非必要尽量不用 ```important```。
* 权重比例。```ID```选择器为100；类选择器为10；属性选择器为1。