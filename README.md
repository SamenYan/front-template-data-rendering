## 前端模板引擎

什么是模板引擎，说的简单点，就是一个字符串待定几个动态变量。通过数据匹配待定变量datamodel输出相应的html代码，提高页面渲染速度、易用性。

#### 1⃣类库框架

- [artTemplate](https://github.com/aui/artTemplate)

- [doT](https://github.com/olado/doT) | [`doT爱好者`](http://dotjs.cn/)

- [tppl](https://github.com/jojoin/tppl)

- [Handlebars](https://github.com/wycats/handlebars.js)

- [jquery-tmpl](http://github.com/jquery/jquery-tmpl)

- [ejs](https://github.com/mde/ejs)

- ...

#### 2⃣跑分性能

通过对各模板引擎测试结果，可以看出artTemplate ,tppl和doT等引擎模板整体性能要有绝对优势。

👉[在线速度测试](http://jojoin.github.io/tppl/test/test.htm)

![image](https://image-1257132344.cos.ap-shanghai.myqcloud.com/tpl-speed.jpg)

#### 3⃣推荐使用

`artTemplate`: 大厂出品(腾讯)，stars多

`doT`: 语法简洁，易上手

#### 4⃣demo实例

基于doT.js语法小试牛刀，详见仓库dot文件夹
