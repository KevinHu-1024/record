## 2015/10/23
+ leancloud存储时，http header如何处理？
    + 在页面处理时，requests跨站请求，不会在firebug中抓到包。
    + UserAgent？ 使用requests模拟一下？
    + 可以对key和master加上时间进行md5加密。
    + 跨站请求经过fildder，报ssl错误

## 2015/10/24
+ python的RaiseError
+ Excel模块xlrd, xlwt

## 2015/10/25
+ wsgiref模块，application
+ __slots__
    + __dict__, 
    + 限制动态绑定属性
+ 博客园发布xlrd模块
+ __name__
+ types模块
    + type(3) == int  
    + types.MethodType(set_age, stu, Student), 怎么绑定到一块的? 动态绑定方法

## 2015/10/26
+ pdb调试(sublime repl设置快捷键)      
+ setupmethod装饰器(Flask)
+ builtin dict
+ doctest测试模块

## 2015/10/27
+ sys.exit()
+ vue.js demo
    + el, data, methods
+ 博客园发布pdb调试

## 2015/10/28
+ jinja2模版引擎
+ try/except/else
+ ~~itertools(移到11/06)~~

## 2015/10/29
+ scrapy初探
+ repl 与 str 区别
+ 字符串格式化format
    + built-in type
    + string module
    + "repr() shows quotes: {!r}; str() doesn't: {!s}".format('test1', 'test2')
    + '{:%Y-%m-%d %H:%M}'.format(datetime.datetime.now())
+ str, repl, eval
+ self.encode('unicode-escape')
+ @property
+ [jquery选择器引擎效率问题](http://www.ruanyifeng.com/blog/2011/08/jquery_best_practices.html)
    + 调用原生 (getElementById，getElementByName，getElementByTagName)
    + 使用缓存
    + Event Delegation
    + 减少DOM的改动 (reflow, repaint)
    + 减少作用域链 (prototype, closure)
+ json的操作 
    + dumps(->json), loads(->py)
+ 连接两个dictionary 
    + dict(dict1.items() + dict2.items())
    + dict(dict1, **dict2)
+ python -m timeit -s
    + trace module
    + timeit module
+ lxml解析库使用

## 2015/10/30
+ node debug
+ ES5, ES6 Array操作
+ Flask 返回json格式
    + make_response().headers[''] = ''

## 2015/10/31
+ 字符串基本操作
    + replace
    + find
    + split
    + format
+ __call__, 
+ for else
    + for如果正常退出，则执行else
+ 调试flask等web应用
    + [Flask-DebugToolbar](http://flask-debugtoolbar.readthedocs.org/en/latest/)
    + ipdb
    + pudb
+ localStorage

## 2015/11/1
+ webapp diary
    + 使用localStorage，第一次加载缓慢，以后直接从本地存储加载与更新
    + 使用动态加载，不需要一次性加载，上拉刷新
+ angular $scope 通信
    + emit 向上传递
    + broadcast 向下传递
    + ionic, refresh与loadmore冲突
+ angular $resource
+ js读取json
+ angular模板转义
    + vue {{{ html }}}
    + jinja2 {{ html | safe }}
    + angular trustAsHtml
+ css3 
    + translate3D
    + pointer-event
    + user-select
+ js Array
    + splice, pop, shift
    + unshift, push
+ vue.js watch

## 2015/11/2
+ python urlparse
    + _parse_cache 是什么鬼，没有赋值，值从哪里来
+ **promise**
+ ionic的ng-collection下的height都一样？
+ ionic的ion-view是什么，如何加按钮？
+ python descriptor
    + __get__()
    + __set__()
    + __delete__()
    + 实现property, staticmethod, classmethod
+ python cProfile
    + %timeit 
    + 程序性能分析

## 2015/11/3
+ javascript 正则表达式
    + RegExp exec, test
    + str match, search, 
+ python copy, pickle module
    + l = l[:], l = copy.copy(l)
    + l = copy.deepcopy(l)
+ jquery deferred
    + resolve/done
    + reject/fail
    + notify/progess
    + then/always/when
+ ES6 Promise
+ firebase, BAAS
+ javascript DOM
    + 
+ javascript Object

## 2015/11/4
+ javascript [类型判断](http://www.cnblogs.com/mofish/p/3388427.html)
+ web框架！！！！！！！
+ python setitem, getitem, delitem
+ 前端动画

## 2015/11/5
+ python [metaclass](http://blog.jobbole.com/21351/)

## 2015/11/6
+ python itertools, operator module
+ jquery dir, sibling实现

## 2015/11/7
+ jquery 
+ javascript AMD

## 2015/11/8
+ [移动端viewport](http://www.cnblogs.com/2050/p/3877280.html)
+ document.addEventListener
+ bind, caller

## 2015/11/9
+ 移动端手势
+ ife task2 小练习
+ 树莓派基础认识
+ gulp.py 源码分析
+ npm --save-dev, --save区别
+ xShell 5 调试com

## 2015/11/10
+ bootstrap button
+ 子层是否影响父层的盒模型(static)?
    + static/relative width默认为100%，height默认为child的总height, box-model为child的border-content;
    + absolute/fixed width默认为child的总width, height默认为child的总height, box-model为child加margin。
    + 如果高度未设定，则由文档流最后的位置决定
+ [CSS challenges](https://en.wikiversity.org/wiki/Web_Design/CSS_challenges)
+ [DOM 2](http://segmentfault.com/q/1010000000766310)

## 2015/11/11
+ 百度脑图
+ 冒泡与捕获
+ [node爬虫](http://www.cnblogs.com/coco1s/p/4954063.html)
+ 100% 布局，height指定，有border，滚动条出现
    + 取消height，
+ asdfjd../ASdftb../WXzfb..
+ 编辑/删除按钮浮动变为块状元素
+ 左右布局
    + 左自适应, 右固定
        + 左width 100%, padding-right, 右绝对定位
        + 左绝对定位, 右浮动
+ -margin 文档流
    + 相对于父容器的宽度
    + left, top移动自身位置(不管怎么样我都要往前走)，right, bottom拉着紧随其后的文档流元素(我身后的这些位置我不要了，后边的你就占了吧)
    + http://www.cnblogs.com/2050/archive/2012/08/13/2636467.html#2457812
    + http://www.cnblogs.com/jscode/archive/2012/08/28/2660078.html
    + http://www.cnblogs.com/leejersey/p/3477855.html

## 2015/11/12
+ csslint/recess/sublimelinter
+ css3
    + word-wrap
+ javascript 删除数组中特定的值

## 2015/11/13
+ 刘东的博客(http://fordawn.net/)
+ 高浩阳(http://gaohaoyang.github.io/about/)
+ (https://pages.github.com)https://www.anotherhome.net
+ (http://ncuey.sinaapp.com/CrispElite/)
+ (http://newraina.com/)
+ (http://liuyifeneve.github.io/)

## 2015/11/14
+ callback函数中如何退出?
+ js var a, 与 a不是在同一个作用域
    + 先试用bind, call无法改变this指向？
    + Function.prototype.call.bind(Array.prototype.slice)

## 2015/11/15
+ vue.js methods/v-on/v-for/v-model
+ zip(*([iter(a)] * 3))
+ [html dom尺寸](http://www.cnblogs.com/HCJJ/p/4967332.html)

## 2015/11/16
+ overflow absolute与relative的区别
+ float变成快元素的
+ vue-todo
    + watch
    + computed
    + nextTick
    + $remove
    + director.js
    + v-cloak
    + :class
+ PhantomJS、

## 2015/11/18
+ dom就是动态加载，事件委托，oo就是原型，继承，还有闭包，ajax
+ 约瑟夫环
+ bfc
+ ([^\?])

## 2015/11/19
+ python __init__(*args, **kwargs)
+ python mapping数据类型
+ css inline-block
+ [jquery 事件委托](http://www.cnblogs.com/chuaWeb/p/jQuery-1-9-1-addEvents-3.html)
+ [pyhon后端面试](http://blog.csdn.net/yueguanghaidao)
+ [python赋值过程](http://www.cnblogs.com/happyframework/p/3260233.html)
+ python heapq
+ python self.__class__(self)

## 2015/11/20
+ test/test1.js 关于函数作用域的面试题
+ [了解pouchdb](http://pouchdb.com/learn.html)
+ hasOwnProperty
+ vue.js 中data中有属性需要延迟
+ [类型转换](http://www.cnblogs.com/mizzle/archive/2011/08/12/2135885.html)

## 2015/11/21
+ vue.js 中数组添加第一个元素时，viewmodel无响应。
    + computed出错，设置为getter之后，只读。
    + 添加数组后，不会显示到DOM中。
+ Excel
    + countif
        + 筛选重复值
    + index + mtach
        + 单条件查询
        + 多条件查询
    + vlookup
        + 单条件查询
        + 多条件查询
    + 分列
    + 数据有效性

## 2015/11/22
+ 绝对定位总是遮盖其他元素

## 2015/11/23
+ director.js
+ es6 module
+ nodejs superagent

## 2015/11/24
+ [主题](https://github.com/shashankmehta/greyshade)
+ 好徒弟 1
    + sublime text3，package control，emmet的安装。
    + emmet的安装及使用
        + .container>(.header>.span*3)+(.content)+(.footer)
    + 属性
        + __text-indent__
        + text-transform
        + text-decoration
        + __text-align__
        + __white-space__
        + __color__
        + __line-height__
        + __background__
        + __word-wrap__
        + __word-break__
        + word-spacing
        + letter-spacing
        + __font__
        + font-family
        + font-size
        + font-weight
        + font-face
    + div, h1-h6, hr, p, a, ul>li, 
    + class, id, :hover, :focus
    + css/js的引入

## 2015/11/25
+ 兼容edge,不是从圆心散出，firefox有阴影。

## 2015/11/26

## 2015/11/27
+ 单例模式
+ 描述符，元类
    + 一个类的属性是另一个类的实例
+ xpath
+ addclass源码
+ async, co并发

## 2015/11/28
+ [应不应该使用inline-block代替float ](http://www.w3cplus.com/css/inline-blocks.html)
+ float center

## 2015/11/30
+ [优先级](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Specificity)

