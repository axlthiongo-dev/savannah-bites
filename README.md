<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Savannah Bites Nairobi</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f8f8f8;
}

header {
  background: #222;
  color: white;
  padding: 15px;
  text-align: center;
}

.hero {
  background: url('https://images.unsplash.com/photo-1504674900247-0877df9cc836') center/cover;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 40px;
}

.hero button {
  padding: 12px 20px;
  border: none;
  background: #ff6600;
  color: white;
  font-size: 16px;
  cursor: pointer;
}

.section {
  padding: 40px 20px;
  text-align: center;
}

.menu {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.card {
  background: white;
  margin: 10px;
  padding: 20px;
  width: 250px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.card img {
  width: 100%;
}

footer {
  background: #222;
  color: white;
  text-align: center;
  padding: 20px;
}
</style>

</head>

<body>

<header>
  <h2>Savannah Bites</h2>
</header>

<section class="hero">
  <h1>Delicious Meals Delivered Fast</h1>
  <p>Kenyan & Continental Cuisine in Nairobi</p>
  <button onclick="window.location.href='https://wa.me/254700000000'">
    Order on WhatsApp
  </button>
</section>

<section class="section">
  <h2>Our Menu</h2>
  <div class="menu">
    
    <div class="card">
      <img src="https://images.unsplash.com/photo-1604908176997-431b1d6a5f68">
      <h3>Nyama Choma</h3>
      <p>KES 1200</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092">
      <h3>Chicken Pilau</h3>
      <p>KES 800</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
      <h3>Burger & Fries</h3>
      <p>KES 700</p>
    </div>

  </div>
</section>

<section class="section">
  <h2>Why Choose Us</h2>
  <p>Fresh ingredients, fast delivery, and great taste!</p>
</section>

<section class="section">
  <h2>Contact Us</h2>
  <p>📍 Nairobi, Kenya</p>
  <p>📞 0700 000000</p>
</section>

<footer>
  <p>© 2026 Savannah Bites Nairobi</p>
</footer>

</body>
</html>
