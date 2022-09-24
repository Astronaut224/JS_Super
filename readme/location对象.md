# location对象

| location对象属性  | 返回值                           |
| ----------------- | -------------------------------- |
| location.href     | 获取或者设置整个url              |
| location.host     | 返回主机域名                     |
| location.port     | 返回端口号，如果没有返回空字符串 |
| location.pathname | 返回网页路径                     |
| location.search   | 返回参数 ?a=1&b=2                |
| location.hash     | 返回链接锚点：#后面内容          |



```html
// 和设置location.href一样跳转，记录浏览历史可以回退
location.assign()
// 替换当前页面，不记录浏览历史
location.replace()
// 重新加载页面，相当于刷新，如果参数为true强制刷新
location.reload()
```

# navigator对象

获取浏览器对象的一些信息，常用的如user-Agent，获取打开浏览器的终端。

# history对象

和浏览器的历史进行交互。

| history对象方法   | 左右                                                         |
| ----------------- | ------------------------------------------------------------ |
| history.back()    | 后退功能                                                     |
| history.forward() | 前进功能                                                     |
| history.go(参数)  | 前进后退功能，参数如果是1前进一个页面，如果是-1后退一个页面。 |

