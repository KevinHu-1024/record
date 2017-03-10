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
  + rebase -s
  + grep && ag

## 2017/03/10
> 因过竹院逢僧话，又得浮生半日闲。

+ webpack 热替换图片
