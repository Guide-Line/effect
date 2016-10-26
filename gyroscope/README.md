
# [목차이동](https://github.com/Guide-Line/effect#TOC)

## <a name='휴대폰 기울기 효과 '>휴대폰 기울기 효과</a> 

<!-- ![Alt text](img/light.jpg)  -->


```javascript

<!DOCTYPE html>
<html lang="ko">
<head>
	<meta charset="euc-kr">
	<title>옥션 - test</title>
	<meta name="viewport" content="user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, width=device-width"/>
	<meta http-equiv="cleartype" content="on"/>
	<style>
		*{margin:0;padding:0;}
		img{border:0;}
		li{list-style:none;}
		html{overflow:scroll}
		#p_wrapper{max-width:640px;margin:0 auto;}
		#p_wrapper img{width:100%;vertical-align:top;}

		.visual{position:relative;width:100%;overflow:hidden;}
		.visual  h2{position:absolute;top:0;left:0;width:100%;text-align:center;z-index:10;}
		.visual .object{position:relative;overflow:hidden;opacity:0;}
		.visual .object h3{position:relative;width:100%;text-align:center;z-index:20;}
		.visual .object #rooms_img{position:absolute;left:-9%;top:-8%;width:118%;height:100%;z-index:5;}
		.visual .object #rooms_img .px_layer{width:100%;height:100%;}
	</style>
	<script type="text/javascript" src="http://script.auction.co.kr/common/jquery.js"></script>
	<link rel="stylesheet" href="http://eventimg.auction.co.kr/md/auction/08405BF42E/swiper.min.css">
	<script type="text/javascript" src="http://eventimg.auction.co.kr/md/auction/04D25F0304/jquery.easing-1.3.min.js"></script>
	<script src="http://eventimg.auction.co.kr/md/auction/08405BF42E/swiper.min.js"></script>
	<script src="http://eventimg.auction.co.kr/md/auction/08B909122F/jquery.parallax.js"></script>
	
	<script type="text/javascript">
		$(document).ready(function(){
			$('.visual').parallax();
			$(".object").animate({opacity:1},100);
		});

		
	</script>
</head>
<body>

	<div id="p_wrapper">
		<div class="visual">
			<div id="obj-mask">

				<div class="object">
					<!-- 타이틀이미지 -->
					<h3><img src="http://eventimg.auction.co.kr/md/auction/08B909122F/m_room06_tit.png" class="px_layer" data-depth="0.0" alt="" /></h3>
					<div id="rooms_img">
						<div class="px_layer" data-depth="0.35">
							<!-- 큰이미지 -->
							<p><img src="http://eventimg.auction.co.kr/md/auction/08B909122F/m_ioi_room_06_01.jpg" alt="" /></p>
						</div>
					</div>
					<!-- 실제배경사이즈 -->
					<p><img src="http://eventimg.auction.co.kr/md/auction/08B909122F/m_bg_room.png" class="bg_room" alt="" /></p>
				</div>
			</div>
		</div>

		<div id="p_container">
			
		
		</div>

	</div>

</body>
</html>

```	



