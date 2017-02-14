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
  + [The branch 'XXX' is not fully merged.]()
  + tips
    + git help everyday
    + git commit -vv --amend
    + git log master...develop

hello, world.
