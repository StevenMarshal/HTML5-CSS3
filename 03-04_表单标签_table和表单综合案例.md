## 3.4 table和表单综合案例

文本域标签，可以用来做留言板等

示例代码：

	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>表格域表单综合案例</title>
	</head>
	<body>
		<table border="1px" width="400px" height="120px" cellspacing="0px">
			<tr>
				<td>姓名</td>
				<td><input type="text" name="username"></td>
			</tr>
			<tr>
				<td>密码</td>
				<td><input type="password" name="password"></td>
			</tr>
			<tr>
				<td>性别</td>
				<td><input type="radio" name="gender">男<input type="radio" name="gender">女</td>
			</tr>
			<tr>
				<td>职业</td>
				<td>
					<select name="job">
						<option value="1">Java开发工程师</option>
						<option value="2">Web前端开发工程师</option>
						<option value="3">大数据挖掘师</option>
					</select>
				</td>
			</tr>
			<tr>
				<td>email</td>
				<td><input type="text" name="email"></td>
			</tr>
			<tr>
				<td>爱好</td>
				<td>
					<input type="checkbox">音乐
					<input type="checkbox">文学
					<input type="checkbox">体育
					<input type="checkbox">游戏
				</td>
			</tr>
			<tr>
				<td>头像</td>
				<td><input type="file" name="headImage"></td>
			</tr>
			<tr>
				<td colspan="2"><input type="submit" value="提交"></td>
			</tr>
		</table>
	
	</body>
	</html>