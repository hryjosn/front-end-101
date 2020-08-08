# HTML

\#\#\#HTML 基本介紹

‌

#### 最基本的 HTML格式 <a id="zui-ji-ben-de-html-ge-shi"></a>

```text
<!DOCTYPE html><html>  <head>    <title>Page Title</title>  </head>​  <body>    <h1>This is a Heading</h1>    <p>This is a paragraph.</p>  </body></html>​
```

‌

存成.html檔後用瀏覽器打開的結果就會是下面這樣![](https://gblobscdn.gitbook.com/assets%2F-MECcvVVhu0QbPDq5qlH%2F-MECm_refIKQPwgN1JCY%2F-MECn-R91aGkbB-YUq-D%2F%E6%88%AA%E5%9C%96%202020-08-08%20%E4%B8%8B%E5%8D%887.18.12.png?alt=media&token=98b544a0-3c13-4c99-a7cd-d44496784509)Basic HTML‌

#### HTML Tag _**通常**_ 都是成雙成對的  <a id="html-tag-tong-chang-du-shi-cheng-shuang-cheng-dui-de"></a>

‌

由兩個角括號圍繞起來的就成為Tag\(標籤\)‌

例如常見的‌

&lt;div&gt; &lt;/div&gt;‌

&lt;a&gt;&lt;/a&gt;‌

&lt;span&gt;&lt;/span&gt;‌

而如果我們在Tag中放如其他元素（純文字或是其他Tag）‌

例如:

```text
<body>    <h1>This is a Heading</h1>    <p>This is a paragraph.</p></body>
```

‌

我們就會稱 &lt;h1&gt; 和 &lt;p&gt; 是 &lt;body&gt; 的子元素 \(child element\)‌

所以相對於&lt;h1&gt; 來說&lt;body&gt; 就是 &lt;h1&gt;的父元素\(parent element\)‌

~~不要問我為什麼不叫母元素~~[~~https://www.zhihu.com/question/21111030~~](https://www.zhihu.com/question/21111030)~~​~~‌

#### 常見的ＨＴＭＬTag <a id="chang-jian-de-tag"></a>

‌

&lt;div&gt; &lt;a&gt; &lt;head&gt;‌

都有不同的功能‌

可以從W3C的網站檢視相對應的功能：[https://www.w3schools.com/html/html\_elements.asp](https://www.w3schools.com/html/html_elements.asp)​‌

完整Tag 列表：[HTML ReferenceWell organized and easy to understand Web building tutorials with lots of examples of how to use HTML, CSS, JavaScript, SQL, PHP, Python, Bootstrap, Java and XML.www.w3schools.com](https://www.w3schools.com/tags/default.asp)‌

## HTML attribute <a id="html-attribute"></a>

‌

#### Attribute（特性\)  <a id="attribute-te-xing"></a>

‌

~~不是attitude \(態度）~~‌

attribute特性由HTML定義，所有出現在HTML標籤內的描述節點都是attribute特性。

```text
<div id="test" class="button" custom-attr="1"></div>
```

‌

**attribute的型態總會是字串**‌

以上面的DIV為例 **id class custom-attr** 都是 **attribute**

