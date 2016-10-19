
# [목차이동](https://github.com/Guide-Line/effect#TOC)

## <a name='빛효과'>빛효과</a>

```javascript

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=euc-kr" />
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
<meta name="viewport" content="user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, width=device-width"/>


<script type="text/javascript" src="http://script.auction.co.kr/common/jquery.js"></script>

<title>옥션</title>
<style>
	*{padding: 0; margin:0; border: 0;}
	.rel{position: relative; width:100%;}
	
	#p_wrapper{position:relative; width:100%; line-height: 0px; max-width: 640px; margin:0 auto;}
	#p_wrapper img{vertical-align: top; line-height: 0px;}
	.light{position: absolute; left: 5%; top:5%; display: none;}
	
</style>
<script>

	$(document).ready(function(){
		function lightFun(){
			$('.light').delay(1500).fadeIn(200, function(){
				$(this).fadeOut(200 , function(){
					
				})
			});
		}
		lightFun(); // 1.5초뒤에 실행
		setTimeout(lightFun, 5000); // 5초뒤 실행 
		setTimeout(lightFun, 14000); // 14 초뒤 실행
	})

</script>
</head>

<body>
	
	<div id="p_wrapper">
	
			<div class="light">
				<img src="images/light.png" alt=""/>
			</div>
			
			<img src="images/bg.jpg" alt=""/>
	
		
	</div>
</body>
</html>

```	



![Alt text](img/light.jpg) 