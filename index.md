<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, shrink-to-fit=no, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <title>E-Portfolio Joppe Duthoit</title>

    <!-- Styles -->
	<link href="https://fonts.googleapis.com/css?family=Source+Code+Pro:300,400,600" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600" rel="stylesheet">
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/styles.css" rel="stylesheet">

    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
        <script src="https://oss+.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
        <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->

</head>
<body>
    <div id="wrapper">

        <!-- Sidebar -->
        <div id="sidebar-wrapper">
			<p>E-Portfolio<br> Joppe Duthoit</p>
            <ul class="sidebar-nav">
                <li class="sidebar-brand">
                </li>
                <li>
                    <a href="#home">HOME</a>
                </li>
				<li>
                    <a href="#projecten">PROJECTEN</a>
                </li>
                <li>
                    <a href="competenties.html">COMPETENTIES</a>
				</li>
				<li>
					<a href="#cv">CV</a>
				</li>
                <li>
                    <a href="#contact">CONTACT</a>
                </li>
            </ul>
        </div>
        <!-- end of sidebar wrapper -->


        <!-- Page Content -->
        <div id="page-content-wrapper">
            <div class="container-fluid">
                <div class="row">
                    <div id="home" class="col-lg-12">
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <h1>Home</h1>
                        <h2>Welkom op mijn e-portfolio</h2>
                        <br>
                        <p>Ik ben Joppe Duthoit student toegepaste informatica aan de hogeschool UC Leuven Limburg op campus Proximus in haasrode en dit is mijn e-portfolio.</p>
                        <br>
                        <br>
                        <h2>Over mijzelf</h2>
                        <br>
                        <p>Met deze website probeer ik een zo goed mogelijk beeld te scheppen van wie ik ben en wat ik allemaal bereikt heb in mijn schoolcarrière waar ik zelf fier op ben.</p>
                        <br>
					</div> <!-- end of introduction -->
                    

					<div class="col-lg-12"><hr></div> <!-- gray separator line -->
                    
                    <div id="projecten" class="col-lg-12">
                        <h1>Projecten</h1>
                        <br>
                        <br>
                        <p>Voor het vak multimedia hebben we in C++ eenprogramma geschreven dat midi files inleest en hiervan een beatmap maakt.</p>
                        <br>
                        <img src="multiple-instruments.png" width="300" height="300">
                        <br>
                        <br>
                        <br>
                        <p>Voor het vak Web4 hebben we een asynchrone <a href="https://github.com/Web4academiejaar20192020semester3/DuthoitJoppe-ChatApp">chat-website</a> gemaakt met behulp van jquery.</p>
                        <br>
                        <br>
                        <p>Voor het vak Internet Programmeren hebben we een website gemaakt met behulp van het framework spring.</p>
                        <br>
                        <img src="OOO.png" width="500" height="354">
					</div> <!-- end of introduction -->
                    

					<div class="col-lg-12 lijn"><hr></div> <!-- gray separator line -->
                    
                    <div id="contact" class="col-lg-12">
                        <br>
                        <br>
                        <h1>CV</h1>
                        <br>
                        <br>
                        <p><a href="cv.pdf" class="myButton">Open CV</a></p>
                        <br>
                        <br>
					</div> <!-- end of introduction -->

					<div class="col-lg-12"><hr></div> <!-- gray separator line -->
                    
                    <div id="cv" class="col-lg-12">
                        <br>
                        <br>
                        <h1>Contact</h1>
                        <br>
                        <br>
                        <p>Ik ben altijd te bereiken via email: joppe.duthoit@gmail.com</p>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
					</div> <!-- end of introduction -->
                </div>
            </div>
        </div> <!-- end of page-content-wrapper -->
    </div> <!-- end of wrapper -->
    

    <!-- Scripts Libraries -->
    <script src="js/jquery.js" type="text/javascript"></script>
    <script src="js/bootstrap.min.js" type="text/javascript"></script>

	
	<!-- Custom Scripts -->
    <script>
    <!-- Menu Toggle Script -->
	$("#menu-toggle").click(function(e) {
        e.preventDefault();
        $("#wrapper").toggleClass("toggled");
    });
	
	/* Smooth Scrolling To Anchors  */
		$(function() {
			$('a[href*="#"]:not([data-toggle="tab"])').click(function() {
				if (location.pathname.replace(/^\//,'') == this.pathname.replace(/^\//,'') && location.hostname == this.hostname) {
					var target = $(this.hash);
					target = target.length ? target : $('[name=' + this.hash.slice(1) +']');
					if (target.length) {
						$('html, body').animate({
							scrollTop: target.offset().top
						}, 700);
						return false;
					}
				}
			});
		});
	</script>

</body>
</html>
