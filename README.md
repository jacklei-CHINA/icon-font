icon-font
=====
有一个岗位，叫前端开发；有一种技术，叫 CSS Sprite；有一种突破，叫font+HTML/CSS。移动互联网时代的到来，让CSS Sprite似乎有点Hold不住。Font+HTML/CSS将会做到，小巧的体积、更快的加载速度、任意改变颜色和尺寸，完美的兼容性，是你在网页中画小图标的不二之选。

在过去，我们为了使网页变得丰富多彩，免不了会使用一些小按钮、小图标，相信聪明的你对CSS Sprites（CSS精灵）一点也不陌生。那么，现在呢？如果你只知道CSS Sprites，那么你就有点OUT了。今天要给大家介绍的是一种更方便、高效，在多种设备上完美显呈现的小图标技术。

### 课程简介:

> 你有想过在网页中画小按钮、小图标就像在网页中输入文本一样高效、快捷吗？
    是的，她将成为现实。她在天猫、淘宝、土豆、优酷等国内大型网站上已经开始崭露头角。她绝对是前端开发里的一场盛宴。可以通过font-size来改变图标大小，通过color改变颜色等；她体格娇小，兼容所有主流浏览器，并且在所有现代浏览器里实现放大、旋转等CSS3动画效果效果。
    在各种分辨率下她都能高清无码完美显示展现自己迷人的风采，她绝对会令你大开眼界，你一定会深深的爱上她。
   
### 你能学到什么？
> eot、woff、ttf、svg字体格式<br>
> @font-face、font-family字体相关属性<br>
> :before、:after伪元素，content属性<br>
> 使用IcoMoon App管理字体图标<br>
> 轻松改变图标大小及颜色等CSS属性，就像操作文本一样简单。

代码演示
-----
下面我们来展示两种用字体在网页中画小图标的方法：<br>

一、HTML实体
```html
<i class="icon-ui">&#xe600;</i>
<i class="icon-ui">&#xe601;</i>
<i class="icon-ui">&#xe602;</i>
<i class="icon-ui">&#xe603;</i>
<i class="icon-ui">&#xe604;</i>


```css
@font-face {
  font-family: 'icon-font';
	src:url('fonts/icomoon.eot');
	src:url('fonts/icomoon.eot?#iefix') format('embedded-opentype'),
		url('fonts/icomoon.ttf') format('truetype'),
		url('fonts/icomoon.woff') format('woff'),
		url('fonts/icomoon.svg') format('svg');
	font-weight: normal;
	font-style: normal;
}
icon-ui {
	font-family: 'icon-font';
	speak: none;
	font-style: normal;
	font-weight: normal;
	font-variant: normal;
	text-transform: none;
	line-height: 1;

	/* Better Font Rendering =========== */
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}

二、class名称
```html
<i class="icon-chrome"> </i>
<i class="icon-firefox"> </i>
<i class="icon-IE"> </i>
<i class="icon-opera"> </i>
<i class="icon-safari"> </i>