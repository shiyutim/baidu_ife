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