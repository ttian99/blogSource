layout: "'hello"
title: "hexo学习笔记"
date: 2016-03-10 10:00:33
tags:
---
## hexo学习笔记
### References
* [hexo官网](http://hexo.io)
* [Hexo 3.0 静态博客使用指南](http://www.tuicool.com/articles/Jva2iaA)
* [HEXO+Github,搭建属于自己的博客](http://www.jianshu.com/p/465830080ea9)
* [搭建hexo部署到github图文教程 亲测可用超详细](http://www.==paopaoche==.net/jiaocheng/85988.html)
* [史上最详细“截图”搭建Hexo博客并部署到Github](http://jingyan.baidu.com/article/d8072ac47aca0fec95cefd2d.html)
* [Cmd Markdown 编辑阅读器](https://www.zybuluo.com/mdeditor)
* [在coding上搭建hexo博客](https://segmentfault.com/a/1190000002900848?utm_source=tuicool)


### 快速开始
```
npm install hexo-cli -g 
hexo init blog(文件夹名)
cd blog(文件夹名)
npm install
hexo server
```

### 常用命令
```
hexo help       //查看帮助
hexo version    //查看Hexo的版本
hexo generate   //生成静态页面至public目录
hexo server     //开启预览访问端口(默认端口4000，Ctrl+C关闭服务器)
hexo deploy     //将.deploy目录部署到GitHub

hexo new ""     //新建文章
hexo new page "pageName" //新建页面
 

// 简化模式----hexo现在支持更加简单的命令格式了，比如：
hexo g == hexo generate
hexo d == hexo deploy
hexo s == hexo server
hexo n == hexo new

```

### 部署步骤
``` 
hexo clean
hexo generate
hexo deploy
```
### 浏览查看
- 浏览器访问：http://[你的github账号名].github.io
- 我的地址: http://ttian99.github.io/

### 主题推荐 (下表用于记录自己使用过的主题)
在知乎上，[家顺张](http://www.zhihu.com/people/jia-shun-zhang)大神扒出来一个排行榜，[有哪些好看的 Hexo 主题？]()，可供选择的有很多,相信总有一款你的菜。
主题名字|描述|Demo
---|---|---
[Yilia](https://github.com/litten/hexo-theme-yilia)|Responsive and simple style|
[NexT](https://github.com/iissnan/hexo-theme-next)|精于心，简于形|
[Random](https://github.com/stiekel/hexo-theme-random)|这款主题很可能适合你。|[Demo on Openshift](http://chensd.com/)