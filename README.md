# HammerSportsCards
Need help for an E-commerce website. I want to make this look as incredible as possible. Open to any suggestions!
<!DOCTYPE html>
<html lang="en-US">

<!--All the links to run the scripts-->
	<head>
	<link rel='stylesheet' href='style.css'/>
	<script src='script.js'></script>
		<link type="text/css" rel="stylesheet" href="stylesheet.css"/>
		<title>Hammer Sports Cards</title>
	<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>

<!--Carousel script-->
<style>
  .carousel-inner > .item > img,
  .carousel-inner > .item > a > img {
      width: 70%;
      margin: auto;
  }
  </style>
 
 
<!--This is the script to toggle the panels-->
<script> 
$(document).ready(function(){
    $("#flip").click(function(){
        $("#panel").slideToggle("slow");
    });
});
</script>

<style> 
#panel, #flip {
    padding: 5px;
    text-align: center;
    background-color: #0000FF;
    border: solid 1px #c3c3c3;
    color:silver;
}

#panel {
    padding: 50px;
    display: none;
}
</style>

	</head>
	
<!--Navigation Bar-->
	<body>
	<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span> 
      </button>
      <a class="navbar-brand" href="#">Hammer Sports Cards</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li><a href="www.HammerSportsCards.com/index.html">Home</a></li>
        <li class="active"><a href="www.HammerSportsCards.com/aboutus.html">About Us</a></li> 
        <li><a href="http://www.ebay.com/usr/mltreasures1?_trksid=p2047675.l2559">Available Items</a></li>
        <li><a href="www.HammerSportsCards.com/contactus.html">Contact Us</a></li>
      </ul>
    </div>
  </div>
</nav>

<!--Here's the buttons to Linkedin and Facebook-->
	<div class="btn-group btn-group-lg">
	    <a href="https://www.linkedin.com/profile/view?id=423376456&trk=nav_responsive_tab_profile" class="btn btn-info" role="button" button type="button" class="btn btn-primary">Connect with me on Linkedin!</a>
	    </div>
	    
<!--Just below is the title-->
<div class="jumbotron">
	<h1>Hammer Sports Cards</h1>
	<h2 class="Description">Founded and Headed by Mike Langhammer</p>
</div>
<div class="row">

<!--Here is the about us paragraphs and pictures-->
<div class="container">
  <h2>About Us</h2>
  <p>Hammer Sports Cards has been a prosperous business in the sports memorabilia industry offering prices no one else matches</p>
  <div class="panel panel-primary panel-group">
    <div class="panel panel-primary panel-default">
      <div class="panel-heading">Michael Langhammer Jr.<img src = www.HammerSportsCards.com/MikeLanghammer.jpeg></src></div>
      <div class="panel-body">Mike began his career with a huge interest in sports as a young kid. He quickly developed a passion for business amidst his high school years and decided to incorporate both into his life.</div>
	  <div class="panel-body">Thus Hammer Sports Cards was founded in 2013 and has since then continued to see a steady growth rate. The company operates in the Chicagoland Area and continues to expand its borders to surrounding areas.</div>
	</div>
    <div class="panel panel-primary panel-default">
      <div class="panel-heading">Eric Noelke Jr.<img src = www.HammerSportsCards.com/EricNoelke.jpeg></src></div>
      <div class="panel-body">Eric attends the University of Illinois at Urbana-Champaign studying Finance with a minor in Computer Science and has interned at a small derivatives trading firm.</div>
      <div class="panel-body"> Eric joined the company in 2015 as the Chief Technology Officer. He built up the company's online presence through an e-commerce website linked to Ebay and Linkedin.</div>
	</div>
  </div>
</div>

    
    </body>
</html>

<!DOCTYPE html>
<html lang="en-US">

<!--All the links to run the scripts-->
	<head>
	<link rel='stylesheet' href='style.css'/>
	<script src='script.js'></script>
		<link type="text/css" rel="stylesheet" href="stylesheet.css"/>
		<title>Hammer Sports Cards</title>
	<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
<style>
  .carousel-inner > .item > img,
  .carousel-inner > .item > a > img {
      width: 70%;
      margin: auto;
  }
  </style>
	</head>
	
<!--Navigation Bar-->
	<body>
	<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span> 
      </button>
      <a class="navbar-brand" href="#">Hammer Sports Cards</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li><a href="www.HammerSportsCards.com/index.html">Home</a></li>
        <li><a href="www.HammerSportsCards.com/aboutus.html">About Us</a></li> 
        <li><a href="www.HammerSportsCards.com/availableitems.html">Available Items</a></li>
        <li class="active"><a href="www.HammerSportsCards.com/contactus.html">Contact Us</a></li>
      </ul>
    </div>
  </div>
</nav>

<!--Here's the buttons to Linkedin and Facebook-->
	<div class="btn-group btn-group-lg">
	    <a href="https://www.linkedin.com/profile/view?id=423376456&trk=nav_responsive_tab_profile" class="btn btn-info" role="button" button type="button" class="btn btn-primary">Connect with me on Linkedin!</a>
	    </div>
	    
<!--Just below is the title-->
<div class="jumbotron">
	<h1>Contact Hammer Sports Cards</h1>
	<h2 class="Description">Email Hammers Sports Cards at <a href="mailto:mlanghammer49@gmail.com">mlanghammer49@gmail.com</a> with your name, contact information and any information about a product you are interested in buying or selling. We value your business dearly and thank you for choosing Hammer Sports Cards!</p>
</div>
<div class="row">

</body>
</html>

<!DOCTYPE html>
<html lang="en-US">

<!--All the links to run the scripts-->
	<head>
	<link rel='stylesheet' href='style.css'/>
	<script src='script.js'></script>
		<link type="text/css" rel="stylesheet" href="stylesheet.css"/>
		<title>Hammer Sports Cards</title>
	<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
  <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
<style>
  .carousel-inner > .item > img,
  .carousel-inner > .item > a > img {
      width: 70%;
      margin: auto;
  }
  </style>
	</head>
	
<!--Navigation Bar-->
	<body>
	<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span> 
      </button>
      <a class="navbar-brand" href="#">Hammer Sports Cards</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="www.HammerSportsCards.com/index.html">Home</a></li>
        <li><a href="www.HammerSportsCards.com/aboutus.html">About Us</a></li> 
        <li><a href="www.HammerSportsCards.com/availableitems.html">Available Items</a></li>
        <li><a href="www.HammerSportsCards.com/contactus.html">Contact Us</a></li>
      </ul>
    </div>
  </div>
</nav>

<!--Here's the button to Linkedin-->
	<div class="btn-group btn-group-lg">
	    <a href="https://www.linkedin.com/profile/view?id=423376456&trk=nav_responsive_tab_profile" class="btn btn-info" role="button" button type="button" class="btn btn-primary">Connect with me on Linkedin!</a>
	    </div>
	    
<!--Just below is the title-->
<div class="jumbotron">
	<h1>Hammer Sports Cards</h1>
	<h2 class="Description">Founded and Operated by Michael Langhammer</p>
</div>
<div class="row">

<!--Paragraphs of information-->
    <div class="col-sm-4">
	<div class="panel panel-primary">
      <div class="panel-heading">Overview</div>
      <div class="panel-body">If you are looking to buy or sell any size, type or form of sports memorabilia then you're in the right place! We buy any type of sports memorabilia.</div>
    </div>
    </div>
    
    <div class="col-sm-4">
    <div class="panel panel-primary">
      <div class="panel-heading">Location</div>
      <div class="panel-body">Business is primarily operated and run in the Greater Chicagoland Area, however the CEO attends trade shows in St. Louis, MO and Louisville, KY bimonthly.</div>
    </div>
    </div>
    
    <div class="col-sm-4">
    <div class="panel panel-primary">
      <div class="panel-heading">Priorities</div>
      <div class="panel-body">As a small business we place relationships with our clients at the highest of our priorities. Along with that priority comes customer satisfaction to ensure a favored purchase/sale on both ends of the deal. At Hammer Sports Cards quality comes before quantity and we stand by this.</div>
    </div>
	</div>

<!--The Carousel-->
<div class="container">
  <br>
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
      <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">

      <div class="item active">
        <img src="www.HammerSportsCards.com/KrisBryant.jpeg" alt="2014 Bowman Chrome KRIS BRYANT #/50 Blue Wave Refractor Auto BLACK LABEL BGS 10!" width="460" height="345">
        <div class="carousel-caption">
          <h3>Kris Bryant</h3>
          <p>A Chicago Cubs Rookie's baseball card in pristine condition and in high demand</p>
        </div>
      </div>

      <div class="item">
        <img src="www.HammerSportsCards.com/TomBradyPatch.jpeg" alt="2014 Panini Flawless TOM BRADY #/5 Green Emerald Logo Patriots Patch Auto!" width="460" height="345">
        <div class="carousel-caption">
          <h3>Tom Brady Patch</h3>
          <p>Tom Brady's Emerald Green Patch</p>
        </div>
      </div>

      <div class="item">
        <img src="www.HammerSportsCards.com/TomBradyHelmet.jpeg" alt="TOM BRADY Signed Patriots Full Size Helmet Tristar SB XXXIX Champs LE #/12 RARE" width="460" height="345">
        <div class="carousel-caption">
          <h3>Tom Brady Helmet</h3>
          <p>A RARE full size signed Tom Brady Helmet from Superbowl XXXIX</p>
        </div>
      </div>

      <div class="item">
        <img src="www.HammerSportsCards.com/LebronJamesTicket.jpeg" alt="2007-08 Upper Deck Black LEBRON JAMES #01/15 Gold Ticket Ink Auto!" width="460" height="345">
        <div class="carousel-caption">
          <h3>Lebron James Ticket</h3>
          <p>An Upper Deck Black and Gold Ticket to see Lebron James from 2007-2008</p>
        </div>
      </div>

	  </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>
    
    </body>
</html>

body {
	font-family:Garamond;
}

.jumbotron {
    font-family:Garamond;
}

h1 {
    font-size:65px;
    text-align:center;
    text-decoration:underline;
    font-family:Garamond;
    color:black;
};

.Description {
    text-align:center;
    font-family:Garamond;
};

h2 {
    text-align:center;
    text-decoration:none;
    color:black
	font-family:Garamond;
	font-size:45px;
};

h3 {
    font-size:20px;
    text-align:left;
    text-decoration:underline;
    margin-right:50px;
    margin-left:100px;
	font-family:Garamond;
	font-size:24px;
};

.col-sm-4 {
    font-family:Garamond;
    font-size:20px;
};

a {
	text-decoration: none;
	color: #0267FF;
	font-family: Garamond, sans-serif;
	font-size:18px;
};

span {
	font-weight: bold;
	font-size: 30px;
	color: white;
	font-family:Garamond;
};

ul {
    list-style-type: none;
    margin: 10;
	font-family:Garamond;
};

li {
    display: inline;
    border-radius: 5px;
	border: 2.5px solid #DCD2EE;
	font-weight: bold;
    padding: 3;
	font-family:Garamond;
};

.Network {
    border-radius: 5px;
	border: 2px solid #6495ED;
	background-color: #BCD2EE;
	height: 70px;
	width: 170px;
	margin: auto;
	text-align: center;
	float: right;
	display:inline;
	font-family:Garamond;
};
