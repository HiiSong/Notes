# 使用Github仓库

GitHub是一个很强大线上仓库，本篇笔记记录新手小白从零开始使用GitHub的经历。

***本篇笔记参考网站：***
https://www.cnblogs.com/wangcuican/p/12522239.html
https://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html

### 基本概念

先介绍几个基础概念便于理解，本地代码提交到GitHub远程是途经多个站点，不是一蹴而就的。

![](assets/GitHub流程.png)

1. **Workspac**: 本地代码文件夹，*起点*
2. **Stage/Index**: 暂存区，想象成一个中转站
3. **Repository**: git为代码文件夹创建的本地仓库区
4. **Remote**: GitHub远程仓库，*终点*

### git实现 (在这操作之前，你需要安装git客户端，如有需要自行百度安装)
了解流程后我们再来看每一步是怎么实现的的。

0. 首先要做的是，将本地代码文件夹初始化成git仓库，在本地为代码文件夹创建一个仓库区
   终端到代码文件夹下运行 `git init`
   创建成功后，文件夹会变色，绿色代表新建的文件夹，同时代码文件夹下也会出现 *.git* 文件夹
   ![](assets/initial%20local%20repository.jpg)
1. 