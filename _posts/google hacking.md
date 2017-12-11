# Google Hacking

### 常用操作符

```
intitle allintitle 页面标题里查找关键字
filetype 查找指定文件类型 等同于 ext
site 锁定站点，比如 Freebuf 的搜索就是这样
inurl allinurl 在url中查找关键字
intext allintext 网页内容查找关键字
link 搜索链接到某个网站的链接
```



### 搜索文件

```
filetype:
xls doc txt

收集服务器信息：
intitle:index.of filetype:log
```

### 搜索错误信息

此外还可以在指定站点搜索一些常见的错误信息，比如 intitle:error intitle:warning给大家列一些常用的关键字：

```
intitle:index.of
error|warning
login|logon
username|userid|ID
password|passcode
admin|administrator
-ext:html|-ext:htm|-ext:asp|-exp:php 过滤掉常见的
inurl:temp|inurl:tmp|inurl:backup|inurl:bak 这个不一定用url来
```



### 注意

1、基本使用方法就是 操作符:关键字，要注意这三者之间是不能有空格的，如果关键字里有空格就得用引号包起来。

2、带all的操作符貌似不能跟其他的关键字一起用

3、遇到搜不出来结果的，注意看Google的提示或者调整下关键词顺序