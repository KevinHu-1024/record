## 2017/01/05
+ vim
  + lightline solarized
+ shell
  + $#
  + $\*
  + $@
  + ' "
  + $[3 * 4 + 9]
+ javascript
  + use strict
+ zsh-themes
  + muse
  + cloud
  + wuffers
  + peepcode
  + simple
  + lambda
  + dieter

## 2017/01/10
+ tmux
  + -s / server, session

## 2017/01/13
+ git
  + count commit
  + git shortlog --sumary --numbered

## 2017/01/14
+ ansible
  + get started

## 2017/01/17
+ docker
  + Dockerfile arguments
  + docker build | memory cpu build-arg 
  + ENV always overwride ARG
  + HEALTHCHECK
+ curl -L

## 2017/01/18
+ tcp
  + iptables
+ docker
  + [change password to root](http://stackoverflow.com/questions/28721699/root-password-inside-a-docker-container)
+ ansible
  + ansible all --module-name ping --user dev
  + [ansible examples](https://github.com/ansible/ansible-examples)

## 2017/01/19
+ ansible
  + 幂等性
  + ansible-playbook sites.yml
  + ansible-playbook sites.yml --list-hosts
  + ansible-playbook sites.yml --list-tags -i(--inventory-file)
  + Action Shorthand
+ linux
  + sudo -H
  + sudo --preserve-env
+ css
  + modal
    + 自身高度过于屏高，自身滚动条与外部滚动条
  + flex
    + difference with width and flex-basis

## 2010/01/22
+ git
  + git-hooks
    + pre-commit
+ css (think)
  + rem(root) & em
    + .container > .row > .item  1.5em 1.5em ?
  + boder and center
  + flex(align-items: center) flex-item(align-self: stretch)

## 2017/01/24
+ git-hooks (review 2017/01/22)
  + pre-commit
  + patch
  + reset
  + revert
  + working/stage/repositry
+ ansible
  + handlers
  + file
+ proctocal
  + icmp (internet control message protocal)
+ shell
  + iptables
+ react
  + life cycle
+ graphql

## 2017/01/25
+ ansible
  + 回滚
  + root /etc/hosts
+ docker
  + portainer set user
+ git
  + submodule
+ css
  + background
    + background-origin
    + background-clip
    + background-attachment
    + background-blendmode
## 2017/01/26
+ ansible
  + ProxyCommand
  + ansible_user / ansible_port / ansible_host / ansible_connection
+ network
  + route
  + nc

## 2017/01/27
+ http
  + pragma: no-cache
  + from memory cache / from disk cache
+ Command Line API
  + copy
  + monitor
  + monitorEvents

## 2017/01/28
+ [前端部署](https://www.zhihu.com/question/20790576/answer/32602154)
  + CDN
  + hash
  + 非覆盖发布
  + 超长缓存

## 2017/01/29
+ css
  + rgba(0,0,0,.3) => rgb(179,179,179)
    + [](http://stackoverflow.com/questions/6672374/convert-rgb-to-rgba-over-white)
    + [](http://stackoverflow.com/questions/2049230/convert-rgba-color-to-rgb?rq=1)
  + [Alpha Compositing](https://en.wikipedia.org/wiki/Alpha_compositing)
  + Stacking Context
    + absolute, relative + z-index: n
    + fixed
    + flex-item + z-index: n
    + transform
    + opacity
+ tmux
  + pane-boder-width
+ npm
  + shrinkwrap

## 2017/01/30
+ event
  + pagehide / pageshow / visibilitychange / bfcache  browser backward mechanism
+ html
  + window.opener
  + target="\_blank" 漏洞
+ ES6
  + class and proptype

## 2017/02/01
+ containing block
  + position
    + sticky
+ writing mode
  + horizontal-tb
  + vertical-lr
  + vertical-rl
+ css
  + text-transform
  + text-orientation
    + upright
    + mixed
+ github
  + img

## 2017/02/02
+ json web token

## 2017/02/03
+ vim
  + emmet
+ CSS function
  + attr
    + a:empty::after{ content: attr(href) }
    + CSS Values Level 3
  + calc
    + CSS Values Level 3
    + inline-block + calc  incorrect left-right layout
+ baseline
+ ::after
  + Selectors Level 3
+ inline-block space
  + white-space-collapsing: discard (Text Level 4)
+ FormData
+ ansible
  + yum
+ YAML
  + --- seperate directives from document content

## 2017/02/04
+ ARP(Address Resolution Protocal)
  + basic concept
    + arp cache
    + A (ip, MAC) B (ip) broadcast -> local newwork
  + arp spoofing
+ css3
  + all: unset
+ ansible
  + file
  + get_url
  + yum
  + apt
  + template
+ ansible
  + file mode 0755 why 0

## 2017/02/06
+ tcpdump
  + tcpdump host <ip>
  + tcpdump 'tcp port 80'
+ wireshark
+ Progressive Web Apps
  + Cache Storage
  + Service Worker
    + Web Worker
    + App Cache 从html5.1中移除
  + Manifest
    + orientation
    + theme_color
  + Notification Api
  + Push Api
+ ansible
  + ansible-pull
  + Roles
  + ansible-galaxy

## 2017/02/07
+ nslookup
+ dig
+ ansible
  + pretask
  + posttask
  + {{ inventory_hostname }}
  + local_action
  + notify / handle
+ grid
  + grid-auto-columns

## 2017/02/09
+ ansible
  + ansible-galaxy
  + cosway
  + git
    + accept-hostkey
  + error
    + [ansible-galaxy python version](https://github.com/ansible/galaxy-issues/issues/209)
    + [python3 version](https://github.com/ansible/ansible/issues/20012)
+ git
  + known_hosts
  + RSA
  + SHA256
  + ECDSA
+ markdown
  + < escape
+ regular expresion
  + (?=exp)
  + (?<=exp)

## 2017/02/10
+ git
  + git clean -d -fx ""
+ content-box
+ css
  + `.row>.column*3`
    + .row height: 100px, .column: 100% (100px)
    + .row height: auto(100px), .column:first-child: 100px (撑高父级) .column: 100% (**0px**) 
    + think: height (多列登高)
  + **min-height not work but work with height**
+ webpack
  + webpack-dev-server source
    
## 2017/02/11

+ [height](http://stackoverflow.com/questions/1122381/how-to-force-child-div-to-100-of-parents-div-without-specifying-parents-heigh?rq=1)

## 2017/02/13
+ css
  + property
    + initial / inherit / unset
  + svg
    + glyph
    + missing-glyph
+ ansible
  + tags / always
  + verbose / -vvv more / -vvvv debug
+ git
  + links
    + [git-tips](https://github.com/521xueweihan/git-tips)
    + [git-guide](http://rogerdudler.github.io/git-guide/index.zh.html)
  + tips
    + git config color.ui true
    + git help -g
    + git update-ref -d HEAD
    + git diff          index / working
    + git diff HEAD     index, working / last commit
    + git diff cached   index / last commit
    + git checkout - 
    + git branch -vv

## 2017/02/14
+ git
  + [Signed-off-by](http://stackoverflow.com/questions/1962094/what-is-the-sign-off-feature-in-git-for)
  + [The branch 'XXX' is not fully merged.](http://stackoverflow.com/questions/7548926/git-and-the-branch-x-is-not-fully-merged-error)
    + git log --graph --left-right --cherry-pick --oneline origin...develop
    + **--cherry-pick**
  + [Difference between "git add -A" and "git add ."](http://stackoverflow.com/questions/572549/difference-between-git-add-a-and-git-add?rq=1)
  + [Git for beginners](http://stackoverflow.com/questions/315911/git-for-beginners-the-definitive-practical-guide)
  + tips
    + git help everyday
    + git commit -vv --amend
    + git log master...develop
    + git ls-files -o
    + git submodule foreach git pull
    + git cherry -v master
+ [登录那些事](https://cnodejs.org/topic/5671441a1d2912ce2a35aaa1)
+ redux
  + location.state 原理

## 2017/02/15
+ react-router
  + location.state souce-code
    + history.js
      + v3 window.history.state & sessionStorage
      + v4 window.history.state 还没出 release notes，尴尬...
+ peerDependencies
+ semver
  + Tilde ~ 
  + Caret ^
  + Hyphen -
  + X x
  + API
    + satisfies
+ [Master the JavaScript Interview: What is a Closure?](http://www.zcfy.cc/article/master-the-javascript-interview-what-is-a-closure-2127.html)

## 2017/02/16
+ git
  + .git/info/exclude
  + dir
    + info
    + hooks
    + refs
    + logs
    + objects
  + tips
    + git hash-object &lt;file>
    + git cat-file -p &lt;commit-ish>
    + git remote set-url origin &lt;url>
    + git add -p
    + git whatchanged --since "2 days ago"
    + git stash save -u | git stash save --include-untracked
    + git clean -x -d -n     remove untrcked + ignore
    + git clean -X -d -n     remove only ignore
  + commit-ish
    + md5     128bit
    + sha1    160bit   ->   echo hello, world | shasum
    + sha256  256bit
    + sha512
+ gerrit
+ pre git
  + diff / patch
  + CVS (Concurrent Versions System) 
  + svn (Subversion)
  + git -> BitKeeper  (2005)

## 2017/02/17
+ git
  + concept
    + git cat-file -t &lt;commit-ish>  ->  type
    + git cat-file -p &lt;commit-ish>  ->  content
    + tree
    + blob
    + tag
    + commit
  + tips
    + git show &lt;commit-ish>
    + git show &lt;branch-name>:&lt;file-name>
    + git rebase -i | reword  -> commit-ish 会发生改变 修改以前的commit
    + git commit --no-verify 
    + git commit -n
    + git bisect | git checkout HEAD~7
    + git reset &lt;file>
    + git shortlog
    + git cherry -vv
    + git status -sb  ->  --short --branch
    + git log --oneline
    + git ls-files
    + git ls-files -s
    + git ls-tree HEAD
    + git reflog show master
  + objects
    + HEAD
    + master
    + refs/heads/master
    + 
+ shell
  + gawk
  + wc
+ react
  + react.cloneElement()
+ vim
  + q  ->  recording

## 2017/02/18
+ multi-column-layout
+ git
  + git reset -> index
  + git reset --hard -> index working-tree
  + git reset --soft -> commit
  + git reset --mixed -> index commit
  + git checkout -> working-tree
  + git diff
    + --name-only
    + --status-only
  + git ls-files
  + [how-to-use-git-bisect](http://stackoverflow.com/questions/4713088/how-to-use-git-bisect)
  + git checkout &lt;commit>
  + git diff-index 
+ **FE Think**
  + 项目启动期定好 state 和 router ，定好 webpack, eslint。
  + 项目启动期定好一些基本组件，如常见的组件 Tooltip, Modal, Alert
  + 否则技术债很多，比如后加的 eslint 形同虚设，中期难以迁移 webpack，难以 hmr，proxy，最重要是缓存的一些问题，以及各种形式的消息提示框。
+ FP
  + compose
+ **Git Flow Think**
  + 

## 2017/02/21
+ react
  + state is evil
+ git
  + git checkout HEAD~10  -> detached HEAD refers to a valid commit
+ npm
  + types

## 2017/02/22
+ css
  + font
  + selection background-color 不符
  + line-height: 1.5em 根据什么为基准

## 2017/02/23
+ **论表格中的tooltip与层叠上下文**
+ git
  + git push stratety
    + central workflow
    + non-central workflow
    + upstream / simple
+ css
  + ::after 权重

## 2017/02/24
+ git
  + follow
  + **git log need display date** -> git log --pretty=medium
  + tips
    + git log -p &lt;file>
    + git log --first-parent
    + git log master...develop
    + git tag --list
    + git describe -> v1.1.0-5-&lt;hash>
    + git rm &lt;file>
    + git checkout &lt;commit-ish> -- &lt;file>
    + .git/info/exclude : core.excludesfile
    + git archive -o tips.zip HEAD
    + git rev-list master
    + git rev-parse refs/tags/v3.0.2
    + git revert HEAD
    + git clone --bare
    + git commit --allow-empty
    + git show-ref
    + git gc
    + git 
+ [密码学大事件！研究人员公布第一例SHA-1哈希碰撞实例](https://zhuanlan.zhihu.com/p/25401383)

## 2017/02/25
+ git
  + git checkout -b test master
  + git log master..develop
  + git log master...develop

## 2017/02/27
+ git
+ go
  + defer
+ html
  + html entity encode

## 2017/02/28
+ cache
  + cache-control
  + age
+ gulp
  + gulp-rev
+ FP
  + 

## 2017/03/01
> 靡不有初鲜克有终
+ gulp
  + gulp 4.0
+ FP
  + Category Theory 范畴论
  + HOC
  + Partical Function
  + compose
  + curry
  + Point-Free Style

## 2017/03/02
+ RPC
+ message queue
+ FP
  + Predicate
  + Contract
+ ES6
  + [semi](http://www.ecma-international.org/ecma-262/6.0/index.html#sec-automatic-semicolon-insertion)
+ setTimeout 浏览器环境与node环境不一致
+ [如果你想靠前端技术还房贷，你不能连这个都不会](https://zhuanlan.zhihu.com/p/25259283?refer=fe-mm)
+ [Excuse me？这个前端面试在搞事！](https://zhuanlan.zhihu.com/p/25407758)
  + Event Loop && promise
+ **Cache Control**
  + github
  + taobao
  + zhihu
  + gold

## 2017/03/03
+ js
  + 'use strict'  this | 严格模式与node
  + node environment: module this [node this](https://segmentfault.com/q/1010000005128554)
  + Object.seal
  + Object.freeze
+ FP
  + **curry**
  + Constant -> Referential Transparency
  + Category
    + 

## 2017/03/05
> 宠辱不惊，闲看庭前花开花落。去留无意，漫看天边云卷云舒。

+ FP
  + ES6 ...args 无法确定个数  arity 为0
  + declarative programing 声明式编程
  + imperative programing  命令式编程
  + functor
    + Container.of
    + Container.prototype.of

## 2017/03/06
> 岁月本长，而忙者自促；天地本宽，而狭者自碍；风花雪月本闲，而扰攘者自冗。

+ FP
+ docker
  + aufs

## 2017/03/07
+ primitive
+ FP
  + lift

## 2017/03/08
+ FP
  + [Hinder-Milner](http://stackoverflow.com/questions/399312/what-is-hindley-milner/399392#399392)
  + parametricity
+ react

## 2017/03/09
+ js
  + tc39
+ git
  + rebase --onto target 
    + 话说这个功能就像 chery pick 一样
  + rebase -s
    + 据说指定 strategy 可以直接 pull amend后的
  + grep && ag

## 2017/03/10
> 因过竹院逢僧话，又得浮生半日闲。

+ webpack 热替换图片

## 2017/03/13
> 揣而锐之，不可长保。

+ https://github.com/gotwarlost/istanbul
+ https://github.com/remy/nodemon
+ mocha
+ nodeunit
+ webpack
  + yargs 解析命令行，就像是 python 的 argparse
  + CommonsChunkPlugin
  + ChunkManifestWebpackPlugin
+ npm
  + npm link webpack  // symbol link
+ debug
  + node-inspector

## 2017/03/14
> 三十功名尘与土，三千里路云和月。

+ Array.from(new Map())
+ node-inspector
  + 不是控制台，而是使用页面模拟一个控制台，不好使，比如监视某个变量
+ sock-js webpack里用到的，貌似原生库？ sockjs-client
+ 举个栗子 setState 不能放到 componentWillMount 里边，失败告终...
+ react class 的 this bind
+ network
  1. 多域名：cdn 缓存 与 cookie 带宽
  2. what-happend-when
  3. 长轮询在服务器 cache，websockets 双向通信的二进制协议，sse content-type: event-stream 的文本协议。
  4. request and response
    + DNT 不要追踪用户信息
    + Cache-Control 缓存控制
    + Transfer-Encoding
    + Etag 协商缓存 If-Modified-Since
    + X-Frame-Options 不允许嵌入 iframe
  5. method
    + GET
    + PUT
    + POST
    + DELETE
    + HEAD
    + OPTIONS
+ vim
  + 重新加载 :Agbuffer :bufdo e
+ webpack 2.x
  + optimize
    > creat-react-app 优化后仅有46kb (报的并不是 实际大小，而是需要gzip后的大小)，而vue-cli 优化后有 90+ kb
    + devtool: cheat-module-eval-source-map
    + 1.97 mb   native
    + 1.81 mb   webpack -p 即 --optimize-minimize (UglifyJsPlugin) --define process.env.NODE_ENV
    + [uglifyjs 报错](https://github.com/webpack/webpack/issues/1542)
    + 1.80 mb   UglifyJsPlugin 与 DefinePlugin 写到配置文件，自定义配置
    + 4.06 kb / 1.80 mb  把所有三方库都放到 commons 后
    + 1.46kb / 141kb    设置 devtool: ''
    + gzip
  + plugins
    + html-webpack-plugin
    + webpack-manifest-plugin 就像 gulp 的 gulp-rev
    + extract-text-webpack-plugin
    + react-dev-utils/InterpolateHtmlPlugin
    + compression-webpack-plugin
    + webpack-bundle-analyzer
    + friendly-errors-webpack-plugin
+ chalk

## 2017/03/15
+ ag --ignore-dir  好像直接忽略 .ignorefile
+ webpack
  + [big flag]
  + CommonsChunkPlugin
    + [**Long Term Caching**](https://webpack.js.org/guides/caching/)
    + **manifest 存在的必要性** 增量缓存
  + source-read
    + [].concat({ a:3, b:4 })  Array.prototype.concat() 参数可以是对象，来自 webpack 源码 [processOptions #175](https://github.com/webpack/webpack/blob/master/bin/webpack.js#L175)
    + webpack.config.js 中 stats 是什么鬼？ [stats](https://webpack.js.org/configuration/stats/)
    + Error.stackTraceLimit = 30 ;  栈深
    + ProgressPlugin
    + output.chunkFileName 与 output.filename 的区别，为什么有两个...
    + output 配置中 hash 与 chunkHash 的区别
      + hash 为 webpack 打印第一行的值
      + chunkhash 为每个 chunk 的 hash
+ think:
  + 404 页面是否应该重定向链接？ [404 是否应该自动跳转?](https://www.zhihu.com/question/19604683)

## 2017/03/16
+ webpack
  + CommonsChunkPlugin manifest : how to work? 工程化思考
  + MultiChunks
  + TreeShake
  + node-debug
    + 多开浏览器还是挺酷的
+ linux
  + ps -ef
    + ppid  parent pid
    + stime start time
    + time
    + tty


## 2017/03/17
+ webpack
  + Object.defineProperty(\__webpack_require\_\_, '\__esModule', { value: true })
  + jsonp 控制多 chunk

## 2017/03/18
+ vim
  + Ctrl+P 如何查看隐藏文件
  + 使当前标签页变为分屏页


## 2017/03/20
+ vim
  + = 缩进对于 object 出现问题

## 2017/03/21
+ CC By 4.0
+ webpack
  + plugin apply(compile)
  + Compiler => Tapable => Object
  + WebpackOptionsApply

## 2017/03/22
+ git prune
+ webpack
+ [**const-in-for-loop**](http://stackoverflow.com/questions/31987465/ecmascript-2015-const-in-for-loops)
    + `for (const i of l) {}`
    + `for (let i=0; i<10; i++) { let i }`
+ scss
  + 全局变量
+ js
  + [object object]

## 2017/03/23
> 功夫，两个字，一横一竖，赢的站着，输的躺下。

+ https
  + www.baidu.com 为什么访问的是 https 而非 http
    + [HSTS](https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security)
      + SSL 攻击
      + Strict-Transport-Security: max-age=31536000
      + Chrome 查看地址 [HSTS](chrome://net-internals/#hsts)
  + www.zhihu.com 为什么设置了 STS，仍然跳到 https?
+ Do Not Track [https://www.zhihu.com/question/20615448]
  + 不跟踪用户信息，浏览器设置，将会设置一个 DNT: 1 的请求头
+ javascript
  + '' && 3
  + Boolean('')
+ vim
  + emmet class in jsx 应该是 className，jsx 插件是否能解决？

## 2017/03/24
+ react
  + setState 连续多次，如何渲染
+ webpack
  + 控制css被引入的顺序 module DFS

## 2017/03/26
+ vim
  + 关于 tmux 下vim主题的问题
    + 背景显示不全，切换 term: screen-256color 解决问题

## 2017/03/27
+ css
  + difference between unset, initial, inherit
  + all: unset
    + color color 貌似也被排除在外
    + __style style 自身也有样式，display 初始值为 inline，而浏览器默认设置为 none__
    + unicode-bidi 排除在外
    + direction 排除在外
+ javascript
  + eventloop, macrotask and microtask

## 2017/03/28
+ closure
  + promise 如何实现异步 的 once
+ javascript
  + [js 问题集锦](https://github.com/creeperyang/blog/issues/2)
+ webpack
  + EntryPoint
  + EntryChunk 
  + code splitting css
+ algorithm
  + 多路归并

## 2017/03/30
+ JS
  + typeof x => x   // function  subtype
  + difference between function and arrow function
    + f.prototype / this / class
    + arguments / caller
  + __Array.isArray(Array.prototype) // true__
    + 为什么不是 object ！！！！！！
    + Number.prototype              // Number
    + String.prototype              // String
  + difference between __function__ and __object__
    + function   // callable object

## 2017/03/31
+ JS
  + String
    + s1 = new String('hello'); s1[0] = 'A'       // 'hello'
    + s2 = 'hello'; s2[0] = 'A'                   // 'hello'
+ css
  + __div: default: block; initial: inline;__
    + 浏览器 UA 默认为 block，其实初始值是 inline ！！！

## 2017/04/01
+ JS
  + String
    + string 是 immutable，因此任何方法无法改变其本身
    + Array.prototype.reverse.call(s) 无法使其逆置，因为修改了自身
    + this 不能赋值
  + Number
    + IEEE 754 64-bit binary
    + 0o363  // octal
    + 0b111  // binary
    + 0x127  // hexadecimal
    + 0.1 + 0.2
      + Number.EPSILON      2^-52
      + Number.MAX_SAFE_INTEGER     2^53 - 1
      + Number.isSafeInteger
    + 如何判断一个数是整数

## 2017/04/05
+ css
  + vertical-align: middle 给图片设置！

## 2017/04/06
+ images
  + [png, jpg, gif - stackoverflow](http://stackoverflow.com/questions/2336522/png-vs-gif-vs-jpeg-vs-svg-when-best-to-use)
  + [png, jpg, gif - zhihu](https://www.zhihu.com/question/20028452)
  + 分类
    + 有损 / 无损
    + Index Color / Direct Color
    + 点阵图 / 矢量图
+ inline
  + span
  + label
  + i
  + a
  + b
  + img
+ inline-block
  + textarea
  + input
  + select
+ block
  + div
  + h1
  + p

## 2017/04/07
+ countdown
  + 倒计时    多次计时
+ react
  + defaultProps 给 location.state 赋予默认值
+ css
  + [vertical-align](https://zhuanlan.zhihu.com/p/25808995)
  + font-family
    + 华文细黑：STHeiti Light [STXihei] 
    + 华文黑体：STHeiti 
    + 华文楷体：STKaiti 
    + 华文宋体：STSong 
    + 华文仿宋：STFangsong 
    + 儷黑 Pro：LiHei Pro Medium 
    + 儷宋 Pro：LiSong Pro Light 
    + 標楷體：BiauKai 
    + 蘋果儷中黑：Apple LiGothic Medium 
    + 蘋果儷細宋：Apple LiSung Light 
    + Windows的一些： 
    + 新細明體：PMingLiU 
    + 細明體：MingLiU 
    + 標楷體：DFKai-SB 
    + 黑体：SimHei 
    + 宋体：SimSun 
    + 新宋体：NSimSun 
    + 仿宋：FangSong 
    + 楷体：KaiTi 
    + 仿宋_GB2312：FangSong_GB2312 
    + 楷体_GB2312：KaiTi_GB2312 
    + 微軟正黑體：Microsoft JhengHei 
    + 微软雅黑体：Microsoft YaHei 
    + 隶书：LiSu 
    + 幼圆：YouYuan 
    + 华文细黑：STXihei 
    + 华文中宋：STZhongsong 
    + 华文仿宋：STFangsong 
    + 方正舒体：FZShuTi 
    + 方正姚体：FZYaoti 
    + 华文彩云：STCaiyun 
    + 华文琥珀：STHupo 
    + 华文隶书：STLiti 
    + 华文行楷：STXingkai 
    + 华文新魏：STXinwei 

## 2017/04/10
+ Dr. cleaner
+ autojump
+ nunjucks

## 2017/04/11
+ yarn.lock
+ template engine
  + nunjacks
  + jinja2
+ Number IEEE754

## 2017/04/12
+ tree
+ emmet
  + $$$$@2015
+ downloads
  + content-disposition:attachment;
+ browsersync

## 2017/04/14
+ emmet
+ git submodule
  + untracked content
+ http status code
  + 422 Unprocessable Entity  -> github star error
+ git
  + ssh git@github.com
  + 更改以前commit的author
    + git filter-branch
