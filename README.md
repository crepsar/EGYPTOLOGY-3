el-Adaïma
============
html lang="en"><script id="tinyhippos-injected">if (window.top.ripple) { window.top.ripple("bootstrap").inject(window, document); }</script><head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="icon" href="../../favicon.ico">

    <title>DAEA</title>

    <!-- Bootstrap core CSS -->
    <link href="css/bootstrap.css" rel="stylesheet">

    <!-- Custom styles for this template -->
    <link href="css/style.css" rel="stylesheet">
    <link rel="stylesheet" href="css/leaflet.css" />

    <!-- Just for debugging purposes. Don't actually copy these 2 lines! -->
    <!--[if lt IE 9]><script src="../../assets/js/ie8-responsive-file-warning.js"></script><![endif]-->
    <!--<script src="js/ie-emulation-modes-warning.js"></script>-->

    <!-- IE10 viewport hack for Surface/desktop Windows 8 bug -->
    <!--<script src="js/ie10-viewport-bug-workaround.js"></script>-->

    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>

  <body>

      
    <!-- Fixed navbar -->
    <div class="navbar navbar-default navbar-fixed-top" role="navigation">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="http://matrix-msu.github.io/daea/index.html"><strong>Digital Atlas of Egyptian Archaeology</strong></a>
        </div>
        <div class="collapse navbar-collapse">
          <ul class="nav navbar-nav">
            <li><a href="http://matrix-msu.github.io/daea/index.html">Atlas</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown">About <span class="caret"></span></a>
              <ul class="dropdown-menu" role="menu">
                <li><a href="http://matrix-msu.github.io/daea/projects.html">About the Project</a></li>
				<li><a href="http://matrix-msu.github.io/daea/class.html">About the Class</a></li>
                <li><a href="http://matrix-msu.github.io/daea/students.html">Students</a></li>
                <li><a href="http://matrix-msu.github.io/daea/colophon.html">Colophon</a></li>
              </ul>
            </li>
          </ul>
        </div><!--/.nav-collapse -->
      </div>
    </div>

    <!-- Begin page content -->
      
     <div id="detail">
      <h1>SITE NAME</h1>
      <h3>TIME PERIOD</h3>
	  <h4>AUTHOR</h4>
         <h3>FIRST SECTION HEADING</h3>
		 <hr><!--this draws a line across the page, which I put under each section heading in the example-->
		 <p>Paragraph text goes between these</p>
		 <a href="#" rel="citation" data-toggle="popover" data-content=""><!--this is the required <a href> beginning tag for inline reference popups-->
		 <br><!--this creates a break, to separate things a little better-->
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
		 
	</div>
     
       <br>
         <br>

    <div class="footer2">
      <div class="container">
        <!--<p class="text-muted">Place sticky footer content here.</p>-->
      </div>
    </div>


    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    <script src="leaflet-omnivore-master/leaflet-omnivore.js"></script>
    <script src="js/leaflet.js"></script>
	<script type="text/javascript">
		$(document).ready(function(){
			$("a[rel=citation]").popover({
				placement : 'top'
			}).click(function (p) {
				p.preventDefault();
				var $self = $(this);
				setTimeout(function () {
					$self.popover('hide');
				}, 4000);
			});
		});
	</script>
	</body></html>
	
