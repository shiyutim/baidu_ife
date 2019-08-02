# 2019/6/30 day17 and day18    JavaScript
1. `Switch`语句用来选择多个需要被执行的代码块。
    * 把表达式的值与每个`case`的值进行对比
    * `break`，如果JavaScript遇到`break`关键词，会跳出`switch`代码块。
    * `default`关键词规定不存在case匹配时所运行的代码。
2. `do/while` 循环,在检查条件是否为真之前，会先执行一次代码块
3. `break`用于跳出循环；`continue`用于跳过循环。
4. `constructor`属性可以返回所有JavaScript变量的构造器函数
    ```
    console.log("bill".constructor);
    // function String()
    ```
5. 在正则表达式中:
* `search()方法`使用表达式来搜索匹配，然后返回匹配的位置。
* `replace()方法`返回模式被替换处修改后的字符串。
* `test()方法`搜索字符串，然后根据结果返回true或false。
* `exec()方法`搜索字符串，并返回已找到的文本。
6. `==`判断只是否相等，`===`判断数据类型和值是否都相等。
7. `indexOf()`方法判断字符串是否在这个值里面，不存在返回-1。
8. 使用`[][]`能够查看第二个嵌套的数组项。
9. `toLowerCase()和toUpperCase()`方法用来转换大小写。
10. `replace()`方法可以用来替换。
11. `slice()`方法将返回指定参数位置的值。如果有两个参数，则返回起始和结束位置之间的项，但不包括结尾位置的项。
```
var colors = ["red", "yellow", "blue", "orange"];
var colors2 = colors.slice(1); // ["yellow", "blue", "orange"]
var colors3 = colors.slice(1, 3);  // ["yellow", "blue"]
```
12. `splice()`方法能够进行：
* 删除：`splice(1, 2)`1是要删除位置，2是删除项数。
* 插入：`splice(1, 0, "red", "green")`1是要插入的位置，0是要删除的项，剩下两个是要插入的项
* 替换：`splice(1, 2, "red", "green")`1是起始位置，2是要删除的项，剩下两个是要替换的项
13. `indexOf()`和`lastIndexOf()`是用来查找的。接收两个参数，要查找的项和表示查找起点位置的索引。`indexOf()`从前向后查找，`lastIndexOf()`相反。如果没找到，返回-1。