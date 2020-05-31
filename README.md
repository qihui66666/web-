​
齐慧七班2019012565

https://github.com/qihui66666/web-.git

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>雪梨在线</title>
</head>l

<style>
/*重置浏览器样式*/
* {
    padding: 0;
    margin: 0;
}

a {
    text-decoration: none;
}

ul {
    list-style-type: none;
}

/*清除浮动*/
.clear:after {
    content: '';
    display: block;
    height: 0;
    clear: both;
}
.title{
	width: 95px;
	height: 22px;
	font-size:23px;
	font-family:Microsoft YaHei;
	font-weight:bold;
	color:#00A4FF;
	float: left;
	position: relative;
	left: 208px;
	top: 18px;
}
.all{
	width: 1400px;
	height: 2400px;
	position: relative;
	background-color: rgb(245,245,255);
}
.list li{
	display: inline-block;
	width: 80px;
	height: 25px;
	text-align: center;
	float: left;
	position: relative;
	left: 288px;
	top: 20px;
}
.list a:hover{
	border-bottom: 2px blue solid;
}
form{
	position: relative;
	left: 320px;
	top: 17px;
}
.search{
	float: left;
	width: 200px;
	padding: 9px;
	border: 1px solid;
}
.submit{
	float: left;
	width: 35px;
	height: 35px;
	background-color: rgb(20,88,180);
}
.fa-search{
	width: 20px;
	height: 20px;
	position: relative;
	left: 292px;
	top: 23px;
}
.personal{
	color: grey;
	position: relative;
	left: 350px;
	top: 23px;
}
.banner2{
	width: 1080px;
	height: 337px;
	position: absolute;
	top: 67px;
	left: 80px;
}
.content{
	width: 150px;
	height: 337px;
	padding-left: 5px;
	position: absolute;
	top: 67px;
	left: 180px;
	background-color: rgba(0,0,0,0.4);
	line-height: 2.3em;
}
.content li a{
	color: white;
}
.classify{
	width: 1080px;
	height: 30px;
	border: 1px black dotted;
	padding-top: 10px;
	position: absolute;
	left: 80px;
	top: 430px;
}
.classify ul li a{
	display: inline-block;
	width: 120px;
	float: left;
	border-left: 1px black dotted;
	text-align: center;
	color: black;
}
#change{
	float: right;
	color: #00A4FF;
}
#recommend{
	color: #00A4FF;
	font-size: 20px;
	font-weight: bold;
}
.h3{
	font-weight: normal;
	position: absolute;
	left: 80px;
	top: 520px;
}
.h33{
	font-weight: normal;
	position: absolute;
	left: 80px;
	top: 1160px;
}
.jingpin{
	width: 1080px;
	height: 520px;
	position: absolute;
	left: 80px;
	top: 600px;
}
.picture{
	background-color: white;
	padding: 3px;
	float: left;
	width: 208px;
	height: 250px;
	box-shadow: 3px rgba(118,118,118,0.5);
}
.pic{
	width: 208px;
	height: 150px;
}
.picture ul{
	padding: 20px;
	color: black;
}
.red{
	color: red;
	display: inline-block;
}
.study{
	display: inline-block;
	float: right;
}
#lists{
	float: left;
	width: 500px;
	height: 40px;
	position: absolute;
	left: 250px;
	top: 1160px;
	padding-left: 200px;
	padding-right: 200px;
}
#lists li a{
	display: inline-block;
	float: left;
	padding-left: 50px;
}
h4 a{
	position: absolute;
	left: 1100px;
	top: 1160px;
	color: grey;
	font-weight: normal;
}
.qianduan{
	width: 1080px;
	height: 260px;
	position: absolute;
	left: 90px;
	top: 1200px;
}
.h333{
	font-weight: normal;
	position: absolute;
	left: 90px;
	top: 1500px;	
}
.niuren{
	width: 1080px;
	height: 300px;
	position: absolute;
	left: 90px;
	top: 1550px;
}
.grad a img{
	border: 1px dotted;
	width: 416px;
	height: 295px;
	background-color: white;
	padding: 3px;
	float: left;
}
.people a img{
	border: 1px dotted;
	width: 208px;
	height: 295px;
	padding: 3px;
	float: left;
}
.bottom{
	width: 1400px;
	height: 400px;
	background-color: white;
	position: absolute;
	left: 0;
	bottom: 0;
}
.xueli{
	font-size:40px;
	font-family:Microsoft YaHei;
	font-weight:bold;
	color:#00A4FF;
	position: absolute;
	left: 150px;
	top: 110px;
}
.explain{
	font-size: 10px;
	color: grey;
	position: absolute;
	left: 150px;
	top: 190px;
}
.app a{
	display: block;
	width: 110px;
	height: 32px;
	padding-top: 5px;
	font-size: 20px;
	position: absolute;
	left: 150px;
	top: 240px;
	text-align: center;
	color: #00A4FF;
	border:2px #00A4FF solid;
}
.list1{
	display: block;
	width: 170px;
	height: 400px;
	padding-top: 100px;
	position: absolute;
	left: 600px;
}
.about{
	font-size: 20px;
}
.blank{
	color: white;
}
ul.list1 li a{
	color: black;
}
.list2{
	display: block;
	width: 170px;
	height: 400px;
	padding-top: 100px;
	position: absolute;
	left: 800px;
}
ul.list2 li a{
	color: black;
}
.list3{
	display: block;
	width: 170px;
	height: 400px;
	padding-top: 100px;
	position: absolute;
	left: 1000px;
}
ul.list3 li a{
	color: black;
}
</style>

<body>
	<div class="all">
		<div class="title">
			雪梨在线
		</div>
		<div>
			<ul class="list">
				<li><a href="">首页</a></li>
				<li><a href="">课程</a></li>
				<li><a href="">职业规划</a></li>
			</ul>
		</div>
		<form>
			<input type="text" name="search" class="search">
			<input type="button" name="submit" class="submit">
		</form>
		<img src="img/fa-search.png" class="fa-search">
		<a href="" class="personal">个人中心</a>
		<img src="img/banner2.png" class="banner2">
		<div class="content">
			<ul>
				<li><a href="">前端开发 ></a></li>
				<li><a href="">后端开发 ></a></li>
				<li><a href="">移动开发 ></a></li>
				<li><a href="">人工智能 ></a></li>
				<li><a href="">商业预测 ></a></li>
				<li><a href="">云计算&大数据 ></a></li>
				<li><a href="">运维&从测试 ></a></li>
				<li><a href="">UI设计 ></a></li>
				<li><a href="">产品 ></a></li>
			</ul>
		</div>
		<div class="classify">
			<ul>
				<li><a href="" id="recommend">精品推荐</a></li>
				<li><a href="">jQuery</a></li>
				<li><a href="">Spark</a></li>
				<li><a href="">MySQL</a></li>
				<li><a href="">JavaWeb</a></li>
				<li><a href="">MySQL</a></li>
				<li><a href="">JavaWeb</a></li>
				<li><a href="" id="change">修改兴趣</a></li>
			</ul>
		</div>
		<h3 class="h3">精品推荐</h3>
		<div class="jingpintuijian">
			<div class="picture">
				<a href="">
					<img src="1.jpg" class="pi">
					<ul>
						<li>Think PHP 5.0博客系统实战项目演练</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="2.jpg" class="pi">
					<ul>
						<li>Android网络图片加载框架详解</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="3.jpg" class="pi">
					<ul>
						<li>Angular 2 最新框架+主流技术+项目实战</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="4.jpg" class="pi">
					<ul>
						<li>Android Hybrid APP 开发实战 H5+原生</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="5.jpg" class="pi">
					<ul>
						<li>Android Hybrid APP 开发实战 H5+原生</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="6.jpg" class="pc">
					<ul>
						<li>Think PHP 5.0博客系统实战项目演练</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="7.jpg" class="pi">
					<ul>
						<li>Android网络图片加载框架详解</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="8.jpg" class="pi">
					<ul>
						<li>Angular 2 最新框架+主流技术+项目实战</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="9.jpg" class="pi">
					<ul>
						<li>Android Hybrid APP 开发实战 H5+原生</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="10.jpg" class="pi">
					<ul>
						<li>Android Hybrid APP 开发实战 H5+原生</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
		</div>
		<h3 class="h33">前段开发工程师</h3>
		<div id="lists">
			<ul>
				<li><a href="">热门</a></li>
				<li><a href="">初级</a></li>
				<li><a href="">中级</a></li>
				<li><a href="">高级</a></li>
			</ul>
		</div>
		<h4><a href="">查看全部</a></h4>
		<div class="qianduan">
			<div class="picture">
				<a href="">
					<img src="" class="pi">
					<ul>
						<li>微软人工智能-数据分析平台</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="11.jpg" class="pi">
					<ul>
						<li>Unity Profiler入门</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="12.jpg" class="pi">
					<ul>
						<li>Cocos2d-x 引擎源码中的纹理优化</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="13.jpg" class="pi">
					<ul>
						<li>Kami2首页界面切换效果</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
			<div class="picture">
				<a href="">
					<img src="14.jpg" class="pi">
					<ul>
						<li>Android Hybrid APP 开发实战 H5+原生</li>
						<li class="re">高级</li>
						<li class="study">1125人在学习</li>
					</ul>
				</a>
			</div>
		</div>
		<h3 class="h333">牛人推荐</h3>
		<div class="niuren">
			<div class="grad">
				<a href="">
					<img src="15.jpg">
				</a>
			</div>
			<div class="people">
				<a href="">
					<img src="16.jpg">
				</a>
			</div>
			<div class="people">
				<a href="">
					<img src="17.jpg">
				</a>
			</div>
			<div class="people">
				<a href="">
					<img src="18.jpg">
				</a>
			</div>
		</div>
		<div class="bottom">
			<ul>
				<li class="xueli">雪梨在线</li>
				<li class="explain">致力于普及中国最好的教育，与中国一流大学和机构合作提供在线课程</li>
				<li class="app"><a href="">下载APP</a></li>
			</ul>
			<ul class="li1">
				<li class="about">关于雪梨网</li>
				<li class="blank">blank</li>
				<li><a href="">关于</a></li>
				<li><a href="">管理团队</a></li>
				<li><a href="">工作机会</a></li>
				<li><a href="">客户服务</a></li>
				<li><a href="">帮助</a></li>
			</ul>
			<ul class="li2">
				<li class="about">新手指南</li>
				<li class="blank">blank</li>
				<li><a href="">如何注册</a></li>
				<li><a href="">如何选课</a></li>
				<li><a href="">如何拿到毕业证</a></li>
				<li><a href="">学分是什么</a></li>
				<li><a href="">考试未通过怎么办</a></li>
			</ul>
			<ul class="li3">
				<li class="about">合作伙伴</li>
				<li class="blank">blank</li>
				<li><a href="">合作机构</a></li>
				<li><a href="">合作导师</a></li>
			</ul>
		</div>
	</div>
</body>
</html>

 

