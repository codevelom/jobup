<script>
    let subscriberEmail;

    const handleSubscribe = (e) => {
        console.log(subscriberEmail)
    }
</script>

<svelte:head>
  <link rel="shortcut icon" href="image/favicon.png" type="image/x-icon">
  <!-- Bootstrap , fonts & icons  -->
  <link rel="stylesheet" href="css/bootstrap.css">
  <link rel="stylesheet" href="fonts/icon-font/css/style.css">
  <link rel="stylesheet" href="fonts/typography-font/typo.css">
  <link rel="stylesheet" href="fonts/fontawesome-5/css/all.css">
  <!-- Plugin'stylesheets  -->
  <link rel="stylesheet" href="plugins/aos/aos.min.css">
  <link rel="stylesheet" href="plugins/fancybox/jquery.fancybox.min.css">
  <link rel="stylesheet" href="plugins/nice-select/nice-select.min.css">
  <link rel="stylesheet" href="plugins/slick/slick.min.css">
  <!-- Vendor stylesheets  -->
  <link rel="stylesheet" href="css/main.css">
</svelte:head>

<div class="site-wrapper overflow-hidden ">
    <!-- <div id="loading">
      <img src="image/preloader.gif" alt="">
    </div> -->
    <!-- Header Area -->
    <!-- Header Area -->
    <header class="site-header site-header--menu-center bg-default px-7 px-lg-10 ml-auto ml-lg-0 site-header--absolute site-header--sticky">
      <div class="container-fluid">
        <nav class="navbar site-navbar offcanvas-active navbar-expand-lg  px-0">
          <!-- Brand Logo-->
          <div class="brand-logo mt-3 mt-md-0"><a href="https://finity.uxtheme.net/finity">
              <!-- light version logo (logo must be black)-->
              <img src="image/logo-main-black.png" alt="" class="light-version-logo">
              <!-- Dark version logo (logo must be White)-->
              <img src="image/logo-main-white.png" alt="" class="dark-version-logo">
            </a></div>
          <div class="collapse navbar-collapse" id="mobile-menu">
            <div class="navbar-nav-wrapper">
              <ul class="navbar-nav main-menu">
                <li class="nav-item">
                    <a href="/" class="nav-link">Home</a>
                </li>
                <li class="nav-item">
                    <a href="/about-us" class="nav-link">About Us</a>
                </li>
                <li class="nav-item">
                    <a href="/recruiter" class="nav-link">Partners</a>
                </li>
                <li class="nav-item">
                    <a href="/faq" class="nav-link">FAQs</a>
                </li>
                <li class="nav-item">
                    <a href="/contact-us" class="nav-link">Contact Us</a>
                </li>
                <!-- <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle gr-toggle-arrow" id="navbarDropdown" href="#features" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Demos <i class="icon icon-small-down"></i></a>
                  <ul class="gr-menu-dropdown dropdown-menu" aria-labelledby="navbarDropdown">
                    <li class="drop-menu-item">
                      <a href="home-1.html">
                        Home 1
                      </a>
                    </li>
                    <li class="drop-menu-item">
                      <a href="home-2.html">
                        Home 2
                      </a>
                    </li>
                    <li class="drop-menu-item">
                      <a href="home-3.html">
                        Home 3
                      </a>
                    </li>
                    <li class="drop-menu-item">
                      <a href="home-4.html">
                        Home 4
                      </a>
                    </li>
                    <li class="drop-menu-item">
                      <a href="home-5.html">
                        Home 5
                      </a>
                    </li>
                    <li class="drop-menu-item">
                      <a href="home-6.html">
                        Home 6
                      </a>
                    </li>
                  </ul>
                </li> -->
              </ul>
            </div>
            <button class="d-block d-lg-none offcanvas-btn-close" type="button" data-toggle="collapse" data-target="#mobile-menu" aria-controls="mobile-menu" aria-expanded="true" aria-label="Toggle navigation">
              <i class="gr-cross-icon"></i>
            </button>
          </div>
          <div class="header-btn ml-auto ml-lg-0 d-none d-sm-block">
            <a class="btn btn btn-dodger-blue-2 header-btn rounded-5" href="/user/login">
              Get Started for Free
            </a>
          </div>
          <!-- Mobile Menu Hamburger-->
          <button class="navbar-toggler btn-close-off-canvas  hamburger-icon border-0" type="button" data-toggle="collapse" data-target="#mobile-menu" aria-controls="mobile-menu" aria-expanded="false" aria-label="Toggle navigation">
            <!-- <i class="icon icon-simple-remove icon-close"></i> -->
            <span class="hamburger hamburger--squeeze js-hamburger">
          <span class="hamburger-box">
            <span class="hamburger-inner"></span>
            </span>
            </span>
          </button>
          <!--/.Mobile Menu Hamburger Ends-->
        </nav>
      </div>
    </header>

        <slot />

    <!-- Footer Area -->
    <div class="pt-13 pt-lg-25 pb-13 pb-lg-25">
        <div class="container">
          <div class="row">
            <div class="col-lg-7">
              <div class="row">
                <!-- Single Widgets -->
                <div class="col-xs-4">
                  <div class="mb-10 mb-lg-0">
                    <h4 class="font-size-6 font-weight-medium mb-10">Community</h4>
                    <ul class="list-unstyled">
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">For Talents</a>
                      </li>
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">For Companies</a>
                      </li>
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">Facebook Group</a>
                      </li>
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">FAQ</a>
                      </li>
                    </ul>
                  </div>
                </div>
                <!-- End Single Widgets -->
                <!-- Single Widgets -->
                <div class="col-xs-4">
                  <div class="mb-10 mb-lg-0">
                    <h4 class="font-size-6 font-weight-medium mb-10">About us</h4>
                    <ul class="list-unstyled">
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">Meet the Team</a>
                      </li>
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">Our Story</a>
                      </li>
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">Career</a>
                      </li>
                    </ul>
                  </div>
                </div>
                <!-- End Single Widgets -->
                <!-- Single Widgets -->
                <div class="col-xs-4">
                  <div class="mb-10 mb-lg-0">
                    <h4 class="font-size-6 font-weight-medium mb-10">Useful</h4>
                    <ul class="list-unstyled">
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">Free Resume Builder</a>
                      </li>
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">Free Graphics</a>
                      </li>
                      <li class="mb-6">
                        <a class="font-size-5 text-default-color" href="#">Career Blog</a>
                      </li>
                    </ul>
                  </div>
                </div>
                <!-- End Single Widgets -->
              </div>
            </div>
            <div class="col-lg-5 col-md-8">
              <div class="mb-9">
                <h4 class="font-size-6 font-weight-medium mb-8">Subscribe to Our Newsletter</h4>
                <p class="font-size-5 line-height-28 pr-xs-20 pr-md-13 pr-lg-0">Time is the most precious thing you have when
                  bootstrapping. You can't take time.</p>
              </div>
              <div class="mb-0 mr-xl-9">
                <div class="shadow-3 bg-white rounded-4">
                  <form on:submit|preventDefault={handleSubscribe}>
                    <div class="subscribe-inline-form-2">
                      <div class="form-group">
                        <label for="mail"><i class="icon icon-email-84 mb-0 ml-10"></i></label>
                        <input id="mail" type="email" bind:value={subscriberEmail} class="form-control" placeholder="Enter your email">
                    </div>
                        <button class="btn btn-dodger-blue-2 rounded-5">Subscribe</button>
                    </div>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- End Footer Area -->
    </div>
    <!-- Vendor Scripts -->
    <div>
        <script src="js/vendor.min.js"></script>
        <!-- Plugin's Scripts -->
        <script src="plugins/fancybox/jquery.fancybox.min.js"></script>
        <script src="plugins/nice-select/jquery.nice-select.min.js"></script>
        <script src="plugins/aos/aos.min.js"></script>
        <script src="plugins/slick/slick.min.js"></script>
        <script src="plugins/counter-up/jquery.counterup.min.js"></script>
        <script src="plugins/counter-up/jquery.waypoints.min.js"></script>
        <!-- Activation Script -->
        <script src="js/custom.js"></script>
    </div>
