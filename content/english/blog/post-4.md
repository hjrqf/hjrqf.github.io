---
title: "git总结"
meta_title: ""
description: "this is meta description"
date: 2022-04-04T05:00:00Z
image: "/images/blog/git-nav.jpg"
categories: ["技术"]
author: "任晓龙"
tags: ["git"]
draft: false
---



#     辗转反侧，不甚理解，遂总结如下，方便记忆：

![git总结](/images/blog/git总结.png)



# 1、git顺序上传步骤：

1、git init: 在当前目录初始化一个新的 Git 仓库。

2、git add <file>: 将文件添加到暂存区。

3、git commit -m "Commit message": 将暂存区的文件提交到本地仓库。

4、git remote add <仓库名> <远程仓库地址>: 添加一个新的远程仓库。

5、git push -u <仓库名> <分支名>: 将本地提交推送到远程仓库。



# 2、git常用查看命令：

1、git status     查看暂存区与缓存区的状态。

2、git remote -v   显示远程仓库地址的详细信息。

3、git branch <分支名>     列出本地分支。

4、git branch -m <分支名>     重命名当前分支。

5、git checkout <分支名>     切换到指定分支。

6、git checkout -b <分支名>     创建并切换到指定分支。



# 3、注意事项

1、命令不要敲错和漏敲了，一个字母敲错就error，很难发现的！

2、报错看error，根据error找问题（百度和gpt很香的）。

3、git push会经常碰到网络问题，不要急等一会就好了！

4、参考文档是个好东西，要看细致了，漏看东西很致命！



**一分耕耘，一分收获，       加油！**     



​																																		小记：2024年8月1日







