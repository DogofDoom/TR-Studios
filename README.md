<!DOCTYPE HTML>
<html>
	<head>
		<title>DogofDoom's Projekt</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<!--[if lte IE 8]><script src="assets/js/ie/html5shiv.js"></script><![endif]-->
		<link rel="stylesheet" href="assets/css/main.css" />
		<!--[if lte IE 9]><link rel="stylesheet" href="assets/css/ie9.css" /><![endif]-->
		<!--[if lte IE 8]><link rel="stylesheet" href="assets/css/ie8.css" /><![endif]-->
<script src="https://cdn.jsdelivr.net/web-animations/latest/web-animations.min.js">
  function animiere() { 
    var ladebalken = document.getElementById('ladebalken');
    ladebalken.animate([{
      width: '1em',
      background: 'green'
      }, {
      width: '20em',
      background: 'lime'
      }
      ], {
      duration: 2000,
      iterations: 1,
      fill: 'forwards'
    });
  }
var request = new XMLHttpRequest();
request.open("GET","daten.txt");
request.setRequestHeader("X-Test","test1");
request.setRequestHeader("X-Test","test2"); request.addEventListener('load', function(event) {
   if (request.status >= 200 && request.status < 300) {
      console.log(request.responseText);
   } else {
      console.warn(request.statusText, request.responseText);
   }
});
request.send();
</script>
<meta name="keywords" content="Hier kommen ein paar Keywords hin">
<meta name="description" content="Hier steht der Content">
<meta name="robots" content="index, follow">
<meta name="revisit-after" content="7 days">
<meta name="language" content="DE">
<base href="Domain.de">
	</head>
	<body>

<noscript>
Um diese Anzeige zu sehen müssen sie JavaScript aktivieren.
</noscript>


		<!-- Wrapper -->
			<div id="wrapper">

				<!-- Header -->
					<header id="header" class="alt">
						<span class="logo"><img src="images/logo.svg" alt="" /></span>
						<h1>Überschrift</h1>
						<br>Lorem Ipsum<br />
						</p>
					</header>

				<!-- Nav -->
					<nav id="nav">
						<ul>
							<li><a href="#intro" class="active">Introduction</a></li>
							<li><a

 href="#first">First Section</a></li>

href="#second">Second Section</a></li>
							<li><a href="#third">Third Section</a></li>
							<li><a 
href="#fourth">Fourth Section</a></li>
<li><a


href="#cta">Get Started</a></li>
						</ul>
					</nav>

				<!-- Main -->
					<div id="main">

						<!-- Introduction -->
							<section id="intro" class="main">
								<div class="spotlight">
									<div class="content">
										<header class="major">
											<h2>Überschrift</h2>
										</header>
										<p>Text</p>
										<ul class="actions">
											<li><a href="text.html" class="button">Button</a></li>
										</ul>
									
								</div>
							</section>
<!-- Second Section -->


							<section id="intro" class="main">

<class="content">

<class="spotlight">								
									
<header class="major">										
											<h2>Überschrift</h2>
										</header>
										<p>Hier steht ganz viel Text
<br>
Lückenfüller
<hr />
Written by &bull;Tim | DogofDoom &bull; </p>
										<ul class="actions">
											<li><a href="generic.html" class="button">Button</a></li>
										</ul>
									</div>
									<span 
		<meta charset="u" alt="" /></span>
								</div>
							</section>

			
						<!-- Third Section -->
							<section id="first" class="main special">
								<header class="major">
									<h2>Namen</h2>
								</header>
								<ul class="features">
									<li>
										<span class="icon major style1 fa-code"></span>
										<h3>Überschrift</h3>
										<p>Namen</p>
									</li>
									<li>
										<span class="icon major style2 fa-copy"></span>
										<h3>Überschrift</h3>
										<p>Namen</p>
									</li>
									<li>
										<span class="icon major style5 fa-diamond"></span>
										<h3>Überschrift</h3>
										<p>Name</p>
								</li>
									<li>
										<span class="icon major style1 fa-camera"></span>

<h3>Überschrift</h3>

<p>Name</p>

										<ul class="actions">
											
										</ul>
								</ul>
								<footer>
								</footer>
							</section>

						<!-- Fourth Section -->
							<section id="second" class="main special">
								<header class="major">
									<h2>Statistiken</h2>
									
								</header>
								<ul class="statistics">
									<li class="style1">
										<span class="icon fa-code-fork"></span>
										<strong>0</strong> Text
									</li>
									<li class="style2">
										<span class="icon fa-folder-open-o"></span>
										<strong>1</strong>Text
									</li>
									<li class="style3">
										<span class="icon fa-signal"></span>
									<strong>0</strong> Text
									</li>
									<li class="style4">
										<span class="icon fa-check"></span>
										<strong>0</strong> Lorem Ipsum
									</li>
									<li class="style5">
										<span class="icon fa-diamond"></span>
										<strong>In 1</strong> Land Vertreten
									</li>
								</ul>
								<p class="content">Text</p>
								<footer class="major">
									<ul class="actions">
										
									</ul>
								</footer>
							</section>

						<!-- Get Started -->
							<section id="cta" class="main special">
								<header class="major">
									<h2>Download</h2>
								<p>Hier steht Text
<b />
Text.</p>
								</header>
								<footer class="major">
									<ul class="actions">
										<li><a href="download" class="button special">Download</a></li>
										
									</ul>
								</footer>
							</section>

					</div>

				<!-- Footer -->
					<footer id="footer">
						<section>
							<h2>Lückenfüller</h2>
<p>Hier steht Text</p>
							<ul class="actions">
							
						</section>
						<section>
							<h2>Impressum</h2>
							<dl class="alt">
								<dt>Addresse</dt>
								<dd>Adresse &bull; Stadt, TN 38116 &bull; Germany</dd>
								<dt>Telephon</dt>
								<dd>Hier steht eine Nummer</dd>
								<dt>Email</dt>
								<dd><a href="#">dogofdoom3@gmail.com</a></dd>
							</dl>
							<ul href="#" class="icon fa-twitter alt"><span class="label">Twitter</span></a></li>
								<li><a href="#" class="icon fa-facebook alt"><span class="label">Facebook</span></a></li>
								<li><a href="#" class="icon fa-instagram alt"><span class="label">Instagram</span></a></li>
								<li><a href="#" class="icon fa-github alt"><span class="label">GitHub</span></a></li>
								<li><a href="#" class="icon fa-youtube alt"><span class="label">YouTube</span></a></li>

						<li>	<a href="#" class="icon fa-discord alt"><span class="label">Discord</span></a></li>
							</ul>
						</section>
						<p class="copyright">&copy; TR Studios <script>document.write(new Date().getFullYear())</script></p>
					</footer>

			</div>

		<!-- Scripts -->
			<script src="assets/js/jquery.min.js"></script>
			<script src="assets/js/jquery.scrollex.min.js"></script>
			<script src="assets/js/jquery.scrolly.min.js"></script>
			<script src="assets/js/skel.min.js"></script>
			<script src="assets/js/util.js"></script>
			<!--[if lte IE 8]><script src="assets/js/ie/respond.min.js"></script><![endif]-->
			<script src="assets/js/main.>
<script src="https://code.jquery.com/jquery-latest.js"></script>
</script>

	</body>
</html>
