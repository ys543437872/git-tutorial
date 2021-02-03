# Markdown 链接

链接使用方法如下：  
```
[链接名称](链接地址)

或者

<链接地址>
```

<br/>
例如：
```
这是一个链接 [百度](https://www.百度.com)
```

显示效果如下：  
这是一个链接 [百度](https://www.baidu.com)

直接使用链接地址：  
```
https://www.baidu.com
```

显示效果如下：  
https://www.baidu.com


---
## 高级链接

我们可以通过变量来设置一个链接，变量赋值在文档末尾进行：  
```
这个链接用 1 作为网址变量 [Google][1]  
这个链接用 baidu 作为网址变量 [Baidu][baidu]  
然后在文档的结尾为变量赋值（网址）  

[1]: http://www.google.com/
[baidu]: http://www.runoob.com/
```

显示结果如下：  
这个链接用 1 作为网址变量 [Google][1]  
这个链接用 baidu 作为网址变量 [Baidu][baidu]  
然后在文档的结尾为变量赋值（网址）  

[1]: http://www.google.com/
[baidu]: http://www.runoob.com/