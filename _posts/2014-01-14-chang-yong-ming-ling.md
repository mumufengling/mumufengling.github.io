---
layout: post

title: 常用命令及Markdown新手入门

categories: 常用

tags: 博客 Markdown 入门

---

# 建立一篇新的博客，自动添加生成时间
    rake post title=yourTitle
    注意：文章名不能用中文，想在网站上面让文章名显示中文的话，可以在生成的文档里面对title进行修改。


# Markdown常用语法
以下摘自：[Markdown语法说明（简体中文）](http://wowubuntu.com/markdown/)
## 标题
    # 一级标题
    ## 二级标题
    ### 三级标题
    #### 四级标题
    ##### 五级标题
    ###### 六级标题
## 列表
只需要在文字前面加上`-`就可以了

如果你希望有序列表，也可以在文字前面加上 `1. 2. 3.` 

注：`-、1.`和文本之间要保留一个字符的空格。
## 链接和图片
    链接：只需要使用 [显示文本](链接地址) 这样的语法即可
    图片：![](图片链接地址)
## 引用
只需要在你希望引用的文字前面加上`> `就好了
## 粗体和斜体
用两个 * 包含一段文本就是**粗体**的语法，用一个 * 包含一段文本就是*斜体*的语法。
## 代码区块
    只要简单地缩进 4 个空格或是 1 个制表符就可以。

## 代码高亮
{% highlight  C++ %}
#include <iostream>
using namespace std;
void main()
{
  cout << "Hello World!" << endl;
  cout << "Welcome to C++ Programming" << endl;
  }
{% endhighlight %}
