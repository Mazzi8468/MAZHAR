<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rosa Amore | Italian-Inspired Women’s Fashion</title>
  <meta name="description" content="Rosa Amore – Italian-inspired women’s fashion. Elegant dresses with premium quality. Cash on Delivery available across Pakistan." />
  <style>
    :root {
      --rose:#d88aa3;
      --cream:#fff7f9;
      --gold:#c9a24d;
      --dark:#2b2b2b;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;color:var(--dark);background:var(--cream);}
    a{text-decoration:none;color:inherit}
    header{background:#fff;padding:20px 6%;display:flex;align-items:center;justify-content:space-between;box-shadow:0 6px 20px rgba(0,0,0,.05)}
    .logo{font-size:28px;font-weight:600;letter-spacing:1px}
    .logo span{color:var(--rose)}
    nav a{margin-left:22px;font-weight:500}
    .btn{background:var(--rose);color:#fff;padding:12px 18px;border-radius:30px;display:inline-block}
    .hero{padding:90px 6%;display:grid;grid-template-columns:1.1fr .9fr;gap:40px;align-items:center}
    .hero h1{font-size:48px;line-height:1.1}
    .hero h1 span{color:var(--rose)}
    .hero p{margin:18px 0 28px;font-size:18px;max-width:520px}
    .hero-card{background:#fff;border-radius:24px;padding:30px;box-shadow:0 10px 30px rgba(0,0,0,.08)}
    .badge{display:inline-block;background:rgba(216,138,163,.12);color:var(--rose);padding:6px 12px;border-radius:20px;margin-bottom:12px}
    section{padding:70px 6%}
    .section-title{text-align:center;margin-bottom:40px}
    .section-title h2{font-size:36px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:26px}
    .card{background:#fff;border-radius:22px;padding:26px;box-shadow:0 10px 26px rgba(0,0,0,.07)}
    .card h3{margin:10px 0}
    .price{color:var(--rose);font-weight:700}
    .why li{margin:10px 0}
    footer{background:#fff;padding:30px 6%;display:grid;grid-template-columns:1.2fr .8fr .8fr;gap:20px}
    footer h4{margin-bottom:10px}
    .copy{grid-column:1/-1;text-align:center;margin-top:10px;font-size:14px;color:#666}
    @media(max-width:900px){.hero{grid-template-columns:1fr}.hero h1{font-size:38px}footer{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="logo">Rosa <span>Amore</span></div>
    <nav>
      <a href="#home">Home</a>
      <a href="#collection">Collection</a>
      <a href="#about">About</a>
      <a href="#contact" class="btn">Order Now</a>
    </nav>
  </header>

  <main id="home">
    <section class="hero">
      <div>
        <span class="badge">Italian-Inspired Women’s Fashion</span>
        <h1>Elegant Dresses<br/>Made with <span>Love</span></h1>
        <p>Discover timeless style with Rosa Amore. Premium quality dresses designed for confidence, comfort, and everyday elegance.</p>
        <a class="btn" href="#contact">Shop on WhatsApp</a>
      </div>
      <div class="hero-card">
        <h3>Why Rosa Amore?</h3>
        <ul class="why">
          <li>🌹 Premium fabrics & flattering fits</li>
          <li>🇮🇹 Italian-inspired designs</li>
          <li>🚚 Cash on Delivery across Pakistan</li>
          <li>📦 Fast nationwide delivery</li>
        </ul>
      </div>
    </section>

    <section id="collection">
      <div class="section-title">
        <h2>Featured Collection</h2>
        <p>Handpicked styles for every mood</p>
      </div>
      <div class="grid">
        <div class="card">
          <h3>Floral Elegance</h3>
          <p>Soft tones, premium finish</p>
          <p class="price">PKR 2,999</p>
        </div>
        <div class="card">
          <h3>Classic Black</h3>
          <p>Timeless & graceful</p>
          <p class="price">PKR 3,299</p>
        </div>
        <div class="card">
          <h3>Rose Chic</h3>
          <p>Modern Italian vibe</p>
          <p class="price">PKR 3,499</p>
        </div>
      </div>
    </section>

    <section id="about">
      <div class="section-title">
        <h2>About Rosa Amore</h2>
      </div>
      <div class="grid">
        <div class="card">
          <p>Rosa Amore is a women’s fashion brand inspired by Italian elegance and timeless beauty. We bring modern trends with classic charm—designed to make you feel confident and graceful every day.</p>
        </div>
        <div class="card">
          <p>Our focus is quality, comfort, and affordability. From casual wear to special occasions, every piece is selected with care and attention to detail.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="section-title">
        <h2>Order Now</h2>
        <p>Fast & easy ordering via WhatsApp</p>
      </div>
      <div class="grid">
        <div class="card">
          <h3>How to Order</h3>
          <ol>
            <li>Send dress screenshot/code</li>
            <li>Share size & city</li>
            <li>Confirm address & phone</li>
          </ol>
        </div>
        <div class="card">
          <h3>Contact</h3>
          <p>📲 WhatsApp: <strong>+92-XXXXXXXXXX</strong></p>
          <p>🚚 Cash on Delivery Available</p>
          <a class="btn" href="https://wa.me/92XXXXXXXXXX" target="_blank">Chat on WhatsApp</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div>
      <h4>Rosa Amore</h4>
      <p>Italian Style. Made with Love.</p>
    </div>
    <div>
      <h4>Quick Links</h4>
      <p><a href="#collection">Collection</a></p>
      <p><a href="#about">About</a></p>
    </div>
    <div>
      <h4>Support</h4>
      <p>COD & Returns</p>
      <p>Delivery Info</p>
    </div>
    <div class="copy">© 2026 Rosa Amore. All rights reserved.</div>
  </footer>
</body>
</html>
