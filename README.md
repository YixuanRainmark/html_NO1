# HTML 学习笔记
## DOCTYPE 声明
`<!DOCTYPE html>` 声明文档类型，告诉浏览器这是一个 HTML5 文档。
## 基本结构
```html
<!DOCTYPE html><!--这是注释。documemnt type,本行的作用是声明文件类型-->
<html>
    <head>
        <meta charset="utf-8">
        <title>这是标题</title>
    </head>
    <body>
        <!-- 内容 -->
    </body>
</html>
```
## 标题
HTML 提供了六种级别的标题，从 `<h1>` 到 `<h6>`。
```html
<h1>这是1级标题</h1>
<h2>这是2级标题</h2>
<h3>这是3级标题</h3>
<h4>这是4级标题</h4>
<h5>这是5级标题</h5>
<h6>这是6级标题</h6>
```
<h1>这是1级标题</h1>
<h2>这是2级标题</h2>
<h3>这是3级标题</h3>
<h4>这是4级标题</h4>
<h5>这是5级标题</h5>
<h6>这是6级标题</h6>

## 样式和事件
HTML 元素可以通过 `style` 属性来直接添加样式，也可以通过 JavaScript 来添加事件。
```html
<h6 style="color: red;font-size: 2em;" onclick="alert('hi,html')">这是6级标题</h6>
```
<h6 style="color: red;font-size: 2em;" onclick="alert('hi,html')">这是6级标题</h6>

## 常用标签
- `<p>` 定义段落。
- `<strong>` 定义加粗文本。
- `<em>` 定义斜体文本。
- `<sup>` 定义上标文本。
- `<sub>` 定义下标文本。
- `<ins>` 定义插入文本。
- `<del>` 定义删除文本。
- `<cite>` 定义引用。
- `<blockquote>` 定义块引用。
- `<small>` 定义小字体文本。
- `<abbr>` 定义缩写。
- `<bdo>` 定义文本方向。

### 示例
```html
<p>这是段落&lt;p&gt;1</p>
<p>这是<strong>strong</strong></p>
<p>这是<em>em</em></p>
<p>这是上标<sup>sup</sup></p>
<p>这是下标<sub>sub</sub></p>
<p>这是插入标记<ins>ins(insert)</ins></p>
<p>这是删除标记<del>del(delele)</del></p>
<p>这是引用标记<cite>cite</cite></p>
<p>这是块引用<blockquote>blokquote</blockquote></p>
<p>这是注解标记<small>small</small></p>
<p>这是缩写标记<abbr>abbr</abbr></p>
<p>这是文本方向<bdo dir="rtl">bdo标记</bdo></p>
```
<p>这是段落&lt;p&gt;1</p>
<p>这是<strong>strong</strong></p>
<p>这是<em>em</em></p>
<p>这是上标<sup>sup</sup></p>
<p>这是下标<sub>sub</sub></p>
<p>这是插入标记<ins>ins(insert)</ins></p>
<p>这是删除标记<del>del(delele)</del></p>
<p>这是引用标记<cite>cite</cite></p>
<p>这是块引用<blockquote>blokquote</blockquote></p>
<p>这是注解标记<small>small</small></p>
<p>这是缩写标记<abbr>abbr</abbr></p>
<p>这是文本方向<bdo dir="rtl">bdo标记</bdo></p>

## 文本格式化
- `<pre>` 定义预格式化的文本。
- `<code>` 定义计算机代码片段。
- `<dfn>` 定义一个定义。

### 示例
```html
<pre>文本格式化标记pre
  if(a>b){
     max=a;
  }else{
     max=b
  }
</pre>
<code>这是code标记</code>
<dfn>这是dfn标记</dfn>
```
<pre>文本格式化标记pre
  if(a>b){
     max=a;
  }else{
     max=b
  }
</pre>
<code>这是code标记</code>
<dfn>这是dfn标记</dfn>

## 容器和内联元素
- `<div>` 定义文档中的分区或节。
- `<span>` 定义文档中的行内元素。

### 示例
```html
<div>这是一个div</div>
<div>这是一个div<span style="color:red;">span</span></div>
```
<div>这是一个div</div>
<div>这是一个div<span style="color:red;">span</span></div>

## 换行和注释
- `<br/>` 定义换行（line break）。
- `<!-- -->` 定义注释。

### 示例
```html
<br/>
<!-- 这是注释 -->
```
## 其他
- `<ruby>` 定义 ruby 注释（中文注音或解释）。

### 示例
```html
<ruby>望<rt>wang</rt>霁<rt>ji</rt></ruby>
```
<ruby>望<rt>wang</rt>霁<rt>ji</rt></ruby>
---
