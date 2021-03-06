## 2015/10/23
+ leancloud存储时，http header如何处理？
  + 在页面处理时，requests跨站请求，不会在firebug中抓到包。
  + UserAgent？ 使用requests模拟一下？
  + 可以对key和master加上时间进行md5加密。
  + 跨站请求经过fildder，报ssl错误

## 2015/10/24
+ python
  + RaiseError
    + NameError
    + AttributeError
    + ...
  + xlrd, xlwt, xlutils
    + xlrd    读文件
    + xlwt    写文件
    + xlutils 作为二者桥梁，修改文件

## 2015/10/25
+ wsgiref模块，application
+ builtin dict
  + \__slots__
    + \__dict__ 
    + 限制动态绑定属性
  + \__name__
+ [写一篇 xlrd 博客](http://www.cnblogs.com/xianwang/p/4909391.html)
+ types module
  + type(3) == int
  + types.MethodType(set_age, stu, Student), 怎么绑定到一块的? 动态绑定方法

## 2015/10/26
+ pdb调试(sublime repl设置快捷键)
+ setupmethod装饰器(Flask)
+ builtin dict
  + \__call__ 
+ doctest测试模块

## 2015/10/27
+ sys.exit()
+ vue.js demo
  + el
  + data
  + methods
+ [博客园发布pdb调试](http://www.cnblogs.com/xianwang/p/4916045.html)

## 2015/10/28
+ jinja2 template engine
+ python Exception
  + try/except/else

## 2015/10/29
+ scrapy初探
+ python
  + 字符串格式化format
    + built-in type
    + string module
    + "repr() shows quotes: {!r}; str() doesn't: {!s}".format('test1', 'test2')
    + '{:%Y-%m-%d %H:%M}'.format(datetime.datetime.now())
  + str, repl, eval
  + str.encode('unicode-escape')
  + @property
  + json的操作 
    + dumps(->json), loads(->dict)
  + 合并两个dictionary 
    + dict(dict1.items() + dict2.items())
    + dict(dict1, \**dict2)
  + python -m timeit -s 性能
    + trace module
    + timeit module
  + lxml解析库使用
+ [jquery选择器引擎效率问题](http://www.ruanyifeng.com/blog/2011/08/jquery_best_practices.html)
  + 调用原生 (getElementById，getElementByName，getElementByTagName)
  + 使用缓存
  + Event Delegation
  + 减少DOM的改动 (reflow, repaint)
  + 减少作用域链 (prototype, closure)

## 2015/10/30
+ node debug
  + node-inspector
+ ES5, ES6 Array操作
+ Flask 返回json格式
  + make_response().headers[''] = ''  ?

## 2015/10/31
+ 字符串基本操作
  + replace
  + find
  + split
  + format
+ for else
  + for如果正常退出，则执行else
+ 调试flask等web应用
  + [Flask-DebugToolbar](http://flask-debugtoolbar.readthedocs.org/en/latest/)
  + ipdb
  + pudb
+ html5
  + localStorage
  + sessionStorage
    + 当浏览器窗口关闭时，storage 失效

## 2015/11/1
+ webapp diary
  + 使用localStorage，第一次加载缓慢，以后直接从本地存储加载与更新
  + 使用动态加载，不需要一次性加载，上拉刷新
+ angular
  + $scope
    + emit 向上传递
    + broadcast 向下传递
    + ionic, refresh与loadmore冲突
  + $resource
+ js读取json
  + require('a.json')
+ angular模板直接转义，思考 vue 与 jinja2
  + vue {{{ html }}}
  + jinja2 {{ html | safe }}
  + angular trustAsHtml
+ css3 
  + translate3D
  + pointer-event
  + user-select
+ ES5 Array
  + splice, pop, shift
  + unshift, push
+ vue.js
  + watch
    + Object.defineProperty seter

## 2015/11/2
+ python urlparse
  + \_parse_cache 是什么鬼，没有赋值，值从哪里来
+ ionic
  + ng-collection下的height都一样？
  + ion-view是什么，如何加按钮？
+ python descriptor
  + \__get__()
  + \__set__()
  + \__delete__()
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

## 2015/11/4
+ javascript [类型判断](http://www.cnblogs.com/mofish/p/3388427.html)
+ python
  + setitem
  + getitem
  + delitem
+ css3 动画

## 2015/11/5
+ python
  + [metaclass](http://blog.jobbole.com/21351/)

## 2015/11/6
+ python
  + itertools module
    + 部分代码实现
  + operator module
+ jquery complecation
  + dir
  + sibling

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
+ gulp.js 源码分析
+ npm --save-dev, --save区别
+ 树莓派基础认识
+ xShell 5 调试com

## 2015/11/10
+ bootstrap button
+ css
  + 子层是否影响父层的盒模型(static)?
    + static/relative width默认为100%，height默认为child的总height, box-model为child的border-content;
    + absolute/fixed width默认为child的总width, height默认为child的总height, box-model为child加margin。
    + 如果高度未设定，则由文档流最后的位置决定
  + [CSS challenges](https://en.wikiversity.org/wiki/Web_Design/CSS_challenges)
  + [100dayscss](http://100dayscss.com/)
  + [DOM 2](http://segmentfault.com/q/1010000000766310)

## 2015/11/11
+ 百度脑图
+ 冒泡与捕获
+ [node爬虫](http://www.cnblogs.com/coco1s/p/4954063.html)
+ [notebook 项目思考](https://github.com/shfshanyue/notebook)
  + 100% 布局，height指定，有border，滚动条出现
    + 取消height
  + 编辑/删除按钮浮动变为块状元素
  + 左自适应, 右固定
    + 左width 100%, padding-right, 右绝对定位
    + 左绝对定位, 右浮动
    + (__20170413 整理补__) 右 width: 300px; float: right，并且通过 margin-left 设置间隙；左overflow:hidden，父overflow:hidden
      + .container>.right+.right
+ negative margin 文档流
  + 相对于父容器的宽度
  + left, top移动自身位置(不管怎么样我都要往前走)，right, bottom拉着紧随其后的文档流元素(我身后的这些位置我不要了，后边的你就占了吧)
  + 子元素 width 缺省，则自身左右拉长，在一些场景很有用比如，父元素宽度未知子元素需要 100% + 4px，在没有 css3 calc 的时代这是一种解决方案

## 2015/11/12
+ csslint/resetcss/sublimelinter
+ css3
  + word-wrap
+ javascript 删除数组中特定的值
  + python中 l.remove(value)

## 2015/11/13
+ 刘东的博客(http://fordawn.net/)
+ 高浩阳(http://gaohaoyang.github.io/about/)
+ (https://pages.github.com)https://www.anotherhome.net
+ (http://ncuey.sinaapp.com/CrispElite/)
+ (http://newraina.com/)
+ (http://liuyifeneve.github.io/)

## 2015/11/14
+ **callback函数中如何返回值?**
+ js var a, 与 a不是在同一个作用域
  + 先试用bind, call无法改变this指向？
  + Function.prototype.call.bind(Array.prototype.slice)

## 2015/11/15
+ vue.js
  + methods/v-on/v-for/v-model
+ python
  + zip(*([iter(a)] * 3))
+ [html dom尺寸](http://www.cnblogs.com/HCJJ/p/4967332.html)

## 2015/11/16
+ vue-todo
  + watch
  + computed
  + nextTick
  + $remove
  + directer.js
  + v-cloak
  + :class
+ PhantomJS
  + 类似 selenium webwriver

## 2015/11/18
+ dom就是动态加载，事件委托，oo就是原型，继承，还有闭包，ajax
+ 约瑟夫环
+ bfc
+ ([^\?])

## 2015/11/19
+ python
  + \__init__(*args, \**kwargs)
  + mapping 数据类型
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
+ 为徒弟慧敏与小不点准备的第一堂课
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

# 月初计划
1. hexo建立个人博客
2. nginx配置
3. mongo, mysql数据库熟悉
4. 2048, 个人笔记本修复
5. 走向共和
[稀土招聘](http://gold.xitu.io/i-want-u)

## 2015/12/1
+ js高级程序设计，错误处理与调试
  + ES6 class
+ python itertools.permutations源码分析。
+ reveal.js 制作个人简历
+ keypress, keydown区别
+ is, ==, not, is not None
+ wang811039556ali

## 2015/12/2
+ js高级程序设计，原型链
+ js设计模式，观察者模式
+ python socket编程

## 2015/12/3
+ python urllib2,requests
  + nodejs http, superagent
  + 设置header,cookie
+ python getattr / urllib2源码， bs4源码
+ winpcap, usbpcap
+ wireshark http抓包
  + [wireshark过滤表达式](http://www.csna.cn/viewthread.php?tid=14614)
  + 过滤规则
    + http
      + referer
    + dns
    + tcp
      + 浏览器打开一个网址都发生了什么？
      + srcport, dstport, netstat命令
    + tcp三次握手连接过程
      + win/mss/ws

## 2015/12/4
+ html css
  + 盒模型，border-box
    + 选择器 ./class, #/id
    + input:text
    + firefox/火狐
  + 文档流
    + 定位/ absolute/relative/fixed/static
    + 绝对定位与浮动
  + 定位
    + 绝对定位居中
  + 浮动
    + 导航栏
  + sublime快捷键
    + Ctrl+Shift+K
    + Ctrl+Shift+P
    + Ctrl+Shift+G
    + Ctrl+Enter/Ctrl+Shift+Enter
    + Ctrl+K+B
  + Firefox/控制台
    + 查看元素
    + 查看盒模型
    + 编辑html
    + 查看css
  + markdown
    + +/ul>li
    + 1,2,3/ol>li

## 2015/12/5
+ flask模板
  + jinja2

## 2015/12/6
+ leancloud无法读文件，错误类型bdb，又莫名其妙的好了。。。
    + 无法读取本模块的文件
+ 甜甜日记贴，更新视图，每天进行更新
    + 日期，filter
    + flask-cache
    + 每天定时回复帖子，设置api
+ 模块与包

## 2015/12/7
+ nodejs eventemitter, nvm
+ TypeError: sequence item 1: expected string or Unicode, Tag found

## 2015/12/8
+ document.defaultview, document.getselection
+ c++ auto, :
+ mongo
+ leetcode 4
+ [sublime documention](http://sublime-text.readthedocs.org/en/latest/command_line/command_line.html)
+ use nvm
+ DCloud HBuilder

## 2015/12/9
+ nodejs util, events, 观察者模式

## 2015/12/10
+ hexo博客
+ ajax, jquery ajax, fetch
+ sql
+ python concruent

## 2015/12/11
+ python3 -m http.server
+ [](http://javascript.ruanyifeng.com/tool/browserify.html)

## 2015/12/12
+ highcharts

## 2015/12/13
+ [BFC](http://www.cnblogs.com/lhb25/p/inside-block-formatting-ontext.html)
+ flask markdown
+ [张文丽](http://zhangwenli.com/blog/2015/04/01/2015-front-end-engineer-interview/)
+ [前端面试](http://www.cnblogs.com/winter-cn/archive/2013/05/11/3072926.html)
+ [前端九问](http://weibo.com/1196343093/Bhj510t50?sudaref=www.cnblogs.com&type=comment)

## 2015/12/14
+ 2048
  + 手势支持
  + 可悔子，10步
  + 可砸子
  + redis支持排行榜
+ 爬虫(cheerio)
  + koa做展示
  + redis做排行榜
  + highcharts做图表统计
+ 多人聊天室(socket.io)
  + 可单人聊天
  + 可双人五子棋
+ 笔记本(vue.js)
  + 排序，笔记按任务排序
  + markdown
  + 回收站
  + 可移动化
  + nw.js
  + filter筛选器
+ 甜甜日记
  + flask-cache缓存
  + highcharts做图表统计
  + redis做排行榜(leancloud做排行榜)
  + 可移动化
+ 查看字节码
+ javascript零宽断言
+ git，checkout后，删除全部数据，在checekout回去，数据是否丢失。

## 2015/12/15
+ css position
+ css3 新增选择器，伪类
+ js call，bind，apply，继承的方式
+ js有几种继承方式
+ http 状态码

## 2015/12/22
+ 一周没写东西了，好颓废。

## 2015/12/23
+ 爱奇艺二面
  + 下台阶问题(尾递归，动态规划)
  + 跨域的几种方式
  + prototype解释

## 2015/12/25
+ 可转换对称数组
+ 苹果，梨问题
+ 浏览器兼容问题

## 2015/12/29
+ cross source
  + cors

## 2015/12/30
+ Adobe81
+ 神探夏洛克，问题
  + window无法resize
  + 图片太大，加载太慢
  + 按钮没有居中，无链接
  + 视频链接出错
+ postcss与cssnext
+ fullpage或者幻灯片


## 2015/12/31
+ html5 selection
  + 不能使用样式
+ css
  + [贝赛尔曲线](http://cubic-bezier.com/#.17,.67,.83,.67)
  + transition-origin
+ es6 symbol, set, map
