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

# 参考资料

1. [神器 Markmap！！！](https://mp.weixin.qq.com/s/IguY-DUoHY1xuGJ63jF2fg?st=48FA63A0751C4D558DEFB8446A81872F8F351B1D569F5D4EBBB67363FE0DD7A3DE21052267023271A6519FC34EA99F58F2C23DC3EE22E1312464B543836B0095FF0A7CAD9064F1A7AADBEEDF71189D0B2CD8AF3C40099F595A2E9CFEC694A09AD4E7B64D7170080F918F24DA26C3AEA3E3CEC12A10079F007B5046BCCAC846032A16AB42C5FE7A5CC94D803124E8C4458F1E1514A514D8DFD752ECBCA73C475B996B8BE489B41DC53E1F7626BDACA88780FAD309FA78CC093C6CCF73EE216460&vid=1688853271660643&cst=077C40CEC39C03B0F4402EF9800A4041E4C79280F4FB1CB381089FABA81002A1106CF975C8B054E193D9A40C932EAA0F&deviceid=2d5eb326-deb1-4810-ab9c-87ff4f8edd23&version=3.1.1.3006&platform=win)
1. [太牛逼了，Markdown 几行字符就可以生成思维导图了！](https://blog.csdn.net/jake_tian/article/details/105906542)