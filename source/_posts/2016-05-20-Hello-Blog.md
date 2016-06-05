---
title: Hello, Blog!
category:
tags:
date: 2016-05-20 14:53:18
updated: 2016-05-20 14:53:18
thumbnail: https://
lede: 要有博客,就有了博客
---
------
<!--more-->
## 要有博客,就有了博客!

软件是快速进化的领域.设计开发需要与时俱进
- 洞悉行业发展趋势
- 选择工具并不断改进
- 掌握前沿和实用技术

把伟大而终生的学习理想融入到生活中,于是要有博客,就有了博客!

博客的内容包括,但不限于
- 英文优秀文章的译文
- 面向技术的文章转载
- 原创技术理解和分析

## 搭建博客

使用[**Hexo**](https://hexo.io/zh-cn/).按照官方的介绍,Hexo是快速,简洁且高效的博客框架.最喜欢的特性
- 支持Markdown,专注写作内容
- 丰富的主题和插件,自由组合

以下是简要安装过程:

### 安装Hexo

具体安装过程,参考安装文档
- [**安装**](https://hexo.io/zh-cn/docs/)
- [**建站**](https://hexo.io/zh-cn/docs/setup.html)

注意事项

> “npm install hexo-cli -g” 命令添加参数no-optional,避免错误 _Error: Cannot find module './build/default/DTraceProviderBindings'_

```bash
$ npm install hexo-cli -g --no-optional
```

> 所有‘npm install’ 命令添加参数registry使用淘宝镜像下载安装文件,解决网速或GW问题

```bash
$ npm install --registry=https://registry.npm.taobao.org
```

### 快速开始

#### 发布新文章

``` bash
$ hexo new "My New Post"
```
更多关于[**写作**](https://hexo.io/zh-cn/docs/writing.html)

#### 启动服务器

``` bash
$ hexo server
```

更多关于[**服务器**](https://hexo.io/zh-cn/docs/server.html)

#### 生成静态文件

``` bash
$ hexo generate
```

更多关于[**生成器**](https://hexo.io/zh-cn/docs/generating.html)

#### 远程网站部署

``` bash
$ hexo deploy
```

更多关于[**部署**](https://hexo.io/zh-cn/docs/deployment.html)

注意事项
> 使用[**GitHub Pages**](https://pages.github.com “Goto GitHub Pages”)部署前,需修改站点根目录配置文件_config.yml的Deployment设置

```yml
# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
  type: git
  repository: https://github.com/yrsf/yrsf.github.io.git
  branch: master
```

> 使用以下命令解决错误 _ERROR Deployer not found: git_

```bash
$ npm install hexo-deployer-git –save
```

### 安装主题
- 主题： [**NexT**](https://theme-next.iissnan.com "Goto NexT")
- 主题配置： [**RSS**](https://theme-next.iissnan.com/theme-settings.html#rss) [**标签页面**](https://theme-next.iissnan.com/theme-settings.html#tags-page) [**分类页面**](https://theme-next.iissnan.com/theme-settings.html#categories-page)
- 备选主题： [**Corporate**](https://github.com/ptsteadman/hexo-theme-corporate "Goto Corporate")

### 安装第三方服务
- 评论系统： [**多说**](https://theme-next.iissnan.com/third-party-services.html#duoshuo)
- 内容分享： [**多说**](https://theme-next.iissnan.com/third-party-services.html#share-duoshuo)
- 站内搜索： [**Swiftype**](https://theme-next.iissnan.com/third-party-services.html#swiftype)
- 数据统计与分析： [**LeanCloud**](https://zhuweisheng.com.cn/technology/leancloud-counter/)
- 站点地图： [**sitemap**](http://www.arao.me/2015/hexo-next-theme-optimize-seo/)

## 写在最后

- 获取这个博客的所有配置及资源文件,请访问GitHub工程[**blog**](https://github.com/yrsf/Hexo)
- 如果您对这个博客的内容感兴趣,请点击[**订阅rss**](/atom.xml)
- 如果您对博文有任何疑问和建议,请参与评论
- 如果您想与我取得联系,请致信**<haozyc@sina.com>**


