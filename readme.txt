

# 首次：


## git clone 目标hexo博客

`git clone git@git.coding.net:whiteeyes/blog.git`

## 替换Push地址
用config替换.git/config

## 进入Blog文件夹安装hexo

`npm install hexo-cli -g`


## 进行模块安装

`npm install`
	    *（注意，不需要hexo init这条指令）*

## 安装插件（根据需求来，除了第一个，其余的可选择安装）

（1）为了使用hexo d来部署到git上，需要安装
`npm install hexo-deployer-git --save`

（2）为了建立RSS订阅，需要安装
`npm install hexo-generator-feed --save`

（3）为了建立本地搜索，需要安装
`npm install hexo-generator-search --save`

（3）为了建立谷歌sitemap，需要安装
`npm install hexo-generator-sitemap --save`

（3）为了建立百度sitemap，需要安装
`npm install hexo-generator-baidu-sitemap --save`


## 进行你想要的操作，比如写文章
	
## 更新博客

`hexo clean`
`hexo g -d` 

## 备份

`git add .`
`git commit -m ""`
`git push github或者coding或者all`

***
***

# 日后使用

### 如果在别的电脑上没有更新过Hexo：

直接写文章

然后更新博客：`hexo clean`   `hexo g -d` 

然后备份博客：`git add .` `git commit -m ""` `git push`

### 如果在别的电脑上更新过Hexo：

`git pull`

然后写文章

然后更新：`hexo clean`  `hexo g -d` 

然后备份博客：`git add .` `git commit -m ""` `git push`





