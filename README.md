<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AJ- Owned Personal baby Website</title>
    <link rel="stylesheet" href="styless.css"></link>
</head>
<body>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#">Nathan R<span> Landagan</span></a></div>
            <ul class="menu">
                <li><a href="#home">Main</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#footer">Footer</a></li>
            </ul>
          </nav>
        </div>
        <section class="home" id="home">
            <div class="max-width">
                <div class="home-content">
                    <p>Hi Im AJ! I liked Playing toys and Watching Nursery Rhymes, I also Liked Playing with my Brother and Sister.</p>
                    <button class="btn">Learn more</button>
                    </div> 
                </div>
            </div>
        </div>
    </section>
  <!--About Section-->
    <section class="about" id="about">
      <div class="max-width">
          <h1 class="title">About</h1>
          <div class="about-content">
          <div class="column left">
            <img src="images/2.jpg" alt="Baby AJ">
          </div>
          <div class="column right">
            <h2 class="text">Hi! Im Nathan!</h2>
          <p>Im Nathan AJ Landagan, 1 yr old </p>
        </div>
      </div>
    </div>
    </section>
    <div class="slideshow-container">
      <h1>Latest Photos</h1>
        <div class="mySlides">
          <img src="images/img1.jpg">
          <img src="images/img2.jpg">
          <img src="images/img3.jpg">
        </div>
      
        <div class="mySlides">
          <img src="images/img4.jpg">
          <img src="images/img5.jpg">
          <img src="images/img6.jpg">
        </div>
      
        <div class="mySlides">
          <img src="images/img7.jpg">
          <img src="images/img8.jpg">
          <img src="images/img9.jpg">
        </div>
      
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
      </div>
      <br>
      
      <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
      </div>
         </section>
         <section class="" id="footer">
            <h1>Footer</h1>
            <p>lorem ipsum lorem ipsum</p>
         </section> 
         <script src="script.js"></script>
         <script src="script2.js"></script>
</body>
</html>
