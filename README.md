# <!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
</body>
  <title>FineCrafts</title>
  <style>
    /* Add your custom CSS styles here */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
	
     header {
            height: 300px;
            background: url('vc.jpg') no-repeat center center;
            background-size: cover;
            filter: brightness(1.1) contrast(1.2) saturate(1.2);
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative; 
        }

        .logo {
            position: absolute; 
            top: 50%; 
            left: 50%; 
            transform: translate(-50%, -50%);
            width: 100px; 
            height: 100px;
            background-color: blue; 
            border-radius: 50%; 
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            font-size: 16px;
            text-transform: uppercase;
            font-weight: bold;
        }

        h1 {
            color: #fff;
            font-size: 36px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            margin-top: 20px; 
        }

        .section {
            padding: 40px 20px;
            text-align: center;
        }

        .section h2 {
            font-size: 24px;
            margin-bottom: 20px;
        }

        .section p {
            font-size: 16px;
            line-height: 1.6;
        }
		
    h1 {
      margin: 0;
    }

    section {
      padding: 50px 20px;
      text-align: center;
    }

    .section-title {
      font-size: 24px;
      margin-bottom: 20px;
      color: #000080;
    }

    .section-content {
      max-width: 800px;
      margin: 0 auto;
    }

    .testimonial {
      margin-bottom: 30px;
    }

    .testimonial-text {
      font-style: italic;
      color: #555;
      margin-bottom: 10px;
    }

    .testimonial-author {
      font-weight: bold;
      color: #333;
    }

    .benefit {
      display: inline-block;
      margin: 20px;
      width: 200px;
      text-align: center;
    }

    .benefit-icon {
      font-size: 40px;
      margin-bottom: 10px;
      color: #333;
    }

    .benefit-title {
      font-weight: bold;
      margin-bottom: 10px;
      color: #333;
    }

    .feature {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-bottom: 30px;
    }

    .feature-icon {
      font-size: 40px;
      margin-right: 20px;
      color: #333;
    }

    .feature-text {
      font-size: 16px;
      color: #555;
    }

    .cta {
      margin-top: 40px;
    }

    .cta-text {
      font-size: 18px;
      margin-bottom: 20px;
      color: #333;
    }

    .cta-button {
      padding: 10px 20px;
      background-color: #333;
      color: #fff;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    footer {
      background-color: #333;
      color: ##000080;
      padding: 20px;
      text-align: center;
    }
	h2 {
      margin: 0;
    }

    .gallery-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }

    .gallery-item {
      width: 300px;
      height: 200px;
      overflow: hidden;
      border-radius: 5px;
      position: relative;
    }

    .gallery-item img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.3s ease;
    }

    .gallery-item:hover img {
      transform: scale(1.1);
    }

    .gallery-item-overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.7);
      opacity: 0;
      transition: opacity 0.3s ease;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }

    .gallery-item:hover .gallery-item-overlay {
      opacity: 1;
    }

    .gallery-item-text {
      color: #fff;
      text-align: center;
    }
	
	 .search-icon {
            font-size: 20px;
            color: #555;
            cursor: pointer;
            margin-right: 10px;
        }

        .library-link,
        .signin-link,
        .account-link {
            text-decoration: none;
            color: #000000;
            margin-left: 10px;
        }

        .library-link:hover,
        .signin-link:hover,
        .account-link:hover {
            color: #000;
  

    footer {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
	  }	  
      
	
  </style>
</head>
<body>
  <header>
  <div class="logo"></div>
        <h1>Welcome to My Website</h1>
    </header>

  <section id="value-prop">
    <div class="section-content">
      <h2 class="section-title">Discover the Beauty of Art</h2>
      <p> Experience the rich tapestry of artistic expression as our gallery celebrates a diverse range of styles, mediums, and artistic philosophies. From classic masterpieces to contemporary innovations, we showcase art that speaks to every soul.</p>
    </div>
  </section>

  <section id="social-proof">
    <div class="section-content">
      <h2 class="section-title">What Our Visitors Say</h2>
      <div class="testimonial">
        <p class="testimonial-text">"The art collection here is absolutely captivating. Each piece tells a unique story."</p>
        <p class="testimonial-author">- John Doe</p>
      </div>
      <div class="testimonial">
        <p class="testimonial-text">"The gallery offers a mesmerizing experience. I am always inspired by the exceptional artworks on display."</p>
        <p class="testimonial-author">- Jane Smith</p>
      </div>
    </div>
  </section>

 <div class="gallery-container">
    <div class="gallery-item">
      <img src="hh.jpg" alt="Image 1">
      <div class="gallery-item-overlay">
        <div class="gallery-item-text">
          <h2> Find</h2>
          <p>ART</p>
        </div>
      </div>
    </div>

    <div class="gallery-item">
      <img src="nb.jpg" alt="Image 2">
      <div class="gallery-item-overlay">
        <div class="gallery-item-text">
          <h2>Image 2</h2>
          <p>Description of Image 2</p>
        </div>
      </div>
    </div>

    <div class="gallery-item">
      <img src="sh.jpg" alt="Image 3">
      <div class="gallery-item-overlay">
        <div class="gallery-item-text">
          <h2>Image 3</h2>
          <p>Description of Image 3</p>
        </div>
      </div>
    </div>
  <section id="benefits">
    <div class="section-content">
      <h2 class="section-title">Benefits of Visiting Our Gallery</h2>
      <div class="benefit">
        <span class="benefit-icon">🎨</span>
        <h3 class="benefit-title">Diverse Art Collection</h3>
        <p>Explore a wide range of artistic styles and mediums.</p>
      </div>
      <div class="benefit">
        <span class="benefit-icon">🌟</span>
        <h3 class="benefit-title">Exquisite Masterpieces</h3>
        <p>View exceptional artworks created by renowned artists.</p>
      </div>
      <div class="benefit">
        <span class="benefit-icon">🎭</span>
        <h3 class="benefit-title">Immersive Experience</h3>
        <p>Step into a captivating world of art and culture.</p>
      </div>
    </div>
  </section>

  <section id="features">
    <div class="section-content">
      <h2 class="section-title">Key Features of Our Gallery</h2>
      <div class="feature">
        <span class="feature-icon">🎟️</span>
        <p class="feature-text">Regular exhibitions showcasing new and emerging artists.</p>
      </div>
      <div class="feature">
        <span class="feature-icon">📸</span>
        <p class="feature-text">Photography exhibits capturing breathtaking moments and scenes.</p>
      </div>
      <div class="feature">
        <span class="feature-icon">🖼️</span>
        <p class="feature-text">Permanent collection of iconic and timeless art pieces.</p>
      </div>
    </div>
  </section>

  <section id="cta">
    <div class="section-content cta">
      <h2 class="section-title">Visit Our Gallery Today!</h2>
      <p class="cta-text">Experience the beauty and creativity of art firsthand.</p>
      <a href="#" class="cta-button">Plan Your Visit</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2023 Art Gallery. All rights reserved.</p>
  </footer>
</body>
</html>
