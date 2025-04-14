# streettowear.com
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>StreetVibe Clothing</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">StreetVibe</div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Shop</a></li>
        <li><a href="#">Über uns</a></li>
        <li><a href="#">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Urban Style. Echtes Statement.</h1>
    <p>Entdecke exklusive Streetwear für deinen Vibe.</p>
    <a href="#" class="cta-btn">Jetzt shoppen</a>
  </section>

  <section class="products">
    <h2>Unsere Favoriten</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="shirt.jpg" alt="Streetwear Shirt">
        <h3>Oversized Tee</h3>
        <p>€39,99</p>
      </div>
      <div class="product-card">
        <img src="hoodie.jpg" alt="Streetwear Hoodie">
        <h3>Signature Hoodie</h3>
        <p>€69,99</p>
      </div>
      <!-- Weitere Produkte hier -->
    </div>
  </section>

  <footer>
    <p>&copy; 2025 StreetVibe. Alle Rechte vorbehalten.</p>
  </footer>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Helvetica Neue', sans-serif;
}

body {
  background: #111;
  color: #fff;
  line-height: 1.6;
}

header {
  display: flex;
  justify-content: space-between;
  padding: 20px 40px;
  background: #000;
}

.logo {
  font-size: 1.8rem;
  font-weight: bold;
  letter-spacing: 2px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #f5c518;
}

.hero {
  background: url('streetwear-banner.jpg') no-repeat center center/cover;
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 3rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.cta-btn {
  padding: 10px 25px;
  background: #f5c518;
  color: #000;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.products {
  padding: 60px 40px;
  background: #1a1a1a;
}

.products h2 {
  text-align: center;
  margin-bottom: 40px;
}

.product-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.product-card {
  background: #222;
  padding: 20px;
  text-align: center;
  border-radius: 10px;
  transition: transform 0.3s;
}

.product-card:hover {
  transform: scale(1.05);
}

.product-card img {
  max-width: 100%;
  border-radius: 8px;
  margin-bottom: 15px;
}

footer {
  background: #000;
  text-align: center;
  padding: 20px;
  font-size: 0.9rem;
}
