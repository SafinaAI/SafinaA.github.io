# SafinaA.github.io
Calvin Klein Denim JungKook
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Latest compiled and minified CSS -->
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
      integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u"
      crossorigin="anonymous"
    />

    <!-- Optional theme -->
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css"
      integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp"
      crossorigin="anonymous"
    />

    <!-- Latest compiled and minified JavaScript -->
    <script
      src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"
      integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa"
      crossorigin="anonymous"
    ></script>

    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />

    <link
      href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&family=PT+Sans&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    />
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="/js/main.js">
    <title>Document</title>
  </head>
  <body>
    <div class="container-fluid sticky-top">
      <header class="header container-fluid">
        <!-- HEADER_TOP_START -->
        <div class="header-top">
          <div class="container-fluid-height">
            <div class="row">
              <div class="col-6 col-sm-4 header-top-phone">
                <div class="header-top-phone">
                  <i class="fa-solid fa-mobile-screen-button"></i>
                  <a href="tel:+495675431">(495)67-54-31</a>
                </div>
              </div>
              <div class="col-sm-4 header-top-icons d-none d-sm-block">
                <ul class="social-icons">
                  <li>
                    <a href="#"><i class="fa-brands fa-instagram"></i></a>
                  </li>
                  <li>
                    <a href="#"><i class="fa-brands fa-twitter"></i></a>
                  </li>
                  <li>
                    <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                  </li>
                </ul>
              </div>
              <div class="col-6 col-sm-4 header-top-account">
                <div class="d-flex justify-content-end">
                  <div class="btn-group">
                    <div class="dropdown">
                      <button
                        class="btn btn-mar-pad btn-secondary dropdown-toggle btn-sm btn-header-top"
                        type="button"
                        data-bs-toggle="dropdown"
                        aria-expanded="false"
                      >
                        Account
                      </button>
                      <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Sign In</a></li>
                        <li><a class="dropdown-item" href="#">Sign Up</a></li>
                      </ul>
                    </div>
                  </div>

                  <div class="btn-group">
                    <div class="dropdown">
                      <button
                        class="btn btn-mar-pad btn-secondary dropdown-toggle btn-sm btn-header-top"
                        type="button"
                        data-bs-toggle="dropdown"
                        aria-expanded="false"
                      >
                        EN
                      </button>
                      <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">RU</a></li>
                        <li><a class="dropdown-item" href="#">CH</a></li>
                      </ul>
                    </div>
                  </div>
                </div>
                <!-- header-top-account -->
              </div>
            </div>
          </div>
        </div>
        <!-- </header> -->
        <!-- HEADER_TOP_END ------------------------->

        <div class="header-middle bg-white py-4">
          <div class="container-fluid">
            <div class="row align-items-center">
              <div class="col-6 col-md-4">
                <a href="index.html" class="header-logo h1">Calvin Klein</a>
              </div>
              <div class="col-6 col-md-4 order-md-2 cart-buttons text-end">
                <a href="#" class="btn p-1">
                  <i class="fa-solid fa-heart"></i>
                  <span
                    class="badge text-bg-secondary cart-badge bg-secondary rounded-circle"
                    >3</span
                  >
                </a>
                <button
                  class="btn p-1"
                  type="button"
                  data-bs-toggle="offcanvas"
                  data-bs-target="#offcanvasCart"
                  aria-controls="offcanvasCart"
                >
                  <i class="fa-solid fa-cart-shopping"></i>
                  <span
                    class="badge text-bg-secondary cart-badge bg-secondary rounded-circle"
                    >5</span
                  >
                </button>

                <div
                  class="offcanvas offcanvas-end"
                  tabindex="-1"
                  id="offcanvasCart"
                  aria-labelledby="offcanvasCartleLabel"
                >
                  <div class="offcanvas-header">
                    <h5 class="offcanvas-title" id="offcanvasCartLabel">
                      Cart
                    </h5>
                    <button
                      type="button"
                      class="btn-close"
                      data-bs-dismiss="offcanvas"
                      aria-label="Close"
                    ></button>
                  </div>
                  <div class="offcanvas-body">
                    <div>
                      Some text as placeholder. In real life you can have the
                      elements you have chosen. Like, text, images, lists, etc.
                    </div>
                    <div class="dropdown mt-3">
                      <button
                        class="btn btn-secondary dropdown-toggle"
                        type="button"
                        data-bs-toggle="dropdown"
                      >
                        Dropdown button
                      </button>
                      <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Action</a></li>
                        <li>
                          <a class="dropdown-item" href="#">Another action</a>
                        </li>
                        <li>
                          <a class="dropdown-item" href="#"
                            >Something else here</a
                          >
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-md-4 order-md-1 mt-2 mt-md-0">
                <form action="">
                  <div class="input-group">
                    <input
                      type="text"
                      class="form-control"
                      name="s"
                      placeholder="Searching..."
                      aria-label="Searching..."
                      aria-describedby="button-search"
                    />
                    <button
                      class="btn btn-outline-secondary"
                      type="submit"
                      id="button-search"
                    >
                      <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
        <!-- HEADER-MIDDLE_END ------------------------------->

        <div class="header-bottom">
        <nav class="navbar navbar-expand-md bg-white" >
          <div class="container-fluid cont-fluid-start">
            <button
              class="navbar-toggler"
              type="button"
              data-bs-toggle="offcanvas"
              data-bs-target="#offcanvasNavbar"
              aria-controls="offcanvasNavbar"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="offcanvas offcanvas-start" id="offcanvasNavbar" tabindex="-1" aria-labelledby="offcanvasNavbarLabel">
              <div class="offcanvas-body">             
              <ul class="navbar-nav">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="index.html"
                    >Men</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Women</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Kids</a>
                </li>
                <li class="nav-item dropdown">
                  <a
                    class="nav-link dropdown-toggle"
                    href="#"
                    role="button"
                    data-bs-toggle="dropdown"
                    aria-expanded="false"
                    data-bs-auto-close="outside"
                  >
                    Catalog
                  </a>
                  <ul class="dropdown-menu dropdown-menu-end">
                    <li><a class="dropdown-item" href="#">Underwear</a></li>
                    <li>
                      <a class="dropdown-item" href="#">Jeans</a>
                    </li>
                    <li class="nav-item dropend">
                      <a class="dropdown-item dropdown-toggle" href="#" data-bs-toggle="dropdown" data-bs-auto-close="outside">Sportswear</a>
                    <ul class="dropdown-menu dropdown-menu-end">
                      <li>
                        <a href="#" class="dropdown-item">Shop All</a>
                      </li>
                      <li>
                        <a href="#" class="dropdown-item">Leggins</a>
                      </li>
                      <li>
                        <a href="#" class="dropdown-item">Sports Bras</a>
                      </li>
                      <li>
                        <a href="#" class="dropdown-item">Swimwear</a>
                      </li>
                    </ul>
                    </li>
                    <li>
                      <a class="dropdown-item" href="#">Coat</a>
                    </li>
                    <li>
                      <a class="dropdown-item" href="#">Shirts</a>
                    </li>
                    <li>
                      <a class="dropdown-item" href="#">Shoes</a>
                    </li>
                  </ul>
                </li>
              </ul>
            </div>
            </div>
          </div>
        </nav>
      </div>  

      <!-- <nav
        class="navbar navbar-expand-md navbar-light bg-light navbar-margin-bottom"
      >
         HEADER_NAV_START 
        <div class="container-fluid navbar-height">
          <a class="navbar-brand" href="#">Calvin Klein</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto">
              <li class="nav-item">
                <a href="#" class="nav-link">Home</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">Woman</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">Man</a>
              </li>
              <li class="nav-item">
                <a href="#" class="nav-link">Kids</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      HEADER_NAV_END -->
    </div>

    <main class="main">
      <div class="carousel slide" id="slides">
        <div class="carousel-indicators">
          <button
            type="button"
            data-bs-target="#slides"
            data-bs-slide-to="0"
            class="active"
            aria-current="true"
            aria-label="Slide 1"
          ></button>
          <button
            type="button"
            data-bs-target="#slides"
            data-bs-slide-to="1"
            aria-label="Slide 2"
          ></button>
          <button
            type="button"
            data-bs-target="#slides"
            data-bs-slide-to="2"
            aria-label="Slide 3"
          ></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img/jk_new_4.jpg" alt="" class="d-block w-100" />
            <div class="carousel-caption d-none d-md-block">
              <h2 class="display-2">Essential Denim Jacket</h2>
              <h6 class="display-6">
                Bold new jackets and coats made to adapt to you.​
              </h6>
              <button type="button" class="btn btn-outline-light btn-lg">
                Shop Now
              </button>
            </div>
          </div>
          <div class="carousel-item">
            <img src="img/jk_new_5.jpg" alt="" class="d-block w-100" />
            <div class="carousel-caption d-none d-md-block">
              <h2 class="display-2">Calvin Klein Hero Tee​</h2>
              <h6 class="display-6">Timeless. Essential. Expressive styles.</h6>
              <button type="button" class="btn btn-outline-light btn-lg">
                Shop Now
              </button>
            </div>
          </div>
          <div class="carousel-item">
            <img src="img/jk_calvin.jpg" alt="" class="d-block w-100" />
            <div class="carousel-caption d-none d-md-block">
              <h2 class="display-2">Explore Outerwear​</h2>
              <h6 class="display-6">
                Bold new jackets and coats made to adapt to you.
              </h6>
              <button type="button" class="btn btn-outline-light btn-lg">
                Shop Now
              </button>
            </div>
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#slides"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#slides"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <div class="container-fluid">
        <div class="row jumbotron">
          <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-10">
            <h2 class="h2_text">Fall 2023 Calvin Klein Campaign​</h2>
            <h6 class="h6_text">
              Discover Jung Kook and Kid Cudi in scenes of pleasure and play.
              Confidence simmers on high.​
            </h6>
          </div>
          <div class="col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-2">
            <a href="#"
              ><button class="btn btn-outline-dark btn-lg" type="button">
                Shop Now
              </button></a
            >
          </div>
        </div>
      </div>
      <section class="featured-products">
        <div class="container-fluid">
          <div class="row mb-5">
            <div class="col-12">
              <h2 class="section-title">
                <span>Featured Products</span>
              </h2>
            </div>
          </div>
          <div class="row">
            <div class="col-lg-3 col-md-4 col-sm-6 mb-3">
              <div class="product-card">
                <div class="product-card-offer">
                  <div class="offer-hit">hit</div>
                  <div class="offer-new">new</div>
                </div>
                <div class="product-thump">
                  <a href="product.html"><img src="img/фото_с_сайта_CK_маленькие/APAC Denim Campaign Site Refresh.jpg" alt=""></a>
                </div>
                <div class="products-details">
                  <h4>
                    <a href="product.html">Underwear</a>
                  </h4>
                  <p class="products-exerpt">Cotton Stretch 3 Pack Low Rise Trunk</p>
                  <div class="product-buttom-details d-flex justify-content-between">
                    <div class="product-price">
                      <small>70$</small>
                      $65
                    </div>
                    <div class="product-links">
                      <a href="#" class="btn btn-outline-secondary add-to-cart">
                        <i class="fa-solid fa-cart-plus"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-3 col-md-4 col-sm-6 mb-3">
              <div class="product-card">
                <div class="product-card-offer">
                  <div class="offer-hit">hit</div>
                </div>
                <div class="product-thump">
                  <a href="product.html"><img src="img/фото_с_сайта_CK_маленькие/hoodie men LP desktop5.jpg" alt=""></a>
                </div>
                <div class="products-details">
                  <h4>
                    <a href="product.html">Hoodie</a>
                  </h4>
                  <p class="products-exerpt">Naturals Mineral Dye Monologo Sweatshirt</p>
                  <div class="product-buttom-details d-flex justify-content-between">
                    <div class="product-price">
                      
                      $65
                    </div>
                    <div class="product-links">
                      <a href="#" class="btn btn-outline-secondary add-to-cart">
                        <i class="fa-solid fa-cart-plus"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-3 col-md-4 col-sm-6 mb-3">
              <div class="product-card">
                <div class="product-card-offer">
                  <!-- <div class="offer-hit">hit</div>
                  <div class="offer-new">new</div> -->
                </div>
                <div class="product-thump">
                  <a href="product.html"><img src="img/фото_с_сайта_CK_маленькие/men Ck sport desktop.jpg" alt=""></a>
                </div>
                <div class="products-details">
                  <h4>
                    <a href="product.html">Sport</a>
                  </h4>
                  <p class="products-exerpt">Water-Repellent Gym Shorts</p>
                  <div class="product-buttom-details d-flex justify-content-between">
                    <div class="product-price">
                      <small>80$</small>
                      $95
                    </div>
                    <div class="product-links">
                      <a href="#" class="btn btn-outline-secondary add-to-cart">
                        <i class="fa-solid fa-cart-plus"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-3 col-md-4 col-sm-6 mb-3">
              <div class="product-card">
                <div class="product-card-offer">
                  <!-- <div class="offer-hit">hit</div> -->
                  <div class="offer-new">new</div>
                </div>
                <div class="product-thump">
                  <a href="product.html"><img src="img/фото_с_сайта_CK_маленькие/men hat desktop6.jpg" alt=""></a>
                </div>
                <div class="products-details">
                  <h4>
                    <a href="product.html">Hat</a>
                  </h4>
                  <p class="products-exerpt">Denim Baseball Cap</p>
                  <div class="product-buttom-details d-flex justify-content-between">
                    <div class="product-price">
                      <!-- <small>70$</small> -->
                      $65
                    </div>
                    <div class="product-links">
                      <a href="#" class="btn btn-outline-secondary add-to-cart">
                        <i class="fa-solid fa-cart-plus"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-3 col-md-4 col-sm-6 mb-3">
              <div class="product-card">
                <div class="product-card-offer">
                  <div class="offer-hit">hit</div>
                  <div class="offer-new">new</div>
                </div>
                <div class="product-thump">
                  <a href="product.html"><img src="img/фото_с_сайта_CK_маленькие/men jeans denim jacket desktop.jpg" alt=""></a>
                </div>
                <div class="products-details">
                  <h4>
                    <a href="product.html">Jacket</a>
                  </h4>
                  <p class="products-exerpt">Utility Denim Jacket</p>
                  <div class="product-buttom-details d-flex justify-content-between">
                    <div class="product-price">
                      <small>90$</small>
                      $85
                    </div>
                    <div class="product-links">
                      <a href="#" class="btn btn-outline-secondary add-to-cart">
                        <i class="fa-solid fa-cart-plus"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-3 col-md-4 col-sm-6 mb-3">
              <div class="product-card">
                <div class="product-card-offer">
                  <div class="offer-hit">hit</div>
                  <div class="offer-new">new</div>
                </div>
                <div class="product-thump">
                  <a href="product.html"><img src="img/фото_с_сайта_CK_маленькие/men tee jeans denim desktop.jpg" alt=""></a>
                </div>
                <div class="products-details">
                  <h4>
                    <a href="product.html">Jeans</a>
                  </h4>
                  <p class="products-exerpt">Fitted through the hip and thigh with a slim leg.</p>
                  <div class="product-buttom-details d-flex justify-content-between">
                    <div class="product-price">
                      <small>70$</small>
                      $65
                    </div>
                    <div class="product-links">
                      <a href="#" class="btn btn-outline-secondary add-to-cart">
                        <i class="fa-solid fa-cart-plus"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-3 col-md-4 col-sm-6 mb-3">
              <div class="product-card">
                <div class="product-card-offer">
                  <div class="offer-hit">hit</div>
                  <!-- <div class="offer-new">new</div> -->
                </div>
                <div class="product-thump">
                  <a href="product.html"><img src="img/фото_с_сайта_CK_маленькие/hoodie men LP desktop5.jpg" alt=""></a>
                </div>
                <div class="products-details">
                  <h4>
                    <a href="product.html">Tee</a>
                  </h4>
                  <p class="products-exerpt">Badge Logo Crew Neck Tee</p>
                  <div class="product-buttom-details d-flex justify-content-between">
                    <div class="product-price">
                      <!-- <small>70$</small> -->
                      $65
                    </div>
                    <div class="product-links">
                      <a href="#" class="btn btn-outline-secondary add-to-cart">
                        <i class="fa-solid fa-cart-plus"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-lg-3 col-md-4 col-sm-6 mb-3">
              <div class="product-card">
                <div class="product-card-offer">
                  <div class="offer-hit">hit</div>
                  <div class="offer-new">new</div>
                </div>
                <div class="product-thump">
                  <a href="product.html"><img src="img/фото_с_сайта_CK_маленькие/men unberwear tucker desktop.jpg" alt=""></a>
                </div>
                <div class="products-details">
                  <h4>
                    <a href="product.html">Tucker</a>
                  </h4>
                  <p class="products-exerpt">Intense Power Ultra Cooling Trunks</p>
                  <div class="product-buttom-details d-flex justify-content-between">
                    <div class="product-price">
                      <small>70$</small>
                      $65
                    </div>
                    <div class="product-links">
                      <a href="#" class="btn btn-outline-secondary add-to-cart">
                        <i class="fa-solid fa-cart-plus"></i>
                      </a>
                    </div>
                  </div>
                </div>
              </div>
            </div>


          </div>
        </div>
      </section>
    </main>

    <footer class="footer" id="footer">
      <div class="container-fluid">
          <div class="row">
              <div class="col-md-3 col-6">
                  <h4>Information</h4>
                  <ul class="list-unstyled">
                      <li><a href="index.html">Home</a></li>
                      <li><a href="#">Payment</a></li>
                      <li><a href="#">Delivery</a></li>
                      <li><a href="#">Contacts</a></li>
                  </ul>
              </div>

              <div class="col-md-3 col-6">
                  <h4>Working hours</h4>
                  <ul class="list-unstyled">
                      <li>Paris, str. Bretan</li>
                      <li>mon-fri: 9:00 - 18:00</li>
                  </ul>
              </div>

              <div class="col-md-3 col-6">
                  <h4>Contacts</h4>
                  <ul class="list-unstyled">
                      <li><a href="tel:1234567890">123-456-7890</a></li>
                      <li><a href="tel:0987654321">098-765-4321</a></li>
                  </ul>
              </div>

              <div class="col-md-3 col-6">
                  <h4>Follow us</h4>
                  <ul class="footer-icons">
                      <li><a href="#"><i class="fa-brands fa-youtube"></i></a></li>
                      <li><a href="#"><i class="fa-brands fa-facebook-f"></i></a></li>
                      <li><a href="#"><i class="fa-brands fa-instagram"></i></a></li>
                  </ul>
              </div>
          </div>
      </div>
  </footer>

    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
