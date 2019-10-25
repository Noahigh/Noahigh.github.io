# 使用 django 来新建一个Python的Web项目

## 概述

Python的应用方向诸如数据可视化、机器学习、服务器脚本等非常广泛，其中Web方向也是一个很大的分支，催生出了像django、flask等众多优秀的Web框架，

## 开发环境

**操作系统：** Windows 10 1903 （具体上线还是建议使用Linux系统的发行版本，例如：CentOS、Debian等）

**编辑器：** Visual Studio Code （这个版本没法写，更新太快了，使用最新的就好）

**Python：** 3.7.4

**包（依赖）管理器：** pip （同样是版本更新太快，使用最新即可）

**django：** 2.22

**环境控制：** virtualenv

**代码检查：** pylint 2.4.2

*PS：再次重申，如果是学习怎么使用的话，版本不重要，尽量使用最新的就可以，但是如果是要做多人协同或者对已有项目进行功能更新等，按照约定版本进行操作*

## 具体实操

首先请使用浏览器到[Python官网](https://www.python.org/)的站点上下载最新版本的Python（现在到3.8了 [/doge]手动狗头），然后进行安装。


```shell
pip install virtualenv

python -m venv blog_env
```
