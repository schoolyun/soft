# soft

<!doctype html>
<html lang="zh-CN">
<title>简单导航</title>
<meta charset="utf-8">
<meta content="width=device-width,initial-scale=1,maximum-scale=1"name=viewport>
<meta content="jsthon" name="author">
<meta content="一个极简的网址导航，聚合了多种搜索引擎，收录了各种常用网站。分类合理，内容齐全。处处细微，一切都是理所当然。" name="description">
<meta content="简单导航,导航,网址导航,导航网站,常用网站,常用网址,大学生导航,程序员导航,设计导航,学习导航" name="keywords">
<link href="static/css/style.css"rel=stylesheet>
<script>window.ga=window.ga||function(){(ga.q=ga.q||[]).push(arguments)};ga.l=+new Date;ga('create','UA-69454720-6','auto');ga('send','pageview');</script>
<script async src='static/js/analytics.js'></script>
<body style="background:#fff">
<nav id="site-nav">
<div class="float-left" id="nav-close">
</div>
<ul class="float-right" id="menu">
	<li><a href="/">首页</a>
	<li class="has-submenu"><a href="#">社交</a>
	<ul class="submenu">
		<li><a href="https://www.baidu.com/" target="_blank">Baidu</a>
		<li><a href="https://weibo.com/" target="_blank">Weibo</a>
		<li><a href="https://zhuanlan.zhihu.com/" target="_blank">Zhihu</a>
		<li><a href="https://github.com/" target="_blank">GitHub</a>
	</ul>
</ul>
</nav>
<div id="site-main">
	<div id="main-overlay">
	</div>
	<header id="site-header">
	<div class="container">
		<div class="float-left" id="header-logo">
			<a href="/"><i class="icon-logo"></i></a>
		</div>
		<div class="float-right" id="burger">
			<div id="burger-icon">
				<span class="icon-bar top"></span><span class="icon-bar middle"></span><span class="icon-bar bottom"></span>
			</div>
		</div>
	</div>
	</header>
	<div class="headline search-bar">
		<div class="container">
			<div class="headline-content">
				<div class="search-tab">
					<span class="lookao">购物</span><span class="baidu">百度</span><span class="google">谷歌</span><span class="bing">必应</span><span class="image">图片</span><span class="torrent">种子</span><span class="scholar">学术</span>
				</div>
				<form class="search-form" target="_blank">
					<input class="float-left search-keyword"type=search autocomplete=off autofocus><input class="float-right" type="submit" value="搜索">
				</form>
			</div>
		</div>
	</div>
	<div class="works">
		<div class="work-link">
			<div class="container">
				<div class="tab">
					<span class="common">常用</span><span class="amuse">娱乐</span><span class="study">学习</span><span class="life">生活</span><span class="tech">技术</span><span class="design">设计</span><i class="icon-cog" id="setting-icon"></i>
				</div>
				<div class="info">
				</div>
			</div>
		</div>
		<div class="gallery" data-cols="3" data-height="0.8" data-margin="0">
			<div class="entry work-entry w2">
				<a href="https://ijkxs.com/">
				<div class="reveal">
					<div class="entry-image imageBG"data-img="static/img/thumb-1.jpg">
					</div>
					<div class="info">
						<div class="content">
							<div class="title">
								术の語、涼城
							</div>
							<div class="cat">
								国内知名娱乐网站
							</div>
						</div>
					</div>
				</div>
				</a>
			</div>
			<div class="entry work-entry">
				<a href="https://ijkxs.com/">
				<div class="reveal">
					<div class="entry-image imageBG"data-img="static/img/thumb-2.jpg">
					</div>
					<div class="info">
						<div class="content">
							<div class="title">
								购物推荐
							</div>
							<div class="cat">
								超火的购物网站
							</div>
						</div>
					</div>
				</div>
				</a>
			</div>
		</div>
	</div>
	<footer id="site-footer">
	<div class="container">
		<div class="copy">
			© <span id="current-year">
			<script>document.getElementById("current-year").innerHTML=(new Date).getFullYear()</script>
			</span>&nbsp;简单导航<br>
			一个极简的网址导航<br>
			<a href="http://www.beian.miit.gov.cn/" target="_blank">这里是备案号</a>
		</div>
		<div class="social">
			<a href="https://weibo.com/" target="_blank" class="social-link"><i class="icon-weibo"></i></a>
      <a href="https://zhuanlan.zhihu.com/" target="_blank" class="social-link"><i class="icon-zhihu"></i></a>
      <a href="https://github.com/" target="_blank" class="social-link"><i class="icon-github-circled"></i></a>
      <a href="http://ijkxs.com/" target="_blank" class="social-link"><i class="icon-home"></i></a>
		</div>
	</div>
	</footer>
</div>
<script src="jquery-migrate-1.2.1.min.js"></script>
<script src="static/js/index.js?!"></script>
