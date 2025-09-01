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