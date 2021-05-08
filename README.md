# Tugas_Praktikum_UTS

<!DOCTYPE html>
  <html>
    <head>
      <!--Import Google Icon Font-->
      <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
      <!--Import materialize.css-->
      <link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>

      <!--Let browser know website is optimized for mobile-->
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
      <title>tugas praktikum uts</title>
      
    </head>

    <body>
    <!-- navbar -->
    <div class="navbar-fixed">
      <nav class="grey lighten-3">
        <div class="container">
          <div class="nav-wrapper">
            <a href="#!" class="brand-logo">Logo</a>
            <a href="#" data-target="mobile-nav" class="sidenav-trigger"><i class="material-icons">menu</i></a>
            <ul class="right hide-on-med-and-down black-text">
              <li><a href="">HOME</a></li>
              <li><a href="">ABOUT</a></li>
              <li><a href="">WORK</a></li>
              <li><a href="">PROCESS</a></li>
              <li><a href="">SERVICES</a></li>
              <li><a href="">TESTIMONIALS</a></li>
              <li><a href="">CONTACT</a></li>
            </ul>
          </div>
        </div>
      </nav>
    </div>

    <!-- sidenav -->
    <ul class="sidenav" id="mobile-nav">
    </ul>

    <!--header-->
    <section id="header" class="header">
      <img src="img/header_01.jpg">
      <div class="container">
        <div class="row">
          <div class="col s5 push-s7"><span class="flow-text"><div class="row">
        <div class="col s10 push-s1">
          
          <span class="flow-text">We Design and Develop</span>
          <h6>We are a new design studio based in USA. We have over 
            20 years of combined experience, and know a thing or two 
            about designing websites and mobile apps.</h6>
            <a class="waves-effect waves-light btn">CONTACT US</a>
        </div>
      <div class="col s5 pull-s7"><span class="flow-text"></span></div>
    </div></span></div>
          <div class="col s7 pull-s5"><span class="flow-text"></span></div>
        </div>
        </div>
        
      </div>
    </section>

    <!--About Us-->
    <section id="about" class="about">
      <div class="container">
        <div class="row">
          <h3 class="center">About Us</h3>
          <div class="col s7 push-s2 center">
            <p>Divide have don't man wherein air fourth. Own itself make have night won't make. 
              A you under Seed appear which good give. Own give air without fowl moveth dry first 
              heaven fruit, dominion she'd won't very all.</p>
          </div>
        </div>
      </div>
    </section>

    <!--profesional skills-->
    <section id="skills" class="skills">
      <div class="container">
        <div class="row">
          
        </div>
        <div class="col m6">
          <h5>Profesional Skills</h5>
        </div>
        <div class="col m6 ">
          <p>UI/IX DESIGN 75%</p>
          <div class="progress">
            <div class="determinate" style="width: 75%"></div>
          </div>
        </div>
        <div class="col m6 bold">
          <p>WEB DEVELOPMENT 90%</p>
          <div class="progress">
            <div class="determinate" style="width: 90%"></div>
          </div>
        </div>
        <div class="col m6 bold">
          <p>MARKETING 65%</p>
          <div class="progress">
            <div class="determinate" style="width: 65%"></div>
          </div>
        </div>
      </div>
    </section>

    <!--portofolio-->
    <section class="portfolio" id="portfolio">
      <div class="container">
        <div class="row">
          <div class="col-sm-12 text-center"></div>
        </div>
      </div>
      <div class="row">
        <div class="col-sm-4">
          <a href="" class="thumbnail">
          <img src="img/P1234.jpg" class="responsive-img">
          <img src="img/P5678.jpg" class="responsive-img">
          <img src="img/P9101112.jpg"class="responsive-img">
        </a>
        </div>
      </div>
    </section>

    <!--need a project-->
    <section class="project" id="project">
      <div class="row">
        <div class="col-sm-12 text-center">
          <h4 class="center">Need a Project</h4>
          <div class="col s7 push-s2 center">
            <p>Let us know what you're looking for in an agency. We'll take a look and see 
              if this could be the start of something beautiful.</p>
              
            <div class="row">
              <form class="col s12">
                <div class="row">
                  <div class="input-field col s6">
                    <input id="first_name" type="text" class="validate">
                    <label for="first_name">First Name</label>
                  </div>
                  <div class="input-field col s6">
                    <input id="last_name" type="text" class="validate">
                    <label for="last_name">Last Name</label>
                  </div>
                </div>
                <div class="row">
                  <div class="input-field col s12">
                    <input id="disabled" type="text" class="validate">
                    <label for="disabled">Your Title</label>
                  </div>
                </div>
                <div class="row">
                  <div class="input-field col s12">
                    <input id="password" type="password" class="validate">
                    <label for="password">Your Comment</label>
                  </div>
                </div>
              </form>
          </div>
        </div>        
      </div>    
    </section>

      <!--JavaScript at end of body for optimized loading-->
      <script type="text/javascript" src="js/materialize.min.js"></script>
      <script>
          document.addEventListener('DOMContentLoaded', function() {
      var elems = document.querySelectorAll('.sidenav');
      var instances = M.Sidenav.init(elems, options);
      });


      
      </script>
    </body>
      <footer>
        <h6>Piroll Design, Inc.</h6>
        <p>&copy; 2017 Piroll All Right reserved.</p> 
        <p>Designed by robirunk.</p>
      </footer>

  </html>


  <style>
    /* label color */
   .input-field label {
     color: #000;
   }
   /* label focus color */
   .input-field input[type=text]:focus + label {
     color: #000;
   }
   /* label underline focus color */
   .input-field input[type=text]:focus {
     border-bottom: 1px solid #000;
     box-shadow: 0 1px 0 0 #000;
   }
   /* valid color */
   .input-field input[type=text].valid {
     border-bottom: 1px solid #000;
     box-shadow: 0 1px 0 0 #000;
   }
   /* invalid color */
   .input-field input[type=text].invalid {
     border-bottom: 1px solid #000;
     box-shadow: 0 1px 0 0 #000;
   }
   /* icon prefix focus color */
   .input-field .prefix.active {
     color: #000;
   }

   project {
     font: center;
   }

     footer {
  clear:both;
  background-color:#1d1d1d;
  padding:20px;
  color:#eee;
  font-size: 10px;
 }
  </style>
