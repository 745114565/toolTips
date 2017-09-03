
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

* 设置元素前后动态生成的内容不会影响钙元素原来样式

``` css
*,*:after,*:before{
	-webkit-box-sizing: border-box;
	-moz-box-sizing: border-box;
	-ms-box-sizing: border-box;
	-o-box-sizing: border-box;
	box-sizing: border-box;
}
```

* 使生成的元素变成块状元素

``` css
*:after,*:before{
	display: block;
	content: "";
}
```

* `:after` 清除浮动

``` css
*:after{
	clear: both;
}
```

* html元素被设置为绝对定位以后，自动转为blok(块状)

* [FontAwesome](https://fontawesome.io "FontAwesome") 字体库

* trasform 

``` text
功能：向元素应用2D或3D转换
	 语法：transform:none|transform=functions
	 参数：
	 	translate3d(x,y,z) 定义3D转化
	 	rotate3d(x,y,z,angle) 定义3D旋转
	 	scale3d(x,y,z,flex) 定义3D缩放
```
