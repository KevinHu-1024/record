年与时驰，意与日去，遂成枯落，多不接世，悲守穷庐，将复何及！又是新的一年，又是新的一个月！先把上个月没有完的做完。

## 月初计划

### TODO
1. nginx配置
2. 2048修复
3. 走向共和
4. webpack, broserify等前端模块管理工具
5. [dae熟悉和使用](http://readthedocs.dapps.douban.com/docs/dae/tutorial/sdk.html)
6. leetcode刷10道题目
7. 修正甜甜的日记(vue-cli)
8. [git学习](http://segmentfault.com/a/1190000004222489)
9. 熟悉sql语句
10. 模拟滚动条制作
11. vue制作轮播动画，幻灯片

### Articals
[近年来前端技术发展方向](http://www.barretlee.com/blog/2015/12/10/after-framework-we-gonna-to-hug-data/)
[Git时代的VIM不完全使用教程](http://beiyuu.com/git-vim-tutorial/)
[Vim命令合集](http://www.cnblogs.com/softwaretesting/archive/2011/07/12/2104435.html)
[浏览器渲染专题](http://developer.51cto.com/art/201311/418133.htm)
[手机淘宝H5适配](https://github.com/amfe/article/issues/17)

## 2016/01/04
+ http status code
  + 204 No Content
  + 401 Unauthorized
  + 403 Forbidden
  + 405 Method Not Allowed
  + 502 Bad Gateway
  + 503 Service Unavailable
  + 504 Gatewaty Timeout
+ vue
  + post请求失败，显示请求为options
    + [POST请求失败，变成options请求](http://www.barretlee.com/blog/2014/08/19/post-method-change-to-options/)
    + 处理：先设置为get请求......
    + 再处理：设置请求头为 __{'Content-Type': 'application/x-www-form-urlencoded'}__
  + 设置等待状态符号，异步加载资源。
  + 滚动到最后时，请求加载下一页
    + 参考vue-cnode
    + 170415补： 注意 debounce 和 throttle
  + vue-cli
    + webpack中的publicpath
  + vue中filter no work
    + Vue.filter写到new Vue之前
  + vue-router无法显示路由
    + 没有加载vue的js文件......
+ leancloud
  + 关于日期的存储格式
    + moment与moment-timezone进行时区的转化
    + moment进行日期的格式化

## 2016/01/05

> 人生不相见，动如参与商。
> 今夕复何夕，共此灯烛光。
> 少壮能几时，鬓发各已苍。

+ vagrant 问题解决
  + [vagrant开发环境配置](https://github.com/astaxie/Go-in-Action/blob/master/ebook/zh/preface.md)
  + 网速问题
+ dae
  + [dae环境]()
+ vim
  + 批量替换
    + / ? n N
    + :%s#div#haha#g  ::=> :%s/div/haha/g
  + 撤销
    + u
    + Ctrl+r
  + 删除整行
    + dd
    + cc 删除后进入编辑模式


## 2016/01/06

> 行行重行行，与君生别离。
> 相去万余里，各在天一涯。
> 道路阻且长，会面安可知。
> 胡马依北风，越鸟巢南枝。
> 相去日已远，衣带日已缓。
> 浮云蔽白日，游子不顾返。
> 思君令人老，岁月忽已晚。
> 弃捐勿复道，努力加餐饭。

[IRC文档]()
[Shire环境搭建文档]()

+ python 
  + argparse
    + dest, store, store_true, nargs
  + subprocess
  + -W
  + 无法安装模块，需要sudo权限
    + python setup.py install --home ~bin/site-packages
      首先设置PYTHONPATH环境变量
    + .pth文件设置
      .pth文件设置在系统目录的site-packages或者~目录的site-pacages下
    + 处理，python setup.py install --user
      安装在本地，不需要root权限
+ vim
  + 设置行号
    + :set number
  + 跳转行
    + :12
    + 12G
  + 全选
    + ggvG
+ shell
  + diff -Nur [目录] [目录] > [输出文件]


## 2016/01/07

> 人生若只如初见,何事秋风悲画扇。
> 等闲变却故人心,却道故人心易变。
> 骊山语罢清宵半,泪雨零铃终不怨。
> 何如薄幸锦衣郎,比翼连枝当日愿。

+ vim
  + go
    + $, 0, ^, %, G, O
    + ctrl+g, gg
  + nG
+ git
	+ git stash
	+ git commit -a 


## 2016/01/08

+ virtualenv
  + windows与linux系统所建的目录不一致，使用linux
	+ source env/bin/activate 进行激活，任意目录下deactivate退出激活状态
	+ env/lib/python2.7/site-packages　下载的库的位置
	+ --no-site-packages 不与系统的site-packages挂钩
+ git 
	+ git pull origin next:master
		+ git fetch origin
		+ git merge origin/next
	+ git add --all path 不忽略删除文件，默认为忽略删除文件
+ vim
	+ w, b
	+ ^f, ^b
	+ vundle


## 2016/01/11

> 夫君子之行，静以修身，俭以养德。非淡泊无以明志，非宁静无以致远。夫学须静也，才须学也。非学无以广才，非志无以成学。淫慢则不能励精，险躁则不能冶性。年与时驰，意与日去，遂成枯落，多不接世，悲守穷庐，将复何及！

+ git
    + 工作区，暂存区和版本库
    + git commit --amend 
    + git checkout -- file
    + git reset HEAD file
    + git reset --soft hash
    + git reset --hard hash

## 2016/01/12
+ 浏览器的重排重绘
  + vue的列表渲染
+ [vue与webpack](http://djyde.github.io/2015/08/29/vuejs-and-webpack-1/)

## 2016/01/13

> 淫慢则不能励精，险躁则不能冶性。

+ python
  + descriptor
  + yield
+ fetch与ajax
+ [redis](http://www.jianshu.com/p/01b37cdb3f33)

## 2016/01/14
+ nginx
	+ install and config
	+ select, poll, epoll
+ python
  + os.walk源码
  + node模拟os.walk
	+ celery
	+ setattr, getattr
+ vim
	+ 括号自动补齐
	+ 查找与替换
		+ :set noignorecase
		+ :set hlsearch
		+ rd
		+ ddp
+ pandas
	+ Series
    + DataFrame

## 2016/01/15
+ js
  + 双向绑定和单向绑定
+ sketch
+ vim
  + inoremap
  + dk 删除本行与上一行
  + dj 删除本行与下一行
  + 11, 19d
  + #, * 搜索当前字符
  + gd
  + vsplit, :bn, :only
+ pandas
    + np.random.randint(1, 10, size=(4, 6))
    + df.apply(lambda x: x*4), df\*4
+ mongodb
	+ db.user.find()
	+ db.user.save()
	+ db.user.insert()
    + db.user.aggregate()
	+ db.user.update({}, {$set:{}}, {multi:true})
		+ alter 

## 2016/01/18

> 旧时王谢堂前燕，飞入寻常百姓家。

> 宇宙很大，生活更大，我们还会再见面的。


+ nw.js初探
  + [入坑指南](http://segmentfault.com/a/1190000003870613)
  + [how to package and distribute your apps](https://github.com/nwjs/nw.js/wiki/How-to-package-and-distribute-your-apps#windows-1)
  + package.json
    + windows
    + zip -r app.nw *
    + cat nw app.nw > hello && chmod +x hello
+ rust
  + 哲学家就餐问题和生产者消费者问题
    + pv
    + lock, condition, queue, yield
+ position
  + scrollTop, $().scrollTop()
  + clientHeight + scrollTop = scrollHeight
  + h.scrollTo(0, 100) ::=> h.scrollTop = 100


## 2016/01/19
+ [odin]()
+ [semantic](http://www.semantic-ui.cn/)

## 2016/01/20
+ git
  + git add -A
  + git pull --rebase  upstream master
  + git rebase -i hash
  + git rebase --continue

## 2016/01/21
+ review
	+ less项目
	+ cookie的格式
		+ 字符串格式，名称，内容，域，大小，路径，过期时间，仅http，安全
	+ http method
		+ GET, PUT, POST, DELETE, TRACE, OPTIONS, HEAD
	+ http code
		+ 101, 200, 201, 204, 205, 301, 302, 304, 400, 401, 403, 404, 405, 500, 502, 503, 504, 505
  + webpack
  + page scroll
  + settimeout 0
      + 如果后边是一个死循环会被永远阻塞
  + requestAnimateFrame
+ ssh key already use

## 2016/01/22
+ mouse wheel event
  + mousewheel(chrome)
    + wheelDelta(-120)
  + DOMMouseScroll
    + detail(+3)
+ yield from

## 2016/01/23

> 城下之盟，本就没什么规矩。 -> 走向共和

+ 移动适配
  + <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, minimal-ui">
+ css
  + 三角形制作，高宽为0，上下边框为50, 左边框为50*1.73

## 2016/01/24

> 中堂大人独往独来，云中仙鹤。

> 一个人孤独一枝的时候，只好嘲为仙鹤了。

+ css
  + box-sizing 哪三种值？
  + reset.css为什么要这么多？
  + background顺序是什么？
  + inline-block中间空白的多种去发以及flex的等分。
  + 鼠标指针设置图片
+ vue
  + 自定义监听事件是否支持描述符


## 2016/01/25
+ avos publish
+ css
  + rotate的hover是
  + clip:rect 能否绘制三角形
    + 170418 补: 不可以，能够绘制三角形的是 clip-path，然而兼容性不好
    + [http://www.w3cplus.com/css3/why-you-should-be-excited-about-css-shapes.html]()
+ vue-transition + animate.css

## 2016/01/26
+ 垃圾回收 Garbage Collection
  + 引用计数 reference counting  -> 循环引用
  + 标记清除 mark-and-sweep
  + 分代回收                                  -> 170419 补
  + 增带回收
+ css
  + 字间距 letter-spacing
+ python
  + read
  + readlines

## 2016/01/27

+ css3
  + pointer-events
    + PointerLock API
+ mobile
  + touchstart
  + touchend
  + touchmove
  + vw, vh, vmin, vmax 
+ vue
  + vue-router
    + pushstate
    + 全局配置选项设置history时，出现错误
    + v-link-active，根据路径设置class
  + vue
    + transtion不能同名？
    + .toogle-transition中必须有transiton属性!
    + deactivate水滴能够移开，无法进入。

## 2016/01/28
+ vue-router
  + 跟路由切换时，钩子函数

## 2016/01/29
+ javascript
  + 循环点击按钮
    + let
    + closure
  + string -> array
    + String.prototype.split('')
  + array-like -> array
    + Array.prototype.call(btns)
    + Array.prototype.apply(btns)
    + Array.from(btns)
    + [...btns]
+ css
  + 轮播动画
    + translate
    + left

## 上月总结
今天是大年初一，说一说上个月的总结。
上个月的计划没能完成几条，不过也有几方面的进步，如 __git__, __vim__, __vue__, __vue-router__, 这些技能比已往有了进步。不过也有很多不熟练的地方，如vim的插件，git多人协作，vue的组件。
webpack也不熟，js的基础也有所生疏。

## 本月计划
1. 机器学习
2. git

[fex面试问题](https://github.com/fex-team/interview-questions)
[Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions/tree/master/Translations/Chinese)
[前端面试总结](http://www.cnblogs.com/jikey/p/5201185.html)
[git技能](http://blog.jobbole.com/90061/)

## 2016/02/03
+ Baidu FEX

## 2016/02/04
+ [We have a problem with promises](http://fex.baidu.com/blog/2015/07/we-have-a-problem-with-promises/)
+ javascript Object
  + configurable, enumerable, get, set
  + Object.keys()
  + Object.hasOwnPropertyNames()
+ webpack
+ es6
  + class get/set
+ vue-diary backend
  + > /usr/local/lib/python2.7/dist-packages/requests/packages/urllib3/util/ssl_.py:90: InsecurePlatformWarning: A true SSLContext object is not available. This prevents urllib3 from configuring SSL appropriately and may cause certain SSL connections to fail. For more information, see https://urllib3.readthedocs.org/en/latest/security.html#insecureplatformwarning.
  + > InsecurePlatformWarning
  + $http.post
  + flask query_string req.args.get('id', 2)

## 2016/02/06
+ vue-diary
  + router backend and frontend
  + difference between ready and route
  + ssl and python version, disable warning
    + import requests.packages.urllib3
    + requests.packages.urllib3.disable_warnings()
    + pip install -U requests[security]
  + keep-alive是如何保存路由状态的，如何只保存某个路由的状态

## 2016/02/07
+ eleme
  + vue与angular的双向数据绑定
  + promise.all的实现
  + webpack的按需加载
+ Object.observe

## 2016/02/09

> 中国自有国情在此。

> 国情如此，稳定第一。

+ vue-router
  + data
    + loadingRouteData，无需自定义值

## 2016/02/10
+ front end
  + html5rocks
  + v2ex
+ diary
  + BDE-IMAGE的图像未消除干净。
    + <img[^<>]\*?class="BDE_Image"[^<>]*?>
  + 未知卡顿
    + 可能是路由切换时保存scrollTop所致
+ git
  + (modified content, untracked content)
    + 该目录下存在.git目录，删掉即可
  + fast-forward
+ leancloud 
  + info
+ tiankui
  + 添加早晚安，爬贴等任务

## 2016/02/11
+ tiankui
  + 定时签到
  + __关注吧列表由js生成，解析失败__
  + 月度贴子统计
+ python
  + os.path.exists
+ git
  + 修改历史提交的信息

## 2016/02/12

> 一个正直忠诚又有才干的御史，要是能够出面弹劾瞿鸿禨，他一个人就比我北洋一个镇的军队都要有力量。没有什么人不会被收买，就看你的筹码有多大，现在还没被收买，是还没碰到像我袁世凯这么大的庄家。每个人的一生中都会有一次大赌局，就看发生在何时何地。

+ webpack
+ diary
  + 路由切换时反应迟钝
    如果不设置keep-alive，则首页需要重新加载(本地存储也是)
  + 设置类似贴吧效果
  + router-view不能是片段实例


## 2016/02/14
+ webpack
  + 使diary可以部署在github上
+ diary
  切换时不发生闪烁，有两种方法
  + 取消keep-alive，home放在router-view外
  + 看懂keep-alive源码，设置两个组件，home一个组件，详细信息一个组件
+ git
  + git diff --cached
  + git diff --staged
  + git diff HEAD

## 2016/02/18
+ leancloud
  + find请求9000多次，来源于昨日topic.vue大量的topic监听事件

## 2016/02/19
+ leancloud
  + before\_save与after_save查看原理
+ diary
  + 火狐浏览器html的scrollTop与谷歌浏览器html的scrollTop
    + document.documentElement
    + document.body
  + 火狐浏览器无法保存position的状态，而谷歌浏览器可以

## 2016/02/22
+ fastclick
  + 解决单击300ms的延迟
+ 代码展示工具
  + jsfiddle
  + jsbin
+ icon-font
  + ttf/eot/svg/woff
  + 关于webpack如何处理图标字体
+ path
  + os.path.resolve/os.path.join
  + path.abspath/path.join
+ es5
    + Object.getPrototypeOf，__proto__
    + Object.keys，Object.getOwnPropertyNames
    + Object.hasOwnProperty, for...in

## 2016/02/25
+ background-size: 100% 100%, cover;
+ translate3D
+ transform-origin

## 2016/02/27
+ python
  + stdout，stdin
  + codecs
  + gevent
+ leancloud
  + jsonp
+ 前端SEO
  + catberry.js

## 2016/02/28
+ markdown如何添加样式
+ border-box
  + absolute的box里的元素的定位零点是哪里
  + absolute的定位零点是border-box，而relative的定位零点是content-box
+ overflow:hidden
  + 也是border-box

## 2016/02/29
+ vue-loader
  + scoped会遍历DOM，生成一个哈希值的属性，但是动态生成的节点便无法生成。
+ mouseover与mouseenter

## 三月计划
1. [python game](http://www.checkio.org/complete/github/)

[CSS开发指南](https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS)
[正则表达式](http://regex.alf.nu/)
[正则表达式](http://www.regexr.com/)
[http协议](https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html)

## 2016/03/01
+ z-index定位元素，默认为他爹的z-index
+ margin collapse
  + 垂直margin
    + margin-bottom与兄弟元素的margin-top
    + margin-top与子元素的margin-top
  + [深入理解margin-collapse](http://www.w3cplus.com/css/understanding-bfc-and-margin-collapse.html)
  + when there are more than 2 block of nested, their margin-top computed from inner to out.

## 2016/03/02
+ translate3D
  + 第三个值是什么意思
+ load与ready区别
+ **absolute居中负值与正值的区别是什么**
  + margin: auto到底是什么意思
    + firefox 通过 position，chrome通过设置 margin
+ mousewheel
  + firefox DOMMouseScroll
  + chrome mousewheel
+ scrollheight
  + firefox document.documentElement.scrollTop
  + chrome document.body.scrollTop

## 2016/03/03
+ notebook
  + flex layout
  + drag
+ git
  + git checkout -- file

## 2016/03/04
+ margin
  + 百分比为父元素的宽度
  + auto可以设置居中，左对齐，右对齐
  + negative margin
  + margin collapse
+ backface-opacity
+ background-position
  + 全屏图片如何调整重点位置
+ oncontextmenu
  + 为notebook设置右键
+ bfc生成规则
  + 清楚浮动相关问题
  + writing-mode使得div可以水平排列


## 2016/02/29 - 2016/03/06 (week 10)
1. 以下三个div将会会如何放置(margin collapsing)？
    ``` html
    <style>
    * {
        padding: 0;
        margin: 0;
    }

    .first {
        margin: 20px;
        height: 500px;
        background-color: #666;
    }

    .second {
        margin: -10px;
        height: 300px;
        background-color: #999;
    }

    .third {
        margin: -30px;
        height: 100px;
        background-color: #ccc;
    }
    </style>
    <div class="first">
        <div class="second">
            <div class="third">
                三个元素的外边距折叠
            </div>
        </div>
    </div>
    ``` 
2. 如何清除浮动？根据什么原理？
3. 如何对左侧栏200px，主内容自适应进行布局？
4. 如何使用margin完成圣杯布局，用flex呢？
5. 模拟一个滚动条 
6. 图片如何全屏自适应，并在resize时始终保留重要部分？


## 2016/03/06
+ 圣杯布局为甚么min-width是2x+y像素
+ BFC中margin collapsing都是垂直方向吗，请举例。
+ git config --global credential.helper store
+ css
  + img.naturalWidth
  + img.naturalHeight
+ column-count

## 2016/03/07
+ margin-right什么意思
+ margin的百分比是基于父元素的什么盒子模型？
+ 圣杯布局中右侧栏的margin-left: -x 和margi-right: -x有什么区别？
+ 浮动的元素不会折叠，因为触发BFC。
+ background合起来写

## 2016/03/09
+ python闭包
+ firefox
  + about:config
+ fillder
  + 手机调试
  + 过滤条件
    + 
  + 设置断点


## 2016/03/11
+ position:sticky
+ 语义化
  + figure

## 2016/03/14
+ wireshark
  + wireshark手机抓包
+ git
  + git branch -m 1 2  -> rename


## 2016/03/16
+ vue-slide
+ the difference of between decodeURI and decodeURIComponent
+ flex
+ the difference of between i and s
+ content attrubute
+ chrome notition center

## 2016/03/17
+ border-collapse
+ border-spacing
+ hidden, checked, target
+ tab content(checked, target)
+ webpack文件过大，按需加载，自动生成页面
  + WebPack.optimize.CommonsChunkPlugin
  + WebPack.optimize.UglifyJsPlugin
  + HtmlWebpackPlugin and ExtractTextPlugin
  + require/require.ensure
+ 如何生成文件的hash值
+ 千分符
+ 父元素高度塌陷
+ tower
+ python
  + find与index的区别
    + find -1, index ValueError

## 2016/03/18
+ string
  + match(re.exec)
  + search(re.test)
  + charAt()
  + toLowerCase()
  + toLocaleLowerCase()
  + toUpperCase()
  + toLocaleLowerCase()
  + startsWith()
  + endsWith()
  + slice()
  + substr()
  + substring()
  + replace()
  + repeat()
  + toString()
  + valueOf()
+ javascript
  + how to get the last 3 letter.
    + str.slice(-3)
    + str.substr(-3)
+ python
  + string
    + startswith
    + endswith
    + upper
    + lower
    + find
    + index
    + split
    + strip
    + lstrip
    + rstrip
    + join
    + count
    + replace
    + zfill
    + format

## 2016/03/19
+ css3
  + -webkit-touch-callout
  + -webkit-tap-highlight-color 
  + -webkit-userselect
  + -webkit-border-image
  + webkit-box
+ meta
  + <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
  + <meta content="yes" name="apple-mobile-web-app-capable">
  + <meta content="black" name="apple-mobile-web-app-status-bar-style">
  + <meta content="telephone=no" name="format-detection">
  + <meta content="email=no" name="format-detection">

## 2016/03/14 - 2016/03/20 (week11)
### python
1. 为数字加上千分符，写一个函数
2. `string.find()`与`string.index()`的区别
3. `re.match()`与`re.search()`的区别

### FE
1. 使用图标字体做出如链接所示图标
2. 使用css sprits做出如ife首页动态图片效果
3. 使用css3的target与checked伪类做出轮播效果图
4. 为数字加上千分符，写一个函数
5. 取字符串的最后五个字符
6. figure制作响应式图像
7. webpack如何进行异步加载

## 2016/03/22
+ chrome plugin
+ data-url
+ cookie以及session的设置
+ csrf攻击以及预防
+ http请求减少
+ js大小

## 2016/03/24
+ promise完成三个异步操作
  + 函数嵌套
    + 代码同步执行，效率太低，而且嵌套过多。
  + 计数器
    + 首先初始化一个计数器，每个异步操作使计数器加一，当计数器达到异步操作的个数时，异步操作全部完成。
  + promise.all
+ jquery和vue的大小
    + jquery 40K, vue 20K
+ 并行与并发
  + 并发就是同时与AB两人聊QQ
  + 并行就是一边聊QQ，一边看电视
+ vue guide
  + 响应式数据
  + computed, watch
  + 组件化
  + 模块化
  + 动画
  + 路由
+ REST(representational state transfer)
  + term
    + resource
    + collection
    + http
    + idempotent
    + url segment
    + endpoint
  + methods
    + PUT/DELETE/POST/GET/PATCH/HEAD/OPTIONS/CONNECT
  + headers
    + Accept (406)
    + If-Modified-Since/If-None-Match
    + If-Match (412)
  + status_code
    + 1XX Informational
      + 100 Continue
      + 101 Switching Protocols
    + 2XX Successful 
      + 200 OK
      + 201 Created
      + 202 Accepted
      + 204 No Content
      + 206 Partial Content
    + 3XX Redirection
      + 301 Moved Permanently
      + 302 Found
      + 303 See Other
      + 304 Not Modified
      + 305 Use Proxy
      + 307 Temporary Redirect
    + 4XX Client Error
      + 400 Bad Request
      + 401 Unauthorized
      + 403 Forbiden
      + 404 Not Found
      + 405 Method Not Allowed
      + 406 Not Acceptable
      + 408 Request Timeout
      + 409 Conflict
      + 412 Precondition Failed
      + 413 Request Entiry Too Large
      + 414 Request URI Too Long
    + 5XX Server Error
      + 500 Internal Server Error
      + 502 Bad Gateway
      + 503 Service Unavailable
      + 504 Gateway Timeout
    + Authentication
      + Etag
      + Access-Control
      + rate limiting
      + metrics
    + framework/library
      + python django-rest-framework, eve
    + Documention
      + console
    + example
      + endpoint
        + /threads
        + /topics
        + /posts
        + /users
      + filter
        + ?limit=50
        + ?offset=50
+ OAuth

## 2016/03/25
+ python
	+ Stackless Python 
+ http
  + sudo nc -kl 80
  + get和post区别
    + get获取数据，post修改数据，url资源定位符
    + ~~get长度有限制，不安全~~
+ DOM
  + innerText, innerHTML, textContent
+ call，apply，bind
  + Math.max.apply(null, [1, 3, 5, 7, 9])
  + Array.prototype.slice.call()
    + Array.from()
    + [...arr]
  + Object.prototype.toString.call()
+ 浏览器环境与node环境中this的差别(setTimeout)
+ css 
  + background-origin

## 2016/03/21 - 2016/03/27
### python
1. 写一个单例模式
1. 写一个装饰器，打印程序的运行时间

### FE
1. innerText, innerHTML, textContent的区别
1. 遍历数组时in和length的区别
1. left-pad的实现
1. 有三个取数的异步操作，当异步操作完成时，取最大的数
1. 制作一个Chrome插件，完成贴吧的自动签到
1. 设计博客的REST API
1. REST API的安全认证
1. 减少或者缓存HTTP请求的几种方法
1. 如何预防CSRF攻击


## 2016/03/28
+ renren review
    + 图片GPU加速
    + WebWorker
    + css3与html5的新东西
    + 数组去重复
    + this
    + call, apply, bind
+ meiyan review
    + 事件代理
    + length与in
    + nodejs的异步
+ eleme review
    + scoped css
    + web component
    + 按需加载
    + http请求图片
+ wangyi review
    + http请求
+ setinterval与settimemout

## 2016/03/30
> 不管你学习什么知识，在学之前，都最好先了解你将要学习的知识能帮你解决什么问题

+ 如何实现登陆
+ IP，PV，UV，PR
    + Page View
    + Unique View
    + Page Rank
    + awk
    + pipe?
+ awk，grep，sort
    [](http://www.cnblogs.com/ggjucheng/archive/2013/01/13/2858470.html)
    + ls -l | awk '{if ($5 > 2000) print $5}'
    + ls -l | grep pdf$
    + ls -l | sort -k 7
    + ls -l | sort | uniq -c
+ electron
+ coroutine(协程)
    + gevent/stackless/greenlet/eventlet
    + monkey.patch_socket()
    + gevent.joinall([])
    + gevent.spawn()
+ 多线程爬虫内存爆掉
+ from \__future__ import 是什么意思

## 2016/03/31
+ review
    + ls -al | awk 'BEGIN {count=0} {if ($3=="root") {print $0; count++}} END {print "count \n"count}'
    + ll | awk '{print $5}' | sort -n | uniq -c
+ localstorage/sessionstorage
+ python
    + enumerate('一二三四')为八个字符
+ url/uri
+ logging
+ 测试
+ scrapy

## 2016/04/03
+ vertical-align
+ Chrome与IE的事件冒泡和事件捕获
+ 轮播插件，按需加载
+ word-break/word-wrap
+ 绝对居中
    + top/left/translate
    + top/left/margin
    + top/left/right/bottom
    + flex
+ shfshanyue.github.io/?
+ 圆角矩形，扇形

## 2016/03/28 - 2016/04/03
### python
1. 在python2中 \__future__ 模块有什么作用
1. 实现一个简单的用户注册登陆Demo
1. 实现用 OAuth 进行登陆

### FE
1. CSS如何使过渡渲染加速
1. html5中的WebWorker有什么用
1. html5中有哪些新东西
1. setTimeout与setIntervel有什么不同
1. call, apply, bind 的区别

### Linux
1. awk, grep, sort 对当前路径下大于1024K的PDF文件进行排序打印+ [javascript Promise 迷你书](http://liubin.org/promises-book/)
+ [常见80中植物](http://www.360doc.com/content/10/0324/23/912654_20141681.shtml)

## 2016/04/04
+ 函数式编程
    + 柯里化
    + 高阶函数
    + 柯里化
    + 闭包
+ python cookbook
    + 去除重复
+ flask
    + 当关闭浏览器再打开网站时如何保存登陆状态
    + 每次打开首页时，发送一个cookie，接收到一个cookie

## 2016/04/05
+ 浏览器插件百度贴吧
+ tencent
    + XSS与CSRF的实现原理以及二者的区别
    + Ajax的实现原理
    + ES6 Promise的实现原理
    + http 2.0 
        + 首部压缩
        + 优先级处理
        + 双向字节流的请求与相应
    + post请求会有什么头
    + 缓存的实现机制
    + 闭包的实现
+ baidu
    + 函数继承
    + 如何判断一个变量是否为数组
+ tmall
    + 让一个元素看不见的CSS属性
    + 居中
    + 你最牛逼的项目
+ http2.0
    + 二进制分帧层
    + 多向请求与相应（多路复用）
    + 优先级和依赖性
    + 首部压缩
    + 服务器推送
+ 资源内嵌（base64）
+ translate3D
+ http
    + Upgrade-Insecure-Requests
    + Strict-Transport-Security
+ https
    + 运营商劫持
    + web前端黑客技术揭秘
+ 登陆
    + session
    + 单点登录
    + md5加盐


## 2016/04/07
+ bytes / str

## 2016/04/15
+ python
    + absolute import
+ html5
    + link.download
    + link.click()

## 2016/04/16
+ textContent
+ for of/forEach

## 2016/04/17
+ [深入浅出Fetch API(blog)](http://wwsun.github.io/posts/fetch-api-intro.html)
+ [这个API很“迷人”](http://www.w3ctech.com/topic/854)
+ [This is so fetching](https://hacks.mozilla.org/2015/03/this-api-is-so-fetching/)

## 2016/04/11 - 2016/04/17
### python
1. 什么是 `absolute import`
1. 使用 `logging` 模块，保存日志至文件中，并同时打印到控制台

### FE
1. 设置那些CSS属性，可以使元素不可见
  + display: none
  + opacity: 0
  + hidden
  + position: absolute; left: -1000px;
2. html5 设置 `input[type="text"]` 能够自动补全
3. 统计文档内每种标签的个数
4. `Web Workers` 运算斐波那契数列的前1000项和，并显示在页面
5. `File API` 上传文件，并显示进度
6. `Location API` 获取用户位置，并且每10分钟更新一次
7. `requestAnimationFrame` 制作进度条动画
8. `Fetch API` 发送post请求

## 2016/04/18
+ [Promise 陷阱(blog)](http://www.jianshu.com/p/9e4026614fbe)
+ flask
  + app.add_url_rule()
  + app.error_handle_spec
  + url_for()
  + globals.py
    + context locals

## 2016/04/19
+ [API Store 语音识别](http://apistore.baidu.com/apiworks/servicedetail/792.html)
+ python
  + 各种编码以及大小
  + requests Content-Length
  + fiddle https
  + unicode 和 utf-8 bytes 的len (你好)
    + unicode 2
    + utf-8 6
    + bytes 6
  + flask(0.10.1)
  + scrapy(1.0.5)
    + [win32API](https://sourceforge.net/projects/pywin32/files/pywin32/Build%20219/)
    + xpath
    + css
+ sql
  + 随机取五十条数据
  + ItemPipelines

## 2016/04/21
+ XPath
  + extract()
  + escape character
  + /, //, @, text(), ., .., Nodename
  + last(), position
  + type
    + 元素
    + 属性
    + 文本
    + 命名空间
    + 文档


## 2016/04/25

> 天下事尽在吾彀中

> 享清福不在为官，只要囊有钱，仓有粟，腹有诗书，便是山中宰相；
> 祈大年无须服药，但愿身无病，心无忧，门无债主，就是地上神仙。

> [2015前端生态发展回顾(blog)](https://github.com/kuitos/kuitos.github.io/issues/32)

+ blog
  + child-blog
    + [javascript如何实现监听一个变量的改变](javascript如何实现监听一个变量的改变)
  + React
    + Virtual DOM / jsx / immutable object
  + Redux
    + 函数式编程 / 单一数据源 / 不可变数据 / 中间件
  + Angular 2 / Aurelia
  + Vue / Vuex
  + ES2015
    + Module
    + Class
    + Promise / Reflect API
    + O.o
      + polymer observe-js
      + immutable / Proxy / accessor
  + ES2016
    + Async / Await
    + Decorator
  + WebAssembly
  + Web Components
    + Shadow DOM
    + Custom Element
    + Template Element
    + HTML imports
  + 组件化
  + Webpack / Cssnext / postcss
+ DOM
  + document.ownerDocument / ownerSVGElement

## 2016/04/25
> [JavaScript中的不可变性(blog)](https://segmentfault.com/a/1190000004906518)

+ DOM2
  + document.impletation.createDocument(null, 'root', null)
  + document.impletation.createHTMLDocument
  + document.body.isEqualNode(document.body)
  + el.style.removeproperty('width')
  + document.createNodeIterator()
  + document.createTreeWalker()
+ event
  + bubbles
  + cancelable
  + eventPhase
  + type
  + target
  + currentTarget 
  + preventDefault()
  + stopPropagation
  + defaultPrevented
  + detail
  + view
  + stiopImmediatePropagation
  + trusted


## 2016/04/27
+ Django ORM
  + IntegerField
  + CharField
  + DatetimeField
  + DateField
  + TimeField
  + URLField
  + FilePathField
  + BooleanField
+ SQL-Alchemy (7/16)
  + Integer
  + SmallInteger
  + BigInteger
  + Text
  + Datetime
  + Date
  + Time
  + Float
  + Numeric
  + String
  + Unicode
  + UnicodeText
  + Boolean
  + Interval
  + PickleType
  + LargeBinary
+ Question
  + Question.objects.all()
  + Question.objects.filter(question_text__startswith='who')
  + q.choice\_set.create(choice_text='xiange', votes=3)
  + q.choice_set.all()
  + q.delete()

## 2016/04/28
+ ORM
  + flask q.query.all()  / django Question.objects.all()
+ pip
  + pip install pyopenssl ndg-httpsclient pyasn1
+ scrapy
  + weki
  使用 `collection.deque` 数据结构，分布式爬虫。请求被异步调度和处理。
  + structure
    + items.py
    + pipelines.py
    + spiders
      + tieba
      + zhihu
  + command line
    + scrapy crawl tieba -o data.json
  + scrapy runspider tieba.py -o data.json
    + scrapy shell 'http://www.zhihu.com'
    + scrapy genspider tieba
    + scrapy list
    + scrapy fetch
  + ubuntu install error
    + sudo pip install pyOpenSSL==0.14

## 2016/04/29
+ CSS 3.0
    + 伪元素选择文本或属性节点

## 2016/04/30 |||| ||||
[XPath](http://zvon.org/comp/r/tut-XPath_1.html#Pages~XPath_as_filesystem_addressing)

+ Event
  + KeyboardEvent
    + keypress
      仅仅在按下字符的时候触发事件。在 Firefox 中为任意键。
    + keyup
      按下的字母键都会转为大写。
    + keydown
  + TextEvent
    + textInput
      data接受输入的数据，Firefox 中不支持
  + MutationEvent
    + DOMNoderemoved
    + DOMSubtreeModified
+ scrapy
  + Selector
    + CSS 与 XPath 的嵌套选择器
      XPath需要使用 `.//`
    + 正则表达式支持
      sel.xpath(div[re:text(@class, '\d$')])
    + CSS 使用 ::attr()，::text
    + XPath 使用 @，text()
+ sqlalchemy
  + create_engine
  + declarative


## 2016/05/01 |||| |
+ mongo
  + sort
  + group
  + distinct
  + index
  + explain
+ scrapy
	+ scrapy.crawl
	+ 先获取数据，回调，再获取数据
	+ 设置超时，部署，设置spider的参数
	+ 设置http头，设置cookie
+ js
  + charCodeAt
  + fromcharCode
  + encodeURIComponet

## 2016/05/03 |||| |

## 2016/05/04 |||| ||
+ html5 event
  + touchstart
  + touchmove
  + touchend
  + createEvent
  + initCustomEvent
  + pageshow/pagehide

## 2016/05/05 |||

> 不经一番寒彻骨，怎得梅花扑鼻香。

+ crontab 
  + vim test.cron
  + crontab test.cron
  + crontab -l
+ bootstrap
  + dropdown
    + background-clip
+ urlparse
+ review
  + django
    + `models.IntegerField(default=10)`
    + `question = models.ForeignKey(Question)`
    + `Question.objects.all()`
    + `Question.objects.filter(question_text__startswith='how')`
    + `Question.objects.order_by('question_text')`
    + `Question.objects.get(pk=1)`
    + `q.choice_set.create()`
    + `q.choice_set.all()`
  + flask-sqlalchemy
    + `db.Column(db.Integer, primary_key=True)`
    + `question_id = db.Column(db.Integer, db.Foreignkey('questions.id'))`
    + `choices = db.relationship('Choice', backref='question')`
    + `question.choices`
    + `Question.query.all()`
    + `Question.query.filter()`
	+ 多情剑客无情剑
		+ 黑白双蛇/铁传衣/阿飞/七妙手 妙郎君花峰 妙郎中梅二先生/青魔手伊哭/丘独/铁面无私赵正义/秦重/鱼肠剑游龙生/龙啸云/林诗音/龙小云/林仙儿/极乐峒/心眉/心树/心湖/心鉴/百晓生/荆无命/向松/蓝蝎子/大欢喜菩萨/孙二驼子/郭嵩阳/银戟温侯吕奉先/中原八义/天机老人/孙小红/西门柔/诸葛刚

## 2016/05/06 |

## 2016/05/07 ||||
+ review
  + Event
    + MouseEvent/UIEvent/Event
      + createEvent/initEvent/dispatchEvent
    + dragdrop Event
      + dragstart
      + drag
      + dragend
      + dragenter
      + dragover
      + dragleave/drop
    + NodeIterator
      + document.createNodeIterator(document, NodeFilter.SHOW_ELEMENT, null)
      + document.createTreeWalker()
        + nextSibling()
        + previousSibling()
        + firstChild()
        + lastChild()
        + parentNode()

## 2016/05/09 ||||

## 2016/05/10 |||| |
+ [JavaScript template engine in just 20 lines](http://krasimirtsonev.com/blog/article/Javascript-template-engine-in-just-20-line)
+ [JavaScript template engine in just 20 lines(译)](http://blog.jobbole.com/56689/)

+ review
  + vuex
    + action
    + mutation
    + store
  + react
    + React.Children.map
    + getDefaultProps
    + propTypes
    + React.PropTypes.string.isRequired
    + getInitialState
+ canvas
  + toDataURL
  + getContext
  + strokeStyle/fillStyle
  + strokeRect/fillRect
  + strokeText/fillText
  + path
    + arc/arcTo/lineTo/moveTo/rect
+ ajax与comet
  + SSE
  + websocket
+ webpack
  + ~ 运算符

## 2016/05/11 ||||
+ React
  + constructor
  + componentWillMount
  + render
  + componentDidMount
  + componentWillReceiveProps
  + shouldComponentUpdate
  + componentWillUpdate(nextprops, nextstate)
  + render
  + componentDidUpdate(prevprops, prevstate)
  + componentWillUnmount

  + defaultProps
  + displayName

## 2016/05/12 ||

## 2016/05/13 |||
+ metrial design
  + snippet
+ vue-async-data
+ css3
  + will-change
  + matrix
  + transform-style
  + -webkit-box-direction
  + -webkit-box-orient
  + -webkit-tap-highlight-color

## 2016/05/14 |||| |
+ ingacentHtml
+ touchAction
+ cordova
  + 修改名称
  + 修改logo

## 2016/05/15 ||
+ ionic
  + live deploy
  + user auth
  + ionic start diary / ionic serve
+ ionic2
+ datetime
  + strptime
  + strftime
+ restful api

## 2016/05/16 ||||
+ babel
+ html
  + dl/dt

## 2016/05/17 |||| ||
+ str.match(/#[\u4e00-\u9fa5A-Za-z]+[$\s]/g)
+ data-url
  + base64
    + + / -
    + ? / _
+ ionic
  + app初始空白

## 2016/05/19 ||||
+ Array.prototype.sort
+ css
  + touch-action
    + auto
    + none
    + pan-x
  + perspective
+ Object
  + Array
      + toLocalString/toString/valueOf/join
      + push/pop/shift/unshift
      + indexOf/lastIndexOf/includes
      + concat/slice/splice
      + sort/reverse
      + every/some/filter/map/forEach/reduce/reduceRight
  + date
      + Date.UTC/Date.parse/Date.now
      + toLocalTimeString/toLocalDateString/toLocalString

## 2016/05/22

+ [grid-layout](https://platform-status.mozilla.org/#grid-layout)

+ django
  + python manage.py makemigrations polls
  + python manage.py migrate
  + python manage.py sqlmigrate polls 0001
+ interview /toutiao
  + arguments 是数组吗
  + 如何把类数组转化为数组
  + 如何判断一个变量的数据类型
  + localStorage 和 sessionStorage 的区别是什么
  + 同源策略的目的是什么
  + 三等分div，左边固定右边自适应
  + 什么是BFC
  + 如何居中一个元素
  + 二分查找/归并排序

  + https://www.interviewzen.com/
  + 什么是wsgi
  + 协程和线程的区别
  + gevent 是什么
  + gevent/scrapy做爬虫的分工是怎么样的
  + 云平台的代码和自己的代码是如何工作的
+ javascript
  + 下标即值
    + Array.from({length: 100})
    + Array.apply(null, {length: 100})
    + [...Array(100)]
    + Array(100).fill().map((_, i) => i)

## 2016/05/24 ||
+ https://www.toptal.com/react/tips-and-practices
+ tomato
  + 禁止路由

## 2016/05/25 |
+ react
  + babel-core
  + babel-presets
  + babel-loader

## 2016/05/26
+ interview/zhihu
  + javascript适合做前端吗，其他语言呢，为什么
  + javascript能实现多态重载继承吗，与python的有什么不同
  + javascript的原型链
  + http 请求与响应的报文格式
  + websocket与http有什么不同
  + SSE是如何关闭链接的
  + react和vue有什么不同
  + angular和vue有什么不同
  + html5有什么新的东西
  + 你在豆瓣学到了什么，为什么不留在豆瓣
  + 你以后想做前后，后端还是移动端
  + 你以前做的东西遇到过什么困难
  + 你对你几年后是如何看待的
  + 你对你的工作有什么要求
+ html5 / review
  + js
    1. RequestAnimationFrame
    2. Page Visibility API
    3. Geolocation API
    4. File API
    5. Web Timing
    6. Web workers
    7. WebSocket API
    8. Fetch API
    9. Audio
    10. Video
    11. dragdrop API
    12. history API
  + DOM
    12. tag 
    12. contenteditable
    13. Selectors API
    14. Travelsal API
    15. classList
    16. insertAdjacentHTML / innerHTML
    17. scrollIntoView
    18. dataset
    19. canvas
  + other
    20. 离线缓存
    21. localStorage / sessionStorage
    22. indexDB
+ http / 报文格式

## 2016/05/27 ||
+ review
  + http报文格式
  + grid
    + container
      + grid-template-rows / grid-template-columns
      + grid-template-areas
      + grid-gap
      + grid-auto-columns / grid-auto-rows
      + justify-items / align-items
      + justify-content / align-content
        + start
        + end
        + center
        + stretch
        + space-around
        + space-between
        + space-evenly
      + grid-auto-flow
        + row
        + column
        + dense
    + item
      + grid-area
      + align-self
      + justify-self
+ webpack
  + webpack-dev-server --inline --content-base .
  + webpack-dev-server --inline --hot
  + webpack --progress --hide-modules
  + externals
+ node
  + path.join
  + path.resolve
+ html5
  + public storage

## 2016/05/28 
+ object
  + Object.is()
  + Object.assign()
+ react router
  + 404
+ router event
  + popstate
  + hashchange

## 2016/05/30
+ time
+ ajax
+ tomato
  + post need get ObjectId

## 2016/06/01
+ Vue.nextTick
+ console.timestamp

## 2016/06/02
+ git
  + git rm --cached
+ review
  + git 生成 gh-pages 不要太麻烦
    + gh-pages 库
  + Object
    + getOwnPropertyNames
    + getOwnPropertyDescriptor(复制描述符对象)
    + is
    + for...in...
    + Object.setPrototypeOf()
    + Object.getPrototypeOf()
    + __Object.create()__
    + Object.assign(), {...obj}
+ python
  + getattr / getattribute
  + setattr

## 2016/06/06
+ shell
  + apt-catch search jdk
  + openjdk
  + update-alternatives

## 2016/06/10
+ [Linux工具快速教程](http://linuxtools-rst.readthedocs.io/zh_CN/latest/)
+ lsof -i:3000

## 2016/06/11
+ crosswalk
  + cordova plugin add cordova-plugin-crosswalk-webview

## 2016/06/17
+ [html5test](http://beta.html5test.com/)
+ Web Animation API

## 2016/06/18
+ 多态
+ 重载
  + 参数个数不同
  + 参数类型不同
+ 继承

## 2016/06/19
+ Web Speech API
+ FullScreen API
+ Web Notification API

## 2016/06/20
+ ArrayBuffer
+ Data-Url
+ WeakSet / WeakMap

## 2016/06/27
+ react
  + version
  + creat react app
    + vue-cli
+ git
  + remove remote

## 2016/07/04
+ html5
  + elements
    + new elements
    + dataset
    + hidden
      + 又多一种隐藏元素的方式
  + sementics
    + html parsing
    + selectors api
    + element traversal api
    + dataset
  + forms
    + field types
    + validation
    + required
    + datalist
  + communication
    + web socket
    + sse
    + xhr2
    + web rtc
    + fetch
    + beacon
  + UI
    + Dragdrop
    + contenteditable
    + desine mode
  + performance
    + web workers
  + storage
    + localstorage / sessionstorage
    + indexedDb
    + web sql
  + File API
  + offline app
    + application cache
    + service worker
  + device
    + geolocation
    + __device orientation__
    + __device motion__
  + output
    + full screen
    + __web notification__
  + graphics
    + canvas
    + responsive images
      + picture element
      + srcset
      + sizes
    + web gl
    + requestAnimationFrame
  + web components
    + custom elements
    + shadow dom
    + html template
    + html imports
  + media
    + video / audio
  + other
    + history api
    + web timing
    + performance api
    + web speech
    + async script
    + page visibility

## 2016/07/05
+ BFC Block Formatting Context
  + 特性
    + BFC不与浮动元素重叠
    + BFC不会发生margin collapse
    + BFC包含浮动

## 2016/07/06
+ bind
+ prototype
+ Object.create 

## 2016/07/08

> 昔乘匹马去,今驱万乘来.

+ hot reload
+ web components

## 2016/07/09

+ [安全hash算法](https://en.wikipedia.org/wiki/Secure_Hash_Algorithm)
+ [荒野公学](http://www.wildschool.cn/portal.php)
+ tieba scrapy
  + 获取所有的用户头像
  + 获取每月帖子排名
  + 使用 gevent 替些爬虫
  + 熟悉 xpath 与正则表达式
  + 熟悉 mongo 与 sql
+ scrapy
  + 项目组织结构
  + 带密码如何爬取
  + 传递参数
  + 下载文件
  + scrapy.pipeline.images.ImagesPipeline

## 2016/07/11
+ python
  + print(3, 4) and print 3, 4
  + new styled class
  + try else
  + for else
  + defaultdict
