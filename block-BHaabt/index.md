writeCode

- Create an insurance website according to the layout shown below.

![Web Typography Assignment level 2](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/web-typography/ex-2.png)

### Typography

**Heading**

Font Family: [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display?query=dm+se)

**Body**

Font Family: [Karla](https://fonts.google.com/specimen/Karla?query=karla)

- Using CSS resets is necessary.
- Use semantic tags and keep the nesting and indentation proper.
- Work on typography in detail.
<!DOCTYPE html>
<html lang="end">
    <head> 
        <meta charset="UTF-8">
        <title> Hackant </title>
        <script src="https://kit.fontawesome.com/ef43d9bbc3.js" crossorigin="anonymous"></script>
        <link rel="stylesheet" href="assets/style.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=Karla:wght@300&display=swap" rel="stylesheet"> 
    </head>
    <body>
        <header class="container flex">
            <div class="brand-name">
                <h2>ProInsure</h2>
            </div>
            <nav class="home">
                <a href="#">Home</a>
                <a href="#">About</a>
                <a href="#">Contact</a>
                <a href="#">View Plans</a>
                </div>
            </nav>
        </header>
      <main>
          <section class="background">
              <div class=" sec-1 container flex">
                  <article class="art-1">
                      <hr>
                      <h1>Humanizing<br> 
                          your insurance</h1>
                      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
                          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a gallery 
                          printing and typesetting industry. 
                      </p>
                      <button class="but-1">VIEW PLANS</button>
                  </article>
                  <div class="img-1">
                      <img class="img-1-1" src="assets/01.png" alt="image-1">
                  </div>
              </div>
          </section>
          <section class="sec-2 container flex">
              <div class="img-2">
                  <img src="assets/02.png" alt="immg 2">
              </div>
              <article class="art-1 art-2">
                  <h3>About the insurance</h3>
                  <p>orem Ipsum is simply dummy text of the printing and typesetting industry. 
                    Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a gallery 
                </p>
                <button class="but-1">Know More</button>
              </article>
          </section>
          <section class="sec-3 container">
              <hr>
              <h3>We are different</h3>
              <div class="features flex">
                  <div class="feat-1">
                    <i class="fas fa-user-cog icon-1"></i>
                    <h4>Easy Process</h4>
                    <p>orem Ipsum is simply dummy text of the printing and typesetting industry. 
                        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,</p>
                  </div>
                  <div class="features flex">
                    <div class="feat-1">
                      <i class="fas fa-user-cog icon-1"></i>
                      <h4>Affordable Price</h4>
                      <p>orem Ipsum is simply dummy text of the printing and typesetting industry. 
                          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,</p>
                    </div>
                    <div class="features flex">
                        <div class="feat-1">
                          <i class="fas fa-user-cog icon-1"></i>
                          <h4>You come first</h4>
                          <p>orem Ipsum is simply dummy text of the printing and typesetting industry. 
                              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,</p>
                        </div>
                    </div>
          </section>
          <section class="sec-4 container flex">
              <div class="subhead">
                  <h3>Find out more about how we work</h3>
              </div>
              <button class="but-1">
                  HOW WE WORK
              </button>
          </section>
      </main>
      <footer class="container">
          <div class="footer-1 flex">
              <div class="footer-name">
                <h2>ProInsure</h2>
                </div>
              <div class="icon2">
                  <a href="#"><i class="fab fa-facebook-square icon-2"></i></a>
                  <a href="#"><i class="fab fa-twitter-square icon-2"></i></a>
              </div>
          </div>
          <hr>
          <nav class="nav-f">
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
            <a href="#">How we work</a>
            </div>
          </nav>
          <div class="copyright">
              <p>Altcampus Services Private Limited,2016</p>
          </div>
      </footer>
   </body>
</html>
