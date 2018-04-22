---
layout: post
title: vscode 设置 node 运行环境
subtitle: node + js
date: 2016-02-11
author: jacob
header-img: img/post-bg-ios9-web.jpg
catalog: true
tags: 
    - js
    - vscode
---
# 小记
>因为经常使用vscode,所以方便开发，配置好运行环境很重要，下面简单记录一下node 的环境配置。
# 安装
![](https://ws1.sinaimg.cn/large/006tKfTcgy1fqk1n6unktj30g60d8dfs.jpg)

# 设置
项目文件夹下面有.vscode 文件夹，里面的`launch.js`就是配置文件;具体设置如下：
![](https://ws2.sinaimg.cn/large/006tKfTcly1fql3wwq9a0j30ou0qgn0z.jpg)
````
    "version": "0.2.0",
    "configurations": [
        
        {
            "type": "node",
            "request": "launch",
            "name": "demojs",
            "program": "${workspaceRoot}/demo.js"
        }
    ]
````





