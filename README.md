<!DOCTYPE html>
<html>
	<head>
		<title> جدول ثبت مشخصات</title>	
	</head>
	<body dir="rtl" align="center">	
		<h1>فرم ثبت نام</h1>
	<center>
		<form>
			<table border="1" width="300px" >
		<tr>
			<td>نام</td>
			<td><input type="text" placeholder="نام... " /></td>
		</tr>
			<tr>
			<td>نام خانوادگی</td>
			<td><input type="text" placeholder="نام خانوادگی... " /></td>
		</tr>
		<tr>
			<td>ایمیل</td>
			<td><input type="email" placeholder="ایمیل خود را وارد کنید... " /></td>
		</tr>
		<tr>
			<td>رمز عبور</td>
			<td><input type="password" placeholder="رمز عبور خود را وارد کنید.. " /></td>
		</tr>	
		<tr>
			<td>وضعیت تاهل</td>
			<td><label> مجرد
			<input type="radio" name="yek" />
			</label>
			<label> متاهل
			<input type="radio" name="yek" /></td>
			</label>
		</tr>
		<tr>
		 <td>جنس پوست شما</td>
		<td>
			<select>
				<option> نوع پوست </option>
				<option> خشک </option>
				<option> چرب </option>
				<option> مختلط </option>
				<option>معمولی </option>
			</select></td>
		</tr>
		<tr>
			<td> ارسال فایل</td>
			<td><input type="file" name="myfile" /></td>
		</tr>
		<tr>
		<th colspan="2" >
		<label>
		<input type="submit" value="ثبت نام کاربر" />
		</label>
		</table>
		</form>
		</center>
	</body>
</html>
