<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Mundo Gallo – Premium Live Chickens</title>
<meta name="description" content="Premium farm-raised live chickens. Healthy, clean, and trusted poultry seller." />

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #000;
  color: #fff;
  line-height: 1.6;
}

header {
  background: linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.75)),
    url('./mundo-gallo-cover.png');
  background-size: cover;
  background-position: center;
  padding: 100px 20px;
  text-align: center;
}

header h1 {
  font-size: 3rem;
  color: #d4af37;
  letter-spacing: 3px;
  margin: 0;
}

header p {
  font-size: 1.2rem;
  color: #f5f5f5;
}

section {
  max-width: 1100px;
  margin: auto;
  padding: 60px 20px;
}

h2 {
  color: #d4af37;
  margin-bottom: 20px;
}

.products, .features, .services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: #111;
  border: 1px solid #333;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 6px 20px rgba(212,175,55,0.15);
  transition: transform 0.3s, box-shadow 0.3s;
}

.card:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 30px rgba(212,175,55,0.35);
}

.card h3 {
  color: #d4af37;
  margin-top: 0;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px,1fr));
  gap: 15px;
}

.gallery img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 12px;
  border: 1px solid #333;
}

table {
  width: 100%;
  border-collapse: collapse;
  background: #111;
}

th, td {
  border: 1px solid #333;
  padding: 14px;
}

th {
  background: #d4af37;
  color: #000;
}

.map {
  width: 100%;
  height: 350px;
  border-radius: 12px;
  border: 1px solid #333;
}

.cta {
  background: #111;
  text-align: center;
  padding: 80px 20px;
  border-top: 1px solid #333;
}

.cta a {
  display: inline-block;
  background: #d4af37;
  color: #000;
  padding: 16px 36px;
  border-radius: 10px;
  font-weight: bold;
  text-decoration: none;
  margin: 10px;
  box-shadow: 0 0 20px rgba(212,175,55,0.4);
  transition: 0.3s;
}

.cta a:hover {
  background: #b8962e;
  box-shadow: 0 0 35px rgba(212,175,55,0.8);
}

footer {
  background: #000;
  color: #aaa;
  text-align: center;
  padding: 25px;
  border-top: 1px solid #333;
}

.whatsapp-button {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: #d4af37;
  color: #000;
  padding: 16px 18px;
  border-radius: 50%;
  font-size: 20px;
  box-shadow: 0 6px 25px rgba(212,175,55,0.6);
  text-decoration: none;
  z-index: 1000;
}
</style>
</head>

<body>

<header>
  <h1>MUNDO GALLO</h1>
  <p>Premium Live Chickens • Farm Raised • Trusted Quality</p>
</header>

<section>
  <h2>About Us</h2>
  <p>
    We sell premium-quality live chickens raised with care, hygiene,
    and proper nutrition for homes, farms, and breeders.
  </p>
</section>

<section>
  <h2>Available Chickens</h2>
  <div class="products">
    <div class="card"><h3>Broiler Chickens</h3><p>Healthy and market-ready.</p></div>
    <div class="card"><h3>Local / Desi</h3><p>Naturally raised with strong immunity.</p></div>
    <div class="card"><h3>Chicks</h3><p>Day-old and growing chicks.</p></div>
  </div>
</section>

<section>
  <h2>Gallery</h2>
  <div class="gallery">
    <img src="./chicken1.jpg" alt="Chicken">
    <img src="./farm.jpg" alt="Farm">
    <img src="./market.jpg" alt="Market">
    <img src="./stock.jpg" alt="Stock">
  </div>
</section>

<section>
  <h2>Today’s Prices</h2>
  <table>
    <tr><th>Type</th><th>Price</th></tr>
    <tr><td>Broiler Chicken</td><td>$5 / kg</td></tr>
    <tr><td>Local / Desi</td><td>$8 / kg</td></tr>
    <tr><td>Chicks</td><td>Call for price</td></tr>
  </table>
</section>

<section>
  <h2>Our Location</h2>
  <iframe class="map"
    src="https://www.google.com/maps?q=New+York&output=embed"
    loading="lazy"></iframe>
</section>

<section class="cta">
  <h2>Order on WhatsApp</h2>
  <a href="https://wa.me/123456789?text=Hello%20Mundo%20Gallo,%20I%20would%20like%20to%20order%20live%20chickens."
     target="_blank">
    💬 WhatsApp Order
  </a>
</section>

<footer>
  <p>© 2026 Mundo Gallo. All Rights Reserved.</p>
</footer>

<a class="whatsapp-button"
   href="https://wa.me/123456789?text=Hello%20Mundo%20Gallo,%20I%20want%20to%20order%20live%20chickens."
   target="_blank">💬</a>

</body>
</html>
