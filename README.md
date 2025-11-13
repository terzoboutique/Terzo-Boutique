<!DOCTYPE html>
<html lang="bg">
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
    .product img { width:200px; height: auto; border-radius:5px; }
    .product button { background:#222; color:white; border:none; padding:10px 20px; cursor:pointer; border-radius:5px; margin-top:10px; }
    .product button:hover { background:#575757; }
    .gallery img { width:200px; margin:10px; border-radius:5px; }
    form input, form textarea { width:100%; padding:10px; margin-bottom:10px; border:1px solid #ccc; border-radius:5px; }
    form button { background:#222; color:white; border:none; padding:10px 20px; cursor:pointer; border-radius:5px; }
    form button:hover { background:#575757; }
    footer { background:#222; color:white; text-align:center; padding:10px; }
    @media(max-width:600px) {
      .products { flex-direction:column; align-items:center; }
      nav a { float:none; display:block; text-align:center; }
    }
  </style>
</head>
<body>

<header>
  <h1>Terzo Boutique</h1>
  <p>Модни дрехи и аксесоари в Ларнака – минимална поръчка 20€</p>
</header>

<nav>
  <a href="#home">Начало</a>
  <a href="#about">За нас</a>
  <a href="#products">Продукти</a>
  <a href="#gallery">Галерия</a>
  <a href="#testimonials">Отзиви</a>
  <a href="#contact">Контакти</a>
</nav>

<section id="home">
  <h2>Добре дошли!</h2>
  <p>Разгледайте нашите най-нови колекции и стилни предложения за всяка жена.</p>
</section>

<section id="about">
  <h2>За нас</h2>
  <p>Terzo Boutique предлага качествени дрехи и аксесоари за съвременната жена. Всички продукти са внимателно подбрани за стил и удобство.</p>
</section>

<section id="products">
  <h2>Продукти</h2>
  <div class="products">
    <div class="product">
      <img src="product1.jpg" alt="Дреха 1">
      <h3>Дреха 1</h3>
      <p>Материал: Памук</p>
      <p>Цена: 25€</p>
      <button>Купи сега</button>
    </div>
    <div class="product">
      <img src="product2.jpg" alt="Дреха 2">
      <h3>Дреха 2</h3>
      <p>Материал: Полиестер</p>
      <p>Цена: 30€</p>
      <button>Купи сега</button>
    </div>
    <!-- Добави още продукти тук -->
  </div>
</section>

<section id="gallery">
  <h2>Галерия</h2>
  <div class="gallery">
    <img src="gallery1.jpg" alt="Галерия 1">
    <img src="gallery2.jpg" alt="Галерия 2">
    <!-- Добави още снимки тук -->
  </div>
</section>

<section id="testimonials">
  <h2>Отзиви</h2>
  <p>„Страхотни продукти и бързо обслужване!“ – Мария</p>
  <p>„Много съм доволна от качеството на дрехите.“ – Елена</p>
  <!-- Добави още отзиви тук -->
</section>

<section id="contact">
  <h2>Контакти</h2>
  <p>Адрес: Ларнака, Кипър</p>
  <p>Телефон / WhatsApp: +357 XXX XXX XXX</p>
  <p>Email: info@terzoboutique.com</p>
  <form>
    <input type="text" placeholder="Име" required>
    <input type="email" placeholder="Email" required>
    <textarea placeholder="Съобщение" required></textarea>
    <button type="submit">Изпрати</button>
  </form>
</section>

<footer>
  <p>© 2025 Terzo Boutique. Всички права запазени.</p>
</footer>

</body>
</html>
