# sriharsh01
CCExtractor-Web
<html>
	<head>
		<title>CCExtractor Dev.</title>
		<style type="text/css">
			body {
				margin: 0;
			}
			#front {

				height: 70%;

				width: 100%;

				background-color: #ec1f10;

				font-family: 'Montserrat', sans-serif;

				z-index: 0;

			}

			#front img {

				position: absolute;

				top: 20%;

				right: 0;

				height: 70%;

				width: 48%;

				animation: iment 2s;

				border-bottom-left-radius: 50px;

				border-bottom-right-radius: 50px;

				transition: 1s;


z-index: 0;

			}

			#front img:hover {

				border-bottom-right-radius: 0px;

				border-bottom-left-radius: 0pc;

				width: 52%;

				height: 92%;
				z-index: 1;

			}

			@keyframes iment {

				0% {

					top: 0;

					opacity: 0;

				}

			}

			#front h1 {

				position: absolute;

				left: 5%;

				animation: tent 2s;

				top: 7.7%;

				font-size: 7vw;

				color: white;

z-index: 0.5;

			}

			@keyframes tent {

				0% {

					left: -10%;

					opacity: 0;

				}

			}

			#front h2 {

				position: absolute;

				font-size: 5vw;

				left: 8%;

				color: white;

				top: 50%;

z-index: 0;

				animation: tents 2s;

			}

			@keyframes tents {

				0% {

					opacity: 0;

					left: -10%;

				}

			}
			#sec {
				padding-left: 10%;
				padding-right: 10%;
				background-color: #ffd088;
				color: #f7a552;
				height: 30%;
z-index: 0;
			}
			#sec h2 {
				position: absolute;
				font-size: 2vw;
				font-family: 'Montserrat', sans-serif;
				animation: tenter 2s;
			}
			@keyframes tenter {
				0% {
					transform: translate(0,180%);
					opacity: 0;
				}
			}
			#logo {
				position: fixed;
				left: 0;
				top: 0;
				width: 12%;
				height: 16%;
				transition: 1s;
z-index: 1;
			}
			#logo:hover {
				width: 18%;
				height: 24%;
			}
			
			#second {
				background-color: #f54d40;
				height: 70%;
				width: 100%;
z-index: 0;
			}
			.imgOut {
				position: absolute;
				transform:translate(0,30%);
				left: 0;
				opacity: 0;
				height: 60%;
				width: 50%;
			}
			.imgIn {
				position: absolute;
				transform:translate(0,30%);
				left: 0;
				animation: imner 2s;
				height: 60%;
				width: 50%;
				transition: 1s;
				border-bottom-left-radius: 50px;
z-index: 0;
				border-bottom-right-radius: 50px;
			}
			.imgIn:hover {
				border-bottom-left-radius: 0px;
				border-bottom-right-radius: 0px;
				width: 55%;
				height: 66%;
			}
			@keyframes imner {
				0% {
					opacity: 0;
					transform: translate(0,0);
				}
			}
			#second h1 {
				position: absolute;
				right: 20%;
				transform: translate(0,170%);
				font-size: 5vw;
z-index: 0;
				color: white;
				font-family: 'Montserrat', sans-serif;
			}
			.h1Out {
				position: absolute;
				right: 20%;
				opacity: 0;
				transform: translate(0,170%);
				font-size: 5vw;
				color: white;
				font-family: 'Montserrat', sans-serif;
			}
			.h1In {
				position: absolute;
				right: 20%;
				transform: translate(0,170%);
				font-size: 5vw;
z-index: 0;
				color: white;
				font-family: 'Montserrat', sans-serif;
				animation: hinner 2s;
			}
			@keyframes hinner {
				0% {
					opacity: 0;
					transform: translate(-100%,170%);
				}
			}
			#oversec {
				padding-left: 10%;
				padding-right: 10%;
				background-color: #ffd088;
				color: #f7a552;
z-index: 0;
				height: 30%;
			}
			.h2Out {
				position: absolute;
				font-size: 1.5vw;
				opacity: 0;
			}
			.h2In {
				position: absolute;
				font-size: 1.5vw;
				animation: henan 2s;
transform: translate(0,50%);
			}
			@keyframes henan {
				0% {
					opacity: 0;
					transform: translate(0,170%);
				}
			}
			#GCI {
				background-color: #f54d40;
				font-family: 'Montserrat', sans-serif;
				height: 70%;
				width: 100%;
z-index: 0;
			}
			.img2Out {
				position: absolute;
				transform:translate(0,50%);
				right: 25%;
				opacity: 0;
				left: 25%;
				height: 10%;
				width: 30%;
			}
			.img2In {
				position: absolute;
				transform:translate(0,35%);
				right: 25%;
				left: 25%;
				animation: imager 2s;
				height: 80%;
				width: 20%;
				border-bottom-left-radius: 50px;
				border-bottom-right-radius: 50px;
				transition: 1s;
			}
			.img2In:hover {
				border-bottom-right-radius: 0px;
				border-bottom-left-radius: 0px;
				height: 96%;
				width: 60%;
				left: 20%;
				right: 20%;
				transform: translate(0,20%);
			}
			@keyframes imager {
				0% {
					opacity: 0;
					transform: translate(0,0);
				}
			}
			.h12Out {
				position: absolute;
				left: 25%;
				right: 25%;
				width: 50%;
				transform: translate(0,70%);
				font-size: 5vw;
				opacity: 0;
				color: white;
				font-family: 'Montserrat', sans-serif;
			}
			.h12In {
				position: absolute;
				left: 25%;
				animation: header 2s;
z-index: 0;
				right: 25%;
				width: 50%;
				text-align: center;
				transform: translate(0,70%);
				font-size: 5vw;
				color: white;
				font-family: 'Montserrat', sans-serif;
			}
			@keyframes header {
				0% {
					opacity: 0;
					transform: translate(0,200%);
				}
			}
			.p1Out {
				color:white;
				position: absolute;
				margin: 4%;
				left: 0;
				opacity: 0;
				width: 20%;
z-index: 0;
				transform: translate(0,50%);
				font-size: 1.2vw;
			}
			.p1In {
				color:white;
				position: absolute;
				margin: 4%;
				left: 0;
z-index: 0;
				width: 20%;
				animation: para 2s;
				transform: translate(0,80%);
				font-size: 1.2vw;
			}
			@keyframes para {
				0% {
					opacity: 0;
					transform: translate(100%,50%);
				}
			}
			.p2Out {
				position: absolute;
				margin: 4%;
				right:0;
				width: 20%;
				opacity: 0;
				color: white;
				transform: translate(0,50%);
				font-size: 1.2vw;
			}
			.p2In {
				position: absolute;
				margin: 4%;
				right:0;
				width: 20%;
z-index: 0;
				color: white;
				transform: translate(0,50%);
				font-size: 1.2vw;
				animation: paragraph 2s;
			}
			@keyframes paragraph {
				0% {
					opacity: 0;
					transform: translate(-100%,50%);
				}
			}
			#document {

				padding-left: 10%;

				padding-right: 10%;

				background-color: #ffd088;

				color: #f7a552;

				height: 60%;
				padding-top: 17%;

z-index: 0;

			}

			.h22Out {

				position: absolute;

				font-size: 1.5vw;

				left: 5%;

				opacity: 0;

				width: 50%;

				

			}

			.h22Out span {

				font-size: 3.5vw;

				font-family: 'Montserrat', sans-serif;

			}

			.h22In {

				position: absolute;

				font-size: 1.5vw;

				left: 5%;

z-index: 0;

				animation: headers 2s;

				width: 40%;

				

			}

			@keyframes headers {

				0% {

					opacity: 0;

					transform: translate(0,0);

				}

			}

			.h22In span {

				font-size: 3.5vw;

				font-family: 'Montserrat', sans-serif;

z-index: 0;

			}

			.h23Out {

				position: absolute;

				font-size: 1.5vw;

				right: 5%;

				opacity: 0;

				width: 40%;

				

			}

			.h23Out span {

				font-size: 3.5vw;

				font-family: 'Montserrat', sans-serif;

			}

			.h23In {

				position: absolute;

				font-size: 1.5vw;

				right: 5%;

				animation: heft 2s;

z-index: 0;

				width: 40%;

				

			}

			.h23In span {

				font-size: 3.5vw;

				font-family: 'Montserrat', sans-serif;

			}

			@keyframes heft {

				0% {

					opacity: 0;

					transform: translate(0,0);

				}

			}
			.btn {

				transition: 1s;

				border: 1px solid rgb(41, 233, 16);

				color: #f7a552;

				padding: 1%;

z-index: 0;

				text-decoration: none;

			}

			.btn:hover {

				border-bottom-right-radius: 25px;

				border-top-left-radius: 25px;

				background-color: white;

				color: black;

			}
		</style>
		<script type="text/javascript">
			var x = 1;
			function load1() {
				if (x == 1) {
					document.getElementById('img2').classList.toggle('imgOut');
					document.getElementById('img2').classList.toggle('imgIn');
					document.getElementById('h12').classList.toggle('h1Out');
					document.getElementById('h12').classList.toggle('h1In');
					document.getElementById('h23').classList.toggle('h2Out');
					document.getElementById('h23').classList.toggle('h2In');
					x = 0;
				}
			}
			var y = 1;
			function load3() {
				if (y == 1) {
					document.getElementById('img3').classList.toggle('img2Out');
					document.getElementById('img3').classList.toggle('img2In');
					document.getElementById('h13').classList.toggle('h12Out');
					document.getElementById('h13').classList.toggle('h12In');
					document.getElementById('p1').classList.toggle('p1Out');
					document.getElementById('p1').classList.toggle('p1In');
					document.getElementById('p2').classList.toggle('p2Out');
					document.getElementById('p2').classList.toggle('p2In');
					y = 0;
				}
			}
			var a = 1;
			function load4() {
				if (a == 1) {
					document.getElementById('h21').classList.toggle('h22Out');
					document.getElementById('h21').classList.toggle('h22In');
					document.getElementById('h22').classList.toggle('h23Out');
					document.getElementById('h22').classList.toggle('h23In');
					a = 0;
				}
			}
		</script>
	</head>
	<body>
		<div id="front">
			<img src="logo.png">
			<h1>CCExtractor Development</h1>
			<h2>For GoogleSummerOfCode</h2>
		</div>
		<div id="sec">
			<h2 align="left">
				CCExtractor is a tool to extract subtitles/closed captions from video streams. It's used by universities for 

research purposes, as well by regular users that want to extract captions from various formats.
			</h2>
		</div>
		<img id="logo" src="logo.png">
		<div id="second" onmouseover="load1()">
			<img id="img2" src="i1.png" class="imgOut">
			<h1 id="h12" class="h1Out">About us</h1>
		</div>
		<div id="oversec">
			<h2 align="right" id="h23" class="h2Out">
				CCExtractor Development is an informal (meaning we're not incorporated anywhere) organization that exists 

to coordinate the development efforts of the volunteers that contribute to the software and to manage our participation in specific events such as 

Google Summer of Code and Code-In. 
			</h2>
		</div>
		<div id="GCI" onmouseover="load3()">
			<img src="logo2.png" id="img3" class="img2Out">
			<h1 id="h13" align="center" class="h12Out">GoogleSummerOfCode</h1>
			<p id="p1" align="center" class="p1Out">
				We are a small org, which means that your contribution will have a large impact. It's not going to mean a 0.5% 

improvement on a big project - it's going to be more than 10% on a medium size one. If you like challenges and want a chance to shine this is your 

place. 
			</p>
			<p id="p2" align="center" class="p2Out">
				We have *mentors all over the world* (North America, Europe, Asia and Australia), so time zones are never a 

problem. Our main channel of communication is a Slack channel to which everyone is welcome. We expect all accepted students to be available on 

Slack very often, even if you don't need to talk to your mentor. This will help you ask questions when necessary, and you might be able to help others 

out as well while working on your project. 
			</p>
        </div>
        <div id="document" onmouseover="load4()">
            
			<h2 id="h21" align="center" class="h22Out">
				<span>Know more</span><br>
				<br>To know more about GSoC with CCExtractor Development click here:<br>
				<a class="btn" href="">Know 

more</a>
			</h2>
			<h2 id="h22" align="center" class="h23Out">
				<span>GCI</span><br>
				Also check out our participation in Google Code In<br>
				<a class="btn" href="https://www.ccextractor.org/public:codein:google_code-in_2018">CCExtractor GCI</a>
			</h2>
		</div>
		
	</body>
</html>
