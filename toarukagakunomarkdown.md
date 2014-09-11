# 某(不)科学的超 Markdown 指南!

Markdown 是一种由蓝星人首发的轻量级标记语言, 唯一的特点是, 不写任何标记也可以让文档萌~萌~哒~  
然后...就没有然后了, 这个文档为了和 MK 一样简洁吾辈就没必要把[维基的内容](http://zh.wikipedia.org/wiki/Markdown)抄一次了.

你现在看到的内容, 以及[某不科学的 git 教程](http://cuter44.github.io/hello-git/hello-git-2014), 都是用 MD 写然后导出 HTML 的...当然也可以导出成 PDF , 或者导出成任何蓝星上可用的文本格式, 这个我们放到最后说.
  
然后我建议你现在下载这个教程的[源文件](./toarukagakunomarkdown.md), 以便进行对照.

## 关于标题
用 `#` `##` `###` ... + 标题 可以定义出各级标题.

# 我是上位喵 (｀･ω･)ノ
## 中位喵 >_<"
### 下位喵 (°д°|||)

## 换行和分段

传统的 Markdown 语法要求以 空格×2+回车 来手动换行,
而 Github flavored Markdown 则没有这个繁琐的设定.  
如果是前者这段只有两行, 如果是后者这段会变成三行.  

这视乎你用的 Markdown 渲染器使用哪种语法, 但这通常是可自行设定的.

文字之间插入多于一个 空行 就可以分段

## 格式
\__斜体_\_ \*\***粗体**\*\*

只使用 Markdown 标记无法插入更多的格式(主要是没有必要), <font color=#030C6F>但</font><font color=#061878>你</font><font color=#092481>可</font><font color=#0C308A>以</font><font color=#0F3C93>使</font><font color=#12489C>用</font><font color=#1554A5>H</font><font color=#1860AE>T</font><font color=#1B6CB7>M</font><font color=#1E78C0>L</font><font color=#2184C9>标</font><font color=#2490D2>记</font><font color=#279CDB>来</font><font color=#2AA8E4>达</font><font color=#2DB4ED>成</font><font color=#30C0F6>.</font> 因为在MD中使用的任何HTML标记都会被原样地翻译, 只要目标文本格式支持等价的功能.

\~\~~~删除线~~\~\~
只有 GFM 支持

## 插入!

### 图片
!\[\]\(_url_\)  

![](http://img3.douban.com/view/photo/thumb/public/p2183790103.jpg)

### 超链

\[_title_\]\(_url_\)

[点击查看大图](http://www.douban.com/photos/photo/2183790103/)

### 代码

行前空四格.

	while (true)
		(▽·ω·▽)

GFM 支持段前后 重音符×3 + 语言名 进行代码高亮

### 引用

行前右尖括号加空格 `> `

> wow  
> so cute  
> nice dog  

### 行内引用

重音符

`wow` `much pretty`  
   `such dog`  `omg`

### 水平线

\-×4 或 =×4 即可 

----

### 有/无序列表

有序列表只要用 `数字.` 开头就行了, 数字不必是严格升序的, 因为编译之后会变成正确的顺序.  
无序列表只要用 `*` `-` `+` 开头就行了.

* 这个
- 是
+ 有序
* 列表

<!-- 隔开 -->

21. 这个
47. 是
48. 无序
36. 列表
47. (没错这是要害死强迫症)

### 表格

仅 GFM 支持, 否则会变成一团糟. 比如 MarkdownPad 2 的免费版就这么不良心.

|表|格|是|啥|可|以|吃|吗|  
|--|--|--|--|--|--|--|--|  
|(累觉不爱...)||||||||  


### 颜文字  

ฅ(・ω・ )ฅ  
(直接输入就可以了...)

### 其他乱七八糟的东西
<embed height="452" width="544" quality="high" allowfullscreen="true" type="application/x-shockwave-flash" src="http://share.acg.tv/flash.swf" flashvars="aid=959137&page=1" pluginspage="http://www.adobe.com/shockwave/download/download.cgi?P1_Prod_Version=ShockwaveFlash"></embed>  
  
(依赖HTML)

## WebApp 解决方案

FTS. 推荐使用 [StackEdit](https://stackedit.io/)

## Windows 解决方案

5+0 推荐使用 [MarkdownPad 2](http://www.markdownpad.com/)  
5+0 和 FTS. 都推荐使用 [Pandoc](http://johnmacfarlane.net/pandoc/)

## Linux 解决方案

(FTS. 后补)

## 编程解决方案

(此处征稿)