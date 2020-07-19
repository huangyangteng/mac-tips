# 自定义全局快捷键

> 自定义全局快捷键的目的是为了在不同的程序(窗口)之间快速切换

## 为什么要自定义全局快捷键

我除了电脑还有两台外界显示器，一般这三台显示器的功能如下：

* 右显示器： 只写代码，常用程序Vscode
* 左显示器：80%的情况下只开一个Chrome浏览器，用来如查看代码运行结果
* 中间笔记本显示器：用来处理一些临时的事情，比如打开dash查文档，打开qq回个信息，打开终端执行个命令等等

![image-20200719101728635](https://tva1.sinaimg.cn/large/007S8ZIlgy1ggw2crbm6qj30mo0crt8y.jpg)



由于经常要在不同的显示器之间切换，拖动鼠标到对应的显示器显得有点慢，所以我使用Keyboard Maestro软件绑定了快捷键，用于在不同的程序（屏幕）之间切换。使用场景如下：

* 想写代码的时候，按option+v ，就可以快速进入vscode中
* 要在浏览器中调试代码，按option+c，快进进入浏览器
* 临时想打开终端执行条命令，按option+i快速打开
* 工作的时候常常关闭qq，想找人，option+q,快速打开qq，发完消息之后，command+q直接退出qq,进入写代码状态

## 如何配置

我的配置原则是：

* 只配置使用最频繁的软件（每天都要使用），未配置的软件使用Alfred打开
* 快捷键优先使用option+应用首字母
* 如果有冲突，就随便吧   例如微信和word首字母都是w,你可以使用option+w作为微信的，然后再给word安排一个自己记得住的

配置的快捷键如下：

| 打开或切换应用        | 快捷键   |
| --------------------- | -------- |
| QQ                    | option+q |
| Wechat                | option+w |
| Chrome(浏览器)        | option+c |
| Vscode(代码编辑器)665 | option+v |
| iTerm2(终端)          | option+i |
| Finder                | option+f |
| ...                   | ...      |

### 配置方式



![image-20200625100556700](https://tva1.sinaimg.cn/large/007S8ZIlgy1gg4b5eputej30zf0hktbv.jpg)

![image-20200625100937664](https://tva1.sinaimg.cn/large/007S8ZIlgy1gg4b97820bj30zg0hpjxb.jpg)

### 参考文章

* [Keyboard Maestro入门指南](https://sspai.com/post/36442)



