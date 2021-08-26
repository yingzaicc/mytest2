# Markdown语法

## 1.标题  
示例：
~~~
# 一级标题
## 二级标题
### 三级标题
依次类推，最多支持6级标题
~~~
效果：

# 一级标题

## 二级标题

### 三级标题

***
## 2.字体  
~~\~~删除线~~\~~  
*\*斜体字\**       _\_斜体字\__  
**\**粗体**\**    __\__粗体__\__  
***\***粗斜体***\***      ___\___粗斜体___\___   	 

***
## 3.分割线  
3个或3个以上的 `-` 或 `*` ，效果是相同的  
示例：

~~~
---  
***  
~~~

## 4.引用文本
示例：  
~~~
> 引用文本1
> > 引用文本2
> > > 引用文本3
~~~
效果：  
> 引用文本
> > 引用文本2
> >
> > > 引用文本3  

> 引用：如果想换行，需要在末尾键入两个以上空格，然后回车  

## 5.锚点和链接
示例：
~~~
[普通链接](https://www.baidu.com/)  
[带标题的链接](https://www.baidu.com/ "百度一下")  
直接链接：<https://www.baidu.com/>  

[锚点链接][地址]
[地址]：https://www.baidu.com/  

邮箱地址：wanghaiyingtt@163.com  
~~~
效果：  
[普通链接](https://www.baidu.com/)  
[带标题的链接](https://www.baidu.com/ "百度一下")  
直接链接：<https://www.baidu.com/>  

[锚点链接][地址1]  
[地址]：https://www.baidu.com/  

邮箱地址：wanghaiyingtt@163.com  

## 6.语法高亮
### 行内代码
使用符号：`  
> 执行命令：`install package`  

### 代码块
~~~javascript
function test(){
	console.log("hello world!")
}
~~~

## 7.插入图片
示例：
~~~
仅插入图片：  
![图片标题](http://pic1.win4000.com/wallpaper/2020-03-09/5e65b92a5656d.jpg)  

插入图片加链接：
![图片标题](http://pic1.win4000.com/wallpaper/2020-03-09/5e65b92a5656d.jpg) 
~~~
效果：  
![图片标题](http://pic1.win4000.com/wallpaper/2020-03-09/5e65b92a5656d.jpg)  

[![](http://pic1.win4000.com/wallpaper/2020-03-09/5e65b92a5656d.jpg)](http://pic1.win4000.com/wallpaper/2020-03-09/5e65b92a5656d.jpg "美女写真")  

![图片标题](E:\库\图片\手机图片\111.gif"动图")  

## 8.列表
### 1.无序列表
使用 `-` 或 `*` 或 `+`  
示例：
~~~
* 列表一  
	- 1.1
	- 1.2
* 列表二 
~~~
效果：  
***
* 列表一  
	- 1.1
	- 1.2
* 列表二  

### 2.有序列表
数字后面加个英文 `.` + `space`  
示例：  
~~~
1. 第一行
2. 第二行
3. 第三行
~~~
效果：  
***
1. 第一行
2. 第二行
3. 第三行

### 3.GFM任务列表
- [x] task list 1
- [ ] task list 2
	+ [ ] task list 2-1
	+ [ ] task list 2-2

## 9.绘制表格
| id     | name     | amt      |
| :----: | :------: | -------: |
| 1      | tom      | $100     |
| 2      | jim      | $300     |
| 3      | make     | $2000    |

## 10.分页符

[========]

下面有一行代码，被隐藏了

<div STYLE="page-break-after: always;"></div>



## 插入表情包

[表情包]:(https://www.webfx.com/tools/emoji-cheat-sheet/)

:smile:

:kissing:

:grinning:

:smiley:

:no_mouth:

:kiss:

:exclamation:

:heavy_check_mark:

:cherries:

:lock:

:mag:



## 上标、下标

```xml
H<sub>2</sub>O  CO<sub>2</sub>
1024<sup>2</sup>
```

效果

H<sub>2</sub>O

1024<sup>2</sup>



