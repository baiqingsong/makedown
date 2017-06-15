## 目录
* [标题](#标题)
* [分割线](#分割线)
* [文本](#文本)
    * [普通文本](#普通文本)
    * [单行文本](#单行文本)
    * [文本块](#文本块)
    * [文字高亮](#文字高亮)
    * [换行](#换行)
    * [特殊字体](#特殊字体)
* [图片](#图片)
* [链接](#链接)
* [图片链接](#图片链接)
* [锚点](#锚点)
* [列表](#列表)
    * [无序列表](#无序列表)
    * [多级无序列表](#多级无序列表)
    * [有序列表](#有序列表)
    * [有序列表自动排序](#有序列表自动排序)
    * [多级有序列表](#多级有序列表)
* [引用](#引用)
    * [常用引用文本](#常用引用文本)
    * [多级引用文本](#多级引用文本)
* [表格](#表格)
* [表情](#表情)

   




   
#### 标题
    标题分六级
    分别是一级标题（#），二级标题（##），三级标题（###），四级标题（####），
    五级标题（#####），六级标题（######）
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题


#### 分割线
    你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。
    你也可以在星号或是减号中间插入空格
    例如：*** --- ___
    

#### 文本
###### 普通文本
这是一段普通文本，不需要加任何标识
###### 单行文本
    在一行开头加Tab或者四个空格或者利用p标签嵌套code标签
###### 文本块
    在连续几行的
    文本开头加入
    1个Tab或者4个空格
###### 文字高亮

    文字高亮功能能使行内部分文字高亮，使用一对反引号（`）
    
例如：`你好`，`谢谢`
###### 换行
直接回车不能换行，  
可以在上一行文本后面补两个空格，这样下一行的文本就换行了。

或者就是在两行文本直接加一个空行。

也能实现换行效果，不过这个行间距有点大。
###### 特殊字体

    斜体在两侧加一个符号(*)或者符号(_)  
    
这个是 *斜体* 或者 _斜体_  

    粗体在两侧加两个符号(**)或者符号(__)
    
这个是 **粗体** 或者 __粗体__  

    删除线在两侧加两个符号~
    
这个是 ~~删除线~~ 

    斜体，粗体和删除线可以同时出现
例如 ***斜粗体*** ~~*斜删除线*~~ ~~**粗删除线**~~ ~~***斜粗删除线***~~


#### 图片
基本格式:

    ![alt](URL title)
alt和title即对应HTML中的alt和title属性（都可省略）：  

    alt表示图片显示失败时的替换文本  
    title表示鼠标悬停在图片时的显示文本（注意这里要加引号） 
URL即图片的url地址，如果引用本仓库中的图片，直接使用相对路径就可了，
如果引用其他github仓库中的图片要注意格式，即： '仓库地址/raw/分支名/图片路径'

例如：

    ![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
    
![baidu](http://www.baidu.com/img/bdlogo.gif "悬浮显示：百度logo")


#### 链接
    [alt](URL title)
    例如：
    [百度](http://www.baidu.com "悬浮显示：百度地址")
    alt：显示文字
    url：跳转网址
    title：悬浮文字
    
[百度](http://www.baidu.com "悬浮显示：百度地址")

#### 图片链接

    [![baidu](http://www.baidu.com/img/bdlogo.gif "悬浮显示：点击进入百度页面")](http://www.baidu.com)
    [![baidu](http://www.baidu.com/img/bdlogo.gif)](http://www.baidu.com  "悬浮显示：点击进入百度页面")

[![baidu](http://www.baidu.com/img/bdlogo.gif "悬浮显示：点击进入百度页面")](http://www.baidu.com)

[![baidu](http://www.baidu.com/img/bdlogo.gif)](http://www.baidu.com  "悬浮显示：点击进入百度页面")

#### 锚点

    每一个标题都是一个锚点，和HTML的锚点（#）类似
    不过要注意，标题中的英文字母都被转化为小写字母了
    例如：[回到顶部](#目录)

[回到顶部](#目录)

#### 列表

###### 无序列表  
    在每段文字前加符号（*）
    * 昵称
    * 别名
    * 英文名
* 昵称
* 别名
* 英文名

###### 多级无序列表
    在下一个级别前加个Tab
    * 学校
        * 年级
            * 班级
* 学校
    * 年级
        * 班级
        
###### 有序列表
    一般就是在数字后面加一个点，再加一个空格
    1. 封装
    2. 继承
    3. 多态
1. 封装
2. 继承
3. 多态  

###### 有序列表自动排序
    在第一行指定`1.`而接下来的几行用星号`*`（或者继续用数字1. ）就可以了，它会自动显示成2、3、4……
    1. 封装
    1. 继承
    1. 多态
1. 封装
1. 继承
1. 多态
###### 多级有序列表
    和无序列表一样，有序列表也有多级结构
    1. 学校
        1. 年级
            1. 一班
            2. 二班
1. 学校
    1. 年级
        1. 一班
        2. 二班


#### 引用
###### 常用引用文本
    可以用一个符号>在引用段落前
    > 引用第一段  
    引用第二段  
    引用第三段  
> 引用第一段    
引用第二段  
引用第三段  

###### 多级引用文本
    可以用多个符号>在每段引用文本前
    > 学校  
    >> 一年级  
    >>> 一班  
    >>>> 张三  
    >>>> 李四
> 学校  
>> 一年级  
>>> 一班  
>>>> 张三  
>>>> 李四


#### 表格
    利用符号（|）（-）（:）
    | 班级 |  姓名  | 学号  |
    | ---- | :----: | ----: |
    | 一班 |  张三  | 01    |
    | 二班 |  李四  | 02    |
| 班级 |  姓名  | 学号  |
| ---- | :----: | ----: |
| 一班 |  张三  | 01    |
| 二班 |  李四  | 02    |

#### 表情
    Github的Markdown语法支持添加emoji表情，输入不同的符号码（两个冒号包围的字符）可以显示出不同的表情。
    比如:blush:，可以显示😊。
    具体每一个表情的符号码，可以查询GitHub的官方网页http://www.emoji-cheat-sheet.com。
