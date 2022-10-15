---
layout: 2
title: python切换环境
date: 2022-9-4 13:59:33
tags:
---
### Python环境切换
在上CS61A网课时，需要用Python3.6进行操作，Archlinux自带的Python版本是最新的3.11无法进行Lab实验操作，在网上寻找之后，找到了最为简单且效果最好的。`pyenv`
首先下载`pyenv`
```
 git clone https://github.com/pyenv/pyenv.git ~/.pyenv
```
安装需要版本的Python
```
pyenv install 3.10.4
```
运用`pyenv`对python版本就行修改
```
pyenv shell <version> -- 仅仅为当前shell修改
pyenv local <version> -- 将为此文件夹修改
pyenv global <version> -- 修改全局变量
```