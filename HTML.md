1.学习HTML开始。

什么是html?
hypertext markup language  超文本标记语言

由标签组成
```<html lang="en">/*值钱的知识点。告诉搜索引擎我们的网站是关于什么内容的。
SEO搜索引擎爬虫技术。lang="en"
<head>
<meta charset="utf-8">//mata字典 charset是属性
</head>
<body></body>
</html>
```
```
最常用utf-8,unicode
<title></title>
<p></p>
<h1></h1>//有加粗的功能。
```
行级元素
块级元素
行内块级元素
11.24练习
html代码：
```<html lang="en">
<head>
	<meta charset="utf-8">
	<title>练习</title>
<link rel="stylesheet" type="text/css" href="01.css">

</head>
<body>


<div class='c1'></div>
<div class='c2'></div>
<div class='c3'></div>
<div class='c3'></div>
<div class='c4'></div>


</body>
</html>```
css:
````
	*{
		margin: 0;

	}



	div{
		display: inline;
		padding: 30px;
		position: relative;
		top: 50px;
		width: 200px;
		height: 200px;
		background: white;
		border:20px solid black;
	    border-radius: 50%;
	/*width: 100px;
	height: 100px;
	border-radius: 50%;
	margin: 5px;
	border: 100px;
	padding: 20px;
	padding-color:yellow;
	background-color:red;*/
	}

/*	body{

		background: yellow;
	}*/
```
