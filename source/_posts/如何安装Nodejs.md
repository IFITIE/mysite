---
title: 如何安装Node.js
abbrlink: 8affae78
date: 2024-02-11 17:36:08
tags:
top_img: /img/top3.jpg
cover:
---
# 环境准备
## 安装Node.js
### 安装
Node.js中文官网：https://www.nodejs.com.cn/
选择适合自己系统的LTS长期支持版

安装方式有多种，建议选择后缀为.msi的安装包

安装时无需进行设置，默认安装即可，一路Next

安装完成后点击Finish完成安装

以管理员方式打开cmd命令行窗口
在窗口中输入node -v:
``` cmd
node -v
```
在窗口中输入npm -v (npm为nodejs自带的包管理器)
``` cmd
npm -v
```

若能显示版本号则表示安装成功
### 环境配置
找到nodejs的安装路径，默认为C:\Program Files\nodejs_版本号

此时nodejs的根目录下只有一个文件夹\node_modules\和其他的一些文件

手动添加两个文件夹 node_cache 和node_global

创建完后打开命令行输入以下代码：
``` cmd
npm config set preifx "nodejs根目录\node_global"
npm config set cache "nodejs根目录\node_cache"
```

然后设置系统环境变量

右键此电脑——属性——高级系统设置——环境变量

环境变量窗口有两个小窗口，在下面的系统变量窗口点击新建：
系统变量 NODE_PATH
nodejs根目录\node_global\node_cache 示例：(C:\Program Files\nodejs_18.18.0\node_global\node_modules)

Node.js准备完成
## 什么是Nodejs
nodejs是使用C++开发的一个运行环境，本身作为一个V8引擎的容器，使得JavaScript可以运行

V8引擎是由Google为Chrome浏览器开发的引擎，专门用于执行JavaScript代码，是Chrome浏览器的一部分


Nodejs使得Javascript代码不仅仅能在浏览器（客户端）运行，也可以在服务端运行

## 什么是npm
npm（Node Package Manager）node包管理器

通过 npm，开发者可以轻松地安装、更新和卸载JavaScript包。这些包可以是其他开发者编写的模块、库、工具或框架。





