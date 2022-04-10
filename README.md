# cbook
####介绍
cbook允许您在无后端的情况下整一个html手册，仅支持md

#### 0.1使用方法
你也许看到了0.1这个文件夹，里面有index.html和cb.min.js，这两个是必不可少的。
cbook仅适合放在服务器上，因为在自己的电脑上访问不了文件。
这以book.svipking.top为例：
【'http://book.svipking.top/0.1/?ml=awa&wj=index'】相当于访问book.svipking.top/0.1下的awa目录中的index.md。
【'http://book.svipking.top/0.1/?wj=index'】相当于访问book.svipking.top/0.1下的的index.md。
ps:0.1判断机制：如果检测到ml参数和wj参数就访问，否则如果检测到wj参数也访问，所以当你访问【'http://book.svipking.top/0.1/?wjadwaw=indeadadx&wj=index'】也同样可以访问到【'http://book.svipking.top/0.1/index.md'】,此外，cb.min.js集成了jQuery、marked，然后还加了点我自己写的代码，在最后面，有需要的可以自己分开查看。
