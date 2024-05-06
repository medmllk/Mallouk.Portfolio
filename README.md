
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <meta http-equiv="X-UA-Compatible" content="ie=edge">

  <meta name="copyright" content="MACode ID, https://www.macodeid.com/">

  <title>Mohamed Mallouk Portfolio</title>

  <link rel="shortcut icon" href="../assets/logo_MM.ico" type="image/x-icon">

  <link rel="stylesheet" type="text/css" href="../assets/css/themify-icons.css">

  <link rel="stylesheet" type="text/css" href="../assets/css/bootstrap.css">

  <link rel="stylesheet" type="text/css" href="../assets/vendor/animate/animate.css">

  <link rel="stylesheet" type="text/css" href="../assets/vendor/owl-carousel/owl.carousel.css">

  <link rel="stylesheet" type="text/css" href="../assets/vendor/perfect-scrollbar/css/perfect-scrollbar.css">

  <link rel="stylesheet" type="text/css" href="../assets/vendor/nice-select/css/nice-select.css">

  <link rel="stylesheet" type="text/css" href="../assets/vendor/fancybox/css/jquery.fancybox.min.css">

  <link rel="stylesheet" type="text/css" href="../assets/css/virtual.css">

  <link rel="stylesheet" type="text/css" href="../assets/css/topbar.virtual.css">
</head>

<body class="theme-red">

  <!-- Back to top button -->
  <div class="btn-back_to_top">
    <span class="ti-arrow-up"></span>
  </div>

  <!-- Setting button -->
  <div class="config">
    <div class="template-config">
      <!-- Settings -->
      <div class="d-block">
        <button class="btn btn-fab btn-sm" id="sideel" title="Settings"><span class="ti-settings"></span></button>
      </div>
      <!-- Puschase -->
      <div class="d-block">
        <a href="mailto:med.mallouk@hotmail.com" class="btn btn-fab btn-sm" title="Send mail" data-toggle="tooltip"
          data-placement="left"><span class="ti-download"></span></a>
      </div>
      <!-- Help -->
      <div class="d-block">
        <a href="#" class="btn btn-fab btn-sm" title="Help" data-toggle="tooltip" data-placement="left"><span
            class="ti-help"></span></a>
      </div>
    </div>
    <div class="set-menu">
      <p>Select Color</p>
      <div class="color-bar" data-toggle="selected">
        <span class="color-item bg-theme-red selected" data-class="theme-red"></span>
        <span class="color-item bg-theme-blue" data-class="theme-blue"></span>
        <span class="color-item bg-theme-green" data-class="theme-green"></span>
        <span class="color-item bg-theme-orange" data-class="theme-orange"></span>
        <span class="color-item bg-theme-purple" data-class="theme-purple"></span>
      </div>
      <select class="custom-select d-block my-2" id="change-page">
        <option value="">Choose Page</option>
        <option value="index">Topbar</option>
        <option value="blog-topbar">Blog (Topbar)</option>
        <option value="index-2">Minibar</option>
        <option value="blog-minibar">Blog (Minibar)</option>
      </select>
    </div>
  </div>

  <div class="vg-page page-home" id="home" style="background-image: url(../assets/img/bg_image_1.jpg)">
    <!-- Navbar -->
    <div class="navbar navbar-expand-lg navbar-dark sticky" data-offset="500">
      <div class="container">
        <a href="" class="navbar-brand"></a>
        <button class="navbar-toggler" data-toggle="collapse" data-target="#main-navbar" aria-expanded="true">
          <span class="ti-menu"></span>
        </button>
        <div class="collapse navbar-collapse" id="main-navbar">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active">
              <a href="#home" class="nav-link" data-animate="scrolling">Home</a>
            </li>
            <li class="nav-item">
              <a href="#about" class="nav-link" data-animate="scrolling">About</a>
            </li>
            <li class="nav-item">
              <a href="#portfolio" class="nav-link" data-animate="scrolling">Portfolio</a>
            </li>
            <!-- <li class="nav-item">
              <a href="#blog" class="nav-link" data-animate="scrolling">Blog</a>
            </li> -->
            <li class="nav-item">
              <a href="#contact" class="nav-link" data-animate="scrolling">Contact</a>
            </li>
          </ul>
          <ul class="nav ml-auto">
            <li class="nav-item">
              <button class="btn btn-fab btn-theme no-shadow">En</button>
            </li>
          </ul>
        </div>
      </div>
    </div> 
    <!-- End Navbar -->
    <!-- Caption header -->
    <div class="caption-header text-center wow zoomInDown">
      <h5 class="fw-normal">Welcome</h5>
      <h1 class="fw-light mb-4">I'm <b class="fg-theme">MALLOUK</b> Mohamed</h1>
      <div class="badge">Graphic Designer & Web Developer </div>
    </div> <!-- End Caption header -->
    <div class="floating-button"><span class="ti-mouse"></span></div>
  </div>

  <div class="vg-page page-about" id="about">
    <div class="container py-5">
      <div class="row">
        <div class="col-lg-4 py-3">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/person.jpg" alt="">
          </div>
        </div>
        <div class="col-lg-6 offset-lg-1 wow fadeInRight">
          <h1 class="fw-light">MALLOUK Mohamed</h1>
          <h5 class="fg-theme mb-3">Graphic Designer & Web Developer</h5>
          <p class="text-muted">Graphic and Web designer who works in several disciplines. I love working in a team and having new ideas. Multi-talented graphic designer with over 25 years of experience designing for digital and print publications.</p>
          <ul class="theme-list">
            <li><b>From:</b> Casablanca</li>
            <li><b>Lives In:</b> Italy</li>
            <!-- <li><b>Age:</b> 45</li>
            <li><b>Gender:</b> Male</li> -->
          </ul>
          <!-- <button class="btn btn-theme-outline">Download CV</button> -->
        </div>
      </div>
    </div>
    <div class="container py-5">
      <h1 class="text-center fw-normal wow fadeIn">My Skills</h1>
      <div class="row py-3">
        <div class="col-md-6">
          <div class="px-lg-3">
            <h4 class="wow fadeInUp">Design skills</h4>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Print Design</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 90%;" aria-valuenow="75" aria-valuemin="0"
                  aria-valuemax="100">90%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Web Design</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="75" aria-valuemin="0"
                  aria-valuemax="100">70%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Logo Design</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="75" aria-valuemin="0"
                  aria-valuemax="100">80%</div>
              </div>
            </div>
            <!-- <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Phyton</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="75" aria-valuemin="0"
                  aria-valuemax="100">70%</div>
              </div>
            </div> -->
          </div>
        </div>
        <div class="col-md-6">
          <div class="px-lg-3">
            <h4 class="wow fadeInUp">Coding Skills</h4>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">HTML</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 60%;" aria-valuenow="75" aria-valuemin="0"
                  aria-valuemax="100">60%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">CSS</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 60%;" aria-valuenow="75" aria-valuemin="0"
                  aria-valuemax="100">60%</div>
              </div>
            </div>
            <div class="progress-wrapper wow fadeInUp">
              <span class="caption">Java script</span>
              <div class="progress">
                <div class="progress-bar" role="progressbar" style="width: 40%;" aria-valuenow="75" aria-valuemin="0"
                  aria-valuemax="100">40%</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container pt-5">
      <div class="row">
        <div class="col-md-6 wow fadeInRight">
          <h2 class="fw-normal">Education</h2>
          <ul class="timeline mt-4 pr-md-5">
            <li>
              <div class="title">2000</div>
              <div class="details">
                <h5>Grapic arts diploma</h5>
                <small class="fg-theme">Graphic Arts Institute of Casablanca </small>
                <!--<p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered</p>-->
              </div>
            </li>
            <li>
              <div class="title">2016</div>
              <div class="details">
                <h5>Industrial & logistics management diploma</h5>
                <small class="fg-theme">University of casablanca</small>
                <!--<p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered</p>-->
              </div>
            </li>
          </ul>
        </div>
        <div class="col-md-6 wow fadeInRight" data-wow-delay="200ms">
          <h2 class="fw-normal">Experience</h2>
          <ul class="timeline mt-4 pr-md-5">
            <li>
              <div class="title">2019</div>
              <div class="details">
                <h5>Segnior Graphic Designer</h5>
                <!--<small class="fg-theme">University of Study</small>-->
                <!--<p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered</p>-->
              </div>
            </li>
            <li>
              <div class="title">2005</div>
              <div class="details">
                <h5>Junior Graphic Designer</h5>
                <!--<small class="fg-theme">University of Study</small>-->
                <!--<p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered</p>-->
              </div>
            </li>
            <li>
              <div class="title">2000</div>
              <div class="details">
                <h5>Graphic Designer</h5>
                <!--<small class="fg-theme">University of Study</small>-->
                <!--<p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered</p>-->
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <div class="vg-page page-service">
    <div class="container">
      <div class="text-center wow fadeInUp">
        <div class="badge badge-subhead">Service</div>
      </div>
      <h1 class="fw-normal text-center wow fadeInUp">What can i do?</h1>
      <div class="row mt-5">
        <div class="col-md-6 col-lg-4 col-xl-3">
          <div class="card card-service wow fadeInUp">
            <div class="icon">
              <span class="ti-vector"></span>
            </div>
            <div class="caption">
              <h4 class="fg-theme">Graphic Design</h4>
              <p>Creation & consulting for print ads, packaging, marketing materials, space design, logo, newsletters...</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3">
          <div class="card card-service wow fadeInUp">
            <div class="icon">
              <span class="ti-paint-bucket"></span>
            </div>
            <div class="caption">
              <h4 class="fg-theme">Web Design</h4>
              <p>Websites, digital branding, mailing, social media images...</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3">
          <div class="card card-service wow fadeInUp">
            <div class="icon">
              <span class="ti-desktop"></span>
            </div>
            <div class="caption">
              <h4 class="fg-theme">Web Development</h4>
              <p>Web Design, web development, Banners</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3">
          <div class="card card-service wow fadeInUp">
            <div class="icon">
              <span class="ti-search"></span>
            </div>
            <div class="caption">
              <h4 class="fg-theme">Consulting</h4>
              <p>Consulting with clients to understand their needs. Working with developers and designers to create a
                design strategy.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- <div class="vg-page page-funfact" style="background-image: url(../assets/img/bg_banner.jpg);">
    <div class="container">
      <div class="row section-counter">
        <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
          <h1 class="number" data-number="768">768</h1>
          <span>Clients</span>
        </div>
        <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
          <h1 class="number" data-number="230">230</h1>
          <span>Project Compleate</span>
        </div>
        <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
          <h1 class="number" data-number="97">11</h1>
          <span>Project Ongoing</span>
        </div>
        <div class="col-md-6 col-lg-3 py-4 wow fadeIn">
          <h1 class="number" data-number="699">699</h1>
          <span>Client Satisfaction</span>
        </div>
      </div>
    </div>
  </div> -->

  <!-- Portfolio page -->
  <div class="vg-page page-portfolio" id="portfolio">
    <div class="container">
      <div class="text-center wow fadeInUp">
        <div class="badge badge-subhead">Portfolio</div>
      </div>
      <h1 class="text-center fw-normal wow fadeInUp">My Studio</h1>
      <!-- <div class="filterable-button py-3 wow fadeInUp" data-toggle="selected"> -->
        <!-- <button class="btn btn-theme-outline selected" data-filter="*">All</button> -->
        <!--<button class="btn btn-theme-outline" data-filter=".apps">Apps</button>-->
        <!-- <button class="btn btn-theme-outline" data-filter=".template">Web site</button> -->
        <!--<button class="btn btn-theme-outline" data-filter=".ios">IOS</button>-->
        <!-- <button class="btn btn-theme-outline" data-filter=".ui-ux">Print</button> -->
        <!-- <button class="btn btn-theme-outline" data-filter=".graphic">Logo</button> -->
        <!--<button class="btn btn-theme-outline" data-filter=".wireframes">Wireframes</button>-->
      </div> 


      <div class="gridder my-3">
        <div class="grid-item apps wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-1.jpg" data-fancybox
            data-caption="<h5 class='fg-theme'>Books</h5> <p>Accounting, Finance</p>">
            <img src="../assets/img/work/work-1.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Edition</h5>
              <p>Accounting, Finance</p>
            </div>
          </div>
        </div>
        <div class="grid-item template wireframes wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/My Studio-01.jpg" data-fancybox
            data-caption="<h5 class='fg-theme'>Web Design</h5> <p>Edition</p>">
            <img src="../assets/img/work/My Studio-01.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Web Design</h5>
              <p>Economy, Business</p>
            </div>
          </div>
        </div>
        <div class="grid-item apps ios wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/My Studio-03.jpg" data-fancybox
            data-caption="<h5 class='fg-theme'>Mapping</h5> <p>Road map, Travel</p>">
            <img src="../assets/img/work/My Studio-03.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Mapping</h5>
              <p>Road map, Travel</p>
            </div>
          </div>
        </div>
        <div class="grid-item graphic ui-ux wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/My Studio-02.jpg" data-fancybox
            data-caption="<h5 class='fg-theme'>Advertising</h5> <p>Building, Housing</p>">
            <img src="../assets/img/work/My Studio-02.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Advertising</h5>
              <p>Building, Housing</p>
            </div>
          </div>
        </div>
        <div class="grid-item apps ios wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-5.jpg" data-fancybox
            data-caption="<h5 class='fg-theme'>Visual identityr</h5> <p>Sunscreen, Protective film</p>">
            <img src="../assets/img/work/work-5.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Visual Identity</h5>
              <p>Sunscreen, Protective film</p>
            </div>
          </div>
        </div>
        <div class="grid-item graphic ui-ux wireframes wow zoomIn">
          <div class="img-place" data-src="../assets/img/work/work-6.jpg" data-fancybox
            data-caption="<h5 class='fg-theme'>Interior Design</h5> <p>Bank, Resturation</p>">
            <img src="../assets/img/work/work-6.jpg" alt="">
            <div class="img-caption">
              <h5 class="fg-theme">Interior Design</h5>
              <p>Bank, Resturation</p>
            </div>
          </div>
        </div>
      </div> <!-- End gridder -->
      <!-- <div class="text-center wow fadeInUp">
        <a href="javascript:void(0)" class="btn btn-theme">Load More</a>
      </div> -->
    </div>
  </div> <!-- End Portfolio page -->

  <!-- Testimonial -->
  <div class="vg-page page-testimonial">
    <div class="container">
      <h1 class="text-center fw-normal wow fadeInUp">Branding Design</h1>
      <div class="row justify-content-center mt-5 wow fadeInUp">
        <div class="col-md-9">
          <div class="owl-carousel testi-carousel">

          <!-- start Branding -->
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_25.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">With definitions that are both rigorous and simple, this dictionary aims to help both children and adult beginners to discover and understand written language, thanks to precise examples and color illustrations.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_25.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_26.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This logo features a modern, abstract symbol that evokes technology and innovation, perhaps in the form of a stylized geometric shape or an abstraction of electronic circuits, reflecting the dynamic and ever-changing nature of the IT industry.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_26.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_27.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This logo is a simple representation of an element of nature, such as a leaf, a flower, to evoke the purity and simplicity of the natural ingredients used in the product. The lines are soft and organic, reflecting the idea of sustainability and respect for the environment.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_27.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_28.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">The cover features a clean, professional design, with a neutral colored background such as gray or navy blue, evoking the confidence and stability associated with accounting. In the center, the title of the book is usually displayed in bold, clean font. The typography is carefully chosen to convey an impression of seriousness and clarity, making the content easier to read and understand.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_28.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_29.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">The catalog layout is a visually captivating and professionally designed template that presents design projects in a stunning way. With a sleek and modern design, it provides an ideal platform to showcase products, with high-quality images, detailed descriptions and layout plans. Whether showcasing residential or commercial projects, the catalog layout elevates design work, impressing clients and demonstrating expertise in creating beautiful and functional spaces.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_29.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_30.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">Today, packaging not only attracts attention: it also saves the planet. The more we are consumers, the more sustainable design can have a positive impact on our world.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_30.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_31.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">The concept and layout were carefully developed. With a specific design for education and learning, enough development time was spent playing with the design to see the final result. This book was a labor of love.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_31.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_32.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This cover exudes a professional and refined aesthetic, inviting the reader to explore the essential financial management knowledge it contains. possibly accompanied by minimalist graphic elements related to numbers or graphs, thus emphasizing the central subject of the book.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_32.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_33.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_33.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_34.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_34.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_35.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_35.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_36.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_36.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_37.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_37.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_38.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_38.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_39.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_39.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Branding_40.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Branding_40.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          <!-- end Branding -->

          </div>
        </div>
      </div>

      
    </div>
  </div> 
  
  <div class="vg-page page-testimonial">
    <div class="container">
      <h1 class="text-center fw-normal wow fadeInUp">Advertising</h1>
      <div class="row justify-content-center mt-5 wow fadeInUp">
        <div class="col-md-9">
          <div class="owl-carousel testi-carousel">

          <!-- Start Advertising   -->

            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_01.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">With definitions that are both rigorous and simple, this dictionary aims to help both children and adult beginners to discover and understand written language, thanks to precise examples and color illustrations.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Advertising_01.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_02.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This logo features a modern, abstract symbol that evokes technology and innovation, perhaps in the form of a stylized geometric shape or an abstraction of electronic circuits, reflecting the dynamic and ever-changing nature of the IT industry.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Advertising_01.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_03.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This logo is a simple representation of an element of nature, such as a leaf, a flower, to evoke the purity and simplicity of the natural ingredients used in the product. The lines are soft and organic, reflecting the idea of sustainability and respect for the environment.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Advertising_01.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_04.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">The cover features a clean, professional design, with a neutral colored background such as gray or navy blue, evoking the confidence and stability associated with accounting. In the center, the title of the book is usually displayed in bold, clean font. The typography is carefully chosen to convey an impression of seriousness and clarity, making the content easier to read and understand.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Advertising_04.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_05.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">The catalog layout is a visually captivating and professionally designed template that presents design projects in a stunning way. With a sleek and modern design, it provides an ideal platform to showcase products, with high-quality images, detailed descriptions and layout plans. Whether showcasing residential or commercial projects, the catalog layout elevates design work, impressing clients and demonstrating expertise in creating beautiful and functional spaces.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/Advertising_05.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_06.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">Today, packaging not only attracts attention: it also saves the planet. The more we are consumers, the more sustainable design can have a positive impact on our world.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/studio_22.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_07.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">The concept and layout were carefully developed. With a specific design for education and learning, enough development time was spent playing with the design to see the final result. This book was a labor of love.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/studio_22.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_08.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This cover exudes a professional and refined aesthetic, inviting the reader to explore the essential financial management knowledge it contains. possibly accompanied by minimalist graphic elements related to numbers or graphs, thus emphasizing the central subject of the book.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/studio_22.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_09.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">This book was a labor of love. The concept and layout were developed free of charge. Since the design had no structure, a lot of development time was spent playing with the design to see how everything would fit together.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/studio_22.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="item">
              <div class="row">
                <div class="col-md-6">
                  <div class="img-place">
                    <img src="../assets/img/testimonials/Advertising_10.jpg" alt="">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="caption">
                    <div class="testi-content">The map making process isn't too long and once you understand it, it will get easier every time. For maps, scale is an important standard. Being able to understand this language and train your eye to determine the size of an area on a large scale is a key skill.</div>
                    <div class="testi-info">
                      <!-- <div class="thumb-profile"> -->
                        <!--<img src="../assets/img/testimonials/studio_22.jpg" alt="">-->
                      <!-- </div> -->
                      <div class="tagline">
                        <h5 class="mb-0"></h5>
                        <!--
                          <span class="text-muted">CEO Nutshell</span>
                        -->
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            
            
        

          <!-- end Advertising   -->

          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- End testimonial -->

  <!-- Client 
  <div class="vg-page page-client">
    <div class="container">
      <div class="row">
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_1.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_2.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_3.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_4.svg" alt="">
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_5.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_6.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_7.svg" alt="">
          </div>
        </div>
        <div class="col-md-6 col-lg-4 col-xl-3 item">
          <div class="img-place wow fadeInUp">
            <img src="../assets/img/logo/company_8.svg" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>-->
  <!-- End client -->

  <!-- Blog -->
  <!-- <div class="vg-page page-blog" id="blog">
    <div class="container">
      <div class="text-center">
        <div class="badge badge-subhead wow fadeInUp">Blog</div>
      </div>
      <h1 class="text-center fw-normal wow fadeInUp">Latest Post</h1>
      <div class="row post-grid">
        <div class="col-md-6 col-lg-4 wow fadeInUp">
          <div class="card">
            <div class="img-place">
              <img src="../assets/img/work/work-9.jpg" alt="">
            </div>
            <div class="caption">
              <a href="javascript:void(0)" class="post-category">Technology</a>
              <a href="#" class="post-title">Invision design forward fund</a>
              <span class="post-date"><span class="sr-only">Published on</span> May 22, 2018</span>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 wow fadeInUp">
          <div class="card">
            <div class="img-place">
              <img src="../assets/img/work/work-6.jpg" alt="">
            </div>
            <div class="caption">
              <a href="javascript:void(0)" class="post-category">Business</a>
              <a href="#" class="post-title">Announcing a plan for small teams</a>
              <span class="post-date"><span class="sr-only">Published on</span> May 22, 2018</span>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-4 wow fadeInUp">
          <div class="card">
            <div class="img-place">
              <img src="../assets/img/work/work-1.jpg" alt="">
            </div>
            <div class="caption">
              <a href="javascript:void(0)" class="post-category">Design</a>
              <a href="#" class="post-title">5 basic tips for illustrating</a>
              <span class="post-date"><span class="sr-only">Published on</span> May 22, 2018</span>
            </div>
          </div>
        </div>
        <div class="col-12 text-center py-3 wow fadeInUp">
          <a href="blog-fullbar.html" class="btn btn-theme">See All Post</a>
        </div>
      </div>
    </div>
  </div> End blog -->

  <!-- Contact -->
  <div class="vg-page page-contact" id="contact">
    <div class="container-fluid">
      <div class="text-center wow fadeInUp">
        <div class="badge badge-subhead">Contact</div>
      </div>
      <h1 class="text-center fw-normal wow fadeInUp">Get in touch</h1>
      <div class="row py-5">
        <div class="col-lg-7 px-0 pr-lg-3 wow zoomIn">
          <div class="vg-maps">
            <div id="google-maps" style="width: 100%; height: 100%;"></div>
          </div>
        </div>
        <div class="col-lg-5">
          <form class="vg-contact-form">
            <div class="form-row">
              <div class="col-12 mt-3 wow fadeInUp">
                <input class="form-control" type="text" name="Name" placeholder="Your Name">
              </div>
              <div class="col-6 mt-3 wow fadeInUp">
                <input class="form-control" type="text" name="Email" placeholder="Email Address">
              </div>
              <div class="col-6 mt-3 wow fadeInUp">
                <input class="form-control" type="text" name="Subject" placeholder="Subject">
              </div>
              <div class="col-12 mt-3 wow fadeInUp">
                <textarea class="form-control" name="Message" rows="6" placeholder="Enter message here.."></textarea>
              </div>
              <button type="submit" class="btn btn-theme mt-3 wow fadeInUp ml-1">Send Message</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div> <!-- End Contact -->

  <!-- Footer -->
  <div class="vg-footer">
    <h1 class="text-center">Mallouk portfolio</h1>
    <div class="container">
      <div class="row">
        <!--<div class="col-lg-4 py-3">
          <div class="footer-info">
            <p>Where to find me</p>
            <hr class="divider">
            <p class="fs-large fg-white">1600 Amphitheatre Parkway Mountain View, California 94043 US</p>
          </div>
        </div>-->
        <div class="col-md-6 col-lg-3 py-3">
          <div class="float-lg-right">
            <p>Follow me</p>
            <hr class="divider">
            <ul class="list-unstyled">
              <li><a href="#">Instagram</a></li>
              <li><a href="#">Facebook</a></li>
              <li><a href="#">Twitter</a></li>
              <li><a href="#">Youtube</a></li>
            </ul>
          </div>
        </div>
        <div class="col-md-6 col-lg-3 py-3">
          <div class="float-lg-right">
            <p>Contact me</p>
            <hr class="divider">
            <ul class="list-unstyled">
              <li>med.mallouk@hotmail.com</li>
              <li>+39 3487095185</li>
              <!--<li>+813023</li>-->
            </ul>
          </div>
        </div>
      </div>
      <div class="row justify-content-center mt-3">
        <div class="col-12 mb-3">
          <h3 class="fw-normal text-center">Subscribe</h3>
        </div>
        <div class="col-lg-6">
          <form class="mb-3">
            <div class="input-group">
              <input type="text" class="form-control" placeholder="Email address">
              <input type="submit" class="btn btn-theme no-shadow" value="Subscribe">
            </div>
          </form>
        </div>
        <div class="col-12">
          <p class="text-center mb-0 mt-4"> MALLOUK Mohamed portfolio | 2024
          <!-- <p class="text-center mb-0 mt-4">Copyright &copy;2024. All right reserved | Mohamed Mallouk portfolio -->
          </p>
        </div>
      </div>
    </div>
  </div> <!-- End footer -->


  <script src="../assets/js/jquery-3.5.1.min.js"></script>

  <script src="../assets/js/bootstrap.bundle.min.js"></script>

  <script src="../assets/vendor/owl-carousel/owl.carousel.min.js"></script>

  <script src="../assets/vendor/perfect-scrollbar/js/perfect-scrollbar.js"></script>

  <script src="../assets/vendor/isotope/isotope.pkgd.min.js"></script>

  <script src="../assets/vendor/nice-select/js/jquery.nice-select.min.js"></script>

  <script src="../assets/vendor/fancybox/js/jquery.fancybox.min.js"></script>

  <script src="../assets/vendor/wow/wow.min.js"></script>

  <script src="../assets/vendor/animateNumber/jquery.animateNumber.min.js"></script>

  <script src="../assets/vendor/waypoints/jquery.waypoints.min.js"></script>

  <script src="../assets/js/google-maps.js"></script>

  <script src="../assets/js/topbar-virtual.js"></script>

  <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAIA_zqjFMsJM_sxP9-6Pde5vVCTyJmUHM&callback=initMap"></script>

</body>

</html>
