<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Terzo Boutique</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f5f5f5; }
    header { background:#222; color:white; padding:20px; text-align:center; }
    header h1 { margin:0; }
    header p { margin:5px 0 0 0; }
    nav { background:#333; overflow:hidden; }
    nav a { float:left; color:white; padding:14px 20px; text-decoration:none; }
    nav a:hover { background:#575757; }
    section { padding:20px; }
    .products { display:flex; flex-wrap:wrap; justify-content:center; }
    .product { background:white; width:220px; margin:10px; padding:10px; text-align:center; border-radius:5px; box-shadow:0 0 5px rgba(0,0,0,0.1); }
    .product img { width:200px; height:auto; border-radius:5px; }
    .product button { background:#222; color:white; border:none; padding:10px 20px; cursor:pointer; border-radius:5px; margin-top:10px; }
    .product button:hover { background:#575757; }
    .gallery img { width:200px; margin:10px; border-radius:5px; }
    form input, form textarea { width:100%; padding:10px; margin-bottom:10px; border:1px solid #ccc; border-radius:5px; }
    form button { background:#222; color:white; border:none; padding:10px 20px; cursor:pointer; border-radius:5px; }
    form button:hover { background:#575757; }
    footer { background:#222; color:white; text-align:center; padding:10px; }
    .contact-icons a { margin-right:10px; color:white; text-decoration:none; font-weight:bold; }
    @media(max-width:600px) {
      .products { flex-direction:column; align-items:center; }
      nav a { float:none; display:block; text-align:center; }
    }
  </style>
</head>
<body>

<header>
  <h1>Terzo Boutique</h1>
  <p>High-quality clothing boutique – Minimum order €20</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About Us</a>
  <a href="#products">Products</a>
  <a href="#gallery">Gallery</a>
  <a href="#testimonials">Testimonials</a>
  <a href="#contact">Contact</a>
</nav>

<section id="home">
  <h2>Welcome!</h2>
  <p>Discover our latest collections and stylish pieces for every woman.</p>
</section>

<section id="about">
  <h2>About Us</h2>
  <p>We are a boutique offering high-quality clothing. All products are carefully selected for style and comfort.</p>
</section>

<section id="products">
  <h2>Products</h2>
  <div class="products">
    <div class="product">
      <img src="product1.jpg" alt="Product 1">
      <h3>Clothing 1</h3>
      <p>Material: Cotton</p>
      <p>Price: €25</p>
      <button onclick="window.location.href='https://wa.me/35795650750'">Order via WhatsApp</button>
    </div>
    <div class="product">
      <img src="product2.jpg" alt="Product 2">
      <h3>Clothing 2</h3>
      <p>Material: Polyester</p>
      <p>Price: €30</p>
      <button onclick="window.location.href='https://wa.me/35795650750'">Order via WhatsApp</button>
    </div>
    <!-- Add more products here -->
  </div>
</section>

<section id="gallery">
  <h2>Gallery</h2>
  <div class="gallery">
    <img src="gallery1.jpg" alt="Gallery 1">
    <img src="gallery2.jpg" alt="Gallery 2">
    <!-- Add more gallery images here -->
  </div>
</section>

<section id="testimonials">
  <h2>Testimonials</h2>
  <p>"Amazing products and fast service!" – Maria</p>
  <p>"Very happy with the quality of the clothes." – Elena</p>
  <!-- Add more testimonials here -->
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Address: Larnaca, Cyprus</p>
  <p>Phone / WhatsApp: +35795650750</p>
  <p>Instagram: <a href="https://www.instagram.com/terzoboutique_lca/" target="_blank">@terzoboutique_lca</a></p>
  <form>
    <input type="text" placeholder="Name" required>
    <input type="email" placeholder="Email" required>
    <textarea placeholder="Message" required></textarea>
    <button type="submit">Send</button>
  </form>
</section>

<footer>
  <p>© 2025 Terzo Boutique. All rights reserved.</p>
</footer>

</body>
</html>