<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="css/style.css" />
    <link rel="shortcut icon" href="Images/page_5.png" type="image/x-icon" />

    <link
      href="https://fonts.googleapis.com/css2?family=Abel&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <title>SM</title>
  </head>
  <body>
    <div class="container">
      <div class="top-nav">
        <div class="logo-container">
          <img class="nav-img" src="Images/page_5.png" alt="logo" />
          <span class="nav-span">Strategic Management Experts</span>
        </div>

        <div class="nav-a-container">
          <ul class="nav-ul" id="myTopnav">
            
            <a href="#" class="nav-a" id="current">HOME</a>
            <a href="#" class="nav-a">SERVICES</a>
            <a href="#" class="nav-a">OUR TEAM</a>
            <a href="#" class="nav-a">RESOURCES</a>
            <a href="#" class="nav-a">CONTACT US</a>
            <a href="javascript:void(0);" class="icon" onclick="myFunction()"><li class="fa fa-bars"></li></a>
            
          </ul>
        </div>
      </div>

      <div class="under-nav">
        <p class="p-under-nav">
          Try not to be a man of success. <br />
          Rather become <span>a man of Value.</span>
        </p>
      </div>
      
      <div class="cc-container">
        <div class="cards-container">
          <div class="card">
            <div class="about-img"></div>
            <div>
              <h3>About Us</h3>
              <p class="p-card">
                SM Experts comes to you with the expertise of some of the top
                notch professionals in SM Experts deliver to our clients the
                solutions that meet their needs and requirements.
              </p>
            </div>
            <div class="read-more">
              <a href="#" class="a-card">READ MORE</a>
            </div>
          </div>
          <div class="card">
            <div class="vision-img"></div>
            <div class="txt-container">
              <h3>Our Vision</h3>
              <p class="p-card">
                SM Experts comes to you with the expertise of some of the top
                notch professionals in SM Experts deliver to our clients the
                solutions that meet their needs and requirements.
              </p>
              <div class="read-more">
                <a href="#" class="a-card">READ MORE</a>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="value-img"></div>
            <div>
              <h3>Our Values</h3>

              <p class="p-card">
                SM Experts comes to you with the expertise of some of the top
                notch professionals in SM Experts deliver to our clients the
                solutions that meet their needs and requirements.
              </p>
              <div class="read-more">
                <a href="#" class="a-card">READ MORE</a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="arrow-up"></div>

      <div class="our-tr-container">
        <div class="our-tr">
          <img
            src="Images/our_training.png"
            alt="our_training"
            class="our-tr-img"
          />
          <p class="p-tr"><span>OUR </span>TRAINING</p>
          <div class="p-tr-l-c">
            <p class="p-tr-l">
              In <span>SM Experts</span>, Our professional instructor are
              specialized in the following training topics for corporates
            </p>
          </div>
        </div>

        <div class="h-card-container">
          <div class="h-card">
            <div>
              <div class="pm-img"></div>
            </div>

            <div class="h-c-content">
              <h2 class="h-hcard">Project Management Training</h2>
              <p class="p-h-card">
                Project Management will help your organizations meet its
                strategic goals in a clearer way and will boost your tearms
                efficiency.
              </p>
            </div>
          </div>

          <div class="h-card">
            <div>
              <div class="ba-img"></div>
            </div>

            <div class="h-c-content">
              <h2 class="h-hcard">Busisness Analysis Training ?</h2>
              <div class="rm-h">
                <a class="h-read-more" href="#">READ MORE</a>
              </div>
            </div>
          </div>
        </div>
        <div class="h-card-container">
          <div class="h-card">
            <div>
              <div class="ms-img"></div>
            </div>

            <div class="h-c-content">
              <h2 class="h-hcard">Management skills Training</h2>
              <p class="p-h-card">
                Project Management will help your organizations meet its
                strategic goals in a clearer way and will boost your tearms
                efficiency.
              </p>
            </div>
          </div>

          <div class="h-card">
            <div>
              <div class="ct-img"></div>
            </div>

            <div class="h-c-content">
              <h2 class="h-hcard">Customized Training</h2>
              <p class="p-h-card">
                Project Management will help your organizations meet its
                strategic goals in a clearer way and will boost your tearms
                efficiency.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="map-container">
        <div>
          <hr />
          <img class="m-p" src="Images/map_pointer.png" alt="map pointer" />
        </div>

        <div class="map"></div>
      </div>
      <div class="footer">
        <p class="p-footer">
          copyright © 2015 | Strategic Management Experts. All right Reserved
        </p>
        <div style="float: right">
          <img class="img-footer" src="Images/page_5.png" alt="logo" />
        </div>
      </div>
    </div>
    <script>
      function myFunction() {
        var x = document.getElementById("myTopnav");
        if (x.className === "nav-ul") {
          x.className += " responsive";
        } else {
          x.className = "topnav";
        }
      }
    </script>
  </body>
</html>