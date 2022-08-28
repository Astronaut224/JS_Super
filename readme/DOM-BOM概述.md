# DOM

文档对象模型(document object model)

- DOM就是把文档（网页）当作一个对象来看待
- DOM的顶级对象是document
- 主要作用是操作页面元素

1. 文档：一个页面就是一个文档，用document表示
2. 元素：所有标签都是元素，用element表示
3. 节点：网页中所有内容都是节点（标签、属性、注释等），用node表示

**DOM把以上内容都看作对象**。

# BOM

浏览器对象(browser object model)

- 把浏览器当作一个对象来看待
- BOM的顶级对象是window
- 主要作用是浏览器窗口的一些交互

window是一个全局对象，定义在全局作用域的变量、函数都会变成window对象的属性、方法。

调用时可以省略window，如alert()、prompt()等。

注意：window有一个特殊属性window.name，输出为空，一般不要使用name这个变量名。



