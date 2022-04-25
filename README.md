# slyjs
导航单向滚动元素, 用于项目中的导航栏支持<br>
<img src="http://www.wware.org/img/dh001.png" width="400px"><br>
普通属性<br>
data-slyid	每一个元素必须设置自己的独一无二的id号。	<br>
data-startat	设置显示选中第几个.默认从0开始。	0<br>
data-speed	设置导航滑动的速度,默认为300	300<br>
#### css样式如下
```css
<style type="text/css">/* Frame */
.frame1 {
	height: 50px;
	line-height: 50px;
	overflow: hidden;
}
.frame1 ul {
	list-style: none;
	margin: 0;
	padding: 0;
	height: 100%;
	font-size: 16px;
}
.frame1 ul li {
	float: left;
	width: 50px;
	height: 100%;
	margin: 0 10px 0 0;
	padding: 0;
	background: #333;
	color: #ddd;
	text-align: center;
	cursor: pointer;
}
.frame1 ul li.active {
	color: #fff;
	background: #a03232;
}
</style>
```
