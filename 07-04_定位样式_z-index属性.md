## 7.4 z-index属性

### 7.4.1 z-index属性定义

z-index 属性设置元素的堆叠顺序。  
拥有更高堆叠顺序的元素总是会处于堆叠顺序较低的元素的前面。

### 7.4.2 案例演示

![](images/duidieyangshi.png) 
	
	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>z-index案例演示</title>
		<style type="text/css">
			.box1{
				width: 100px;
				height: 100px;
				background: red;
				float: left;
				position: relative;
				z-index: 9999;
			}
			.box2{
				width: 100px;
				height: 100px;
				background: blue;
				float: left;
				position: relative;
				left: -30px;
				top: 30px;
				z-index: 5;
			}
			.box3{
				width: 100px;
				height: 100px;
				background: green;
				float: left;
				position: relative;
				left: -60px;
				top: 60px;
				z-index: 6;
			}
			/*z-index：可以控制标签元素之间的堆叠顺序，z-index的属性值越大，堆叠的级别越高。
			z-index属性市场主流的浏览器软件都支持，但是IE浏览器不支持*/
		</style>
	</head>
	<body>
		<div class="box1">盒子1</div>
		<div class="box2">盒子2</div>
		<div class="box3">盒子3</div>
	</body>
	</html>

### 7.4.3 总结

* z-index属性可以设置两个盒子堆叠的先后关系
* 拥有更高堆叠顺序的元素总是会处于堆叠顺序较低的元素的前面。
* 元素可拥有负的 z-index 属性值。
* 仅能在定位元素上奏效