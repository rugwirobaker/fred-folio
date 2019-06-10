<template>
  <div class="app">
    <!--=============== Start Header Area=================-->
    <div class="wrapper">
      <nav class="navbar navbar-expand-lg">
        <a class="navbar-brand text-white" href="#/">
          <h1>Portfolio</h1>
        </a>
      </nav>
      <!--================ Start Home Area =================-->
      <section class="home_banner_area">
        <div class="container">
          <div class="row align-items-center justify-content-between">
            <div class="col-lg-6">
              <div class="banner_content">
                <h3>Hey There !</h3>
                <h1 class="text-uppercase">I am ......... .........</h1>
                <h5 class="text-uppercase">Creative web developer & designer</h5>
                <div class="social_icons my-5">
                  <a href="#">
                    <i class="fa fa-facebook-f"></i>
                  </a>
                  <a href="#">
                    <i class="fa fa-twitter"></i>
                  </a>
                  <a href="#">
                    <i class="fa fa-instagram"></i>
                  </a>
                  <a href="#">
                    <i class="fa fa-github"></i>
                  </a>
                </div>
                <a class="primary_btn" href="#">
                  <span>See My Work</span>
                </a>
              </div>
            </div>
            <div class="col-lg-4">
              <div class="home_right_img">
                <img class="img-fluid" src="../assets/logo.png" alt>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!--================ End Home Area =================-->
    </div>
    <!--================ End Header Area =================-->
    <div class="content">
      <!--================ Start About Me Area =================-->
      <section class="about_area section_gap">
        <div class="container">
          <div class="row justify-content-start align-items-center">
            <div class="col-lg-5">
              <div class="about_img">
                <img class="img-fluid" src="../assets/logo.png" alt>
              </div>
            </div>
            <div class="offset-lg-1 col-lg-5">
              <div class="main_title text-left">
                <p class="top_text">About me</p>
                <h2>
                  Creative Web Developer
                  <br>And Designer
                </h2>
                <p>Lorem ipsum dolor,t amet consectetur adipisicing elit. Voluptates, maxime neque illo iure reprehenderit placeat, explicabo molestiae expedita eligendi quos corrupti quo at tenetur iste ullam! Hic alias numquam tenetur optio ratione libero ipsum aliquam autem! Accusamus eum excepturi nesciunt perferendis natus aliquid, enim quasi ipsum voluptatem ea recusandae. Quis.</p>
                <a class="primary_btn" href="#">
                  <span>Download CV</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!--================ End About Me Area =================-->
      <!--================ Start Services Area =================-->
      <section class="services_area">
        <div class="container">
          <div class="row">
            <div class="col-lg-12">
              <div class="main_title">
                <p class="top_text">Services i offer</p>
                <br>
                <br>
              </div>
            </div>
          </div>

          <div class="row">
            <div class="col-lg-4 col-md-6 mb-4 mb-lg-0">
              <div class="service_item">
                <img src="../assets/s1.png" alt style="height:7em;width:7em">
                <h4>Web Development</h4>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit officiis at, temporibus tenetur rem perferendis iste voluptas repellendus nesciunt corrupti!</p>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 mb-4 mb-lg-0">
              <div class="service_item">
                <img src="../assets/s2.png" alt style="height:7em;width:7em">
                <h4>Front-end Design</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum, nam rem aperiam esse dolorem explicabo ab consectetur nobis adipisci labore.</p>
              </div>
            </div>

            <div class="col-lg-4 col-md-6 mb-4 mb-lg-0">
              <div class="service_item">
                <img src="../assets/s3.png" alt style="height:7em;width:7em">
                <h4>API Developing</h4>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. In unde numquam eum amet quam repellendus aspernatur quia quos asperiores non.</p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- ================ Service section end ================= -->
      <!-- ================ contact section start ================= -->
      <section class="section-margin">
        <div class="row">
          <div class="col-12">
            <h2 class="contact-title">Get in Touch</h2>
          </div>
          <div class="col-lg-4">
            <div class="media contact-info">
              <span class="contact-info__icon">
                <i class="ti-home"></i>
              </span>
              <div class="media-body">
                <h3>Kigali, Rwanda.</h3>
              </div>
            </div>
            <div class="media contact-info">
              <span class="contact-info__icon">
                <i class="ti-email"></i>
              </span>
              <div class="media-body">
                <h3>
                  <a href="mailto:me@mail.com">mailme@mail.com</a>
                </h3>
              </div>
            </div>
            <div class="media contact-info">
              <span class="contact-info__icon">
                <i class="ti-tablet"></i>
              </span>
              <div class="media-body">
                <h3>
                  <a href="tel:+250788888888">(250) 788 888 888</a>
                </h3>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- ================ contact section end ================= -->
    </div>
    <div class="footer">
      <!--================Footer Area =================-->
      <footer class="footer_area">
        <div class="container">
          <div class="footer_social mt-lg-0 mt-4">
            <center>
              <a href="#">
                <i class="fa fa-facebook-f"></i>
              </a>
              <a href="#">
                <i class="fa fa-twitter"></i>
              </a>
              <a href="#">
                <i class="fa fa-instagram"></i>
              </a>
              <a href="#">
                <i class="fa fa-github"></i>
              </a>
            </center>
          </div>
          <div class="footer_bottom">
            <center>
              <p class="col-lg-8 col-sm-12 footer-text">
                Copyright &copy;
                <span id="year"></span> All rights reserved
              </p>
            </center>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: "Homepage"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped src="../css/custom.css">
</style>
