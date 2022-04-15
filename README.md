<!-- <!DOCTYPE html> -->
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Faith Web Portfolio</title>

  <!-- Google Fonts -->

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@800&family=Ubuntu:wght@300&display=swap"
    rel="stylesheet" />

  <!-- CSS Styles -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />

  <link rel="icon" href="images/favicon.ico" />

  <link rel="stylesheet" href="styles.css" />

  <!-- Font Awesome -->
  <script src="https://kit.fontawesome.com/54f669466a.js" crossorigin="anonymous"></script>


  <!-- Bootstrap Script  -->
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js"
    integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous">
  </script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js"
    integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous">
  </script>
</head>

<body>
  <!-- Title section -->
  <section id="title">
    <!-- Navbar -->
    <div class="container-fluid">
      <nav class="navbar fixed-top navbar-expand-lg navbar-dark" style="background-color: #00acff;">

        <a class="navbar-brand logo-name" href="#">
          <img src="images/faith-logo3.png" alt="" width="80" height="80" class="d-inline-block align-text-center" />
          Faith </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01"
          aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#title">HOME</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#portfolio">PORTFOLIO</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#my-job">SERVICES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">ABOUT ME</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#footer">CONTACT</a>
            </li>
          </ul>
        </div>

      </nav>


      <!-- carousel -->
      <div class="container-carousel">
        <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="images/carosel4.jpg" class="d-block w-100" alt="carousel-image1">
            </div>
            <div class="carousel-item">
              <img src="images/carosel2.jpg" class="d-block w-100" alt="carousel-image2">
            </div>
            <div class="carousel-item">
              <img src="images/carosel8.jpg" class="d-block w-100" alt="carousel-image3">
            </div>
          </div>
        </div>
        <div class="head1">
          <hr>
          <h1 class="h-heading">HELLO, I'M FAITH!</h1>
          <p>Am a Web Developer Enthusiast</p>
        </div>
      </div>
    </div>
  </section>

  <!-- My JOB SECTION -->
  <section id="my-job">
    <div class="container-fluid container-my-job">
      <img src="images/profile2.png" alt="profile picture" style="width: 100%;">


      <div class="row job-description">

        <div class="col-lg-6">
          <div class="job-picture">
            <img src="images/job-picture.png" alt="Job Picture">
          </div>
        </div>

        <div class="col-lg-6">

          <div class="job-heading">
            <h2 class="jobs">MY JOBS</h2>
            <p class="p-job">I develop website, design website and manage website</p>
          </div>

          <div class="job1">

            <i class="job-icon fa-solid fa-code fa-3x"></i>
            <h3>I Develop Website</h3>
            <p class="p-job">
              My core competency lies in complete end-end management of a new
              website development project, and I am seeking opportunities to build
              websites from the ground up for you or your business.
            </p>
            <button class="btn btn-lg btn-danger">Any Enquiry</button>
          </div>

          <div class="job2">
            <i class="job-icon fa-solid fa-browser fa-3x"></i>
            <h3 class="design1">I Design Website</h3>
            <p class="p-job">
              I enjoy the structures and the puzzles that each new challenge brings.
              I see Design as finding a solution to a problem.
            </p>
            <button class="btn btn-lg btn-danger">Portfolio</button>
          </div>

        </div>

      </div>
    </div>
  </section>

  <!-- MY PORTFOLIO SECTION -->
  <section id="portfolio">
    <div class="my-portfolio">
      <h2 class="h2-port">MY PORTFOLIO - </h2>
      <h2 class="h2-port">Let me help you succeed online.</h2>

      <em>
        <p class="p-port">
          “I don't just build website, I help you succeed online and offline.
          Websites promote you 24/7 no employee will do that for you”.
        </p>
      </em>
      <button class="btn btn-lg btn-outline-primary"><i class="fa-solid fa-suitcase"></i> See more projects</button>
    </div>
    <!-- <div>
      <img src="" alt="My Portfolio Images" />
    </div> -->
  </section>

  <!-- ABOUT ME SECTION -->
  <section id="about">
    <div class="row">
      <div class="col-lg-6">
        <div class="about-me">
          <h2 class="h-about">ABOUT ME</h2>
          <p class="p-about">
            Hi everyone! My name is <strong>Adeoye Faith</strong> and I can create a modern,
            attractive and clean design for your website, online store or mobile
            application. I also know very well how to create an eCommerce website
            that is highly converting and user-friendly.
          </p>

          <p class="p-about">
            In my portfolio there are dozens of layouts for Shopify and WordPress
            online stores with WooCommerce.</p>

          <p class="p-about">Tell me your ideas and I will bring
            them to life in the best way. I will be your style guide and choose
            the most appropriate website style to match your brand. I provide design services for:
          </p>

          <p class="p-about">
            — Landing pages;— Multi-page sites; —
            E-commerce sites; — Mobile applications; — Redesign of existing websites.
          </p>

          <p class="p-about"> The most important thing for me is a satisfied client and the creation
            of a site that everyone will admire. So — what're you waiting for?
            Let's make a great design for you. Just click the “hire” button or
            send me a message.
          </p>
        </div>
      </div>
      <div class="col-lg-6">
        <div>
          <img class="about-image" src="images/faithpix.jpg" alt="My Image" style="width: 100%" ;>
        </div>
      </div>
    </div>
  </section>

  <!-- EXHIBITION SECTION -->

  <section id="exhibition">
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <img class="exhibition-image" src="images/portfolio1.png" alt="exhibition 1" style="width: 100%" ;>
          <h4 class="h-exhibition">HOSTING</h4>
          <p class="p-date">January 12, 2022 /// No Comments</p>
          <p class="p-exhibition">
            Hi everyone! My name is Adeoye Faith and I can create a modern,
            attractive and clean design for your website, online store or mobile
            application. I also know very well how to create an eCommerce website
            that is highly converting and user-friendly.
          </p>
          <a class="a-exhibition" href="">Read More <i class="fa-solid fa-angles-right"></i></a>
        </div>
        <div class=" col-lg-4">
          <img class="exhibition-image" src="images/portfolio2.png" alt="exhibition 2" style="width: 100%" ;>
          <h4 class="h-exhibition">DOMAIN</h4>
          <p class="p-date">January 12, 2022 /// No Comments</p>
          <p class="p-exhibition">
            Hi everyone! My name is Adeoye Faith and I can create a modern,
            attractive and clean design for your website, online store or mobile
            application. I also know very well how to create an eCommerce website
            that is highly converting and user-friendly.
          </p>
          <a class="a-exhibition" href="">Read More <i class="fa-solid fa-angles-right"></i></a>
        </div>
        <div class="col-lg-4">
          <img class="exhibition-image" src="images/portfolio3.png" alt="exhibition 3" style="width: 100%" ; />
          <h4 class="h-exhibition">CONTACT</h4>
          <p class="p-date">January 12, 2022 /// No Comments</p>
          <p class="p-exhibition">
            Hi everyone! My name is Adeoye Faith and I can create a modern,
            attractive and clean design for your website, online store or mobile
            application. I also know very well how to create an eCommerce website
            that is highly converting and user-friendly.
          </p>
          <a class="a-exhibition" href="">Read More <i class="fa-solid fa-angles-right"></i></a>
        </div>
      </div>
    </div>
  </section>

  
  <!-- FOOTER SECTION -->

  <section id="footer">
    <h3 class="h-footer">Copyright © 2022 All Right Reserved</h3>
    <p class="phone-number">Tel: 08168291416</p>
    <p class="p-connect">Connect with me @</p>
    <i class="social-icon fa-brands fa-facebook"></i>
    <i class="social-icon fa-brands fa-twitter"></i>
    <i class="social-icon fa-brands fa-instagram-square"></i>
    <i class="social-icon fa-brands fa-youtube"></i>
    <i class="social-icon fa-brands fa-linkedin"></i>
  </section>
</body>

</html>
