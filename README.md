<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>July L. Bugador</title>
	</head>

	<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lexend+Deca:wght@100..900&family=Lexend+Giga:wght@100..900&family=Roboto+Mono:ital,wght@0,100..700;1,100..700&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lexend+Giga:wght@100..900&family=Roboto+Mono:ital,wght@0,100..700;1,100..700&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Staatliches&display=swap');
		 body{
			background-image: url('bg.jpg');	
			background-size: cover;
			font-family: "Poppins", monospace;
			padding: 0;
			margin: 0;
			height: 100vh;
			width: auto;
		}
		.layout{
			display:flex;	
			height:100vh;
			flex-direction: column;
		}
		nav{
			padding-top:10px;
			padding-bottom:10px;
			display:flex;
			background-color:  	rgba(80, 50, 80, .7);
			justify-content: space-between;
		}
		nav div{
			display:flex
		}
		.v1{
			border-left: 2px solid white;
			height: auto;
			margin-left: 5px;
			margin-right: 5px;
		}
		nav a{
			color: white;
			font-size: 1.2rem;
			text-decoration: none;
			padding:3px;
			margin-left: 5px;
			margin-right: 5px;
			transition: 0.3s ease;
		}
		nav a:hover{	
			border-radius:3px;
			background: rgba(146, 168, 255,.2);
		}
		.main{
			flex:1;
			font-family: "Roboto Mono", monospace;	
			display:flex;
			justify-content: center;
			align-items: center;
			padding:5rem;
		}
		.main h1{
			font-size: 2rem;
			font-weight: 1000;
			color: white;
		}

		.img{
			width:350px;
			height:350px;
			background-image: url('idpic.jpg');
			background-size: cover;
		}

		.logo{
			font-family: "Staatliches", sans-serif;
			font-weight: 400;
			font-style: normal;
			font-size:1.5rem;
			margin-left: 2rem;
		}

		.links{
			margin-right: 2rem;
		}
	</style>
	<body>
		<div class="layout">
			<nav>
				<div>
					<a class="logo" href="https://julybugador.github.io/Intro-to-Comp-Finals/">JULY ENTERPRISE</a>
				</div>
				<div class="links">
					<a href="https://julybulgador.github.io/Intro-to-Comp-Finals/cur.html">Curriculum</a>
					<a href="https://julybugador.github.io/Intro-to-Comp-Finals/cv.html">Resume</a>
					<div class="v1"/>	
					<a href="https://julybugador.github.io/Intro-to-Comp-Finals/login.html">Login</a>
					<a href="https://julybugador.github.io/Intro-to-Comp-Finals/signup.html">Sign up</a>
				</div>
			</nav>
			<div class="main">
				<div class="moto"> 
				<h1>Precision in every line</h1>
				<h1>Innovation in every design.</h1>	
				</div>
				<div class="img"></div>
			</div>
		</div>
	</body>
</html>
