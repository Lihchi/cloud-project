##網頁專題 code

html 部分

```html  
	<!DOCTYPE HTML>
	<html>
	<head>
	<title>Studio</title>
	<meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href="assets/css/style.css">
	<link rel="stylesheet" type="text/css" href="assets/css/boot.css">
	<link rel="stylesheet" type="text/css" href="assets/css/font-awesome.min.css">
	<link rel="stylesheet" type="text/css" href="assets/css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="assets/css/bootstrap.css">
	<link rel="stylesheet" type="text/css" href="assets/css/style_common.css">
	<link rel="stylesheet" type="text/css" href="assets/css/style1.css">
	<link rel="stylesheet" type="text/css" href="assets/css/try2.css">
	<link rel="stylesheet" type="text/css" href="assets/css/commerce.css">
	<link rel='stylesheet' type='text/css' href='http://fonts.googleapis.com/css?family=Open+Sans+Condensed:700,300,300italic'>
	<script src="assets/js/modernizr.custom.69142.js"></script>
	<script src="assets/js/jquery-1.10.1.min.js"></script>
	<script src="assets/js/bootstrap.min.js" ></script>
	<script src="assets/js/try2.js" ></script>
	<script src="https://www.google.com/jsapi"></script>
	<script type="text/javascript">
		  google.load('visualization', '1.0', {'packages':['corechart']});
		  google.setOnLoadCallback(drawChart);

		  function drawChart() {

			var data = new google.visualization.DataTable();
			data.addColumn('string', 'Topping');
			data.addColumn('number', 'Slices');
			data.addRows([
			  ['刷卡', 5],
			  ['超商貨到付款', 3],
			  ['ATM轉帳', 2]
			]);
			var options = {'width':450,
						   'height':230};
			var chart = new google.visualization.PieChart(document.getElementById('rank1'));
			chart.draw(data, options);
			
			var data2 = new google.visualization.DataTable();
			data2.addColumn('string', 'Topping');
			data2.addColumn('number', 'Slices');
			data2.addRows([
			  ['Yahoo', 5],
			  ['Pchome', 5],
			  ['momo', 4]
			]);
			var chart2 = new google.visualization.PieChart(document.getElementById('rank2'));
			chart2.draw(data2, options);
			
			var data3 = new google.visualization.DataTable();
			data3.addColumn('string', 'Topping');
			data3.addColumn('number', 'Slices');
			data3.addRows([
			  ['超商取貨', 82],
			  ['宅配', 79],
			  ['門市取貨', 3.2]
			]);
			var chart3 = new google.visualization.PieChart(document.getElementById('rank3'));
			chart3.draw(data3, options);
			
			var data4 = new google.visualization.DataTable();
			data4.addColumn('string', 'Topping');
			data4.addColumn('number', 'Slices');
			data4.addRows([
			  ['入口網站', 44],
			  ['Facebook', 39],
			  ['電視廣告', 38],
			  ['部落客/網紅', 21],
			  ['line', 17],
			  ['報章雜誌', 14]
			]);
			var chart4 = new google.visualization.PieChart(document.getElementById('rank4'));
			chart4.draw(data4, options);
			
			var data5 = new google.visualization.DataTable();
			data5.addColumn('string', 'Topping');
			data5.addColumn('number', 'Slices');
			data5.addRows([
			  ['Yahoo', 64],
			  ['露天拍賣', 58],
			  ['蝦皮拍賣', 23]
			]);
			var chart5 = new google.visualization.PieChart(document.getElementById('rank5'));
			chart5.draw(data5, options);
			
		  }

	</script>
	<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
	</head>
	<body>
	<div id="page-top" class="index">
	  <nav class="navbar navbar-inverse navbar-fixed-top">
		<div class="container-fluid">
		  <div class="navbar-header">
			<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false"><span class="sr-only">Toggle navigation</span><span class="icon-bar"></span><span class="icon-bar"></span><span class="icon-bar"></span></button>
			<a class="navbar-brand page-scroll" href="#page-top">Top</a></div>
		  <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
			<ul class="nav navbar-nav navbar-right">
			  <li><a class="page-scroll" href="#services">Begin</a></li>
			  <li><a class="page-scroll" href="#Commerce">Commerce</a></li>
			  <li><a class="page-scroll" href="#buyOrNot">WhyShopping</a></li>
			  <li><a class="page-scroll" href="#Ranking">Ranking</a></li>
			  <li><a class="page-scroll" href="#gogo">TopTen</a></li>
			  <li><a class="page-scroll" href="#contact">Contact</a></li>
			</ul>
		  </div>
		</div><!-- /.container-fluid -->
	  </nav>
	  <!-- Header -->
	  <header style="background-image:url(assets/img/3218_Computer-power-abstract-binary-code.jpg)">
		<div class="container">
		  <div class="intro-text">
			<div class="intro-lead-in">Welcome To Our Special Topic</div>
			<div class="intro-heading">E-Commerce</div>
			<a href="#services" class="page-scroll btn btn-primary">Let's Start It</a></div>
		</div>
	  </header>
	</div>

	<section id="services"></section>
		<div id="" class="big">
			<div id="small" class="small">
				<p id="word">Why People Shopping Online ?</p>
				<div class="shopOnline"><h1 class="wordsize">
	網路購物起源由來的說法眾說紛紜，不過一開始的網際網路背景源起自於 1960 年代美國 
	國防部 ARPA 研究所計劃出，連結各所大學建立的通訊網路，當時主要是用在軍事方面上的 
	用途，於通訊協定（protocal）讓不同廠牌、型式、作業系統的電腦間能夠進行資料傳遞的交 
	換，在戰爭發生時的緊急狀況，依然可以確保有完整的資料進行傳輸。 
	 到了 1980 年，美國科學基金會發展建立以「TCP/IP」為通訊協定的學術網路（NSFnet）。 
	後來在 1989 年 3 月全球資訊網（World Wide Web），簡稱「WWW」成立。網路的用途一開始 
	只侷限於學術之間的資訊交換，但隨著使用人口的快速增長，應用範圍也隨之越來越廣，後 
	來加入了商業技術手法，使得網路型態更加多樣化進而引起網路購物的商業發展。</h1></div>
			</div>
		</div>

	<!-- ===== services ===== -

	  <div class="container">
		<div class="row">
		  <div class="col-lg-12 text-center">
			<h2 class="section-heading" style="color:#3680C1">Why People Shopping Online ?</h2>
			<h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
		  </div>
		</div>
		<div class="row text-center">
		  <div class="col-md-4"><span class="fa-stack fa-4x"><i class="fa fa-circle fa-stack-2x text-primary"></i><i class="fa fa-shopping-cart fa-stack-1x fa-inverse"></i></span>
			<h4 class="service-heading">E-Commerce</h4>
			<p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
		  </div>
		  <div class="col-md-4"><span class="fa-stack fa-4x"><i class="fa fa-circle fa-stack-2x text-primary"></i><i class="fa fa-automobile fa-stack-1x fa-inverse"></i></span>
			<h4 class="service-heading">Auto-Mobiles</h4>
			<p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
		  </div>
		  <div class="col-md-4"><span class="fa-stack fa-4x"><i class="fa fa-circle fa-stack-2x text-primary"></i><i class="fa fa-windows fa-stack-1x fa-inverse"></i></span>
			<h4 class="service-heading">Windows</h4>
			<p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto quo inventore harum ex magni, dicta impedit.</p>
		  </div>
		</div>
	  </div>
	->
	<!-- ===== Team Section ===== -->
	<section id="Commerce" >
		<p style="text-align:center;font-size:40px;">What's E-Commerce ?</p>
		<p style="text-align:center;font-size:15px;position:relative;top:-12px;">
		是透過電腦網路所進行商品的銷售、服務提供、業務合作或資訊交換等商務活動
		</p>
		<div id="eCommerce">
			<div class="e1"><p style="font-size:35px;font-weight:700;">特色</p>
				<ol style="text-align:left;font-size:21px;">
					<li> 透過各大社群網站直接以符合消費者所期望的網拍模特兒示範各項服飾及商品</li><br>
					<li> 採用電子化經營模式，可輕易「貨比三家」購得價格合理且滿意之商品</li><br>
					<li> 傳統店家只能針對特定區域的消費者進行銷售，而電子商務可擴大其銷售範圍，佔有極大的優勢</li><br>
					<li> 由網友提供各面向的商品資訊等特色並可利用便捷的管道得知最新產品及訊息提供 24 小時全天候的服務，使購買商品較容易且不受到時間、地區限制</li>
				</ol>
			</div>
			<div class="e1"><p style="font-size:35px;font-weight:700;">效益</p>
				<div id="f1">
					<div id="f2"></div>
					<div id="f3"></div>
					<div id="f4"></div>
					<div id="f5"></div>
					<div id="f6"></div>
					<div id="f7"></div>
					<p class="eWord">消費者</p>
					<p class="eWord2">企業</p>
					<p class="eWord3">政府</p>
				</div>
			<div id="F2" style="-webkit-transition: all 1s;"></div>
			<div id="F3" style="-webkit-transition: all 1s;"></div>
			<div id="F1" style="-webkit-transition: all 1s;"></div>
			<div id="F" class="F"><p id="eWord4"class="eWord4">Click</p></div>
			<p id="ff1"class="">線上網路店家眾多、消費者容易搜尋相關搜尋資訊及直接線上訂購，可 節省購物時間與交通成本，簡單又便利。 </p>
			<p id="ff3"class="">電子商務因突破空間與時間的限制，成為企業十分重視的新通路，而電子商 務的運用不僅能幫助商家縮短新產品進入市場的時間，還可以提高新產品的曝光率，增加 商品的銷售額。 </p>
			<p id="ff2"class="">電子商務可以協助政府在網路上提供方便的服務，例如：網路報稅、網路繳 交罰鍰等，也可提高行政效率，降低政府部門的人事成本。 </p>
			</div>
			<div class="e1"><p style="font-size:35px;font-weight:700;">SWOT</p>
				<div id="b1"><p class="w">優勢</p><ul><li>有成本優勢，無須開設實體店舖</li><li>提供商品資訊的管道及優惠方法，可掌握了解顧客需求，更能吸引消費者的目光</li></ul></div>
				<div id="b2"><p class="w">劣勢</p><ul><li>獨特的商品，容易引起模仿跟抄襲</li><li>網購退換貨頻率較高</li><li>較多安全性問題及風險</li></ul></div>
				<div id="b3"><p class="w">機會</p><ul><li>可針對不同的消費者進行最適切的個人化的專業服務</li><li>有方便性及即時性，使得商品無時無刻都可下單</li></ul></div>
				<div id="b4"><p class="w">威脅</p><ul><li>網路商店進入門檻低，新賣家容易進入市場競爭</li><li>替代品銷售額增長及網路訊息流通性高，容易形成削價模式競爭</li></ul></div>
			</div>
		</div>
	</section>
	<section id="buyOrNot" >
		
		<div id="shopping" class="box1"><p id="word1">YES</p></div>
		  <div id="shop"class="box2"><p id="word2">NO</p></div>
		  <div id="shopping1" class=""><p id="ss1" class="s">親友介紹</p><p id="ss11" class="s">43%</p></div>
		  <div id="shopping2" class=""><p id="ss2" class="s">方便快捷</p><p id="ss22" class="s">36%</p></div>
		  <div id="shopping3" class=""><p id="ss3" class="s">較實體店面便宜</p><p id="ss33" class="s">30%</p></div>
		  <div id="shopping4" class=""><p id="ss4" class="s">其他</p><p id="ss44" class="s">9%</p></div>
		  <div id="shopping5" class=""><span id="ss55" class="s">&nbsp;&nbsp;98%</span><span id="ss5" class="s">&nbsp;滿意度主要原因:</span>
			<div id="min1" class=""><p id="ss6" class="s">準時到貨</p><p id="ss66" class="s">20%</p></div>
			<div id="min2" class=""><p id="ss7" class="s">品質符合期望</p><p id="ss77" class="s">32%</p></div>
			<div id="min3" class=""><p id="ss8" class="s">價格便宜</p><p id="ss88" class="s">50%</p></div>
		  </div>
		  <div id="shop1" class=""><p id="sp1" class="s">擔心個資安全</p><p id="sp11" class="s">30%</p></div>
		  <div id="shop2" class=""><p id="sp2" class="s">無品質保證</p><p id="sp22" class="s">22%</p></div>
		  <div id="shop3" class=""><p id="sp3" class="s">無需要</p><p id="sp33" class="s">15%</p></div>
		  <div id="shop4" class=""><p id="sp4" class="s">喜歡上街購物</p><p id="sp44" class="s">11%</p></div>
		  <div id="shop5" class=""><p id="sp5" class="s">上街購物方便</p><p id="sp55" class="s">9%</p></div>
		  <div id="shop6" class=""><p id="sp6" class="s">缺乏知識</p><p id="sp66" class="s">13%</p></div>
		  <p id="word4" class="word4">Why people shopping online or not?<p>
	</section>

	<script type="text/javascript">
	google.charts.load("current", {packages:["corechart"]});
	google.charts.setOnLoadCallback(drawChart);
	function drawChart() {
		var data = google.visualization.arrayToDataTable([
					["Element", "Density", { role: "style" } ],
					["中國", 72.7, "red"],
					["日本", 40.4, ""],
					["美國", 22.9, ""],
					["韓國", 12.8, ""]
			  ]);
		var view = new google.visualization.DataView(data);
		view.setColumns([0, 1,
			{ calc: "stringify",
			  sourceColumn: 1,
			  type: "string",
			  role: "annotation" },2]);
		var options = {
			width: 400,
			height: 200,
			bar: {groupWidth: "50%"},
			legend: { position: "none" },
		  };
		  var chart = new google.visualization.BarChart(document.getElementById("rank7"));
		  chart.draw(view, options);
		  
		var data2 = google.visualization.arrayToDataTable([
					["Element", "Density", { role: "style" } ],
					["淘寶/天貓", 79.2, "red"],
					["樂天賣場", 29.7, ""],
					["Amazon", 17.4, ""],
					]);
		var view = new google.visualization.DataView(data2);
		view.setColumns([0, 1,
			{ calc: "stringify",
			  sourceColumn: 1,
			  type: "string",
			  role: "annotation" },2]);
		var chart2 = new google.visualization.BarChart(document.getElementById("rank8"));
		  chart2.draw(view, options);
		  
		var data3 = google.visualization.arrayToDataTable([
					["Element", "Density", { role: "style" } ],
					["服飾配件", 51, "red"],
					["3C產品", 43.2, ""],
					["日常用品", 28.9, ""],
			  ]);
		var view = new google.visualization.DataView(data3);
		view.setColumns([0, 1,
			{ calc: "stringify",
			  sourceColumn: 1,
			  type: "string",
			  role: "annotation" },2]);
		var chart3 = new google.visualization.BarChart(document.getElementById("rank11_"));
		  chart3.draw(view, options);
		  
		var data4 = google.visualization.arrayToDataTable([
					["Element", "Density", { role: "style" } ],
					["入口網站", 45.3, "red"],
					["親友推薦", 34.1, ""],
					["Facebook", 25, ""],
					["部落客/網紅", 20.3, ""]
			  ]);
		var view = new google.visualization.DataView(data4);
		view.setColumns([0, 1,
			{ calc: "stringify",
			  sourceColumn: 1,
			  type: "string",
			  role: "annotation" },2]);
		var chart = new google.visualization.BarChart(document.getElementById("rank9"));
		  chart.draw(view, options);
		  
		var data = google.visualization.arrayToDataTable([
					["Element", "Density", { role: "style" } ],
					["價格實惠", 69, "red"],
					["種類多元", 42.2, ""],
					["折扣多/促銷頻繁", 29, ""]
			  ]);
		var view = new google.visualization.DataView(data);
		view.setColumns([0, 1,
			{ calc: "stringify",
			  sourceColumn: 1,
			  type: "string",
			  role: "annotation" },2]);
		var chart = new google.visualization.BarChart(document.getElementById("rank6"));
		  chart.draw(view, options);
		  
		var data = google.visualization.arrayToDataTable([
					["Element", "Density", { role: "style" } ],
					["自行購買", 72.9, "red"],
					["私人代購", 31.8, ""],
					["國內代購網站", 25.8, ""],
					]);
		var view = new google.visualization.DataView(data);
		view.setColumns([0, 1,
			{ calc: "stringify",
			  sourceColumn: 1,
			  type: "string",
			  role: "annotation" },2]);
		var chart = new google.visualization.BarChart(document.getElementById("rank10"));
		  chart.draw(view, options);
		  
		var data = google.visualization.arrayToDataTable([
			  ['Task', 'Hours per Day'],
			  ['阿里巴巴',26.6],
			  ['Amazon',13],
			  ['eBay',  4.5],
			  ['東京商城', 3.8],
			  ['樂天',1.5],
			  ['Apple',1.4],
			  ['Suning蘇寧',1.3],
			  ['小米商城',1],
			  ['DELL',0.9],
			  ['WALMART',0.8],
			  ['其他',54.8]
			]);

			var options = {
			  pieHole: 0.5,
			};

			var chart = new google.visualization.PieChart(document.getElementById('donutchart'));
			chart.draw(data, options);
		
	  }
	  
	  </script>
	<section id="Ranking">
		<p class="rWord2">Ranking</p>
		<div class="all1">
			<div class="rank2" id="" ><div id="rank123"><p class="rWord3">網購主力年齡層</p><p class="rWord4">36~55</p></div></div>
			<div class="rank" id="rank11" ><p class="rWord">獲取商品管道</p><div id="rank4"></div></div>
			<div class="rank" id="rank22" ><p class="rWord">B2C購物網站</p><div id="rank2"></div></div>
			<div class="rank" id="rank33" ><p class="rWord">網購支付方式</p><div id="rank1"></div></div>
			<div class="rank" id="rank44" ><p class="rWord">網購物流方式</p><div id="rank3"></div></div>
			<div class="rank" id="rank55" ><p class="rWord">C2C購物網站</p><div id="rank5"></div></div>
		</div>
		<br><br>
		<div class="all2">
			<div class="rank3" id="" ><div id="rank1234"><p class="rWord_3">跨境購物的消費者</p><p class="rWord_4">84.3%</p></div></div>
			<div class="rank4" id="rank66" ><div id="rank6"></div><p class="rWord5">跨境購物三大誘因</p></div>
			<div class="rank4" id="rank77" ><div id="rank7"></div><p class="rWord5">網友最常跨境購物的國家</p></div>
			<div class="rank4" id="rank88" ><div id="rank8"></div><p class="rWord5">網友最常跨境購物網站</p></div>
			<div class="rank4" id="rank99" ><div id="rank9"></div><p class="rWord5">訊息管道</p></div>
			<div class="rank4" id="rank100" ><div id="rank10"></div><p class="rWord5">消費者習慣</p></div>
			<div class="rank4" id="rank111" ><div id="rank11_"></div><p class="rWord5">購買商品類型</p></div>
		</div>
		<div id="gogo" >
			<div id="donutchart" style="width: 800px; height: 600px;border:"></div>
			<div id="view1"><a  href="https://www.1688.com/"><img class="ten2" src="assets/img/1.png" alt="阿里巴巴"></a></div>
			<div id="view2"><a href="https://www.amazon.com/"><img class="ten2" src="assets/img/2.png" alt="Amazon"></a></div>
			<div id="view3"><a href="https://www.ebay.com/"><img  class="ten2" src="assets/img/3.png" alt="eBay"></a></div>
			<div id="view4"><a href="http://www.jd.com/"><img class="ten2" src="assets/img/4.jpg" alt="東京商城"></a></div>
			<div id="view5"><a href="https://www.rakuten.com.tw/"><img class="ten2" src="assets/img/5.png" alt="樂天"></a></div>
			<p class="ten">十大電子商務市佔率</p>
		</div>
	</section>
		
		
		
	  
		
	  

	<script>	
	Modernizr.load({
		test: Modernizr.csstransforms3d && Modernizr.csstransitions,
		yep: ['assets/js/jquery-1.10.1.min.js', 'assets/js/jquery.hoverfold.js'],
		nope: '',
		callback: function(url, result, key) {
			if (url === 'assets/js/jquery.hoverfold.js') {
				$('#grid').hoverfold();
			}
		}
	});
	</script> 
	<!-- ===== Contact Us ===== -->
	<section id="contact">
	  <div class="container">
		<div class="row">
		  <div class="col-lg-12 text-center">
			<h2 class="section-heading" style="color:#3680C1">Contact Us</h2>
			<h3 class="section-subheading text-muted">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</h3>
		  </div>
		</div>
		<div class="row">
		  <div class="col-lg-12">
			<form action="#" method="post" name="sentMessage" id="contactForm" novalidate>
			  <div class="row">
				<div class="col-md-6">
				  <div class="form-group">
					<input type="text" class="form-control" placeholder="Your Name *" id="name" required>
					<p class="help-block text-danger"></p>
				  </div>
				  <div class="form-group">
					<input type="email" class="form-control" placeholder="Your Email *" id="email" required>
					<p class="help-block text-danger"></p>
				  </div>
				  <div class="form-group">
					<input type="tel" class="form-control" placeholder="Your Phone *" id="phone" required>
					<p class="help-block text-danger"></p>
				  </div>
				</div>
				<div class="col-md-6">
				  <div class="form-group">
					<textarea class="form-control" placeholder="Your Message *" id="message" required></textarea>
					<p class="help-block text-danger"></p>
				  </div>
				</div>
				<div class="clearfix"></div>
				<div class="col-lg-12 text-center">
				  <div id="success"></div>
				  <button type="submit" class="btn btn-primary">Send Message</button>
				</div>
			  </div>
			</form>
		  </div>
		</div>
	  </div>
	</section>
	<footer>
	  <div class="container">
		<div class="row">
		  <div class="col-md-4"></div>
		  <div class="col-md-4 col-md-offset-">
			<ul class="list-inline social-buttons">
			  <li><a href="#"><i class="fa fa-twitter"></i></a></li>
			  <li><a href="#"><i class="fa fa-facebook"></i></a></li>
			  <li><a href="#"><i class="fa fa-linkedin"></i></a></li>
			</ul>
		  </div>
		  <div class="col-md-4"></div>
		</div>
	  </div>
	  <br>
	  <div class="container">
		<div class="row">
		  <div class="col-md-3"></div>
		  <div class="col-md-6">
			<h3 style="color:#3680C1">Thank You For Visiting Our Studio</h3>
			<h3 style="color:#3680C1">Copyright &copy; 2016 All Rights Reserved</h3>
		  </div>
		  <div class="col-md-3"></div>
		</div>
	  </div>
	</footer>
	</body>
	</html>
```