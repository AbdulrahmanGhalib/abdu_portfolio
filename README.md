<!DOCTYPE html>
<html lang="en">

<head>
	<title>Al-Shamiri Portfolio</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

	<meta property="og:title" content="Page Tile" />
	<meta property="og:description" content="Personal Site" />

	<link href="https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900" rel="stylesheet">
	<link rel="stylesheet" href="{{asset('/css/animate.css')}}">
	<link rel="icon" href="{{asset('/images/favicon.png')}}">

	<link rel="stylesheet" href="{{asset('/css/owl.carousel.min.css')}}">
	<link rel="stylesheet" href="{{asset('/css/owl.theme.default.min.css')}}">
	<link rel="stylesheet" href="{{asset('/css/magnific-popup.css')}}">
	<link rel="stylesheet" href="{{asset('/css/aos.css')}}">
	<link rel="stylesheet" href="{{asset('/css/flaticon.css')}}">
	<link rel="stylesheet" href="{{asset('/css/icomoon.css')}}">
	<link rel="stylesheet" href="{{asset('/css/style.css')}}">
</head>

<body data-spy="scroll" data-target=".site-navbar-target" data-offset="300">


	<nav class="navbar navbar-expand-lg navbar-dark bg-dark ftco_navbar ftco-navbar-light site-navbar-target"
		id="ftco-navbar">
		<div class="container">
			<a class="navbar-brand" href="{{ url('/') }}">Abdulrahman </a>
			<button class="navbar-toggler navbar-light js-fh5co-nav-toggle fh5co-nav-toggle" type="button" data-toggle="collapse"
				data-target="#ftco-nav" aria-controls="ftco-nav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                {{-- <span class="oi oi-menu"></span> Menu --}}
			</button>

			<div class="collapse navbar-collapse" id="ftco-nav">
				<ul class="navbar-nav nav ml-auto">
					<li class="nav-item"><a href="{{url('/')}}" class="nav-link"><span>Home</span></a></li>
					<li class="nav-item"><a href="#about-section" class="nav-link"><span>About</span></a></li>
					<li class="nav-item"><a href="#resume-section" class="nav-link"><span>Resume</span></a></li>
					<li class="nav-item"><a href="#project-section" class="nav-link"><span>Projects</span></a></li>
					<li class="nav-item"><a href="#contact-section" class="nav-link"><span>Contact</span></a></li>
				</ul>
			</div>
		</div>
	</nav>


	<!-- particles -->
	<div id="particles-js"></div>

	<section class="hero-wrap js-fullheight">
		<!--       <div class="overlay"></div> -->
		<div class="container">
			<div class="row no-gutters slider-text js-fullheight justify-content-center align-items-center">
				<div class="col-lg-8 col-md-6 ftco-animate d-flex align-items-center">
					<div class="text text-center">
						<span class="subheading">Hey! I am</span>
						<h3>Abdulrahman Al-Shamiri</h3>
						<h2>I like
							<span class="txt-rotate" data-period="2000"
								data-rotate='[ "Coding.", "Software Development", "Problem Solving.", "Photography.", "Books."]'></span>
						</h2>
					</div>
				</div>
			</div>
			<div class="scrollDown">
				<span></span>
				<span></span>
				<span></span>
			</div>
		</div>
		</div>
		</button>
		<div class="glyphicon glyphicon-arrow-down"></div>
	</section>

	<section class="ftco-about img ftco-section ftco-no-pt ftco-no-pb" id="about-section">
		<div class="container">
			<div class="row d-flex no-gutters">
				<div class="col-md-6 col-lg-6 d-flex">
					<div class="img-about img d-flex align-items-stretch">
						<div class="overlay"></div>
						<div class="img d-flex align-self-stretch align-items-center"
							style="background-image:url({{asset('/images/Me.jpg')}}">
						</div>
					</div>
				</div>
				<div class="col-md-6 col-lg-6 pl-md-5 py-5">
					<div class="row justify-content-start pb-3">
						<div class="col-md-12 heading-section ftco-animate">
							<h2 class="mb-4">About Me</h2>
							<p>Here is a little about me</p>
							<ul class="about-info mt-4 px-md-0 px-2">
								<li class="d-flex"><span>Name:</span><span>Abdulrahman Ghaleb</span></li>
								<li class="d-flex"><span>Email:</span><span class="overflow-hidden">abdulrahmanalshameery93@gmail.com</span></li>
								<li class="d-flex"><span>Phone:</span><span>+967 735 254 510</span></li>
								<li class="d-flex"><span>Country:</span> <span>Yemen</span></li>
								<li class="d-flex"><span>City:</span><span>Taiz</span></li>
							</ul>
						</div>
					</div>
					<div class="counter-wrap ftco-animate d-flex mt-md-3">
						<div class="text">
							<p><a target="_blank" href="https://drive.google.com/file/d/1IFFDxCNMx8jyLeuoWIjAk5RzjgKFx0Yj/view?usp=drivesdk" class="btn btn-primary py-3 px-3">Download CV</a></p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section class="ftco-section ftco-no-pb goto-here" id="resume-section">
		<div class="container">
			<div class="row">
				<div class="col-md-3">
					<nav id="navi">
						<ul>
							<li><a href="#page-1">Education</a></li>
							<li><a href="#page-2">Experience</a></li>
							<li><a href="#page-3">Skills</a></li>
							{{-- <li><a href="#page-4">Awards</a></li> --}}
						</ul>
					</nav>
				</div>
				<div class="col-md-9">
					<div id="page-1" class="page one">
						<h2 class="heading">Education</h2>
						<div class="resume-wrap d-flex ftco-animate">
							<div class="icon d-flex align-items-center justify-content-center">
								<span class="flaticon-graduation-cap"></span>
							</div>
							<div class="text pl-3">
								<h2>Sana'a University of Computer Science & Info Technology</h2>
								<span class="position">Bachelor of Computer Programming</span>
								<p><strong>Computer Systems Programming</strong></p>
								<p>Karachi - Pakistan</p>
								<span class="date">2019-2023 (March)</span>
							</div>
						</div>
						<div class="resume-wrap d-flex ftco-animate">
							<div class="icon d-flex align-items-center justify-content-center">
								<span class="flaticon-book"></span>
							</div>
							<div class="text pl-3">
								<h2>Diploma In English </h2>
								<span class="position">Intermediate</span>
								<p><strong>Pre-Programming</strong></p>
								<p>College Of Languages - Sana'a University</p>
								<span class="date">2018/2  -  2018/8</span>
							</div>
						</div>
						<div class="resume-wrap d-flex ftco-animate">
							<div class="icon d-flex align-items-center justify-content-center">
								<span class="flaticon-book"></span>
							</div>
							<div class="text pl-3">
								<h2>High School Certificate</h2>
								<span class="position">Matriculation</span>
								<p><strong>Science</strong></p>
								<p>Jeel Altasheeh - Taiz</p>
								<span class="date">2007-2018</span>
							</div>
						</div>
					</div>

					<div id="page-2" class="page two">
						<h2 class="heading">Experience</h2>
						<div class="resume-wrap d-flex ftco-animate">
							<div class="icon d-flex align-items-center justify-content-center">
								<span class="flaticon-suitcase"></span>
							</div>
							<div class="text pl-3">
								<h2>Software Engineer</h2>
								<span class="position">Ministry of Industry and Trade</span>
								<p class="date">August 2023 - Present</p>
							</div>
						</div>
						{{-- <div class="resume-wrap d-flex ftco-animate">
							<div class="icon d-flex align-items-center justify-content-center">
								<span class="flaticon-suitcase"></span>
							</div>
							<div class="text pl-3">
								<h2>Associate Software Engineer</h2>
								<span class="position">TPS Worldwide</span>
								<p class="date">Dec 2020 - May 2021</p>
								<div class="c d-flex ftco-animate">
									<div class="icon d-flex align-items-center justify-content-center">
										<span class="flaticon-suitcase"></span>
									</div>
									<div class="text pl-3">
										<h2>Intern</h2>
										<span class="position">TPS Worldwide</span>
										<p class="date">Sept 2019 - Oct 2019</p>
										<ul>
											<li>Worked as support for their Intranet portal (TPSConnect)</li>
											<li>Created SharePoint MasterPages using SharePoint Designer</li>
											<li>Developed Custom SharePoint WebParts</li>
										</ul>
									</div>
								</div>
						    </div>
						</div>
						<div class="resume-wrap d-flex ftco-animate">
							<div class="icon d-flex align-items-center justify-content-center">
								<span class="flaticon-suitcase"></span>
							</div>
							<div class="text pl-3">
								<h2>Intern</h2>
								<span class="position">Gaditek</span>
								<p class="date">Sept 2018 - Oct 2018</p>
								<ul>
									<li>Took requirements from HR for development of Automated Probation System. Made Flowcharts, UI designs for the module</li>
									<li>Demonstrated iptables in CentOS 7 using a Virtual Machine</li>
									<li>Wrote a WhatsApp Chat Parser script using Python and Regex</li>
								</ul>
							</div>
						</div> --}}
					</div>
					<div id="page-3" class="page three">
						<h2 class="heading">Skills</h2>
						<!-- Skill Section -->
						<div class="row mb-4 ftco-animate">
							<div class="col grow">
                                <img class="img-fluid" src="{{asset('/images/skills/javascript.png')}}" title="JavaScript"/>
                            </div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/node.png')}}" title="NodeJS"></div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/react.png')}}" title="React"></div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/html.png')}}" title="HTML"></div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/css.png')}}" title="CSS"></div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/bootstrap.png')}}" title="Bootstrap"></div>
						</div>
						<div class="row mb-4 ftco-animate">
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/cplusplus.png')}}" title="C++"></div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/csharp.png')}}" title="C#"></div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/java.png')}}" title="Java"></div>
                            <div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/linux.png')}}" title="Linux"></div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/dart.png')}}" title="Dart"></div>
							<div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/flutter.png')}}" title="Flutter"></div>
                            {{-- <div class="col grow"><img class="img-fluid" src="{{asset('/images/skills/laravel.jpg')}}" title="Laravel"></div> --}}
						</div>



					</div>
					{{-- <div id="page-4" class="page four">
						<h2 class="heading">Awards</h2>
						<div class="resume-wrap d-flex ftco-animate">
							<div class="icon d-flex align-items-center justify-content-center">
								<span class="flaticon-medal"></span>
							</div>
							<div class="text pl-3">
								<h2>Runner Up - Speed Debugging Competition</h2>
								<span class="position"><strong>ITEC</strong></span>
								<span><strong> - NED Universit of Engg. & Tech</strong></span>
								<p class="date">June 2018</p>
								<p>Karachi - Pakistan</p>
							</div>
						</div>
						<div class="resume-wrap d-flex ftco-animate">
							<div class="icon d-flex align-items-center justify-content-center">
								<span class="flaticon-trophy"></span>
							</div>
							<div class="text pl-3">
								<h2>Winner - Speed Debugging Competition</h2>
								<span class="position"><strong>Developer's Day</strong></span>
								<span><strong> - FAST NUCES</strong></span>
								<p class="date">Apr 2018</p>
								<p>Karachi - Pakistan</p>
							</div>
						</div>
					</div> --}}
				</div>
			</div>
		</div>
	</section>

	<section class="ftco-section" id="project-section">
		<div class="container-fluid px-md-5">
			<div class="row justify-content-center py-5 mt-5">
				<div class="col-md-12 heading-section text-center ftco-animate">
					<h2 class="mb-4">Projects</h2>
				</div>
			</div>
			<div class="row">
				<div class="col-md-4 text-center d-flex ftco-animate">
					<a class="services-1 shadow">
						<span class="icon">
							<i class="flaticon-camp"></i>
						</span>
						<div class="desc">
							<h3 class="mb-4">Commerical Agencies System</h3>
							<p><strong>aps.net mvc core6 • sql server database </strong></p>
							<p>A web based application that allows user to view and manage all Agencies in yemen. <br> Used
								Asp .net Mvc along with Express to make the application. sql server DB for the database.</p>
						</div>
					</a>
				</div>
				<div class="col-md-4 text-center d-flex mx-auto ftco-animate">
					<a href="https://ahsankhan.me/books" target="_blank" class="services-1 shadow">
						<span class="icon">
							<i class="icon-book"></i>
						</span>
						<div class="desc">
							<h3 class="mb-4">Speed Recording Radar</h3>
							<p><strong>Python • open cv(AI) • mysql database</strong></p>
							<p>Fetches All cars that are Aganist the Law .<br>All using mysql database to save values of speed and informations about cars </p>
						</div>
					</a>
				</div>
				<div class="col-md-4 text-center d-flex mx-auto ftco-animate">
					<a href="https://ahsankhan.me/TermFolio" target="_blank" class="services-1 shadow">
						<span class="icon">
							<i class="icon-terminal"></i>
						</span>
						<div class="desc">
							<h3 class="mb-4">TermFolio</h3>
							<p><strong>HTML • CSS • JavaScript</strong></p>
							<p>A Portfolio Website that is made to look and act like a Terminal.</p>
						</div>
					</a>
				</div>
			</div>
			{{-- <div class="row">
				<div class="col-md-4 text-center d-flex mx-auto ftco-animate">
					<a href="https://github.com/ahsankhan26/Whatsapp-Chat-Parser" target="_blank"
						class="services-1 shadow">
						<span class="icon">
							<i class="icon-whatsapp"></i>
						</span>
						<div class="desc">
							<h3 class="mb-4">WhatsApp Chat Parser</h3>
							<p><strong>Python • Regex</strong></p>
							<p>An App that takes WhatsApp chat file and parses it for better data analysis.</p>
						</div>
					</a>
				</div>
				<div class="col-md-4 text-center d-flex ftco-animate">
					<a href="https://github.com/ahsankhan26/Laser-Data-Transmission" target="_blank"
						class="services-1 shadow">
						<span class="icon">
							<i class="flaticon-circuit-board"></i>
						</span>
						<div class="desc">
							<h3 class="mb-4">Data Transmission with Laser</h3>
							<p><strong>Arduino</strong></p>
							<p>A hardware based demonstration of Binary ASCII representation of Text, Sent and Received
								from one system to another using Laser and Arduino.</p>
						</div>
					</a>
				</div>
				<div class="col-md-4 text-center d-flex ftco-animate">
					<a href="https://github.com/ahsankhan26/Bomberman-Replica" target="_blank"
						class="services-1 shadow">
						<span class="icon">
							<i class="flaticon-bomberman"></i>
						</span>
						<div class="desc">
							<h3 class="mb-4">SNES Bomberman Replica Game</h3>
							<p><strong>C# • Unity</strong></p>
							<p>Video game using Unity 2D game development environment and C# Scripts for
								interactivity.<br>The game was intended to be multiplayer competing against each other.
							</p>
						</div>
					</a>
				</div>
			</div> --}}
		</div>
		</div>
	</section>



	<!-- <section class="ftco-section ftco-hireme img" style="background-image: url({{asset('/images/bg_1.jpg')}})">
		<div class="overlay"></div>
		<div class="container">
			<div class="row justify-content-center">
				<div class="col-md-7 ftco-animate text-center">
					<h2>I'm <span>Available</span> for Hire</h2>
					<p class="mt-3 mb-0">
						<a id="fiverr" href="https://fiverr.com/ahsankhan26" target="_blank"
							class="btn btn-primary py-3 px-5">Fiverr</a>
					</p>
				</div>
			</div>
		</div>
	</section> -->

	<section class="ftco-section contact-section ftco-no-pb" id="contact-section">
		<div class="container">
			<div class="row justify-content-center mb-4 pb-3">
				<div class="col-md-7 heading-section text-center ftco-animate">
					<h2 class="mb-4">Contact Me</h2>
				</div>
			</div>

			<div class="row d-flex justify-content-center contact-info mb-5">
				<div class="col-md-6 col-lg-3 d-flex ftco-animate">
					<div class="align-self-stretch box text-center p-4 shadow">
						<div class="icon d-flex align-items-center justify-content-center">
							<span class="icon-phone2"></span>
						</div>
						<div>
							<h3 class="mb-4">Contact Number</h3>
							<p><a href="tel:+967735254510">+967 735 254 510</a></p>
						</div>
					</div>
				</div>
				<div class="col-md-6 col-lg-4 d-flex ftco-animate">
					<div class="align-self-stretch box text-center p-4 shadow">
						<div class="icon d-flex align-items-center justify-content-center">
							<span class="icon-paper-plane"></span>
						</div>
						<div>
							<h3 class="mb-4">Email Address</h3>
							<span class=" d-flex overflow-hidden">
                                <a  href="mailto:abdulrahmanalshameery93@gmail">
                                    <span class="overflow-hidden" >abdulrahmanalshameery93@gmail.com</span>
                                </a>
                            </span>
						</div>
					</div>
				</div>
				<div class="col-md-6 col-lg-3 d-flex ftco-animate">
					<div class="align-self-stretch box text-center p-4 shadow">
						<div class="icon d-flex align-items-center justify-content-center">
							<span class="icon-globe"></span>
						</div>
						<div>
							<h3 class="mb-4">Website</h3>
							<p><a>Eng.abdu.com</a></p>
						</div>
					</div>
				</div>
			</div>

			<div class="row no-gutters block-9">
				<div class="col-md-6 order-md-last d-flex">
					<form method="POST" action=""
						class="bg-light p-4 p-md-5 contact-form">
						<div class="form-group">
							<input type="text" class="form-control" name="name" placeholder="Your Name" required>
						</div>
						<div class="form-group">
							<input type="email" class="form-control" name="email" placeholder="Your Email" required>
						</div>
						<div class="form-group">
							<textarea id="" cols="30" rows="7" class="form-control" name="message" placeholder="Message"
								required></textarea>
						</div>

						<div class="form-group">
							<input type="submit" value="Send Message" class="btn btn-primary py-3 px-5">
							<input type="hidden" name="_next" value="//ahsankhan.me" />
						</div>
					</form>

				</div>

				<div class="col-md-6 d-flex">
					<div class="img" style="background-image: url({{asset('/images/Me.jpg')}}"></div>
				</div>
			</div>
		</div>
	</section>


	<footer class="ftco-footer ftco-section">
		<div class="container">
			<div class="row mb-5">
				<div class="col-md">
					<div class="ftco-footer-widget mb-4">
						<h2 class="ftco-heading-2">About</h2>
						<p>I like working with new tools and technologies, and I'm Still a graduate</p>
						<p class="mt-4"><u>Social Links</u></p>
						<ul class="ftco-footer-social list-unstyled float-md-left float-lft">
							<li class="ftco-animate"><a href="https://github.com/AbdulrahmanGhalib" target="_blank"><span
										class="icon-github"></span></a></li>
							<li class="ftco-animate"><a href="https://www.linkedin.com/in/abdulrahman-ghalib-020385228/"
									target="_blank"><span class="icon-linkedin-square"></span></a></li>
							<li class="ftco-animate"><a href="https://stackoverflow.com/users/17405866/abdulrahman-alshamiri"
									target="_blank"><span class="icon-stack-overflow"></span></a></li>
							<li class="ftco-animate"><a href="https://www.facebook.com/profile.php?id=100025878752084" target="_blank"><span
										class="icon-facebook"></span></a></li>
						</ul>
					</div>
				</div>
				<div class="col-md">
					<div class="ftco-footer-widget mb-4 ml-md-4">
						<h2 class="ftco-heading-2">Links</h2>
						<ul class="list-unstyled">
							<li><a href="{{url('/')}}"><span class="icon-long-arrow-right mr-2"></span>Home</a></li>
							<li><a href="#about-section"><span class="icon-long-arrow-right mr-2"></span>About</a></li>
							<li><a href="#resume-section"><span class="icon-long-arrow-right mr-2"></span>Resume</a>
							</li>
							<li><a href="#project-section"><span class="icon-long-arrow-right mr-2"></span>Projects</a>
							</li>
							<li><a href="#contact-section"><span class="icon-long-arrow-right mr-2"></span>Contact</a>
							</li>
						</ul>
					</div>
				</div>

				<div class="col-md">
					<div class="ftco-footer-widget mb-4">
						<h2 class="ftco-heading-2">Have a Question?</h2>
						<div class="block-23 mb-3">
							<ul>
                                <li><a href="#contact-section"><span class="icon-long-arrow-right mr-2"></span>Go to Contact Section</a>
							</ul>
						</div>
					</div>
				</div>
			</div>
			<div class="row">
				<div class="col-md-12 text-center">
					<i class="icon-heart color-danger" aria-hidden="true"></i>
					<i class="icon-heart color-danger" aria-hidden="true"></i>
					<p class="mt-5">Copyright &copy;
						<script>document.write(new Date().getFullYear());</script>
					</p>
				</div>
			</div>
		</div>
	</footer>



	<!-- loader -->
	<div id="ftco-loader" class="show fullscreen"><svg class="circular" width="48px" height="48px">
			<circle class="path-bg" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke="#eeeeee" />
			<circle class="path" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke-miterlimit="10"
				stroke="#F96D00" />
		</svg></div>

	<script src="{{asset('/js/jquery.min.js')}}"></script>
	<script src="{{asset('/js/jquery-migrate-3.0.1.min.js')}}"></script>
	<script src="{{asset('/js/bootstrap.min.js')}}"></script>
	<script src="{{asset('/js/jquery.waypoints.min.js')}}"></script>
	<script src="{{asset('/js/jquery.stellar.min.js')}}"></script>
	<script src="{{asset('/js/owl.carousel.min.js')}}"></script>
	<script src="{{asset('/js/jquery.magnific-popup.min.js')}}"></script>
	<script src="{{asset('/js/aos.js')}}"></script>
	<script src="{{asset('/js/jquery.animateNumber.min.js')}}"></script>
	<script src="{{asset('/js/scrollax.min.js')}}"></script>
	<script src="{{asset('/js/particles.min.js')}}"></script>
	<script src="{{asset('/js/app.js')}}"></script>
	<script src="{{asset('/js/main.js')}}"></script>

</body>

</html>
