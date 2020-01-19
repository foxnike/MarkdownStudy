# Markdown语法笔记
## 语法
    斜体 *content* 或 _content_ 
    粗体 **content** 
    加粗斜体 ***content***
    删除线 ~~content~~
    下划线  <u>content<u>（html用法）
    超链接：
        [链接显示文字](链接地址 “title”)

        [链接显示文字][链接编号],[链接显示文字][链接编号];
        [1]:blog.csdn.net
        [2]:github.com
    
    引用 引用文字前加> 可嵌套使用
    分割线 用三个--- 或者 *** （易与加粗斜体混）表示，实际使用有误差；
    列表使用：（* + - 三项都可）
     *第一项
     *第二项
     *第三项
    有序列表使用数字加.
    1. 2. 3.
    列表的嵌套
        在子列表选项内加四个空格
    代码展示
        用```包住
    图片展示
        开头感叹号![文件的替代文字 图片类型](图片地址 "可选标题title")
    表格展示
        | 表头 | 表 头 |
        | ---- | ---- |
        | xxxx |xx x  |
        对齐方式
            :----
            :---:
            ----:
高级技巧展示： 转义 公式 等   
    [博客地址](https://www.runoob.com/markdown/md-advance.html)

---
## 预览
*content*

 **content**

***content***  

~~content~~  

<u>content<u>
***
[C++学习笔记](https:github/foxnike "施工中")

[1]:https:github.com "施工中"
[我的主页][1]  
***
引用：
>the first quote
>> the second quote  
>>> the third quote  
>> Supplementary data  
***
分割线 
***
列表展示  
+ first  
+ second
+ third  
1. first
2. sencond
3. third  
***
1. 第一项
    + 第一项
    + 第二项
    + 第三项
***
'printf();'
```c
printf("Text");
```
---
![](http://static.runoob.com/images/runoob-logo.png "RUNOOB")
![](picture.jpg "lion")  

---

| 表头 | 表头 | 表头 |
| :---- | :---: | ---:  |
| xxxxxxx |xxx   |   x  |
---



  