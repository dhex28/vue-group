
<template>
  <nav class="navbar navbar-expand-lg custom-bg-color">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01"
        aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
        <a class="navbar-brand text-white" href="#">Dev</a>
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="/manage">Manage</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success text-white" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <div class="">
    <!-- banner section start -->
    <div class="banner_section layout_padding">
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="container">
              <div class="row">
                <div class="col-sm-6">
                  <h1 class="banner_taital">Beauty <br>Kit</h1>
                  <p class="banner_text">Ncididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
                    exercitation ullamco laboris nisi ut aliquip ex ea commodo</p>
                  <div class="read_bt"><a href="#">Buy Now</a></div>
                </div>
                <div class="col-sm-6">
                  <div class="banner_img"><img :src="require('../assets/images/banner-img.png')"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- banner section end --->
  <!-- product section start -->
  <div class="product_section layout_padding">
    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <h1 class="product_taital">Our Products</h1>
          <p class="product_text">incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
            exercitation</p>
        </div>
      </div>
      <div class="product_section_2 layout_padding">
        <div class="row">
          <div class="col-lg-3 col-sm-6">
            <div class="product_box">
              <h4 class="bursh_text">Beauty Bursh</h4>
              <p class="lorem_text">incididunt ut labore et dolore magna aliqua. Ut enim </p>
              <img :src="require('../assets/images/img-7.png')" class="image_1">
              <div class="btn_main">
                <div class="buy_bt">
                  <ul>
                    <li class="active"><a href="#">Buy Now</a></li>
                    <li><a href="#">Buy Now</a></li>
                  </ul>
                </div>
                <h3 class="price_text">Price $30</h3>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6">
            <div class="product_box">
              <h4 class="bursh_text">Beauty Bursh</h4>
              <p class="lorem_text">incididunt ut labore et dolore magna aliqua. Ut enim </p>
              <img :src="require('../assets/images/img-10.png')" class="image_1">
              <div class="btn_main">
                <div class="buy_bt">
                  <ul>
                    <li class="active"><a href="#">Buy Now</a></li>
                    <li><a href="#">Buy Now</a></li>
                  </ul>
                </div>
                <h3 class="price_text">Price $30</h3>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6">
            <div class="product_box">
              <h4 class="bursh_text">Beauty Bursh</h4>
              <p class="lorem_text">incididunt ut labore et dolore magna aliqua. Ut enim </p>
              <img :src="require('../assets/images/img-3.png')" class="image_1">
              <div class="btn_main">
                <div class="buy_bt">
                  <ul>
                    <li class="active"><a href="#">Buy Now</a></li>
                    <li><a href="#">Buy Now</a></li>
                  </ul>
                </div>
                <h3 class="price_text">Price $30</h3>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-sm-6">
            <div class="product_box">
              <h4 class="bursh_text">Beauty Bursh</h4>
              <p class="lorem_text">incididunt ut labore et dolore magna aliqua. Ut enim </p>
              <img :src="require('../assets/images/img-12.png')" class="image_1">
              <div class="btn_main">
                <div class="buy_bt">
                  <ul>
                    <li class="active"><a href="#">Buy Now</a></li>
                    <li><a href="#">Buy Now</a></li>
                  </ul>
                </div>
                <h3 class="price_text">Price $30</h3>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- product section end -->
    <!-- about section start -->
    <div class="about_section layout_padding">
      <div class="container">
        <div class="about_section_main">
          <div class="row">
            <div class="col-md-6">
              <div class="about_taital_main">
                <h1 class="about_taital">About Our beauty sotore</h1>
                <p class="about_text">labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                  ullamco laboris nisi ut aliquip ex ea commodo consequatlabore et dolore magna aliqua. Ut enim ad minim
                  veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequatlabore et
                  dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
                  ex ea commodo consequat</p>
                <div class="readmore_bt"><a href="#">Read More</a></div>
              </div>
            </div>
            <div class="col-md-6">
              <div><img :src="require('../assets/images/about-img.png')" class="image_3"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- about section end -->
    <!-- footer section start -->
    <div class="footer_section layout_padding">
      <div class="container">
        <div class="footer_logo"><a href="index.html"><img src="images/footer-logo.png"></a></div>
        <div class="contact_section_2">
          <div class="row">
            <div class="col-sm-4">
              <h3 class="address_text">Contact Us</h3>
              <div class="address_bt">
                <ul>
                  <li>
                    <a href="#">
                      <i class="fa fa-map-marker" aria-hidden="true"></i><span class="padding_left10">Address : Loram
                        Ipusm</span>
                    </a>
                  </li>
                  <li>
                    <a href="#">
                      <i class="fa fa-phone" aria-hidden="true"></i><span class="padding_left10">Call : +01
                        1234567890</span>
                    </a>
                  </li>
                  <li>
                    <a href="#">
                      <i class="fa fa-envelope" aria-hidden="true"></i><span class="padding_left10">Email :
                        demo@gmail.com</span>
                    </a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-sm-4">
              <div class="footer_logo_1"><a href="index.html"><img :src="require('../assets/images/footer-logo.png')"></a>
              </div>
              <p class="dummy_text">commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non</p>
            </div>
            <div class="col-sm-4">
              <div class="main">
                <h3 class="address_text">Best Products</h3>
                <p class="ipsum_text">dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non</p>
              </div>
            </div>
          </div>
        </div>
        <div class="social_icon">
          <ul>
            <li>
              <a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
            </li>
            <li>
              <a href="#"><i class="fa fa-instagram" aria-hidden="true"></i></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <!-- footer section end -->
</div></template>

