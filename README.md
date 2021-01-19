<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap" rel="stylesheet">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Kaushan+Script&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
	<script src="https://cdn.jsdelivr.net/gh/cferdinandi/smooth-scroll/dist/smooth-scroll.polyfills.min.js"></script>
		<title>Html And Css Project</title>

<style type="text/css">
*{
margin:0;
padding:0;
font-family: 'Poppins', sans-serif;

}
#banner{
background: linear-gradient(rgba(0,0,0,0.5),#009688),url("/storage/emulated/0/Download/Barber_Shop_img (1) (1)/Barber_Shop_img/banner.jpg");
background-size:cover;
background-position:center;
height:100vh;

}

.logo{
width:140px;
position:absolute;
top:4%;
left:10%;

}
.banner-text{
text-align:center;
color:#fff;
padding-top:180px;

}
.banner-text h1{
font-size:130px;
font-family: 'Kaushan Script', cursive;

}
.banner-text p{
font-size:20px;
font-style:italic;

}
.banner-btn{
margin:70px auto 0;

}
.banner-btn a{
width:150px;
text-decoration:none;
display:inline-block;
margin:0 10px;
padding:12px 0;
color:#fff;
border:.5px solid #fff;
position:relative;
z-index:1;
transition:color 0.5s;

}
.banner-btn a span{
width:0%;
height:100%;
position:absolute;
top:0;
left:0;
background:#fff;
z-index:-1;
transition:0.5s;

}
.banner-btn a:hover span{
width:100%;

}
.banner-btn a:hover{
color:#000;

}
#sideNav{
width:250px;
height:100vh;
top:0;
right:-250px;
position:fixed;
background:#009688;
z-index:2;
transition:0.5s;

}
nav ul li{
list-style:none;
margin:50px 20px;

}
nav ul li a{
text-decoration:none;
color:#fff;

}
#menuBtn{
width:50px;
height:50px;
background:#009688;
text-align:center;
position:fixed;
right:30px;
top:20px;
border-radius:3px;
z-index:3;
cursor:pointer;

}
#menuBtn img{
width:20px;
margin-top:15px;

}
@media screen and (max-width:770px){
	.banner-text h1{
		font-size:44px;
	}
	.banner-btn a{
		display:block;
		margin:20px auto;
	}

}

#feature{
width:100%;
padding:70px 0;

}
.title-text{
text-align:center;
padding-bottom:70px;

}
.title-text p{
margin:auto;
color:#009688;
font-weight:bold;
font-size:25px;
position:relative;
z-index:1;
display:inline-block;

}
.title-text p::after{
width:50px;
content:'';
height:35px;
background:linear-gradient(#019587,#fff);
position:absolute;
top:-20px;
left:0;
z-index:-1;
transform:rotete(10deg);
border-top-left-radius:35px;
border-bottom-right-radius:35px;

}
.title-text h1{
font-size:50px;

}

.feature-box{
width:80%;
display:flex;
flex-wrap:wrap;
margin:auto;
align-items:center;
text-align:center;

}
.features{
flex-basis:50%;

}
.features-img{
flex-basis:50%;
margin:auto;

}
.features-img img{
width:70%;
border-radius:10px;

}
.features h1{
text-align:left;
margin-bottom:10px;
font-weight:100;
color:#009688;

}
.features-desc{
display:flex;
align-items:center;
margin-bottom:40px;

}
.features-icon .fa{
width:50px; 
height:50px;
color:#009688;
font-size:30px;
line-height:50px;
border-radius:8px;
border:1px solid #009688;

}
.feature-text p{
padding:0 20px;
text-align:initial;

}
@media screen and (max-width: 770px){
	.title-text h1{
		font-size:35px;
	}
	.features{
		flex-basis:100%;
	}
	.features-img{
		flex-basis:100%
	}

}

/*---Service---*/

#service{
width:100%;
padding:70px 0;
background:#efefef;

}
.service-box{
width:80%;
dosplay:flex;
flex-wrap:wrap;
justify-content:space-around;
margin:auto;

}
.single-service{
flex-basis:40%;
text-align:center;
border-radius:7px;
margin-bottom:20px;
color:#fff;
position:relative;

}
.single-service img{
width:100%;
border-radius:7px;

}
.overlay{
width:100%;
height:100%;
position:absolute;
top:0;
border-radius:7px;
cursor:pointer;
background:linear-gradient(rgba(0,0,0,0.5),#009688);
opacity:0;
transition:1s;

}
.single-service:hover .overlay{
opacity:1;

}
.service-desc{
width:80%;
position:absolute;
bottom:0;
opacity:0;
left:50%;
transform:translateX(-50%);
transition:1s;

}
hr{
background:#fff;
height:2px;
border:0;
margin:15px auto;
width:60%;

}
.service-desc p{
font-size:14px;

}
.single-service:hover .service-desc{
bottom:40%;
opacity:1;

}

/*--Testimontal Start--*/

#testimonial{
width:100%;
padding:70px 0;

}
.testimonial-row{
width:80%;
margin:auto;
display:flex;
justify-content:space-between;
alogn-items:flex-start;
flex-wrap:wrap;

}
.testimonial-col{
flex-basis:28%;
padding:10px;
margin-bottom:30px;
border-radius:5px;
box-shadow:0 10px 20px 3px #00968814;
cursor:pointer;
transition:transform .5s;

}
.testimonial-col p{
font-size:14px;

}
.user{
display:flex;
align-items:center;
margin:20px 0;

}
.user img{
width:40px;
margin-right:20px;
border-radius:3px;

}
.user-info .fab{
margin-left:10px;
color:#27c0ff;
font-size:20px;

}
.user-info small{
color:#009688;

}
.testimonial-col:hover{
transform:translateY(-7px);

}
@media screen and (max-width: 770px){
	.testimonial-col{
		flex-basis:100%;
	
	}

}

/*----Footer Start----*/

#footer{
padding:100px 0 20px;
background:#efefef;
position:relative;

}
.footer-row{
width:80%;
margin:0 auto;
display:flex;
justify-content:space-between;
flex-wrap:wrap;

}
.footer-left, .footer-right{
flex-basis:45%;
padding:10px;
margin-bottom:20px;

} 
.footer-right{
text-align:right;

}
.footer-row h1{
margin:10px 0;

}
.footer-row p{
line-height:35px;

}
.footer-left i{
font-size:20px;
color:#009688;
margin:10px;

}
.footer-right i{
font-size:20px;
color:#009688;
margin:10px;

}
.footer-img{
max-width:370px;
opacity:0.1;
position:absolute;
left:50%;
top:35%;
transform:translate(-50%,-50%);

}
.social-links{
text-align:center;

}
.social-links .fab{
height:40px;
width:40px;
line-height:40px;
font-size:20px;
border:1px solid #009688;
margin:40px 5px 0;
color:#009688;
cursor:pointer;
transition:0.5s;

}
.social-links i:hover{
background:#009688;
color:#fff;
transform:translateY(-7px);

}
.social-links p{
font-size:12px;
margin-top:20px;
background:black;
color:#fff;
padding:15px;

}
@media screen and (max-width: 770px){
	.footer-left, .footer-right{
		flex-basis:100%;
		font-size:14px;
	
	}
	.footer-img{
		top:25%;
	
	}

}




</style>

</head>
<body>

<section id="banner">
	<img class="logo" src="/storage/emulated/0/Download/Barber_Shop_img (1)/Barber_Shop_img/logo.png">
	<div class="banner-text">
		<h1>Hair Studio</h1>
		<p>Style Your Hair Is Style Your Life</p>
		<div class="banner-btn">
			<a href="#" ><span></span>Find Out</a>
			<a href="#" ><span></span>Read More</a>
		</div>
	</div>
</section>

<!--SideNav Started-->

<div id="sideNav">
	<nav>
		<ul>
			<li>
				<a href="#banner">HOME</a>
			</li>
			<li>
				<a href="#feature">FEATURES</a>
			</li>
			<li>
				<a href="#service">SERVICES</a>
			</li>
			<li>
				<a href="#testimonial">TESTIMONIAL</a>
			</li>
			<li>
				<a href="#footer">MEET US</a>
			</li>
		</ul>
	</nav>
</div>
<div id="menuBtn">
	<img id="menu" src="/storage/emulated/0/Download/Barber_Shop_img (1)/Barber_Shop_img/menu.png">
</div>

<!--Feature Started-->
<section id="feature">
	<div class="title-text">
		<p>Feature</p>
		<h1>Why Choose Us</h1>
	</div>
	<div class="feature-box">
		<div class="features">
			<h1>Experienced Staff</h1>
			<div class="features-desc">
				<div class="features-icon">
					<i class="fa fa-shield"></i>
				</div>
				<div class="features-text">
					<p>Xiaomi Mi 11 gets an A+ from DisplayMate, with perfect color accuracy and impressive brightness</p>
				</div>
			</div>
			<h1>Pre Booking Online</h1>
			<div class="features-desc">
				<div class="features-icon">
					<i class="fa fa-check"></i>
				</div>
				<div class="features-text">
					<p>Xiaomi Mi 11 gets an A+ from DisplayMate, with perfect color accuracy and impressive brightness</p>
				</div>
			</div>
			<h1>Affordable Cost</h1>
			<div class="features-desc">
				<div class="features-icon">
					<i class="fa fa-rupee-sign"></i>
				</div>
				<div class="features-text">
					<p>Xiaomi Mi 11 gets an A+ from DisplayMate, with perfect color accuracy and impressive brightness</p>
				</div>
			</div>
		</div>
		<div class="features-img">
			<img src="/storage/emulated/0/Download/Barber_Shop_img (1) (1)/Barber_Shop_img/barber-man.jpg">
		</div>
	</div>
</section>

<!--Services Start-->

<section id="service">
	<div class="title-text">
		<p>SERVICES</p>
		<h1>We Provide Better</h1>
	</div>
	<div class="service-box">
		<div class="single-service">
			<img src="/storage/emulated/0/Download/Barber_Shop_img (1)/Barber_Shop_img/pic-1.jpg">
			<div class="overlay"></div>
			<div class="service-desc"> 
				<h3>Heir Styling</h3>
				<hr>
				<p>My name is Bayazid Bustami.My country name is Bangladesh.I love my work.I am a student and web designer.</p>
			</div>
		</div>
		<div class="single-service">
			<img src="/storage/emulated/0/Download/Barber_Shop_img (1)/Barber_Shop_img/pic-4.jpg">
			<div class="overlay"></div>
			<div class="service-desc"> 
				<h3>Beard Trim</h3>
				<hr>
				<p>My name is Bayazid Bustami.My country name is Bangladesh.I love my work.I am a student and web designer.</p>
			</div>
		</div>
		<div class="single-service">
			<img src="/storage/emulated/0/Download/Barber_Shop_img (1)/Barber_Shop_img/pic-2.jpg">
			<div class="overlay"></div>
			<div class="service-desc"> 
				<h3>Heir Cut</h3>
				<hr>
				<p>My name is Bayazid Bustami.My country name is Bangladesh.I love my work.I am a student and web designer.</p>
			</div>
		</div>
		<div class="single-service">
			<img src="/storage/emulated/0/Download/Barber_Shop_img (1)/Barber_Shop_img/pic-3.jpg">
			<div class="overlay"></div>
			<div class="service-desc"> 
				<h3>Bread Sahpoo</h3>
				<hr>
				<p>My name is Bayazid Bustami.My country name is Bangladesh.I love my work.I am a student and web designer.</p>
			</div>
		</div>
	</div>
</section>

<!--Testimonial Start-->

<section id="testimonial">
	<div class="title-text">
		<p>TESTIMONIAL</p>
		<h1>What Client Says</h1>
	</div>
	<div class="testimonial-row">
		<div class="testimonial-col">
			<div class="user">
				<img src="/storage/emulated/0/Download/Barber_Shop_img (1)/Barber_Shop_img/img-1.jpg">
				<div class="user-info">
					<h4>KEN NORMEN<i class="fab fa-twitter"></i></h4>
					<small>@kennormen</small>
				</div>
			</div>
			<p>The on-screen camera technology is one of the latest tech in the smartphone industry. In fact, this technology is not quite ready for use and there are still some obstacles to scale through. The first commercial device with this technology is the ZTE Axon 20 5G. However, there are numerous questions regarding the performance of the camera. The Axonn 20 5G front camera output is somewhat disappointing. South Korean manufacturer, Samsung has been working on this technology.</p>
		</div>
		<div class="testimonial-col">
			<div class="user">
				<img src="/storage/emulated/0/Download/Barber_Shop_img (1) (1)/Barber_Shop_img/img-2.jpg">
				<div class="user-info">
					<h4>Liara Karian<i class="fab fa-twitter"></i></h4>
					<small>@liarakarian</small>
				</div>
			</div>
			<p>The on-screen camera technology is one of the latest tech in the smartphone industry. In fact, this technology is not quite ready for use and there are still some obstacles to scale through. The first commercial device with this technology is the ZTE Axon 20 5G. However, there are numerous questions regarding the performance of the camera. The Axonn 20 5G front camera output is somewhat disappointing. South Korean manufacturer, Samsung has been working on this technology.</p>
		</div>
		<div class="testimonial-col">
			<div class="user">
				<img src="/storage/emulated/0/Download/Barber_Shop_img (1) (1)/Barber_Shop_img/img-3.jpg">
				<div class="user-info">
					<h4>Ricky Danial<i class="fab fa-twitter"></i></h4>
					<small>@kennormen</small>
				</div>
			</div>
			<p>The on-screen camera technology is one of the latest tech in the smartphone industry. In fact, this technology is not quite ready for use and there are still some obstacles to scale through. The first commercial device with this technology is the ZTE Axon 20 5G. However, there are numerous questions regarding the performance of the camera. The Axonn 20 5G front camera output is somewhat disappointing. South Korean manufacturer, Samsung has been working on this technology.</p>
		</div>
	</div>
</section>

<!---Footer Section Start--->

<section id="footer">
	<img class="footer-img" src="/storage/emulated/0/Download/Barber_Shop_img (1) (1)/Barber_Shop_img/footer-img.png">
	<div class="title-text">
		<p>CONTACT</p>
		<h1>Visit Shop Today</h1>
	</div>
	<div class="footer-row">
		<div class="footer-left">
			<h1>Opening Hours</h1>
			<p><i class="fas fa-clock"></i>Monday to Friday - 9am to 9pm</p>
			<p><i class="fas fa-clock"></i>Saturday and Sunday - 8am to 11pm</p>
		</div>
		<div class="footer-right">
			<h1>Get In Touch</h1>
			<p>Phulpur,Mymensing<i class="fa fa-map-marker"></i></p>
			<p>bayazid22333@gmail.com<i class="fas fa-envelope"></i></p>
			<p>+8801888369870<i class="fa fa-phone"></i></p>
		</div>
	</div>
	<div class="social-links">
		<i class="fab fa-facebook"></i>
		<i class="fab fa-instagram"></i>
		<i class="fab fa-twitter"></i>
		<i class="fab fa-youtube"></i>
		<p>© Copyright By Freelancer Bayazid</p>
	</div>
</section>






<script type="text/javascript">
var menuBtn=document.getElementById("menuBtn")
var sideNav=document.getElementById("sideNav")
var menu=document.getElementById("menu")

sideNav.style.right = "-250px";

menuBtn.onclick=function(){
	if(sideNav.style.right == "-250px"){
		sideNav.style.right = "0";
		menu.src = "/storage/emulated/0/Download/Barber_Shop_img (1)/Barber_Shop_img/close.png";
	}else{
		sideNav.style.right = "-250px";
		menu.src = "/storage/emulated/0/Download/Barber_Shop_img (1) (1)/Barber_Shop_img/menu.png";
	}

}

var scroll = new SmoothScroll('a[href*="#"]', {
	speed:1000,
	speedAsDuration: true
});


</script>


</body>
</html>
