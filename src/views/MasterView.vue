<template>

    <!-- page header -->
    <div class="container" id="home">
      <div class="col-12 text-center">
        <div class="tm-page-header">
          <i class="fas fa-4x fa-chart-bar mr-4"></i>
          <h1 class="d-inline-block text-uppercase">Pro Line</h1>
        </div>
      </div>
    </div>
    <!-- navbar -->
    <div class="tm-nav-section">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <nav class="navbar navbar-expand-md navbar-light">
              <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#tmMainNav"
                aria-controls="tmMainNav"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>

              <div class="collapse navbar-collapse" id="tmMainNav">
                <ul class="navbar-nav mx-auto tm-navbar-nav">
                  <li class="nav-item active">
                    <a class="nav-link" href="#home"
                      >Home <span class="sr-only">(current)</span></a
                    >
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#features">Features</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#activities">Activities</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#company">Company</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                  </li>
                 
                </ul>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>

    <!-- Video Banner -->
    <section class="tm-banner-section" id="tmVideoSection">
      <div class="container tm-banner-text-container">
        <div class="row">
          <div class="col-12">
            <header>
              <h2 class="tm-banner-title">Pro Line Video</h2>
              <p class="mx-auto tm-banner-subtitle">
                The video background has a parallax effect. This is fluid and
                full-width.
              </p>
            </header>
          </div>
        </div>
      </div>

      <!-- Video -->
      <video id="hero-vid" autoplay="" loop="" muted>
        <source src="@/assets/videos/city-night-blur-01.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
    </section>
    <!-- Features -->
    <div class="container tm-features-section" id="features">
      <div class="row tm-features-row">
        <section class="col-md-6 col-sm-12 tm-feature-block">
          <header class="tm-feature-header">
            <i class="fas fa-5x fa-anchor tm-feature-icon"></i>
            <h3 class="tm-feature-h">Cras pretium diam ut metus</h3>
          </header>
          <p>
            Pro Line HTML5 Template is brought to you by
            <a rel="nofollow noopener" href="https://www.tooplate.com"
              >Tooplate</a
            >. This layout used Bootstrap v4.1.3 UI kit. You can easily modify
            this template in any HTML editor for your site.
          </p>
          <p>
            Sed interdum, purus vulputate congue luctus, lorem massa dignissim
            nisi, sed condimentum nibh lorem quis lorem. Nulla sed erat
            dignissim, tincidunt ante ac, egestas turpis.
          </p>
        </section>
        <section class="col-md-6 col-sm-12 tm-feature-block">
          <header class="tm-feature-header">
            <i class="fas fa-5x fa-atom tm-feature-icon"></i>
            <h3 class="tm-feature-h">Cras pretium diam ut metus</h3>
          </header>
          <p>
            Phasellus tristique, sapien quis mattis pellentesque, felis turpis
            placerat turpis, nec viverra quam nisl at velit. Pellentesque
            iaculis convallis egestas.
          </p>
          <p>
            Nunc ut elit eget velit mollis sodales. Ut non mauris ut ligula
            mattis consectetur. Aenean augue arcu, rhoncus at nibh nec, lacinia
            blandit nulla.
          </p>
        </section>
      </div>
    </div>

    <!-- Activities -->
    <div class="container" id="activities">
      <div class="row">
        <div class="col-12">
          <div class="tm-parallax">
            <header class="tm-parallax-header">
              <h2 class="">Activities</h2>
            </header>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-6">
          <div class="tm-activity-block">
            <div class="tm-activity-img-container">
              <img src="@/assets/img/img-01.jpg" alt="Image" class="tm-activity-img" />
            </div>
            <div class="tm-activity-block-text">
              <h3 class="tm-text-blue">Lorem ipsum dolor sit amet</h3>
              <p>
                Orci varius natoque penatibus et magnis dis parturient montes,
                nascetur ridiculus mus. Sed eu turpis nec sem lacinia
                condimentum et a orci.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="tm-activity-block mr-lg-0 ml-lg-auto">
            <div class="tm-activity-img-container">
              <img src="@/assets/img/img-02.jpg" alt="Image" class="tm-activity-img" />
            </div>
            <div class="tm-activity-block-text">
              <h3 class="tm-text-blue">Lorem ipsum dolor sit amet</h3>
              <p>
                Orci varius natoque penatibus et magnis dis parturient montes,
                nascetur ridiculus mus. Sed eu turpis nec sem lacinia
                condimentum et a orci.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="tm-activity-block">
            <div class="tm-activity-img-container">
              <img src="@/assets/img/img-03.jpg" alt="Image" class="tm-activity-img" />
            </div>
            <div class="tm-activity-block-text">
              <h3 class="tm-text-blue">Lorem ipsum dolor sit amet</h3>
              <p>
                Orci varius natoque penatibus et magnis dis parturient montes,
                nascetur ridiculus mus. Sed eu turpis nec sem lacinia
                condimentum et a orci.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="tm-activity-block mr-lg-0 ml-lg-auto">
            <div class="tm-activity-img-container">
              <img src="@/assets/img/img-04.jpg" alt="Image" class="tm-activity-img" />
            </div>
            <div class="tm-activity-block-text">
              <h3 class="tm-text-blue">Lorem ipsum dolor sit amet</h3>
              <p>
                Orci varius natoque penatibus et magnis dis parturient montes,
                nascetur ridiculus mus. Sed eu turpis nec sem lacinia
                condimentum et a orci.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <section class="container tm-company-section" id="company">
      <div class="row">
        <div class="col-xl-9 col-lg-8 col-md-12 tm-company-left">
          <div class="tm-company-about">
            <div class="tm-company-img-container">
              <img src="@/assets/img/img-05.jpg" alt="Image" />
            </div>
            <div class="tm-company-about-text">
              <header>
                <h2 class="tm-company-about-header">Our Company</h2>
              </header>
              <p>
                Phasellus fringilla convallis libero non aliquam. Morbi justo
                lorem, varius ultricies pulvinar ac, aliquet quis ipsum.
              </p>
              <p class="mb-4">
                Suspendisse aliquam pulvinar odio sed rhoncus. Cras pretium diam
                ut metus tristique, a ultricies sapien euismod. Duis dui diam,
                maximus ac ligula a, accumsan cursus ante.
              </p>
              <a href="#" class="btn tm-btn tm-float-right">Read More</a>
            </div>
          </div>
        </div>
        <div
          class="col-xl-9 col-lg-4 col-md-12 tm-company-right  ml-lg-auto mr-lg-0"
        >
          <div class="tm-company-right-inner">
            <ul class="nav nav-tabs" id="tmCompanyTab" role="tablist">
              <li class="nav-item">
                <a
                  class="nav-link tm-nav-link-border-right active"
                  id="vision-tab"
                  data-toggle="tab"
                  href="#vision"
                  role="tab"
                  aria-controls="vision"
                  aria-selected="true"
                  >Vision</a
                >
              </li>
              <li class="nav-item">
                <a
                  class="nav-link tm-no-border-right"
                  id="mission-tab"
                  data-toggle="tab"
                  href="#mission"
                  role="tab"
                  aria-controls="mission"
                  aria-selected="false"
                  >Mission</a
                >
              </li>
            </ul>
            <div class="tab-content" id="tmTabContent">
              <div
                class="tab-pane fade show active"
                id="vision"
                role="tabpanel"
                aria-labelledby="vision-tab"
              >
                <p>
                  Phasellus suscipit sapien magna, vel dictum lorem fringilla.
                </p>
                <p>
                  Class aptent taciti sociosqu ad litora torquent per conubia
                  nostra.
                </p>
                <p>
                  Nulla ornare ligula nibh, sit amet tristique magna efficitur
                  eu.
                </p>
              </div>
              <div
                class="tab-pane fade"
                id="mission"
                role="tabpanel"
                aria-labelledby="mission-tab"
              >
                <p>
                  Class aptent taciti sociosqu ad litora torquent per conubia
                  nostra.
                </p>
                <p>
                  Nulla ornare ligula nibh, sit amet tristique magna efficitur
                  eu.
                </p>
                <p>
                  Phasellus suscipit sapien magna, vel dictum lorem fringilla.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Contact -->
    <section class="container tm-contact-section" id="contact">
      <div class="row">
        <div class="col-xl-5 col-lg-6 col-md-12 tm-contact-left">
          <div class="tm-contact-form-container ml-auto mr-0">
            <header>
              <h2 class="tm-contact-header">Contact Us</h2>
            </header>
            <form action="index.html" class="tm-contact-form" method="POST">
              <div class="form-group">
                <input
                  type="text"
                  id="contact_name"
                  name="contact_name"
                  class="form-control"
                  placeholder="Name"
                  required
                />
              </div>
              <div class="form-group">
                <input
                  type="email"
                  id="contact_email"
                  name="contact_email"
                  class="form-control"
                  placeholder="Email"
                  required
                />
              </div>
              <div class="form-group">
                <textarea
                  rows="5"
                  id="contact_message"
                  name="contact_message"
                  class="form-control"
                  placeholder="Message"
                  required
                ></textarea>
              </div>
              <div class="tm-text-right">
                <button type="submit" class="btn tm-btn tm-btn-big">
                  Send It
                </button>
              </div>
            </form>
          </div>
        </div>
        <div class="col-xl-7 col-lg-6 col-md-12 tm-contact-right">
          <div class="tm-contact-figure-block">
            <figure class="d-inline-block">
              <img src="@/assets/img/img-06.jpg" alt="Image" class="img-fluid" />
              <figcaption class="tm-contact-figcaption">
                Nulla arcu tortor, mattis in diam eget, hendrerit vulputate
                ligula. Nam non purus consequat, dictum lectus lobortis, laoreet
                nibh. Cras vitae facilisis felis. Phasellus tristique.
              </figcaption>
            </figure>
          </div>
        </div>
      </div>
    </section>
    <footer class="container tm-footer">
      <div class="row tm-footer-row">
        <p class="col-md-10 col-sm-12 mb-0">
          Copyright &copy; 2018 Company Name - Design:
          <a rel="nofollow" href="https://www.facebook.com/tooplate" class="tm-footer-link">Tooplate</a>
        </p>
        <div class="col-md-2 col-sm-12 scrolltop">
          <div class="scroll icon"><i class="fa fa-4x fa-angle-up"></i></div>
        </div>
      </div>
    </footer>



</template>

<script>
export default {
    name: 'MasterView',
}
</script>

<style>

</style>