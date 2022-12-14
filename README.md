<!DOCTYPE HTML>
<!--
	Rachel Mills
-->
<html>
	<head>
		<title>Rachel Mills</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />
		<noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>
	</head>
	<body class="is-preload">

		<!-- Wrapper -->
		<div style="overflow:auto; min-width: 850px" id="wrapper" class="divided">

			<!-- One -->
			<section class="banner style1 orient-left content-align-left image-position-right fullscreen onload-image-fade-in onload-content-fade-right">

				<div class="content">
					<center style="padding-bottom:15px; font-family: Helvetica"><h1>Rachel Mills</h1></center>
					<div style="display:flex; flex-direction: row; justify-content: center; align-items: center">

						<div style="padding-right: 8px; padding-left:8px">
							<button onClick="document.getElementById('projects').scrollIntoView();" class="button-47" role="button">Projects</button>
						</div>
						<div style="padding-right: 8px; padding-left:8px">
							<button onClick="document.getElementById('experience').scrollIntoView();" class="button-47" role="button">Experience</button>
						</div>
						<div style="padding-right: 8px; padding-left:8px">
							<button onClick="document.getElementById('resume').scrollIntoView();" class="button-47">Resume</button>
						</div>

					</div>
					<div class="items medium onscroll-fade-in">
						<section style="padding-top:50px">
							<div align="left" style="display:flex; flex-direction: row; justify-content: center; align-items: center">
								<img class="rounded-image" style="width:150px; height:150px" src="images/selfie3.jpg" alt="" />
								<p style="padding-left:25px; min-width: 250px">
									Hello! I'm a software engineer and computer scientist with industry experience and a passion to learn. Feel free to explore my front-end and back-end experience, projects, and resume. Thank you for visiting!
								</p>
							</div>
						</section>

					</div>
				</div>

			</section>


			<!-- Projects -->
			<div style="padding-top: 30px; padding-left: 12.5%; padding-right: 11%; min-width: 850px; min-height: 1050px " id="projects">
				<h2 style="font-family: Helvetica; max-height: 45px;padding-bottom: 0px">Projects</h2>
				<!--<hr style="font-weight: 100; font-size: xx-small; color: rgba(.01,.01,.01, 0.1); "/>-->
				<div style=" padding-bottom: 35px; max-height: 700px; padding-top: 25px ">
					<p style="max-height: 10px; font-weight: 400; padding-bottom: 15px">Julia Fractal GPU Programming</p>
					<div>
						<!--<img style="width:650px; height:350px" src="images/pic01.jpg" alt="" />-->
						<img style="width:450px; height:350px" SRC="images/shaders.png" />
						<p style="padding-top: 8px;max-height:.01px"><em>GLSL</em></p>
						<p>Write fragment and vertex shaders to depict cubic Julia Set fractal that changes as time progresses, edge detection shader on an image, spiral of circles, and ripple. The Julia Set is calculated using the equation z = z^2 + c to update the coordinates to map into the previous iteration's shape, where the x coordinate is the real component of z, and the y coordinate is the imaginary component.</p>
					</div>
				</div>
				<div style=" padding-bottom: 35px ">
					<p style="max-height: 10px; font-weight: 400; padding-bottom: 15px">NLP Part of Speech Tagger</p>
					<div>
						<img style="padding-bottom: 8px;width: 800px; height:200px" src="images/charpos.png" alt="" />
						<p style="max-height:.01px"><em>Pytorch</em></p>
						<p>Colab notebook using a Long Short Term Memory based model trained using English text from the Wall Street Journal, marked with POS tags such as NNP (proper noun) or ADJ (adjective). The project contains a word-level POS tagger and a character-level LSTM, creating a character-level representation of the word for more accurate predictions.</p>
					</div>
				</div>
				<div style=" padding-bottom: 35px ">
					<p style="max-height: 10px; font-weight: 400; padding-bottom: 15px">Dual Meshes</p>
					<div>
						<!--<img style="width:650px; height:350px" src="images/pic01.jpg" alt="" />-->
						<img style="width:680px; height:350px" SRC="images/hi.gif" />
						<p style="max-height:.01px; padding-top: 8px"><em>GLSL</em></p>
						<p>Create triangulated duals using 5 polyhedral models. Able to be toggled between per-face and per-surface normals, and white or random colors for each face</p>
					</div>
				</div>
				<div style=" padding-bottom: 35px ">
					<p style="max-height: 10px; font-weight: 400; padding-bottom: 15px">It Takes a Village Web Application</p>
					<div>
						<div style="padding-bottom: 12px; display:flex; flex-direction: row">
							<div style="padding-right: 50px">
								<img style=" box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.15), 0 2px 4px -1px rgba(0, 0, 0, 0.06); min-width: 420px; max-width: 420px; height: 200px " src="images/itav1.png" alt="" />
							</div>
							<img style="box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.15), 0 2px 4px -1px rgba(0, 0, 0, 0.06); min-width: 450px; max-width: 450px; height: 200px" src="images/itav2.png" alt="" />
						</div>

						<p style="max-height:.01px"><em>ReactJS with Java backend application and SQL database</em></p>
						<p>Project for client Dr. Mine Hashas-Degertekin with group of 5 students. Communication platform designed for single parents to find help around the house in the West End location of Atlanta.</p>
					</div>
				</div>
			</div>

			<!-- Experience -->
			<div style="padding-top:80px; padding-left: 12.5%; padding-right: 20px;  min-width: 850px; min-height: 735px" id="experience">
				<h2 style="padding-bottom: 30px; font-family:Helvetica; font-weight: 300">Experience</h2>
				<div style="padding-bottom:10px; ">
					<div style="display:flex; flex-direction: row">
						<div style=" min-width: 840px; max-width: 840px" align="left">
							<div style=" min-width: 890px; max-width: 890px">
								<p style="max-height:.01px; font-weight: 500">Apple</p>
								<p style="max-height: .01px"><em>Software Engineer Intern</em><br /></p>
							</div>
							<p style="max-width: 850px; min-width: 850px; min-height: 1px">Created an unreleased feature for Apple Music and MusicKit using Objective-C, Swift, and SwiftUI.</p>
						</div>
						<p align="right" style=" padding-right: 55px;font-weight: 400;font-size: 16px; max-width: 310px; min-width: 310px">May 2022 - August 2022</p>
					</div>
				</div>
				<div style="padding-bottom:10px; ">
					<div style="display:flex; flex-direction: row">
						<div style=" min-width: 840px; max-width: 840px" align="left">
							<div style=" min-width: 890px; max-width: 890px">
								<p style="max-height: .01px; font-weight: 500 ">Apple</p>
								<p style="max-height: .01px"><em>Software Engineer Intern</em><br /></p>
							</div>
							<p style="max-width: 850px; min-width: 850px; min-height: 1px">Created a back-end feature for Apple Music using Objective-C, and Swift.</p>
						</div>
						<p align="right" style=" padding-right: 55px;font-weight: 400;font-size: 16px; max-width: 310px; min-width: 310px">May 2021 - August 2021</p>
					</div>
				</div>
				<div style="padding-bottom:10px; ">
					<div style="display:flex; flex-direction: row">
						<div style=" min-width: 840px; max-width: 840px" align="left">
							<div style=" min-width: 890px; max-width: 890px">
								<p style="max-height: .01px; font-weight: 500">Georgia Institute of Technology Alumni Association	</p>
								<p style="max-height: .01px"><em>IT Coordinator</em><br /></p>
							</div>
							<p style="max-width: 850px; min-width: 850px; min-height: 1px">Hardware repair, configuration of devices, and cybersecurity for the Alumni Association. Experience with Windows and macOS operating systems and providing tech support.</p>
						</div>
						<p align="right" style=" padding-right: 55px;font-weight: 400;font-size: 16px; max-width: 310px; min-width: 310px">January 2021 - December 2021</p>
					</div>
				</div>
			</div>

			<!-- Resume -->
			<section class="spotlight style1 orient-right content-align-left image-position-center onscroll-image-fade-in" id="resume">
				<div class="content">
					<embed src="assets/RM2022.pdf" type="application/pdf" width="100%" height="600px" />
				</div>
			</section>






			<!-- Footer -->
			<footer class="wrapper style1 align-center">
				<div class="inner">
					<ul class="icons"
								<li><a href="#" class="icon brands style2 fa-linkedin-in" onclick="window.location.href='https://www.linkedin.com/in/rachel-mills-861b34170/';"><span class="label">LinkedIn</span></a></li>
							</ul>
					<p>&copy; Rachel Mills 2022</p>
				</div>
			</footer>

		</div>

			<!-- Scripts -->
			<script src="assets/js/jquery.min.js"></script>
			<script src="assets/js/jquery.scrollex.min.js"></script>
			<script src="assets/js/jquery.scrolly.min.js"></script>
			<script src="assets/js/browser.min.js"></script>
			<script src="assets/js/breakpoints.min.js"></script>
			<script src="assets/js/util.js"></script>
			<script src="assets/js/main.js"></script>

</body>
</html>
