!DOCTYPE html>
<html lang="en">
  <head>
    <head>
<title>Ice Cream Shop </title>
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <link rel="stylesheet" href="project 3.css">
    </head>

    <body>
      <header class="container">
        <a href="#hero" class="logo clr-transition">Ami Ice Cream</a>
        <nav class="navbar">
          <ul class="nav-items">
            <li class="nav-item"><a href="#hero" class="nav-link clr-transition">Home</a></li>
            <li class="nav-item"><a href="#products" class="nav-link clr-transition">Product</a></li>
            <li class="nav-item"><a href="#about" class="nav-link clr-transition">About</a></li>
            <li class="nav-item"><a href="#contact" class="nav-link clr-transition">Contact</a></li>
          </ul>
          <div class="social-links">
            <ul>
              <li><i class='bx bxl-instagram nav-icon clr-transition'></i></li>
              <li><i class='bx bxl-twitter nav-icon clr-transition'></i></li>
              <li><i class='bx bxl-facebook nav-icon clr-transition'></i></li>
            </ul>
            <span class="line-divider clr-transition"></span>
            <div class="theme-togglers">
              <i class='bx bxs-sun theme-toggler clr-transition'></i>
              <i class='bx bxs-moon theme-toggler clr-transition'></i>
            </div>
          </div>
        </nav>

        <div class="menu-togglers">
          <i class="bx bx-menu menu-toggle clr-transition"></i>
        </div>
      </header>
      <main id="hero" class="main">
        <section class="section section-one">
          <div class="container hook-container">
            <h1 class="hook-title clr-transition"> ice cream for real ice cream lovers</h1>
            <h2 class="hook-sub_title clr-transition">all flavour ice cream for pleasure seekers.</h2>
            <div class="hero-btns-container">
              <button class="button btn-hero btn-primary buy-hero-btn"><i class="bx bx-cart in-btn-icon"></i> BUY ONLINE</button>
              <button class="button btn-hero btn-second-alt"><i class="bx bx-map in-btn-icon"></i> FIND IN STORE</button>
            </div>
          </div>
          
        </section>

        
        <section id="products" class="section section-two container">
          <div class="s-two-upper-info">
            <h2 class="s-two-slogan">We Pride Ourselves On Exceptional Flavors.</h2>
            <p class="s-two-definition s-definition">
              The nearly -200 °C (-328 °F) liquid freezes the ingredients—sweet cream, flavoring, and handpicked mix-ins—almost instantaneously, creating tiny ice crystals and a smooth texture.
            </p>
          </div>
          <div class="s-two-products">
            <div class="product product-one">
              <h3 class="price pos-abs-center">70</h3>
              <img src="./images/cone vennila.jpg" alt="ice cream with honey" loading="lazy">
              <h3 class="buy-btn pos-abs-center">BUY</h3>
              <h3 class="name pos-abs-center">Ice cream <b>honey</b></h3>
            </div>
            <div class="product product-two">
              <h3 class="price pos-abs-center">50</h3>
              <img src="./images/Mint-Chocolate-Chip-Ice-Cream-1-500x375.jpg" loading="lazy">
              <h3 class="buy-btn pos-abs-center">BUY</h3>
              <h3 class="name pos-abs-center">Choco <b>delight</b></h3>
            </div>
            <div class="product product-three">
              <h3 class="price pos-abs-center">150</h3>
              <img src="https://raw.githubusercontent.com/r-e-d-ant/eCream/master/assets/images/product3.png" alt="ice cream with honey" loading="lazy">
              <h3 class="buy-btn pos-abs-center">BUY</h3>
              <h3 class="name pos-abs-center">Carnival <b>strawberry</b></h3>
            </div>
          </div>
        </section>

        <!-- section three -->
        <section class="section section-three container">
          <div class="s-three-upper-img-container">
            <img src="https://raw.githubusercontent.com/r-e-d-ant/eCream/master/assets/images/product4.png" alt="" loading="lazy">
          </div>
          <div class="s-three-lower-container">
            <h3 class="s-three-title">Stress out? Try eating our Ami Ice cream.</h3>
            <p class="s-three-desc s-definition">The nearly -200 °C (-328 °F) liquid freezes the ingredients—sweet cream, flavoring, and handpicked mix-ins—almost instantaneously, creating tiny ice crystals and a smooth texture.</p>
            <span class="s-three-price">120</span>
            <button class="button ad-buy-btn">Buy Now</button>
          </div>
        </section>

        <!-- section four -->
        <section id="about" class="section section-four container">
          <div class="oath-container">
            <h3 class="s-three-title s-four-title">Your ice cream store around the corner.</h3>
            <p class="s-three-desc s-definition">We stands strong to satisfy customers, consumers and other stakeholders with high quality ice creams and superior services.</p>

            <div class="employer-info">
              <div class="employer">
                <h4 class="name">Dinesh kumar</h4>
                <h5 class="title"> manager</h5>
              </div>
              <div class="rate">
                 
              </div>
            </div>
          </div>
          <div class="waiter-img-container">
          </div>
        </section>

        
        <section class="section-five container">
          <div class="promo-card">
            <div class="promo-info-container">
              <h2 class="promo-title s-three-title">Flat 50% OFF, Hurry up before the stock ends</h2>
              <p class="promo-description s-definition">The nearly -200 °C (-328 °F) liquid freezes the ingredients—sweet cream, flavoring, and handpicked</p>
              <button class="button ad-buy-btn promo-btn">Buy Now</button>
            </div>
            <img src = "./images/png-transparent-child-girl-with-ice-cream-thumbnail.png" alt="woman licking eating cream">
          </div>
        </section>
      </main>
      <footer id="contact" class="footer container">
        <h2 class="footer-title">Contact</h2>
        <form class="contact-form">
          <div class="name-email-inputs-container">
            <div class="form-control">
              <label for="name" class="form-label">Name</label>
              <input type="text" id="name" class="normal-input all-input">
            </div>
            <div class="form-control">
              <label for="email" class="form-label">Email</label>
              <input type="text" id="email" class="normal-input all-input">
            </div>
          </div>

          
          <div class="form-control">
            <label for="message" class="form-label">Message</label>
            <div contenteditable="true" id="message" class="textarea-input all-input"></div>
          </div>
          <button type="submit" class="send-msg-btn button ad-buy-btn">SEND</button>
        </form>

        <div class="other-footer-infos-container">
          <span class="footer-info"><i class="bx bx-map"></i> Address, coimbatore 23, India</span>
          <span class="footer-info"><i class="bx bx-phone"></i> 22 (923) 3424 4156</span>
          <span class="footer-info"><i class="bx bx-mail-send"></i> Ami Ice Cream@domain.com</span>
          <div class="footer-social-links">
            <ul>
              <li><i class='bx bxl-instagram-alt nav-icon clr-transition'></i></li>
              <li><i class='bx bxl-twitter nav-icon clr-transition'></i></li>
              <li><i class='bx bxl-facebook-square nav-icon clr-transition'></i></li>
            </ul>
          </div>
        </div>
        <div class="lower-footer">
          <span class="lower-footer-elt copy">copyright © 2022 Ami Ice Cream</span>
          <span class="lower-footer-elt developer">Developed by <a href="https://thierrymugisha.me/" class="developerportfoliolink" title="developer portfolio link">Indhumathi D.</a></span>
          <span class="lower-footer-elt policy"><a href="#" class="policy-link">Privacy • Policy</a></span>
        </div>
      </footer>

      <script src="project 3.js">o</script>
    </body>
</html>
