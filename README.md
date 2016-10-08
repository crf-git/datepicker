# DatePicker
移动端滚动式日期控件，带平滑滚动效果，超小体积，原生js编写，不依赖任何第三方文件。

## 快速开始
1、引入文件
```HTML
<html>
	<head>
		...
		<link rel="stylesheet" href="path/to/datepicker.css" />
	</head>
	<body>
		...
		<script src="path/to/datepicker.js"></script>
	</body>
</html>
```
2、使用
在input上加上role="datepicker"，就这么简单
```HTML
<input type="text" role="datepicker" readonly />
```
3、格式化
日期格式默认为 yyyy-MM-dd 格式，如果你想换格式，添加 data-format="yyyy/MM/dd" 就可以了
```HTML
<input type="text" role="datepicker" data-format="yyyy/MM/dd" readonly />
```
4、如果你只想选年月，将格式化修改为：data-format="yyyy-MM"
```HTML
<input type="text" role="datepicker" data-format="yyyy-MM" readonly />
```

## 预览地址
[datepicker demo](http://htmlpreview.github.io/?https://github.com/Capricair/datepicker/blob/master/output/min/demo.html "title\" target="_blank")
