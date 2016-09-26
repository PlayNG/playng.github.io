---
layout: post
title:  "New Rating Interface"
date:   2016-09-14
desc: "Rating"
keywords: "rating, reviews, stars"
categories: [Info]
tags: [Info]
icon: fa-star-half-o
---

> blah blah blah blah

Some other gibberish stuffs will be found here

第一步：把resources目录下默认的icon和splash图标换成当前APP对应的图标。把resources目录下android和ios文件夹删除。

第二部：在命令行中，执行ionic resources命令，这时会自动生成当前图片对应的icon和splash不同大小的图标。

需要注意的地方：这目录名字和图像文件名字必须是这样的，不能是其他名字，否则生成不了。图像文件格式可以是.png、.psd、.ai格式；icon图像文件大小最小192×192 px，且不能为圆角；splash图像文件大小最小2208x2208px，中间区域1200x1200px。执行命令生成资源之前，一定要为项目添加android或iso platform否则会报错，执行完成之后看看android和ios的icon和splash的图标是不是都生成了。不然build的时候会报错。

还有就是记得装插件哦。

```
ionic plugin add cordova-plugin-splashscreen
```
