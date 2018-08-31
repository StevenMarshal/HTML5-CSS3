## 3.1 input标签

input：这个标签中常见的属性有type、name、value

其中type属性常用的值有：text、password、checkbox、radio、file、color、number、date、button、submit等。

示例代码：

	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>表单标签</title>
	</head>
	<body>
		<!-- 
			表单标签主要是：input
				type:值不一样时，显示的控件效果也不一样
		 -->
		 <form>
			用户名：<input type="text"><br>
			密&nbsp;码：<input type="password"><br>
			兴趣爱好：<input type="checkbox">篮球<input type="checkbox">足球<br>
			性别:<input type="radio" name="gender">男<input type="radio" name="gender">女<br>
			文件上传：<input type="file"><br>
			日期：<input type="date"><br>
			颜色：<input type="color"><br>
			数值选择:<input type="number" max="5" min="0"><br>
			按钮：<input type="button" value="登录">
		</form>
	</body>
	</body>
	</html>

