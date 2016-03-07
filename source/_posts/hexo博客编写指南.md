---
title: Hexo博客编写指南 
---

### 创建新文章 

``` bash
$ hexo new "My New Post"
```

### 运行本地服务器，预览效果 

``` bash
$ hexo server
```

### 生成静态页面 

``` bash
$ hexo generate
```

### 部署到github上，你可以使用deploy，也可以使用 d 

``` bash
$ hexo deploy
```

### 提交hexo源码，同步到github上 

``` bash
$ git add .
```

``` bash
$ git commit -m "更新信息"
$ git push
```

或者 使用强制提交

``` bash
$ git commit -m "更新信息"
$ git push -f origin master
```

