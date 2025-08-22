<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mahak Farm Agro</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #2e7d32;
      color: white;
      text-align: center;
      padding: 20px;
    }
    header h1 {
      margin: 0;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url("https://images.unsplash.com/photo-1506806732259-39c2d0268443?auto=format&fit=crop&w=1350&q=80") no-repeat center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      font-weight: bold;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.6);
    }
    section {
      padding: 40px 20px;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      padding: 20px;
      width: 250px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    .card img {
      max-width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #2e7d32;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mahak Farm Agro</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    Healthy Snacks & Organic Products
  </div>

  <section id="about">
    <h2>About Us</h2>
    <p>At Mahak Farm Agro, we bring you the purity of village farms and the goodness of healthy, organic products. Our mission is to make every home healthier with natural and traditional foods.</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1603048297172-c92544798a41?auto=format&fit=crop&w=500&q=80" alt="Desi Ghee">
        <h3>Desi Ghee</h3>
        <p>Pure, traditional, and made with love.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1606788075761-40d33d5a49c3?auto=format&fit=crop&w=500&q=80" alt="Almonds">
        <h3>Almonds</h3>
        <p>Rich in nutrition, handpicked for quality.</p>
      </div>
      <div class="card">
        <img src="https://images.unsplash.com/photo-1587049352846-4a3290d1c93f?auto=format&fit=crop&w=500&q=80" alt="Raisins">
        <h3>Raisins</h3>
        <p>Sweet, healthy, and naturally dried.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>📞 +91 9634331101</p>
    <p>📧 info@mahakfarmagro.com</p>
  </section>

  <footer>
    <p>© 2025 Mahak Farm Agro. All rights reserved.</p>
  </footer>
</body>
</html>
