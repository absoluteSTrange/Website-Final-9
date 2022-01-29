<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Nuno - Responsive Bootstrap Theme</title>
	<!-- <link rel="stylesheet" href="bootstrap-4.1.3-dist/css/bootstrap.min.css"> -->
	<link rel="stylesheet" href="Lux.css">
	<link rel="stylesheet" href="style.css">
	<link rel="stylesheet" href="css/fixed.css">
	<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" />

</head>

<!-- data-spy="scroll" data-target="#navbarResponsive" -->

<body>

    <!-- * Start Home Section -->
    <div id="home">



    	<!-- * Start of Navigation -->
    	<!-- <nav class="navbar navbar-expand-md navbar-light bg-light fixed-top">
    		<a href="#" class="navbar-brand"><img src="logo-v3.png"></a>
    		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive">
    			<span class="navbar-toggler-icon"></span>
    		</button>

    		<div class="collapse navbar-collapse" id="navbarResponsive">
    			<ul class="navbar-nav ml-auto">

    				<li class="nav-item">
    					<a href="#home" class="nav-link">Home</a>
    				</li>

    				<li class="nav-item">
    					<a href="#about" class="nav-link">About</a>
    				</li>

    				<li class="nav-item">
    					<a href="#UnviersalExports" class="nav-link">Universal Exports</a>
    				</li>

    				<li class="nav-item">
    					<a href="#Clients" class="nav-link">Clients</a>
    				</li>

    				<li class="nav-item">
    					<a href="#BBC Innova" class="nav-link">BBC Innova</a>
    				</li>

    				<li class="nav-item">
    					<a href="#Contact" class="nav-link">Contact</a>
    				</li>


    			</ul>
    		</div>

    	</nav> -->

    	<!-- * End of Navigation -->

    	<!-- * Start of Navigation1  -->

    	<nav class="navbar navbar-expand-lg navbar-light bg-light">
    		<div class="container-fluid">
    			<a class="navbar-brand" href="#"><img src="logo-v3.png" alt=""></a>
    			<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarColor03"
    				aria-controls="navbarColor03" aria-expanded="false" aria-label="Toggle navigation">
    				<span class="navbar-toggler-icon"></span>
    			</button>

    			<div class="collapse navbar-collapse" id="navbarColor03">
    				<ul class="navbar-nav me-auto">
    					<li class="nav-item">
    						<a class="nav-link active" href="#home">Home
    							<!-- <span class="visually-hidden">(current)</span> -->
    						</a>
    					</li>
    					<li class="nav-item">
    						<a class="nav-link" href="#about">About</a>
    					</li>
    					<li class="nav-item">
    						<a class="nav-link" href="#UnviersalExports">Universal Exports</a>
    					</li>
    					<li class="nav-item">
    						<a class="nav-link" href="#Clients">Clients</a>
    					</li>
    					<li class="nav-item">
    						<a class="nav-link" href="#BBC Innova">BBC Innova</a>
    					</li>
    					<a href="#Contact" class="btn btn-outline-primary">
    						Contact us
    					</a>
    					<!-- <li class="nav-item dropdown">
    						<a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button"
    							aria-haspopup="true" aria-expanded="false">Dropdown</a>
    						<div class="dropdown-menu">
    							<a class="dropdown-item" href="#">Action</a>
    							<a class="dropdown-item" href="#">Another action</a>
    							<a class="dropdown-item" href="#">Something else here</a>
    							<div class="dropdown-divider"></div>
    							<a class="dropdown-item" href="#">Separated link</a>
    						</div>
    					</li> -->
    				</ul>
    				<!-- <form class="d-flex">
    					<input class="form-control me-sm-2" type="text" placeholder="Search">
    					<button class="btn btn-secondary my-2 my-sm-0" type="submit" cursorshover="true">Search</button>
    				</form> -->
    			</div>
    		</div>
    	</nav>


    	<!-- * End of Navigation1  -->

    	<div class="scrollTopBtn">
    		<button type="button" class="btn btn-primary text-center upBtn" onclick="topFunction()" id="myBtn"
    			title="Go to top">
    			<i class="fas fa-arrow-up fa-1x"></i>
    		</button>

    		<script>
    			//Get the button:
    			mybutton = document.getElementById("myBtn");

    			// When the user scrolls down 20px from the top of the document, show the button
    			window.onscroll = function () { scrollFunction() };

    			function scrollFunction() {
    				if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    					mybutton.style.display = "block";
    				} else {
    					mybutton.style.display = "none";
    				}
    			}

    			// When the user clicks on the button, scroll to the top of the document
    			function topFunction() {
    				document.body.scrollTop = 0; // For Safari
    				document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
    			}



    		</script>

    	</div>


    	<!-- Start Landing Page Section -->

    	<div class="landing">
    		<div class="home-wrap">
    			<div class="home-inner">

    			</div>
    		</div>
    	</div>

    	<div class="caption text-center">
    		<h1 class="animate__animated animate__slideInDown animate__delay-0.3s" style="color:white">BBC Universal
    			Exports <br> Globally,
    			Locally</h1>
    		<h4 class="animate__animated animate__slideInDown animate__delay-0.2s"
    			style="margin-top: 20px; margin-bottom:20px; color:white">International trading simplified
    			through strategic
    			partnerships</h4>
    		<a href="#about"
    			class="btn btn-outline-light btn-lg animate__animated animate__slideInDown animate__delay-0.1s">Learn
    			More</a>
    	</div>

    	<!-- End Landing Page Section -->


    </div>
    <!-- * End of Home section -->

    <!-- !--------------------------- -->

    <!-- * Start About Section -->
    <div id="about" class="offset">

    	<div class="col-12 narrow text-center">
    		<!-- <h3>Who are we?</h3>
    		<p class="">
    			The Bohra Group, traces its origin to rural transport services founded in 1957 in India and further
    			expanded to Finance, Hire Purchase & other trading businesses in various regions of India. Charting a
    			steady growth, BBC Innova was founded in the year 2005, dealing exclusively in premium real estate and
    			construction material supply & contracting on Pan India basis. Learning the unmatched quality & customer
    			satisfaction for our products & services in India, The group further expanded to the global platform
    			with its company BBC Universal Exports in 2014, which believes in being a globally local company. Just
    			recently, the group ventured into Bohra Electrical Systems & Technologies (BEST), which mainly focuses
    			on providing solution in electrical and lighting aspects for any given space through consultation,
    			application and implementation.

    		</p>
    		<p class="">
    			Bohra Group is a senior member in the PM delegation team for SAARC region for CII. We are exclusive
    			partners for many global brands like Renovo for the region. BBC Universal Exports have joined hands with
    			Maplitho group based in India to organize the marketing aspects and requirements of Bohra group for
    			constructive growth

    		</p> -->

    		<div class="container">
    			<div class="row justify-content-center">
    				<div class="title col-md-12 col-lg-10 text-center">
    					<h3 class="align-center mb-4 display-5" data-aos="fade-down">Who are we?</h3>
    					<div class="heading-underline"></div>
    					<p class="align-center mb-4 display-7 " data-aos="fade-up"
    						data-aos-anchor-placement="center-bottom">
    						The Bohra Group, traces its origin to rural transport services founded in 1957 in India and
    						further expanded to Finance, Hire Purchase & other trading businesses in various regions of
    						India. Charting a steady growth, BBC Innova was founded in the year 2005, dealing
    						exclusively in premium real estate and construction material supply & contracting on Pan
    						India basis. Learning the unmatched quality & customer satisfaction for our products &
    						services in India, The group further expanded to the global platform with its company BBC
    						Universal Exports in 2014, which believes in being a globally local company. Just recently,
    						the group ventured into Bohra Electrical Systems & Technologies (BEST), which mainly focuses
    						on providing solution in electrical and lighting aspects for any given space through
    						consultation, application and implementation.
    					</p>

    					<p data-aos="fade-up" data-aos-anchor-placement="center-bottom">
    						Bohra Group is a senior member in the PM delegation team for SAARC region for CII. We are
    						exclusive partners for many global brands like Renovo for the region. BBC Universal Exports
    						have joined hands with Maplitho group based in India to organize the marketing aspects and
    						requirements of Bohra group for constructive growth
    					</p>

    				</div>
    			</div>
    		</div>

    		<!-- <a href="" class=" btn btn-secondary btn-md"></a> -->



    	</div>




    </div>
    <!-- * End of About section -->

    <!-- !--------------------------- -->

    <hr>



    <!-- * Start Features Section -->
    <div id="about" class="offset">
    	<!-- * Start of Jumbotron -->
    	<div class="jumbotron">
    		<div class="narrow" data-aos="fade-up" data-aos-anchor-placement="center-bottom">
    			<div class="col-12">
    				<!-- <h3 class="heading text-center">Features</h3> -->
    				<p class="text-center">At the Bohra Group,
    					we believe in GROWING STRONG, Together.</p>
    				<div class="heading-underline"></div>

    			</div>

    			<div class="row text-center">
    				<div class="col-md-4">

    					<div class="feature">
    						<i class="far fa-eye fa-5x" data-fa-transform="shrink-1.2 up-5"></i>
    					</div>
    					<h3>Vision</h3>
    					<p>Aims to achieve long term stable growth in harmony with the global environment
    						and the
    						economy, the local communities it serves, and the customers it caters. We remain
    						to believe
    						that, Leadership is the capacity to translate VISION into reality.
    					</p>
    				</div>

    				<div class="col-md-4">

    					<img src="../busines-wel5.jpg" alt="" style="width: 90%;">

    				</div>

    				<div class="col-md-4">
    					<div class="feature">
    						<i class="fas fa-globe-asia fa-5x" data-fa-transform="shrink-1.2 up-5"></i>
    					</div>
    					<h3>Mission</h3>
    					<p>We will provide the support required to sustain long-term growth and customer
    						satisfaction.
    						We will passionately promote quality and service at all levels while enhancing
    						the groups
    						competitive advantage. As we do all our work, with all our STRENGTH.
    					</p>
    				</div>

    			</div><!-- * End of Row -->



    		</div><!-- * End of Narrow -->
    	</div><!-- * End of Jumbotron -->


    </div>
    <!-- * End of Features section -->


    <!-- * Start BBC Universal Exports Section -->
    <div id="UnviersalExports" class="offset">
    	<div class="fixed-background">
    		<div class="row dark">
    			<div class="col-12 text-center">
    				<h3 class="heading text-center" data-aos="fade-up" data-aos-anchor-placement="center-bottom"
    					style="color: white;">BBC
    					Universal Exports</h3>
    				<div class="heading-underline" data-aos="fade-up" data-aos-anchor-placement="center-bottom"></div>
    				<p class="text-center" data-aos="fade-up" data-aos-anchor-placement="center-bottom">BBC Universal
    					Exports, is an international trading company
    					located in
    					Chennai, India. As specialists in sourcing exclusive products and trade consulting
    					for the
    					global market, we facilitate trading partnerships between our vendor associates and
    					clients
    					across the world. We are proud applicants of WTO (World Trade Organization) and CWBF
    					(Commonwealth Business Forum). BBCUE provides its customers with unparalleled
    					business and trade
    					support. With access to a strong network of various industries in different
    					segments, we offer a
    					wide range of exclusive products, as trade and services to our customers Globally.
    					Through
    					experienced learning of our ability to consolidate and leverage vertical and
    					horizontal
    					integration, our company has established itself as one of India’s fastest growing
    					trade and
    					consulting company, as we continue to build on our global vision.
    				</p>
    				<a href="#Clients" class="btn btn-outline-light btn-lg" data-aos="fade-up"
    					data-aos-anchor-placement="center-bottom">Our Clients</a>

    			</div>


    		</div><!-- * End of Row Dark -->


    		<div class="fixed-wrap">
    			<div class="fixed">

    			</div>
    		</div>


    	</div><!-- * End of fixed background -->
    </div>
    <!-- * End of BBC Universal Exports section -->


    <div id="Clients" class="offset">

    	<h2 class="text-center" data-aos="fade-up" data-aos-anchor-placement="center-bottom">Our Clients</h2>
    	<div class="heading-underline" data-aos="fade-up" data-aos-anchor-placement="center-bottom"></div>


    	<div class="row col d-flex justify-content-center">
    		<!-- Client 1 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/aditya brila.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Aditya Brila group</h3>
    			</div>
    		</div>

    		<!-- Client 2 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/appasamyrealestates.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Aditya Brila group</h3>
    			</div>
    		</div>

    		<!-- Client 33 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/apolo.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Appaswamy</h3>
    			</div>
    		</div>

    		<!-- Client 4 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Balaji.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Balaji</h3>
    			</div>
    		</div>

    		<!-- Client 5 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Bajaj.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Bajaj</h3>
    			</div>
    		</div>

    		<!-- Client 6 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Brigade.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Brigade</h3>
    			</div>
    		</div>



    		<!-- Client 7 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/ceebros.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Ceebros</h3>
    			</div>
    		</div>

    		<!-- Client 8 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Ceat.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Ceat</h3>
    			</div>
    		</div>


    		<!-- Client 9 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Cognizant.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Cognizant</h3>
    			</div>
    		</div>

    		<!-- Client 10 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Embassy Group.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Embassy Group </h3>
    			</div>
    		</div>

    		<!-- Client 11 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Genting.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Genting</h3>
    			</div>
    		</div>




    		<!-- Client 12 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Gandhi Research Foundation.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Ghandi Research Foundation</h3>
    			</div>
    		</div>

    		<!-- Client 13 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Glenmark 1.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Glenmark</h3>
    			</div>
    		</div>

    		<!-- Client 14 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Goodrej.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Goodrej</h3>
    			</div>
    		</div>

    		<!-- Client 15 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Haldirams.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Haldiram's</h3>
    			</div>
    		</div>

    		<!-- Client 16 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Hyatt Regency.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Hyatt Regency</h3>
    			</div>
    		</div>

    		<!-- Client 17 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500"">
    			<img class=" card-img-top" src="clientsImages/Honda.png
    			" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Honda</h3>
    			</div>
    		</div>

    		<!-- Client 18 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Hiranandani.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Hiranandani</h3>
    			</div>
    		</div>

    		<!-- Client 19 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Hinduja.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Hinduja</h3>
    			</div>
    		</div>

    		<!-- Client 20 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Infosys.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Infosys</h3>
    			</div>
    		</div>

    		<!-- Client 21 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/ITC Hotels.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">ITC Hotels</h3>
    			</div>
    		</div>

    		<!-- Client 22 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Jain irrigation system.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Jain Irrigation System</h3>
    			</div>
    		</div>

    		<!-- Client 23 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Jain housing.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Jain Housing</h3>
    			</div>
    		</div>

    		<!-- Client 24 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/lasern and toubro.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Larsen and toubro</h3>
    			</div>
    		</div>

    		<!-- Client 25 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Meridien.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Meridien</h3>
    			</div>
    		</div>

    		<!-- Client 26 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/lodha.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Lodha</h3>
    			</div>
    		</div>

    		<!-- Client 27 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Maruti Suzuki.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Maruti Suzuki</h3>
    			</div>
    		</div>

    		<!-- Client 28 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Microsoft.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Microsoft</h3>
    			</div>
    		</div>

    		<!-- Client 29 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/nift.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Nift</h3>
    			</div>
    		</div>

    		<!-- Client 30 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/olympia.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Olympia</h3>
    			</div>
    		</div>

    		<!-- Client 31 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Pfizer.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Pfizer</h3>
    			</div>
    		</div>

    		<!-- Client 32 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Prestige group.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Prestige group</h3>
    			</div>
    		</div>

    		<!-- Client 33 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Ramoji.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Ramoji</h3>
    			</div>
    		</div>

    		<!-- Client 34 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Reliance Industries limited.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Reliance Industries limited</h3>
    			</div>
    		</div>

    		<!-- Client 35 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Renault.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Renault</h3>
    			</div>
    		</div>

    		<!-- Client 36 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Earth World.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Earth World</h3>
    			</div>
    		</div>

    		<!-- Client 37 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/SBI.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">SBI</h3>
    			</div>
    		</div>

    		<!-- Client 38 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/S & S.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">S & S</h3>
    			</div>
    		</div>

    		<!-- Client 39 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Shapoorji Pallonji.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Shapoorji Pallonji</h3>
    			</div>
    		</div>

    		<!-- Client 41 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Taj.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Taj</h3>
    			</div>
    		</div>

    		<!-- Client 42 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/TATA 1.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">TATA</h3>
    			</div>
    		</div>

    		<!-- Client 43 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Oberoi Group.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Oberoi Group</h3>
    			</div>
    		</div>

    		<!-- Client 44 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Toyota.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Toyota</h3>
    			</div>
    		</div>

    		<!-- Client 46 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/The Residency Hotels.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">The Residency Hotels</h3>
    			</div>
    		</div>

    		<!-- Client 47 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/The Leela.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">The Leela</h3>
    			</div>
    		</div>

    		<!-- Client 48 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/Unilever.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">Unilever</h3>
    			</div>
    		</div>

    		<!-- Client 49 -->
    		<div class="card" style="width: 18rem;" data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">
    			<img class="card-img-top" src="clientsImages/WIPRO.png" alt="Card image cap">
    			<div class="card-body">
    				<h5 class="card-text text-center">WIPRO</h3>
    			</div>
    		</div>











    	</div>`


    	<!-- * Start BBC Innova Exports Section -->
    	<div id="BBC Innova" class="offset">
    		<div class="fixed-background">
    			<div class="row dark">
    				<div class="col-12 text-center">
    					<h3 class="heading text-center" data-aos="fade-up" data-aos-anchor-placement="center-bottom"
    						style="color: white;">BBC
    						Innova</h3>
    					<div class="heading-underline" data-aos="fade-up" data-aos-anchor-placement="center-bottom">
    					</div>
    					<p class="text-center" data-aos="fade-up" data-aos-anchor-placement="center-bottom" style="">BBC
    						INNOVA
    						is
    						an exclusive associate for “RENOVO SYNTHETIC PLASTER & PAINTS ”, with excellent service and
    						track record for over a decade. Today the company is associated for its services with
    						leading Real Estate Promoters, Hotels, Industries, SEZ's and various Infrastructure
    						organizations on pan India basis. Our core competency lies in providing our clients with the
    						most appropriate solution within the given range of products & services that we have on
    						offer. At BBC INNOVA we specialize in outdoor painting using exclusively Renovo products,
    						which come with a life span of 20 years and beyond, thus making it a one of its kind
    						revolutionary product in the market. Learning the market demand, BBC INNOVA further stepped
    						into the Interior contracting segment wherein our clients are provided with TURNKEY INTERIOR
    						EXECUTIONS & SOLUTIONS which is known for its high quality & state of the art workmanship,
    						finishing & technology.
    					</p>
    					<!-- <a href="#" class="btn btn-outline-light btn-lg" data-aos="fade-up"
    						data-aos-anchor-placement="center-bottom">Contact Details</a> -->

    				</div>


    			</div><!-- * End of Row Dark -->


    			<div class="fixed-wrap">
    				<div class="fixed">

    				</div>
    			</div>


    		</div><!-- * End of fixed background -->
    	</div>
    	<!-- * End of BBC Universal Exports section -->


    	<div id="Contact" class="offset">
    		<!-- Footer -->
    		<footer class="page-footer font-small indigo" id="section6">
    			<h1 class="text-center" style="padding-top: 20px;
    padding-bottom: 20px; ">Contact Details</h1>
    			<!-- Footer Links -->
    			<div class="container text-center text-md-left">

    				<!-- Grid row -->
    				<div class="row">


    					<!-- Grid column -->

    					<hr class="clearfix w-100 d-md-none">

    					<!-- Grid column -->
    					<div class="col-md-3 mx-auto">

    						<!-- Links -->
    						<h5 class="font-weight-bold text-uppercase mt-3 mb-4">Email</h5>

    						<ul class="list-unstyled">
    							<li>
    								<a href="mailto:bbcue@bohragroup.in">bbcue@bohragroup.in</a>
    							</li>
    							<li>
    								<a href="mailto:bbcinnova@bohragroup.in">bbcinnova@bohragroup.in</a>
    							</li>
    							<li>
    								<a href="mailto:best@bohragroup.in">best@bohragroup.in</a>
    							</li>

    						</ul>

    					</div>
    					<!-- Grid column -->

    					<hr class="clearfix w-100 d-md-none">

    					<!-- Grid column -->
    					<div class="col-md-3 mx-auto">

    						<!-- Links -->
    						<h5 class="font-weight-bold text-uppercase mt-3 mb-4">Phone</h5>

    						<ul class="list-unstyled">
    							<li>
    								<a href="tel:+9144-28292111">(+91)44-28292111</a>
    							</li>
    							<li>
    								<a href="tel:+919943308899">(+91) 9943308899</a>
    							</li>

    						</ul>

    					</div>
    					<!-- Grid column -->

    					<hr class="clearfix w-100 d-md-none">

    					<!-- Grid column -->
    					<div class="col-md-3 mx-auto">

    						<!-- Links -->
    						<h5 class="font-weight-bold text-uppercase mt-3 mb-4">Address</h5>

    						<ul class="list-unstyled">
    							<li>
    								<a href="#!">Bohra Buisness Chambers</a>
    							</li>
    							<li>
    								<a href="#!">No.617, ,1st floor, Bharat Kumar Bhawan</a>
    							</li>
    							<li>
    								<a href="#!">Khivraj Compound, Anna Sallai</a>
    							</li>
    							<li>
    								<a href="#!">Chennai - 600 006, TN</a>
    							</li>
    						</ul>

    					</div>
    					<!-- Grid column -->

    				</div>
    				<!-- Grid row -->

    			</div>
    			<!-- Footer Links -->

    			<!-- Copyright -->
    			<div class="footer-copyright text-center py-3">Copyright © Bohra Group | All Rights Reserved
    			</div>
    			<!-- Copyright -->

    		</footer>
    		<!-- Footer -->

    	</div>









    	<!--data-aos="zoom-in" data-aos-offset="500" data-aos-duration="500">-->






    	<!--- Script Source Files -->
    	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
    		integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
    		crossorigin="anonymous"></script>
    	<script src="https://use.fontawesome.com/releases/v5.5.0/js/all.js"></script>
    	<!--- End of Script Source Files -->
    	<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    	<script>
    		AOS.init();
    	</script>

</body>

</html>

<!--- Check out my courses! -->
<!-- <div class="udemy-course" style="position: fixed; bottom: 0; right: 0; margin-bottom: -5px; z-index: 100;">
	<a href="https://w3newbie.com/courses" target="_blank"
		style="z-index: 999!important; cursor: pointer!important;"><img
			src="https://www.w3newbie.com/wp-content/uploads/nuno-course-banner.png"
			style="max-width: 100%; min-width: 100%;"></a>
</div> -->
