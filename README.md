# canselm28.github.io
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="css/styles.css" />
    <link rel="stylesheet" href="css/glightbox.min.css" />
    <link rel="stylesheet" href="css/all.min.css" />
    <title>My Portfolio</title>
  </head>
  <body>
    <!-- Begin Top Nav -->
    <nav id="top-nav-bar" class="nav-bar top-nav">
      <h1 class="logo"><a href="index.html">Ceanna Anselm</a></h1>
      <ul class="nav-menu">
        <li class="nav-item"><a href="#portfolio">Digital</a></li>
        <li class="nav-item"><a href="#about">Design</a></li>
		<li class="nav-item"><a href="#about">Drawing</a></li>
		<li class="nav-item"><a href="#about">Photography</a></li>
		<li class="nav-item"><a href="#about">About</a></li>
       
        
      </ul>
    </nav>
    <!-- End Top Nav -->

    <!-- Begin Hero Header -->
    <header class="hero-box">
      <section class="hero-image-box">
        <img
          class="hero-video"
          src= "../../Digital/sunset.jpg"
          autoplay
          muted
          loop
        ></img>
      </section>
      <section class="hero-text-box">
        <h1 class="hero-heading">Ceanna Anselm</h1>
        <p class="hero-text">
          Artist · Photographer · Designer
        </p>
        <p>
          <a href="#portfolio">
            <button type="button" class="hero-button">View Portfolio</button>
          </a>
        </p>
      </section>
    </header>
    <!-- End Hero Header -->

    <!-- Begin Portfolio -->
    <section id="portfolio" class="portfolio-container section-stop">
      <h1>Digital</h1>
      <section class="portfolio-gallery">
        <div class="gallery-item">
          <a
            href= "../../Digital/shadow.jpg"
            class="glightbox"
            data-glightbox="title: Shadow; description: Digital drawing with drawing tablet"
          >
            <img
              src= "../../Digital/shadow.jpg"
              alt="Shadow"
              class="gallery-img"
          /></a>
        </div>
        <div class="gallery-item">
          <a
            href= "../../Digital/Perspective Leaf V2.jpg"
            class="glightbox"
			data-glightbox="title: Leaf Portal; description: Image mashup in photoshop"
          >
            <img
              src= "../../Digital/Perspective Leaf V2.jpg"
              alt="Leaf Portal"
              class="gallery-img"
          /></a>
        </div>
        <div class="gallery-item">
          <a
            href= "../../Digital/sunset.jpg"
            class="glightbox"
			data-glightbox="title: City Sunset; description: Digital drawing in Illustrator based on an image of the sunset from my bedroom"
          >
            <img
              src= "../../Digital/sunset.jpg"
              alt="City Sunset"
              class="gallery-img"
          /></a>
        </div>
      </section>
    </section>
	<section id="portfolio" class="portfolio-container section-stop">
      <h1>Design</h1>
      <section class="portfolio-gallery">
        <div class="gallery-item">
          <a
            href= "../../Design/pattern.jpg"
            class="glightbox"
            data-glightbox="title: Shadow; description: Digital drawing with drawing tablet"
          >
            <img
              src= "../../Design/pattern.jpg"
              alt="Pattern"
              class="gallery-img"
          /></a>
        </div>
        <div class="gallery-item">
          <a
            href= "../../Design/book.jpg"
            class="glightbox"
			data-glightbox="title: Leaf Portal; description: Image mashup in photoshop"
          >
            <img
              src= "../../Design/book.jpg"
              alt="Book"
              class="gallery-img"
          /></a>
        </div>
        <div class="gallery-item">
          <a
            href= "../../Design/family.jpg"
            class="glightbox"
			data-glightbox="title: City Sunset; description: Digital drawing in Illustrator based on an image of the sunset from my bedroom"
          >
            <img
              src= "../../Design/family.jpg"
              alt="Family"
              class="gallery-img"
          /></a>
        </div>
      </section>
    </section>
    <!-- End Portfolio-->

    <!-- Begin About -->
    <section id="about" class="about-container section-stop">
      <section class="about-text">
        <h1>About The Artist</h1>
        <p>
          I was raised with creative juices flowing through my veins. My biggest artistic influence 
growing up was my grandmother. She and my dad brought me into the art world and I decided to spread my wings and soar. While I have 
dabbled in many mediums, my favorite is 
photography. This is because of its ability to 
capture emotions and moments in time with such accuracy. I also enjoy the technical aspects of shooting in a studio and setting up lighting. My love of art does not stop there though. 
Experiencing and re-experiencing other forms of art has broadened my interests, and even 
including more traditional mediums. I have found a newfound love for drawing and physical design, which reminds me of a grown-up version of the arts and crafts I would do as a kid. 
        </p>
        <p>
          <a href="mailto:canselm28@gmail.com">Email me</a> canselm28@gmail.com
        </p>
      </section>
      <section class="about-image">
        <img 
          src= "../../my face.jpg"
          alt="Ceanna Anselm Profile Picture"
        />
      </section>
    </section>
    <!-- End About -->

    <!-- Begin Footer -->
    <footer>
      <!-- Begin Footer Nav -->
      <nav class="nav-bar">
        <h1 class="logo"><a href="index.html">Ceanna Anselm</a></h1>
        <ul class="nav-menu">
          <li class="nav-item"><a href="#portfolio">Digital</a></li>
		<li class="nav-item"><a href="#portfolio">Design</a></li>
		<li class="nav-item"><a href="#portfolio">Drawing</a></li>
			<li class="nav-item"><a href="#portfolio">Photography</a></li>
          <li class="nav-item"><a href="#about">About</a></li>
         
        </ul>
      </nav>
      <!-- End Footer Nav -->
      <p class="footer-copyright">Copyright &copy; 2021</p>
    </footer>

    <!-- End Footer -->

    <script>
      window.onscroll = function () {
        scrollFunction();
      };

      function scrollFunction() {
        if (
          document.body.scrollTop > 20 ||
          document.documentElement.scrollTop > 20
        ) {
          document.getElementById("top-nav-bar").style.background = "#000000";
        } else {
          document.getElementById("top-nav-bar").style.background = "none";
        }
      }
    </script>

    <script src="js/glightbox.min.js"></script>
    <script type="text/javascript">
      const lightbox = GLightbox({ loop: true });
    </script>
  </body>
</html>
