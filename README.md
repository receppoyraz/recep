# recep
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bodrum Elektrik | Profesyonel Elektrik Hizmetleri</title>
  <meta name="description" content="Bodrum Elektrik - 7/24 elektrik arıza, tesisat, kamera & alarm, pano sigorta, LED aydınlatma hizmetleri. Hızlı randevu ve WhatsApp destek.">
  <style>
    /* Genel Ayarlar */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      color: #333;
    }

    /* Navbar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #1a1a1a;
      padding: 12px 30px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    .navbar .logo a {
      text-decoration: none;
      font-size: 20px;
      font-weight: bold;
      color: #fff;
    }
    .nav-links {
      list-style: none;
      display: flex;
      gap: 20px;
      margin: 0;
      padding: 0;
    }
    .nav-links li a {
      text-decoration: none;
      color: #fff;
      font-size: 16px;
      transition: color 0.3s;
    }
    .nav-links li a:hover {
      color: #f0c040;
    }

    /* Banner */
    .banner {
      background: url('https://source.unsplash.com/1600x600/?electric,tools') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    .banner h1 {
      font-size: 36px;
      margin: 0 0 15px;
    }
    .banner p {
      font-size: 18px;
    }

    /* Hizmetler */
    .hizmetler {
      padding: 50px 20px;
      text-align: center;
    }
    .hizmetler h2 {
      font-size: 28px;
      margin-bottom: 30px;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card h3 {
      margin-top: 0;
      color: #1a1a1a;
    }

    /* Footer */
    .footer {
      background: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
    .footer a {
      color: #f0c040;
      text-decoration: none;
      font-weight: bold;
    }

    /* Mobil Menü */
    @media (max-width: 768px) {
      .nav-links {
        flex-direction: column;
        background: #1a1a1a;
        position: absolute;
        top: 60px;
        right: 0;
        width: 200px;
        display: none;
        padding: 15px;
      }
      .nav-links.active {
        display: flex;
      }
    }
  </style>
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar">
    <div class="logo">
      <a href="index.html">⚡ Bodrum Elektrik</a>
    </div>
    <ul class="nav-links">
      <li><a href="index.html">Ana Sayfa</a></li>
      <li><a href="elektrik-ariza.html">Elektrik Arıza</a></li>
      <li><a href="tesisat.html">Tesisat & Montaj</a></li>
      <li><a href="kamera.html">Kamera & Alarm</a></li>
      <li><a href="pano.html">Pano & Sigorta</a></li>
      <li><a href="led-aydinlatma.html">LED & Aydınlatma</a></li>
      <li><a href="randevu.html">Randevu</a></li>
      <li><a href="iletisim.html">İletişim</a></li>
      <li><a href="https://wa.me/905342654522" target="_blank">WhatsApp</a></li>
    </ul>
  </nav>

  <!-- BANNER -->
  <section class="banner">
    <h1>Bodrum Elektrik Hizmetleri</h1>
    <p>7/24 Hızlı Çözüm – Profesyonel Elektrikçi Desteği</p>
  </section>

  <!-- HİZMETLER -->
  <section class="hizmetler">
    <h2>Hizmetlerimiz</h2>
    <div class="cards">
      <div class="card">
        <h3>⚡ Elektrik Arıza</h3>
        <p>Kısa devre, kaçak akım, priz & anahtar arızaları için hızlı çözüm.</p>
      </div>
      <div class="card">
        <h3>🔌 Tesisat & Montaj</h3>
        <p>Yeni tesisat, priz, lamba ve elektrik panosu kurulumu.</p>
      </div>
      <div class="card">
        <h3>📷 Kamera & Alarm</h3>
        <p>Güvenlik kamera ve alarm sistemi montajı ve bakımı.</p>
      </div>
      <div class="card">
        <h3>🛠️ Pano & Sigorta</h3>
        <p>Elektrik panosu montajı, sigorta değişimi ve bakım hizmeti.</p>
      </div>
      <div class="card">
        <h3>💡 LED & Aydınlatma</h3>
        <p>Enerji tasarruflu LED sistemleri ve dekoratif aydınlatma.</p>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    <p>📞 0534 265 45 22 | 0533 617 15 03</p>
    <p>WhatsApp için <a href="https://wa.me/905342654522" target="_blank">tıklayın</a></p>
    <p>&copy; 2025 Bodrum Elektrik - Tüm Hakları Saklıdır</p>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hizmetlerimiz | Bodrum Elektrik</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; background:#f9f9f9; color:#333; }
    .navbar { display:flex; justify-content:space-between; align-items:center; background:#1a1a1a; padding:12px 30px; }
    .navbar .logo a { color:#fff; font-weight:bold; text-decoration:none; font-size:20px; }
    .nav-links { list-style:none; display:flex; gap:20px; margin:0; padding:0; }
    .nav-links li a { color:#fff; text-decoration:none; }
    .nav-links li a:hover { color:#f0c040; }
    .container { padding:40px 20px; max-width:1000px; margin:auto; }
    h1 { text-align:center; margin-bottom:30px; }
    .service { background:#fff; margin-bottom:20px; padding:20px; border-radius:10px; box-shadow:0 2px 6px rgba(0,0,0,0.1); }
    .service h2 { margin-top:0; }
  </style>
</head>
<body>
  <!-- NAVBAR -->
  <nav class="navbar">
    <div class="logo"><a href="index.html">⚡ Bodrum Elektrik</a></div>
    <ul class="nav-links">
      <li><a href="index.html">Ana Sayfa</a></li>
      <li><a href="hizmetler.html">Hizmetler</a></li>
      <li><a href="randevu.html">Randevu</a></li>
      <li><a href="iletisim.html">İletişim</a></li>
    </ul>
  </nav>

  <div class="container">
    <h1>Hizmetlerimiz</h1>

    <div class="service">
      <h2>⚡ Elektrik Arıza</h2>
      <p>Kısa devre, sigorta atma, priz arızaları ve tüm elektrik sorunlarını 7/24 çözüyoruz.</p>
    </div>

    <div class="service">
      <h2>🔌 Elektrik Tesisat & Montaj</h2>
      <p>Yeni tesisat kurulumu, kablo döşeme, priz ve anahtar montajı.</p>
    </div>

    <div class="service">
      <h2>📷 Kamera & Alarm Sistemleri</h2>
      <p>Güvenlik kamera kurulumu, alarm sistemleri ve bakım hizmeti.</p>
    </div>

    <div class="service">
      <h2>🛠️ Pano & Sigorta</h2>
      <p>Elektrik panosu kurulumu, sigorta değişimi ve düzenleme.</p>
    </div>

    <div class="service">
      <h2>💡 LED & Aydınlatma Sistemleri</h2>
      <p>LED armatür, dekoratif aydınlatma ve enerji tasarruflu çözümler.</p>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Randevu | Bodrum Elektrik</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; background:#f9f9f9; color:#333; }
    .navbar { display:flex; justify-content:space-between; align-items:center; background:#1a1a1a; padding:12px 30px; }
    .navbar .logo a { color:#fff; font-weight:bold; text-decoration:none; font-size:20px; }
    .nav-links { list-style:none; display:flex; gap:20px; margin:0; padding:0; }
    .nav-links li a { color:#fff; text-decoration:none; }
    .nav-links li a:hover { color:#f0c040; }
    .container { padding:40px 20px; max-width:600px; margin:auto; }
    h1 { text-align:center; margin-bottom:30px; }
    form { display:flex; flex-direction:column; gap:15px; }
    input, textarea, button { padding:12px; border:1px solid #ccc; border-radius:8px; font-size:16px; }
    button { background:#1a1a1a; color:#fff; cursor:pointer; }
    button:hover { background:#f0c040; color:#000; }
    .whatsapp { text-align:center; margin-top:20px; }
    .whatsapp a { background:#25D366; color:#fff; padding:10px 20px; border-radius:8px; text-decoration:none; font-weight:bold; }
  </style>
</head>
<body>
  <!-- NAVBAR -->
  <nav class="navbar">
    <div class="logo"><a href="index.html">⚡ Bodrum Elektrik</a></div>
    <ul class="nav-links">
      <li><a href="index.html">Ana Sayfa</a></li>
      <li><a href="hizmetler.html">Hizmetler</a></li>
      <li><a href="randevu.html">Randevu</a></li>
      <li><a href="iletisim.html">İletişim</a></li>
    </ul>
  </nav>

  <div class="container">
    <h1>Randevu Al</h1>
    <form>
      <input type="text" placeholder="Adınız Soyadınız" required>
      <input type="tel" placeholder="Telefon Numaranız" required>
      <input type="email" placeholder="E-posta (isteğe bağlı)">
      <textarea rows="5" placeholder="Talep ettiğiniz hizmeti yazınız" required></textarea>
      <button type="submit">Randevu Gönder</button>
    </form>

    <div class="whatsapp">
      <p>📱 Hızlı randevu için:</p>
      <a href="https://wa.me/905342654522" target="_blank">WhatsApp’tan Mesaj Gönder</a>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>İletişim | Bodrum Elektrik</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; background:#f9f9f9; color:#333; }
    .navbar { display:flex; justify-content:space-between; align-items:center; background:#1a1a1a; padding:12px 30px; }
    .navbar .logo a { color:#fff; font-weight:bold; text-decoration:none; font-size:20px; }
    .nav-links { list-style:none; display:flex; gap:20px; margin:0; padding:0; }
    .nav-links li a { color:#fff; text-decoration:none; }
    .nav-links li a:hover { color:#f0c040; }
    .container { padding:40px 20px; max-width:800px; margin:auto; }
    h1 { text-align:center; margin-bottom:30px; }
    .info { background:#fff; padding:20px; border-radius:10px; margin-bottom:20px; box-shadow:0 2px 6px rgba(0,0,0,0.1); }
    iframe { width:100%; height:300px; border:0; border-radius:10px; }
  </style>
</head>
<body>
  <!-- NAVBAR -->
  <nav class="navbar">
    <div class="logo"><a href="index.html">⚡ Bodrum Elektrik</a></div>
    <ul class="nav-links">
      <li><a href="index.html">Ana Sayfa</a></li>
      <li><a href="hizmetler.html">Hizmetler</a></li>
      <li><a href="randevu.html">Randevu</a></li>
      <li><a href="iletisim.html">İletişim</a></li>
    </ul>
  </nav>

  <div class="container">
    <h1>İletişim</h1>

    <div class="info">
      <p>📍 Adres: Bodrum, Muğla</p>
      <p>📞 Telefon: 0534 265 45 22 | 0533 617 15 03</p>
      <p>📧 E-posta: info@bodrum-elektrik.com.tr</p>
      <p>💬 WhatsApp: <a href="https://wa.me/905342654522" target="_blank">Tıkla ve Yaz</a></p>
    </div>

    <h2>Konum</h2>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3155.079328581458!2d27.423!3d37.034!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0:0x0!2zMzfCsDAyJzAxLjQiTiAyN8KwMjUnMjIuOCJF!5e0!3m2!1str!2str!4v1699971721556"></iframe>
  </div>
</body>
</html>