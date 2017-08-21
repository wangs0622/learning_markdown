# <font color=red><center>学习 Markdown</center></font> 

## <font color = purple>什么是 Markdown？</font>

自己百度 谷歌去。

## <font color = purple> Markdown 有什么用？</font>

自己百度 谷歌。 我一般用 Markdown 是用来写博客和 GitHub 的 readme 文档。 我的博客[http://www.wangs0622.com](http://www.wangs0622.com)

## <font color = purple> 我用的 Markdown 编辑器</font>

`Markdownpad 2`  至于为什么是这个，我也数不清，感觉都行，没有最好的，只有顺手的。

## <font color=purple> 标题 </font>

标题分为 1 级标题、2 级标题 等等。有两种表示的方法。

### 标题的第一种表示方法 - '#'

`#` 的个数代表几级标题，一级标题就是一个 `#`，二级标题则是两个 `#`。貌似最多是六个 `#`。

**例如：**

`# 一级标题` 

`## 二级标题`

`### 三级标题`

> # 一级标题
> ## 二级标题
> ### 三级标题
> #### 四级标题
> ##### 五级标题
> ###### 六级标题

**注意：**  `#` 与标题之间有空格。

### 标题的另一种表示方法

在文字下标注 `===` 和 `---` 分别表示一级、二级标题。

貌似一般常用的还是 `#`。


## <font color=purple> 粗体 斜体 删除线 </font>

### 粗体

在 `** 粗体文字 **` 或者 `__ 粗体文字 __` 中写入欲加粗的文字。（注意第二种情况时两个下划线）

**例如：**

**我是粗体** 

__我也是粗体__

### 斜体

在 `*斜体*` 中加入欲写为斜体的文字。

**例如：**

*我是斜体*


### 删除线

在 `~~ 删除文字 ~~` 中添加要删除的文字。

**例如：**(有的编辑器不支持)

`我是要 ~~删除的文字~~` 

我是要 ~~删除的文字~~

## <font color=purple> 引用 </font>

使用 ` > ` 表示要引用的文本。

**例如：**

`> 我是要引用的文本1`

`>> 我是要引用的文本2`

`>>> 我是要引用的文本3`

> 我是要引用的文本1
>> 我是要引用的文本2
>>> 我是要引用的文本3

## <font color=purple> 代码块 </font>

有的 Markdown 编辑器在写代码的时候，只要将代码就行缩进就行。

	这是我的代码段
	for i in range(100):
		print i

GitHub 还支持在 ``` 代码 ``` 之间添加代码

```
这是我的代码段
for i in range(100):
	print i
```

## <font color=purple> 超链接</font>

**例如：**

[http://www.wangs0622.com](http://www.wangs0622.com)

[我的博客](http://www.wangs0622.com)

以上两个超链接的指向的地址是一样的，超链接的形式如下：

	[http://www.wangs0622.com](http://www.wangs0622.com)

	[我的博客](http://www.wangs0622.com)

[] 写的是描述 （）写的是地址。

有的编辑器是带有快捷键的，例如我使用的编辑器的快捷键就是 `ctrl+l`

## <font color=purple> 有序列表与无序列表 </font>

**无序列表举例：**

- 第一点
	1. 第一点
	2. 第二点
- 第二点
	* 第一点
	* 第二点
		* 第2.3点
- 第三点

其写的形式是：

	- 第一点
		1. 第一点
		2. 第二点
	- 第二点
		* 第一点
		* 第二点
			* 第2.3点
	- 第三点

**有序列表举例：**

1. 第一点
	* 第一点
	* 第二点
		* 第四点
2. 第二点
	1. 第一单
3. 第三点

其写的形式为：

	1. 第一点
		* 第一点
		* 第二点
			* 第四点
	2. 第二点
		1. 第一单
	3. 第三点

总结就是： 两个可以相互嵌套使用。

**GitHub 还支持一种复选框的列表**

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

书写形式：
	
	- [x] Finish my changes
	- [ ] Push my commits to GitHub
	- [ ] Open a pull request

## <font color=purple> 添加图片 </font>

![图片说明](http://img.ivsky.com/img/tupian/pre/201707/20/chengshu_de_maisui-011.jpg)

书写形式如下：

	![图片说明](http://img.ivsky.com/img/tupian/pre/201707/20/chengshu_de_maisui-011.jpg)

