# 7-yangying-953
1、git与github的区别
github是一个网站，每个程序员可以在其上建立自己的仓库，可以将自己所写的代码提交上去，可供别人浏览，同时别人也可以帮助你修改代码，非常方便程序员之间的交流和学习。
而git的作用就是让你更好的管理自己的程序，是可以在你电脑不联网的情况下，只在本地使用的一个版本管理工具。

2、git与github传输过程
从github到git，首先通过fetch将修改后的远程仓库内容推送到本地仓库，然后本地仓库再通过merge将其推送到工作区。
从git到github，首先工作区查找变动，再stage后到暂存区，再commit后到本地仓库，最后将其push到远程仓库。

