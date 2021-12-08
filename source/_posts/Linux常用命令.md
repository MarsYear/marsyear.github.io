---
title: Linux常用命令
date: 2021-10-20 10:59:42
tags:
    - Linux
categories:
    - 知识储备
---

## 常用命令
### ls
> 列举出当前目录下的文件内容
### ll
> 它是ls -l的一个别名（Ubuntu默认不支持命令ll，必须用 ls -l）
> - 结果说明：`drwxr-xr-x   2 root root 48 2013-11-27 16:34 test/`
> + 第一个栏表示文件属性 - 


### scp复制文件
 > 例子：- 复制打包文件
 scp -P 10000 -r dist/* ACCOUNT@IP:/.../.../.../
```
重启测测试服务器
 - 进入测试服务器 找到docker-servies然后进入,找到对应的项目文件， 使用命令lazydocker进入服务器 点击Servies，然后按X可以查看命令。
```