
# ToolTips
this demo use css3 
* 强制浏览器使用最新版本的模式渲染，以保证CSS3效果能展示出来

``` html
	<meta http-equiv="X-UA-compatible" content="IE=edge">
```

* 让页面自适应设备宽度 并且设置初始化比例为1

``` html
	<meta name="viewport" content="width=device-width" initial-scale="1">

```

* 视图旋转的时候，文字大小不要改变

``` css
	-webkit-text-size-adjust:none;
	-moz-text-size-adjust:none;
	-ms-text-size-adjust:none;
	-o-text-size-adjust:none;
	text-size-adjust:none;
```

* `:after` 与 `:before`

> `:after` 选择器：在被选元素的内容后面插入内容

> `:before` 选择器：在被选元素的内容前面插入内容

>   注意：需使用 `content` 属性来指定要插入的内容
