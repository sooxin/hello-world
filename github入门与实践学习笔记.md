github入门与实践学习笔记
======

## 1. git&GitHub简介

## 2. git导入

- 诞生背景

- 什么是版本管理
  - 集中式版本管理
  - 分布式版本管理

- git的安装
  - Linux&Mac
  - Windows

- 初始设置
  - 打开gitbash,分别键入以下两行：
```
$ git config --global user.name "firstname lastname"
$ git config --global user.email "your_email"
```

  - 顺便键入以下一行，使得gitbash界面命令色彩更易用：
```
$ git config --global color.ui auto
```

> 经过上述命令的执行，会生成一个.config的文件，里面会有以上设置信息，可通过记事本等软件直接修改
> 另外，你所填写的名字与邮箱信息都会被在之后git库公开时公开，所以不要填隐私
