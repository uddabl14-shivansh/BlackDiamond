# BlackDiamond<!DOCTYPE html>
<html lang="ne">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>BlackDiamond Auto Parts | Helmets, Stickers, Accessories</title>
  <meta name="description" content="BlackDiamond Auto Parts – Helmets, Stickers, Bike Accessories, Seat Covers in Dhadingbesi" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root { --bg:#0f172a; --card:#111827; --text:#e5e7eb; --muted:#9ca3af; --accent:#f97316; --accent-2:#ef4444; }
    *{box-sizing:border-box}
    body{
      margin:0; font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial,sans-serif;
      color:var(--text); background:linear-gradient(180deg,#0b1023 0%,#0f172a 40%,#0b1023 100%);
    }
    a{color:inherit; text-decoration:none}
    .container{max-width:1100px; margin:0 auto; padding:0 20px}
    header{position:sticky; top:0; backdrop-filter:saturate(180%) blur(10px); background:rgba(15,23,42,.6); border-bottom:1px solid rgba(255,255,255,.08); z-index:40}
    .nav{display:flex; align-items:center; justify-content:space-between; padding:14px 0}
    .brand{display:flex; gap:10px; align-items:center; font-weight:800; letter-spacing:.3px}
    .logo{width:36px; height:36px; border-radius:10px; background:linear-gradient(135deg,var(--accent),var(--accent-2)); display:grid; place-items:center; color:#0b1023; font-weight:800}
    .cta{display:flex; gap:10px; align-items:center}
    .btn{padding:10px 14px; border-radius:12px; border:1px solid rgba(255,255,255,.12); background:#0b1226; color:var(--text)}
    .btn-primary{background:linear-gradient(135deg,var(--accent),#ea580c); border:none; color:#fff; font-weight:700}
    .hero{padding:52px 0 28px; text-align:center}
    .hero h1{font-size: clamp(28px, 3.6vw, 44px); line-height:1.05; margin:0 0 10px; font-weight:800}
    .hero p{color:var(--muted); font-size:clamp(14px,1.8vw,18px); margin:0 auto 18px; max-width:720px}
    .badges{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0 0}
    .badge{font-size:12px; padding:7px 10px; border-radius:999px; border:1px solid rgba(255,255,255,.12); background:rgba(255,255,255,.04)}

    .section{padding:30px 0}
    .card{background:linear-gradient(180deg,rgba(255,255,255,.06),rgba(255,255,255,.02)); border:1px solid rgba(255,255,255,.1); border-radius:18px; box-shadow:0 10px 30px rgba(0,0,0,.25)}

    .grid{display:grid; gap:14px; grid-template-columns:repeat(12,1fr)}
    .product{grid-column:span 6; padding:12px}
    @media(min-width:800px){ .product{grid-column:span 3} }
    .p-img{aspect-ratio:1/1; border-radius:14px; background:#0b1226; border:1px solid rgba(255,255,255,.08); display:grid; place-items:center; font-size:28px; color:var(--muted)}
    .p-meta{padding:10px 6px 0}
    .p-title{font-weight:700}
    .p-price{color:#fdba74; font-weight:800}

    .about{display:grid; gap:18px; grid-template-columns:1fr; align-items:center}
    @media(min-width:900px){ .about{grid-template-columns:1.2fr .8fr} }
    .about .illustration{min-height:280px; border-radius:18px; background:radial-gradient(1200px 600px at -10% -40%, rgba(239,68,68,.2), transparent 60%), linear-gradient(180deg, rgba(249,115,22,.12), rgba(0,0,0,0)); border:1px solid rgba(255,255,255,.08)}

    .contact{display:grid; gap:14px; grid-template-columns:1fr}
    @media(min-width:800px){ .contact{grid-template-columns:1.1fr .9fr} }
    form{display:grid; gap:10px}
    input, textarea{width:100%; padding:12px 14px; border-radius:12px; border:1px solid rgba(255,255,255,.14); background:#0b1226; color:var(--text)}
    textarea{min-height:120px}
    .whatsapp{display:inline-block; margin-top:6px; font-weight:700}

    footer{padding:26px 0 50px; color:var(--muted); text-align:center}
    .pill{display:inline-flex; gap:8px; align-items:center; padding:6px 10px; border-radius:999px; background:rgba(255,255,255,.06); border:1px solid rgba(255,255,255,.12)}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand"><div class="logo">BD</div> BlackDiamond Auto Parts</div>
      <div class="cta">
        <a href="#products" class="btn">Products</a>
        <a href="#contact" class="btn btn-primary">Order Now</a>
      </div>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="badges">
        <span class="badge">Helmets • Stickers • Accessories</span>
        <span class="badge">Quality Bike Parts</span>
      </div>
      <h1>BlackDiamond Auto Parts – Helmets, Stickers, Bike Accessories & Seat Covers</h1>
      <p>धादिङबेसी, नीलकण्ठ-३, सुगमटोलमा अवस्थित हाम्रो पसलमा मोटरसाइकल तथा स्कुटरका लागि Helmets, Stickers, Seat Covers र विभिन्न Bike Accessories उपलब्ध छन्। उत्तम गुणस्तर र उचित मूल्य हाम्रो प्रतिबद्धता हो।</p>
      <a href="#products" class="btn btn-primary">नवीनतम सामानहरू हेर्नुहोस्</a>
    </section>

    <section id="products" class="section">
      <h2 style="margin:0 0 12px; font-size:24px; font-weight:800">Featured Products</h2>
      <div class="grid">
        <div class="product card">
          <div class="p-img">🪖</div>
          <div class="p-meta">
            <div class="p-title">Helmets</div>
            <div class="p-price">Starting Rs. 1,500</div>
            <div class="p-desc" style="color:var(--muted)">सुरक्षित र स्टाइलिश हेल्मेटहरू।</div>
          </div>
        </div>
        <div class="product card">
          <div class="p-img">🏍️</div>
          <div class="p-meta">
            <div class="p-title">Bike Accessories</div>
            <div class="p-price">From Rs. 299</div>
            <div class="p-desc" style="color:var(--muted)">स्टिकरदेखि लाइट र मोबाइल होल्डर सम्म।</div>
          </div>
        </div>
        <div class="product card">
          <div class="p-img">🪑</div>
          <div class="p-meta">
            <div class="p-title">Seat Covers</div>
            <div class="p-price">From Rs. 499</div>
            <div class="p-desc" style="color:var(--muted)">आरामदायी र टिकाउ सिट कभर।</div>
          </div>
        </div>
        <div class="product card">
          <div class="p-img">✨</div>
          <div class="p-meta">
            <div class="p-title">Stickers</div>
            <div class="p-price">From Rs. 99</div>
            <div class="p-desc" style="color:var(--muted)">स्टाइल दिनका लागि विभिन्न डिजाइन।</div>
          </div>
        </div>
      </div>
    </section>

    <section class="section about">
      <div>
        <h2 style="margin:0 0 10px; font-size:24px; font-weight:800">हाम्रो बारे</h2>
        <p style="color:var(--muted)">BlackDiamond Auto Parts, धादिङबेसी – नीलकण्ठ-३, सुगमटोलमा अवस्थित छ। हामी Helmets, Stickers, Bike Accessories र Seat Covers मा विशेषज्ञ छौं। हाम्रो लक्ष्य: सुरक्षित र स्टाइलिश यात्राका लागि उत्कृष्ट Bike Parts उपलब्ध गराउनु।</p>
        <div class="pill" style="margin-top:8px">📍 धादिङबेसी, नीलकण्ठ-३, सुगमटोल</div>
        <div class="pill" style="margin-top:8px">📞 सम्पर्क: 9841975497</div>
      </div>
      <div class="illustration card"></div>
    </section>

    <section id="contact" class="section contact">
      <div class="card" style="padding:16px">
        <h2 style="margin:0 0 10px; font-size:24px; font-weight:800">सम्पर्क र अर्डर</h2>
        <form onsubmit="event.preventDefault(); window.open('https://wa.me/9779841975497?text='+encodeURIComponent('Namaste, malaī BlackDiamond Auto Parts बाट सामान चाहियो: '), '_blank');">
          <input placeholder="तपाईंको नाम" required>
          <input placeholder="फोन नम्बर" required>
          <textarea placeholder="अर्डर/सन्देश"></textarea>
          <button class="btn btn-primary" type="submit">WhatsApp मार्फत अर्डर पठाउनुहोस्</button>
          <a class="whatsapp" href="https://wa.me/9779841975497" target="_blank">वा सीधै WhatsApp मा सन्देश पठाउनुहोस्</a>
        </form>
      </div>
      <div class="card" style="padding:16px">
        <h3 style="margin:0 0 10px; font-size:18px; font-weight:800">नक्सा</h3>
        <div style="aspect-ratio:16/9; border-radius:12px; overflow:hidden; border:1px solid rgba(255,255,255,.12)">
          <iframe title="Map" src="https://www.openstreetmap.org/export/embed.html?bbox=85.304%2C27.707%2C85.322%2C27.718&layer=mapnik" style="width:100%; height:100%; border:0"></iframe>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <div>© <span id="y"></span> BlackDiamond Auto Parts • सबै अधिकार सुरक्षित</div>
    </div>
  </footer>

  <script>document.getElementById('y').textContent = new Date().getFullYear()</script>
</body>
</html>
