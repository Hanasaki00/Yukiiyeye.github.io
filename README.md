<!-- exam01.html -->
<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <title>儿童食品</title>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link type="text/css" rel="stylesheet" href="prj_childfood.css">
</head>
<script type="text/javascript">
	function $ (id){return document.getElementById(id);}
	function setFont(size){
		$("main").style.fontSize=size;
	}
</script>
<body>
    <div class="wrapper">
        <!-- 头部 -->
        <div class="header">
            <div class="headerwrapper">
                <a href="#">
                    <img src="../儿童食品-资源/儿童食品/woolworths-logo.png" class="logo" alt="">
					<p><a href="#">登录丨</a>&nbsp;&nbsp;<a href="#">联系我们丨</a></p><p><a href="#">注册丨</a>&nbsp;&nbsp;	<div id="div1"><a href="javascript:setFont('10px')">缩小</a>
						<a href="#" onclick="javascript:setFont('20px')"></a>
						<a href="#" onclick="setFont('30px')">放大</a>
				</div>
                </a>
                <div class="search">
                    <!-- margin-top: (120-26)/2=47px; -->
                    <form action="post">
                        <input type="text" name="search" class="text" placeholder="请输入">
                        <button class="button"><img src="../儿童食品-资源/儿童食品/search-green.png" alt="" onclick=""></button>
                    </form>
                </div>
            </div>
        </div>
        <!-- 导航 -->
        <div class="nav">
            <div class="navwrapper">
                <ul>
                    <li><a href="#">博客园</a></li>
                    <li><a href="#">VIP会员专区</a></li>
                    <li><a href="#">儿童食品在线选购</a></li>
                    <li><a href="#">美食社区</a></li>
                    <li><a href="#">食品知识</a></li>
                    <li><a href="#">网站帮助</a></li>
                    <li><a href="#">网银在线支付</a></li>
					<li><a href="#">关于我们</a></li>
                </ul>
            </div>
			<div class="nav_bot">
				<li><a href="#">选购商品</a></li>
				<li><a href="#">在线支付</a></li>
				<li><a href="#">免费试吃</a></li>
				<li><a href="#">冷藏物流</a></li>
				<li><a href="#">速递直达</a></li>
				<li><a href="#">客户服务</a></li>
			</div>
        </div>

        <!-- 主体部分 -->
        <div class="mainbody">
            <!-- 大图 -->
            <div class="banner">
                <img src="../img/banner.jpg" alt="">
            </div>
            <!-- 内容区 -->
            <div class="main">
                
        
            </div>
        </div>
        <!-- 版权区 -->
        <div class="footer">
            <p>地址：福建省福州市仓山区上三路8号福建师范大学仓山校区30号楼（350007）</p>
            <p>福建省福州市大学城科技路1号福建师范大学旗山校区理工楼主楼南楼四楼（350117）</p>
            <p>版权所有&copy;福建师范大学环境科学与工程学院</p>
        </div>
    </div>
</body>
</html>
