# day16 认识JS
1. 防止JS脚本阻塞
* `defer`属性；可以按照脚本在页面中出现的顺序执行
* `async`属性；不会按照脚本出现是顺序执行

如果脚本无需等待页面解析，且无依赖独立运行，那么应使用`async`。

如果脚本需要等待解析，且依赖于其他脚本，调用这些脚本时应该使用`defer`，将关联的脚本按所需顺序置于HTML中。

2. HTML/CSS/JavaScript
* HTML是一种标记语言，用来结构化我们的网页内容并赋予内容含义。
* CSS是一种样式规则语言，可将样式应用于HTML内容。
* JavaScript是一种脚本语言，可以用来创建动态更新的内容，控制多媒体，制作图像动画等。
3. 把脚本置于`body`元素的底部，可改善显示速度，因为脚本编译会拖慢显示
4. 外部JavaScript的优势
* 分离了HTML和代码
* 使HTML和JavaScript更易于阅读和维护
* 已缓存的JavaScript文件可加速页面加载
5. 为了达到最佳可读性，可以把代码控制在80个字符以内。

    如果JavaScript语句太长，对其进行折行的最佳位置是**某个运算符**。
6. JavaScript关键词

    |关键词|描述|
    |:-|:-|
    |break|终止switch或循环|
    |continue|跳出循环并在顶端开始|
    |return|退出函数|
7. 多个单词链接方法
* 连字符：
    ```
    first-name, last-name, master-card, inter-city
    ```
* 下划线：
    ```
    first_name, last_name, master_card, inter_city
    ```
* 驼峰式大小写
    ```
    FirstName, LastName, MasterCard, InterCity
    ```
8. 声明一个变量后没有赋值，其值是`undefined`。
```
var x;
console.log(typeof(x));

undefined
```