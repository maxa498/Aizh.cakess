<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aizh.cakes</title>
  <meta name="description" content="Домашняя выпечка: самса, пироги, десерты и торты на заказ в Уральске.">
  <link rel="icon" href="favicon.ico">
  <style>
    body { margin:0; font-family: Arial, sans-serif; background:#fff7f0; color:#3a2e2a; }
    header { background:#f59e0b; padding:20px; text-align:center; color:#fff; }
    nav a { color:#fff; margin:0 10px; text-decoration:none; font-weight:bold; }
    nav a:hover { text-decoration: underline; opacity: 0.9; }
    .hero { padding:60px 20px; text-align:center; background:#fde68a; }
    .btn { display:inline-block; margin-top:20px; padding:12px 24px; background:#f59e0b; color:#fff; border-radius:12px; text-decoration:none; }
    .btn:hover { background:#f97316; }
    .section { padding:40px 20px; text-align:center; }
    .cards { display:flex; flex-wrap:wrap; justify-content:center; gap:20px; }
    .card { background:#fff; padding:20px; border-radius:16px; width:220px; box-shadow:0 4px 10px rgba(0,0,0,0.1); }
    footer { text-align:center; padding:20px; background:#f59e0b; color:#fff; margin-top:40px; }
    html { scroll-behavior: smooth; }
    @media (max-width: 600px) {
      .cards { flex-direction: column; gap: 16px; }
      .card { width: 100%; }
      .section, .hero { padding: 24px 8px; }
    }
  </style>
</head>
<body>

<header>
  <h1>🍰 Aizh.cakes</h1>
  <nav>
    <a href="#">Главная</a>
    <a href="#menu">Меню</a>
    <a href="#contact">Контакты</a>
  </nav>
</header>

<section class="hero">
  <h2>Свежая выпечка каждый день</h2>
  <p>Самса, пироги и десерты ручной работы ❤️</p>
  <a href="https://wa.me/77471191556" class="btn" target="_blank" rel="noopener">Заказать</a>
</section>

<section class="section" id="menu">
  <h2>Наше меню</h2>
  <div class="cards">
    <div class="card">
      <h3>Самса</h3>
      <p>Сочная, горячая, домашняя</p>
      <p><b>кг. 3500₸</b></p>
      <a href="https://wa.me/77471191556" class="btn" target="_blank" rel="noopener">Заказать</a>
    </div>
    <div class="card">
      <h3>Пироги</h3>
      <p>С разными начинками</p>
      <p><b>от 2700₸</b></p>
      <a href="https://wa.me/77471191556" class="btn" target="_blank" rel="noopener">Заказать</a>
    </div>
    <div class="card">
      <h3>Торты</h3>
      <p>На заказ</p>
      <p><b>от 5000₸</b></p>
      <a href="https://wa.me/77471191556" class="btn" target="_blank" rel="noopener">Заказать</a>
    </div>
  </div>
</section>

<section class="section" id="contact">
  <h2>Контакты</h2>
  <p>📍 Уральск</p>
  <p>📞 WhatsApp: <a href="https://wa.me/77471191556" target="_blank" rel="noopener">+7 747 119 15 56</a></p>
  <p>📸 Instagram: <a href="https://instagram.com/aizh.cakes" target="_blank" rel="noopener">@aizh.cakes</a></p>
  <a href="https://wa.me/77471191556" class="btn" target="_blank" rel="noopener">Заказать</a>
</section>

<footer>
  <p>© 2026 Домашняя кондитерская</p>
</footer>

</body>
</html>
