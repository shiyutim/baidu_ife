# 2019/05/23  Day2  用时：2.5H 学习html里的各种标签
### 问题：html是什么，HTML5是什么，HTML语义化。
* HTML（Hyper Text Markup Language）是用来描述网页的一种语言，是一种标记语言，主要使用标签来描述网页。
* 标题是通过 h1-h6标签进行定义的，但请不要为了显示粗体而使用这个标签。
* 写标签的时候一定不要忘了写结束标签。虽然在浏览器中显示没有问题，但不要依赖这种做法。
* 使用```<br>```（定义换行）标签的时候使用```<br/>```是长远的保障。
* 建议标签全部用小写。
* 使用```<!-- -->```进行注释。浏览器不会把注释显示在页面上。
* 引用样式可以使用三种方法： 外部样式表、内部样式表和内联样式。
* 在a标签中使用target属性可以定义打开新窗口。```target="_blank"```。
* 使用```name```属性和```href```属性，定义锚，可以用来在页面中上下跳转。
* 在```table```表格中，如果其中一个表格里没有数据，可能显示不完整，这时候可以在空单元格中加入一个占位符```&nbsp；``` ，这样就可以将表框显示出来。
* 有时候刚接触的时候不容易分清```th```（table head）和td（table data）的区别。其实可以把th里的h想象成标题标签。（标题一般都是加粗的）
* 无序列表```ul>li ```有序列表``` ol>li ```定义列表 ```dl>dt>dd```。
* 块元素``` <h1> <p> <ul> <table> <div> ```
* 内联元素 ```<b> <td> <a> <span> <img>```
* HTML语义元素``` header```定义文档或节的页眉``` nav``` 定义导航链接的容器 ```section```定义文档中的节```article```	定义独立的自包含文章``` aside```	定义内容之外的内容（比如侧栏）```footer```	定义文档或节的页脚
* 响应式web设计是指能够可变尺寸传递网页，能够适应平板和移动设备。
* ```iframe```用于在网页内显示网页```<iframe src="url"></iframe>```
* ```<head>```标签里，```title```代表页面的标题，是必须需要的。```link ```标签定义文档与外部资源之间的关系。 
```style ```标签用于为HTML文档定义样式信息。```meta``` 标签提供关于HTML文档的元数据。```script```标签定义客户端脚本。
* 颜色```color``` 可以使用三种方式来书写。```#ffffff；rgb(255, 255, 255);white```。
*``` <!DOCTYPE>``` 是用来声明文档的类型。``` <!DOCTYPE html> ```用来声明HTML5类型的文档。
* ```action```属性用来定义表单提交的页面；```method``` 属性规定在提交表单时所用的HTTP方法。如```GET```或```POST```
*``` form```里要想正确的被提交，每个输入字段必须设置一个```name```属性。
* ```select```定义下拉列表 ```select>option```
* ```HTML5 ```是最新的HTML标准，提供了丰富的web内容，拥有新的语义、图形和多媒体元素等。
* 所谓语义化，我理解的是让机器和人能够更好的理解所写的代码。在写的过程中，用适合的标签表达对应的东西。
HTML5新增的一系列标签都是为了让其更加语义化，如```<header> <nav> <footer>```等；这些标签能够更加容易理解。