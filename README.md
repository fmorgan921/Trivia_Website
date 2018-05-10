# Trivia_Website / html for sports trivia website

<html>
<header>
	
</header>
<style>
.blue-text {
	color: blue;
}

.wide-image {
	width: 10px
	height: 10px;
}

.hero-image {
	background-image: url(https://alumni.uga.edu/wp-content/uploads/dallas-LED-Lighted-Skyline-1500x500.jpg);
	height: 30%;
	background-position: center;
	background-size: cover;
	position: relative;
	border-top: 10px;
	border-right: 10px;
	border-bottom: 10px;
	border-left: 10px;
	border-style: ridge;
	border-color: blue;
}

.hero-text {
	text-align: center;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	color: white;
}
.large-text {
	font-size: 50px;
}

@font-face {
	font-family: "cowboysFont";
	src: url("file:<Macinstosh HD:/Users/Frank/Library/Fonts/Cowboys.ttf") format("truetype");
	font-weight: normal;
	font-style: normal;
}

.cowboyLetters {
	font-family: "cowboysFont"
}

h1 {
	font-family: cowboysFont;
}

p {
	font-size: 16px;
}

.thick-blue-border {
	border-color: blue;
	border-width: 10px;
	border-style: solid;
	border-radius: 50%;
}

.smaller-image {
	width: 70px;
}
</style>

<body>
<div class="hero-image">
	<div class="hero-text">
		<h1>Welcome to DFW Sports Trivia</h1>
		<p>Click your favorite team to get started</p>
	</div>
</div>

<h1>DFW Sports Trivia</h1>
<p>Are you ready to test your knowledge of DFW sports? Click your favorite team below!</p>

<div>
	<ul style="list-style-type: none;">
		<li><input type="image" src="https://i1.wp.com/defpen.com/wp-content/uploads/2017/06/dirk-nowitzki.jpg" name="cowboysButton" class="wide-image"></li>
		<li><input type="image" src="https://s3.amazonaws.com/pq-imgs/images/quizzes/texas-rangers-logo-14462.jpg" name="rangersButton" class="smaller-image">
		<li><input type="image" src="http://www.hockeydb.com/ihdb/logos/nhl--dallas_stars_2013-14a.gif" name="starsButton" class="smaller-image"></li>
		<li><input type="image" src="https://seeklogo.com/images/D/dallas-mavericks-logo-BAA5E9D070-seeklogo.com.png" name="mavsButton" class="smaller-image"></li>
	</ul>
	<ul style="list-style-type: none;">
		<li class="large-text"><a href="#"><img class="smaller-image" alt="Cowboys logo" src="http://1000logos.net/wp-content/uploads/2016/12/Dallas-Cowboys-Logo.png"></a>Dallas Cowboys</li>
		<li class="large-text"><a href="#"><img class="smaller-image" alt="Rangers logo" src="https://s3.amazonaws.com/pq-imgs/images/quizzes/texas-rangers-logo-14462.jpg"></a>Texas Rangers</li>
		<li class="large-text"><a href="#"><img class="smaller-image" alt="Stars logo" src="http://www.hockeydb.com/ihdb/logos/nhl--dallas_stars_2013-14a.gif"></a>
		Dallas Stars</li>
		<li class="large-text"><a href="#"><img class="smaller-image" alt="Mavs logo" src="https://seeklogo.com/images/D/dallas-mavericks-logo-BAA5E9D070-seeklogo.com.png"></a>Dallas Mavericks</li>
	</ul>
</div>
</body>
</html>
