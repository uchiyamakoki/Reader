# Reader
Web阅读器

展示

![](https://github.com/uchiyamakoki/Reader/blob/master/img/1.png)

## 每日笔记

2018.9.1：
复习 zepto的引入
``` HTML
<script src="lib/zepto.min.js"></script>
		<script>
			window.jQuery = $;
		</script>
		<script src="js/jquery.base64.js"></script>
		<script src="js/jquery.jsonp.js"></script>
```

2018.9.22：

将JS代码放在闭包中

``` HTML
		<script>
	             （function（）{}）（）；		
		</script>
```

再声明一个内部类
``` HTML
		<script>
	             （function（）{
			var Util=(function(){
				var StorageGetter=function(key){
			    return localStorage.getItem(prefix+key);
			}
			        var StorageSetter=function(key,val){
			}
			})();	
		}）（）；		
		</script>
```



