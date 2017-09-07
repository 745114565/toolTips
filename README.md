
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
``` txt
	 功能：向元素应用2D或3D转换
	 优点：凡使用3d方式的都会调用硬件加速
	 语法：transform:none|transform=functions
	 参数：
	 translate3d(x,y,z) 定义3D转化,x,y,z取值任意，单位px
	 rotate3d(x,y,z,angle) 定义3D旋转,x,y,z取值在0~1之间，angle是弧度
	 scale3d(x,y,z,flex) 定义3D缩放
```

* 设置图标变形

``` css
.tooltip-effect-1 .tooltip-content{
	/*定义在Y轴上转动*/
	-webkit-transform: translate3d(0,10px,0) rotate3d(1,1,1,45deg); 
	transform: translate3d(0,10px,0) rotate3d(1,1,1,45deg); 
	/*将图形中心移动的X轴中心，Y轴最底部，
	此属性只有所在元素在前面使用了transform才有效*/
	-webkit-transform-origin:50% 100%;
	transform-origin:50% 100%;
}

```

* 利用透明度 `opacity`属性 设置元素显示或隐藏
  
  
      `opacity:0` 隐藏， `opacity:1`显示
      
*  `transition` 状态过渡属性

``` txt
    
        功能：在一定时间区间内平滑地过渡指定属性值
        语法：transition:property duration timing-function delay
        参数：
            -- property 规定设置过渡效果css属性的名称
	    -- duration 规定完成过渡效果需要多少秒或毫秒
	    -- timing-function 规定速度效果的速度曲线
	    -- transition-delay 定义过渡效果何时开始
	    
 ```
