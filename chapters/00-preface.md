---
title: 序
nav_order: 1
---

# 序

本书试图通过 [Just the Docs] 主题进行拆解如何利用 [Jekyll] 进行一本书的编写细节。

## 准备工作

要使用 [Jekyll] 和 [Just the Docs] 进行创作当然要先安装相关软件了。

### 1 安装 Ruby

[Ruby] 是 [Jekyll] 运行的舞台，所以首先需要安装 [Ruby]，用户可以根据自己的计算机终端操作系统类型来安装对应的版本，具体可以参考[安装指南](https://www.ruby-lang.org/zh_cn/documentation/installation/)。

### 2 安装 Jekyll 软件和 Just the Docs 主题

[Jekyll] 是基于 [Ruby] 开发的用于将文献内容和模板转换为静态网页的软件，是我们创作的基础程序。[Just the Docs] 是基于 [Jekyll] 开发的一套主题，也就是对相关内容通过 CSS 来定制和美化。所以，我们可以通过直接复刻（Fork）模板就可以完成 [Jekyll] 和 [Just the Docs] 的安装。

## 熟悉命令

由于 [Jekyll] 的使用是通过一系列的终端命令来使用的，所以我们需要学习几个命令的使用。

### Bundler 命令

[Bundler] 是一个用于管理 [Ruby] 应用的软件依赖的软件。绝大部分 [Ruby] 应用通过 [Bundler] 来解决时用软件的依赖问题，同时通过 [Bundler] 来运行软件。[Bundler] 软件运行的命令是 `bundle`：

* `bundle install` 用于系统依赖的软件检查和安装，可以直接简化 `bundle`
* `bundle exec` 用于使用系统自带软件的版本运行，不需要刻意安装最新版本

### Jekyll 命令

[Jekyll] 软件系统执行命令使用 `jekyll`，常用命令有：

* `jekyll new PATH` 生成新的 [Jekyll] 站点到 `PATH` 目录，不过这里一般用不到；
* `jekyll server` 运行系统服务器软件，使网站系统运行，同时将各种文件组合并输出静态网页；
* `jekyll build` 执行将网站内容转换为静态网页到 `./ _site` 目录；
* `jekyll clean` 清除所有生成文件；

实际上，我们最常用的就是结合 [Bundler] 和 [Jekyll] 命令的一个命令：

~~~ bash
bundle exec jekyll server
~~~

只需要这个命令运行系统生成网站即可。

[Just the Docs]: https://justthedocs.com/ "Just the Docs 官方网站"
[Jekyll]: https://jekyllrb.com "Jekyll 官方网站"
[Ruby]: https://ruby-lang.org "Ruby 官方网站"
[Bundler]: https://bundler.io "Bundler 官方站点"
