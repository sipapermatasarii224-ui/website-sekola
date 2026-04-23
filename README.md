# website-sekolah
DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SMKN 1 Banjar</title>  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: #f5f7fa;
      color: #333;
    }

    header {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
    }

    nav {
      background: #34495e;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 20px;
    }

    .hero img {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      border-radius: 10px;
    }

    .section {
      padding: 40px 15px;
      text-align: center;
    }

    .section h2 {
      margin-bottom: 20px;
      color: #2c3e50;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
      max-width: 1000px;
      margin: auto;
    }

    .card {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
    }

    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }

    @media (max-width:600px) {
      header h1 { font-size: 20px; }
    }
  </style></head><body><header>
  <h1>SMKN 1 BANJAR</h1>
  <p>Sekolah Kejuruan Unggulan & Berprestasi</p>
</header><nav>
  <a href="#">Beranda</a>
  <a href="#jurusan">Jurusan</a>
  <a href="#ekstra">Ekstrakurikuler</a>
  <a href="#kontak">Kontak</a>
</nav><section class="hero">
  <img src="https://via.placeholder.com/800x300" alt="SMKN 1 Banjar">
  <h2>Selamat Datang di SMKN 1 Banjar</h2>
  <p>Mencetak Generasi Siap Kerja, Kreatif, dan Berkarakter</p>
</section><section class="section" id="jurusan">
  <h2>Jurusan</h2>
  <div class="grid">
    <div class="card">AKL</div>
    <div class="card">MPLB</div>
    <div class="card">PM</div>
    <div class="card">DKV</div>
    <div class="card">BS</div>
    <div class="card">BCF</div>
    <div class="card">RPL</div>
  </div>
</section><section class="section" id="ekstra">
  <h2>Ekstrakurikuler</h2>
  <div class="grid">
    <div class="card">Pramuka</div>
    <div class="card">Paskibra</div>
    <div class="card">Basket</div>
    <div class="card">Futsal</div>
    <div class="card">Volly</div>
    <div class="card">Green Generation</div>
    <div class="card">KIR</div>
    <div class="card">IRMA</div>
    <div class="card">SISPALA</div>
    <div class="card">Badminton</div>
    <div class="card">Karate</div>
    <div class="card">Kesenian</div>
  </div>
</section><section class="section" id="kontak">
  <h2>Kontak</h2>
  <p>Email: smkn1banjar@gmail.com</p>
  <p>Telepon: 083729176482</p>
</section><footer>
  <p>© 2026 SMKN 1 Banjar</p>
</footer></body>
</html>
