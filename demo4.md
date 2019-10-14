
## 混合强调样式

基本强调样式：

- **加粗**
- *倾斜*
- ~~删除~~

混合强调样式：

- ***加粗倾斜***
- **~~加粗删除**~~
- *~~倾斜删除*~~
- ***~~加粗倾斜删除***~~

## 图片链接

基本文字链接:
	[链接文字](URL)
[百度](http://www.baidu.com)

基本图片：
	![alt](URL text)
	
![](https://offlintab.firefoxchina.cn/static/img/search/baidu_web.png)

图片链接：  
[![](https://offlintab.firefoxchina.cn/static/img/search/baidu_web.png)](http://www.baidu.com)  

[![][baidu_logo]](baidu)

## 引用链接的问题

基本引用链接的用法：

good:  
[baidu]  
[百度][baidu]  
[百度网站][baidu]

lou(自引用):  
[百度]  
[百度网站]

<!-- 以下是本文中的链接 -->

[baidu]: http://www.baidu.com
[baidu_logo]: https://offlintab.firefoxchina.cn/static/img/search/baidu_web.png
[百度]: http://www.baidu.com
[百度网站]: http://www.baidu.com

## 多级列表

- 问题1：如何打断：空行不行，需要文字段落

1. item 1
	1. item 1.1
	2. item 1.2
2. item 2

skdfasdf 

3. item 3
4. item 4


- 问题2：打断的列表，如何续上

1. item 1
	1. item 1.1
	2. item 1.2
2. item 2

	skdf


3. item 3
4. item 4
