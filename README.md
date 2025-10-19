<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>GreenGrow Seeds</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f8f5;
      color: #333;
    }

    header {
      background-color: #4CAF50;
      padding: 20px;
      text-align: center;
      color: white;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: #388E3C;
    }

    nav a {
      padding: 14px 20px;
      display: inline-block;
      color: white;
      text-decoration: none;
    }

    nav a:hover {
      background-color: #2E7D32;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6') no-repeat center center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px #000;
    }

    .hero h1 {
      font-size: 3em;
    }

    .section {
      padding: 40px 20px;
      text-align: center;
    }

    .products {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
    }

    .product {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      width: 250px;
      padding: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 5px;
    }

    footer {
      background-color: #2E7D32;
      color: white;
      text-align: center;
      padding: 20px;
    }

    @media (max-width: 600px) {
      .products {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>GreenGrow Seeds</h1>
    <p>Your trusted source for quality seeds</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#seeds">Seeds</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    <h1>Grow Green, Live Clean</h1>
  </section>

  <section class="section" id="seeds">
    <h2>Our Best-Selling Seeds</h2>
    <div class="products">
      <div class="product">
        <img src="https://source.unsplash.com/250x150/?tomato,seeds" alt="Tomato Seeds">
        <h3>Tomato Seeds</h3>
        <p>Rich in flavor and easy to grow.</p>
        <p><strong.99 / pack</strong></p>
      </div>
      <div class="product">
        <img src="https://source.unsplash.com/250x150/?lettuce,seeds" alt="Lettuce Seeds">
        <h3>Lettuce Seeds</h3>
        <p>Crisp and fresh leaves all season.</p>
        <p><strong>$1.99 / pack</strong></p>
      </div>
      <div class="product">
        <img src="https://source.unsplash.com/250x150/?sunflower,seeds" alt="Sunflower Seeds">
        <h3>Sunflower Seeds</h3>
        <p>Brighten your garden with sunflowers.</p>
        <p><strong>$3.49 / pack</strong></p>
      </div>
    </div>
  </section>

  <section class="section" id="about">
    <h2>About Us</h2>
    <p>GreenGrow Seeds is a family-owned business dedicated to providing high-quality, non-GMO seeds to home gardeners and small farms. We believe in sustainability, biodiversity, and growing your own healthy food.</p>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Email: support@greengrowseeds.com</p>
    <p>Phone: (+91)8822371184</p>
    <p>Location: ASSAM,MORANHAT,RANGOLI,PIN-785670</p>
  </section>

  <footer>
    <p>&copy; 2025 GreenGrow Seeds. All rights reserved.</p>
  </footer>

</body>
</html>
