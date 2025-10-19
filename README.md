<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GreenGrow Seed Shop</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>
  <header>
    <h1>🌱 GreenGrow Seed Shop</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Shop</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Cart (<span id="cart-count">0</span>)</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>Our Bestselling Seeds</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://via.placeholder.com/150" alt="Tomato Seeds">
        <h3>Tomato Seeds</h3>
        <p>$2.99</p>
        <button onclick="addToCart()">Add to Cart</button>
      </div>


  </main>

  <footer>
    <p>&copy; 2025 GreenGrow Seed Shop. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

