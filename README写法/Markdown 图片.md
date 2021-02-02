# Markdown 图片

Markdown 图片语法格式如下：  
```
![alt 属性文本](图片地址)

![alt 属性文本](图片地址 "可选标题")
```

- 开头一个感叹号 !
- 接着一个方括号，里面放上图片的替代文字
- 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。

使用实例：  
```
![Markdown 图片](cache/Markdown图片.png)

![Markdown 图片](cache/Markdown图片.png "Markdown 图片")
```
显示结果如下：  
![Markdown 图片](cache/Markdown图片.png)

![Markdown 图片](cache/Markdown图片.png "Markdown 图片")

<br/>
当然，你也可以像网址那样对图片网址使用变量:  

```
这个链接用 1 作为网址变量 [Markdown 图片][1].
然后在文档的结尾为变量赋值（地址）

[1]: cache/Markdown图片.png
```

显示结果如下：  
这个链接用 1 作为网址变量 [Markdown 图片][1].  
然后在文档的结尾为变量赋值（地址）  

[1]: cache/Markdown图片.png

<br/>
Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的&lt;img&gt;标签。  

```
<img src="cache/Markdown图片.png" width="10%">
```

显示结果如下：  
<img src="cache/Markdown图片.png" width="10%">
