# Markmap

## 前言
Markdown 的好处是专注码字的同时还能兼顾排版，不用像 word 那样文本加个粗都需要移动下鼠标，体验非常好。  

Markdown 的缺点就是可视化能力很弱，这就降低了信息的传播效率，毕竟人对于图像化内容的接收程度要强于文本。  

可视化表达方面，思维导图就很不错。它作为一种图象化工具，通过层级式发散式地组织主题，帮助我们更好的记忆、学习和思考。  

Markmap 就是一款基于 Markdown 语法的思维导图生成工具。

Markmap 的官网： <https://markmap.js.org/>

## Markmap 的使用方法

### Markmap 的语法  

使用 Markmap 绘制思维导图，只需三个符号。
> - #：标题
> - -：列表
> - —：分隔符

Markmap 的 Markdown 语法如下：  
```
# My map

## Search sites

- [Google](https://www.google.com/)
- [Baidu](https://www.baidu.com/)
- [Bing](https://www.bing.com/)

## WeChat public number

### The preparatory work

- The theme
- conceived
- writing

### Late work

- Public number text reading
- The reader forward
- ......

---

- learning
- The input
- The output
```

效果如下：  
![Markmap 思维导图](cache/markmap.svg)

[Markmap 思维导图](cache/markmap.html)

### Markdown 生成思维导图
- 在线版
    > 访问 <https://markmap.js.org/repl> 在线生成
    > 
    > 推荐使用Edge或者Firefox打开，其他浏览器会无法生成
- 离线版
    > VS code 插件： `markmap `
    > 
    > 目前好像只支持mac