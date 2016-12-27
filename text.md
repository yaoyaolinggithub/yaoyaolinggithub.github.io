# hello world
```javascript
	var a = "hello world";
```
## php数据库连接
```php
	$conn = @mysqli_connect("localhost","root","","html5-9");
	if (!$conn) {
		die("连接失败！");
	}
	// 删除数据库里面的数据条
	$conn->query("set names utf8");
```
