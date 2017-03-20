# MyOnlineResumeSite
This is my online resume site. My First one ever.


<!DOCTYPE html>


<html lang="em">


	<head>

			<meta charset="utf-8">
			<meta name="viewport" content="width-device-width, initialscale-1">
			<meta name="description" content="Description goes here">
	
			<title>My Portfolio Page</title>

			<link rel="shortcut icon" href="*/favicon. ico" type="image/x icon">
			<link rel="icon" href="*/favicon. ico" type="image/x icon">
			<link rel="stylesheet" type="text/css" href="style.css">

			<script>document.write('<script src="http://' + (location.host || 'localhost').split(':')[0] + ':35729/livereload.js?snipver=1"></' + 'script>')</script>


	</head>

	<body>

			<section id="welcomeSection">
				
				
					
					<p>"There is no passion to be found in playing small-in settling for a life that is less than you are capable of living."</p>
			</section>


			<section id="aboutSection">
				
				<h1>About</h1>
					<p>South African born currently based near Sheffield, UK.</p>
			</section>


			<section id="skillsSection">
				
				<h1>Skills</h1>
					<p>Been working in telephone based customer technical support for the last 5 years. i enjoy learning and picking up new skills mostly online using my imac. My passion lies in creating things. I love to build from scratch or take elements apart and put them together again. This passion has led to me to the world of coding and web development. Having been teeaching myself HTML and CSS in my spare time,  feel the time has come to step this up from a hobby to a full time engagement. My resume is available upon request for further info onmy skills and experience.</p>

			</section>

			<section id="contactSection">
				
				<h1>Contact me</h1>

				<form id="Contact" action="<?= $_SERVER['PHP_SELF']; ?>" method="post">
					<input name="name" placeholder="What is your name?" class="name" required />
					<input name="emailaddress" placeholder="What is your email?" class="email" type="email" required />
    				<textarea rows="4" cols="50" name="subject" placeholder="Please enter your message" class="message" required></textarea>
   					<input name="submit" class="btn" type="submit" value="Send" />
				</form>
				
			</section>

			<section id="footer">
				Copyright &copy 2017 VLS

			</section>
		




	


	</body>
</html>

