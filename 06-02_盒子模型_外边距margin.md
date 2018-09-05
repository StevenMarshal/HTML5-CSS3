## 6.2 外边距margin

### 6.2.1 边界样式

边界(外边距，margin)：盒子模型中边框(border)的最外一层就是盒子的边界线，边界线是无色透明看不见的，因此不能够控制边界线的颜色和粗细。边框与边界线之间的距离称之为”外边距”。
* margin-top：上外边距
* margin-bottom：下外边距
* margin-left：左外边距
* margin-right：右外边距
* margin：上右下左

### 6.2.2 案例演示

示例1

![](images/heziwaibianju1.png) 

	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>盒子模型的外边距(margin)</title>
		<style type="text/css">
			#box1{
				width: 200px;
				height: 100px;
				/*指定盒子的边框样式*/
				border:solid 5px red;
	
				/*将第一个盒子的下外边距设置为60px*/
				/*margin-bottom: 60px;*/
				margin-left:200px;
			}
			#box2{
				width: 200px;
				height: 100px;
				/*指定盒子的边框样式*/
				border:dashed 5px blue;
	
				/*将第二个盒子的上外边距设置为60px*/
				margin-top: 60px;
				margin-left: 300px;
			}
		</style>
	</head>
	<body>
		<div id="box1">我是第一个盒子</div>
		<div id="box2">我是第二个盒子</div>
	</body>
	</html>

示例2

![](images/heziwaibianju2.png) 

	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>盒子边界2</title>
		<style type="text/css">
			.c1{
				width: 100px;
				height: 100px;
				background: red;
	
				margin-left:100px;
				margin-bottom:20px; 
			}
			.c2{
				width: 100px;
				height: 100px;
				background: yellow;
				margin-bottom:20px; 
			}
			.c3{
				width: 100px;
				height: 100px;
				background: blue;
				margin-left:100px;
			}
		</style>
	</head>
	<body>
		<div class="c1">第一个盒子</div>
		<div class="c2">第二个盒子</div>
		<div class="c3">第三个盒子</div>
	</body>
	</html>

示例3

	![](images/heziwaibianju3.png) 
	
	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>通过盒子模型中的边界可以将某一个盒子居中</title>
		<style type="text/css">
			#box{
				width: 400px;
				height: 250px;
				background: pink;
				margin-left: auto;
				margin-right:auto;
			}
		</style>
	</head>
	<body>
		<div id="box"></div>
	</body>
	</html>

### 6.2.3 总结

边界线：盒子模型中边框(border)的最外一层是边界线，边界线是无色透明看不见的。因此，学习起来比边框(边框可以设置颜色)要困难一些。

边界线与边框之间的距离称之为“外边距”，外边距总共有4个：分别为margin-top(上外边距)、margin-bottom（下外边距）、marginleft（左外边距）、margin-right（右外边距）

可以通过同时将盒子的margin-left、margin-right值设置为auto，从而将某一盒子居中显示。