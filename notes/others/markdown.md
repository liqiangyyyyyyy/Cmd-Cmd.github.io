Markdown 标记语法
========
# 标题

## 全文标题
使用连续8个`=`号隔开

```
全文标题
========
正文
```

## 小标题
标题用`#`插入行首表示，`#`越多表示标题的级数越高(1-6级)

```
# 一级标题
## 二级标题
...
###### 六级标题
```

# 引用
在行首用`>`表示，`>`越多表示越内层的引用

```
> 引用
>> 引用内的引用
>>> 引用内的引用内的引用
> 退出引用需要多一个空行  
```

# 文本样式
* 需要**加粗**的文字分别用两个星号包围左右  

```
**加粗文字**
```

* 需要*斜体*的文字分别用一个星号包围左右

```
*斜体文字*
```  

* 需要~~删除线~~的文字分别用两个波浪号包围左右

```
~~删除文字~~
```

* 超链接

```
[链接文本](链接url)
```

* 插入图片

```
![图片替代文字](图片链接)
```

* 用八个横杠`-`表示分割线  
* 换行时需要在行末追加两个空格  
* 退出列表、退出引用等一般需要多加一个空行    

# 列表
* 无序列表

```
* 列表1
* 列表2
* 列表3
```

* 有序列表

```
1. 列表1
2. 列表2
3. 列表3
```

# 内嵌代码
内嵌代码段落用回勾号包住

```
`一行内的代码`
一段代码在上下两行加三个回勾号
```
# 表格
不是所有markdown解析器都支持表格  

| 表头第一列 | 表头第二列 |
| :-------- | :-------- |
|    1.1    |    2.1    |
|    2.1    |    2.2    |

以上表格在markdown中为  

```
| 表头第一列 | 表头第二列 |
| :-------- | :-------- |
|    1.1    |    2.1    |
|    2.1    |    2.2    |
```

# 个人感悟
想要md语法兼容各种解析器，就要多打空格，多打换行...


--------

# 资料整理
> [百度百科 - markdown](http://baike.baidu.com/subview/2311114/2311114.htm)  
> [markdown 11种基本语法](http://www.cnblogs.com/hnrainll/p/3514637.html)
