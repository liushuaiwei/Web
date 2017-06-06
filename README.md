# 16058518 Liu Shuaiwei

* [homeWork](./web作业/) WEB作业
	* [首页](./web作业/index.html) 
	* [列表页](./web作业/html/综合资讯.html)
	* [详细页](./web作业/html/赵云.html)
    * [表单页](./web作业/html/表单.html) 
# 开发报告 
## 1.策划思路

**策划思路**来自于手游时空召唤，本来是打算制作关于当前最火爆的手游--王者荣耀的一些东西的，但是王者荣耀内容多而复杂，我对于html和css知识的运用不是很熟练，于是就做同是MOBA类手游的时空召唤，这个相对比较容易，易于实现。

**期望达到的效果**是大致做出**部分游戏官网**的效果
![Markdown](https://liushuaiwei.github.io/Web/web%E4%BD%9C%E4%B8%9A/img/img1.png)
![Markdown](https://liushuaiwei.github.io/Web/web%E4%BD%9C%E4%B8%9A/img/img2.png)
![Markdown](https://liushuaiwei.github.io/Web/web%E4%BD%9C%E4%B8%9A/img/img3.png)



## 2.页面结构说明

页面由四个界面组成，包括

* [首页](./web作业/index.html) 首页作用
* [英雄介绍页面](./web作业/html/赵云.html) 即为详细页
* [列表页面](./web作业/html/综合资讯.html) 游戏资讯列表
* [表单页面](./web作业/html/表单.html) 一个简单的本命英雄测试

## 3.技术指标

* 谷歌浏览器完全适应，其他浏览器会出现部分内容不兼容，无法显示的现象
* 使用HTML5,CSS3.0,Javascript
* 开发工具：Chrome,Sublime Text及其插件

## 4.制作过程难点说明

**4.1.滚动效果和几个列表页面采用内联框架 [链接](./web作业/index.html)**

先单独分别做出滚动效果和资讯列表的html文档，在主页里分别弄了aside和section两个块，aside里用iframe来放滚动效果，section中用iframe来放资讯列表


**关键代码**

	 <aside>
		<iframe src="图片轮播切换效果/index.html" frameborder="1" name="myframe"></iframe>
	</aside>
	
	<section>
		<nav id="nav2">
			<ul>
				<li id="li">资讯：</li>
				<li><a href="html/综合资讯.html" target="frame">综合</a></li>
				<li><a href="html/新闻.html" target="frame">新闻</a></li>
				<li><a href="html/公告.html" target="frame">公告</a></li>
				<li><a href="html/活动.html" target="frame">活动</a></li>
				<li><a href="html/攻略.html" target="frame">攻略</a></li>
			</ul>
		</nav>
		<div id="div">
			<iframe src="html/综合资讯.html" frameborder="1" name="frame"></iframe>
		</div>
	</section>
	




**Js部分说明**
-----

由于对js不是太了解，也不太会用，就直接在网上引用了模板，把图片换成了想要展示的图片，然后就直接使用内联框架直接引用（上面已经介绍过），这样做虽然很简单，但同时存在一些问题：图片不能完全填充设置的内联框架的大小。希望老师给出建议。

-----

### 网页存在问题 ###

网页布局在谷歌浏览器能正常显示，但在其他浏览器上会显示杂乱。而且只能在窗口全屏状态下显示良好，改变窗口大小会出现方字溢出，图片重叠的现象使内容杂乱无章，对于这种情况不是太会解决，希望老师能够指导下。
 
### 开发过程中的总结 ###

整个网站花了5个星期，刚开始完全不知道先干什么，也没有一个具体的实施步骤，就先模仿着还原官网上的英雄列表的界面，然后慢慢做出详细页和其它的页面，于是心里就有了首页的布局想法，然后一点点的去实现，在制作过程中遇到了很多较难实现的地方，最后都通过查询学习一一克服，整个过程中，学到了很多有用的东西。

### 对本课程的感想与展望 ###

上学期选了一个HTML的课程，刚开始因为没接触过html，对此一窍不通，老师讲得枯燥无味，也完全听不懂，就没有认真学习，导致最后挂科。但老师的这门课让我对网页的制作有了极大的兴趣，用这些知识可以做出很多有意思的东西来，虽然现在对Html应用的还不是很熟练，有很多知识还不太了解，但老师的课程让我对计算机以及web前端开发有了更深刻的理解，在以后的课程中会认真学习web前端的开发和有关知识，希望以后继续能跟老师学习到更多东西。
