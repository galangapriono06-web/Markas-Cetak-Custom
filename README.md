
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Markas Cetak Custom | Souvenir Profesional</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="topbar">
  <div>
    <h1>Markas Cetak Custom</h1>
    <p>Souvenir Cetak • Profesional • Terpercaya</p>
  </div>
  <button class="login">Masuk</button>
</header>

<!-- HERO -->
<section class="hero">
  <h2>Pesan Souvenir Custom dengan Mudah</h2>
  <p>Proses manual • Aman • Konsultasi langsung via WhatsApp</p>
</section>

<!-- STEP 1 -->
<section class="card">
  <h3>1️⃣ Data Pemesan</h3>
  <input type="text" id="nama" placeholder="Nama Lengkap">
  <input type="text" id="wa" placeholder="Nomor WhatsApp (62...)">
</section>

<!-- STEP 2 -->
<section class="card">
  <h3>2️⃣ Pilih Jenis Souvenir</h3>
  <select id="jenis">
    <option value="">-- Pilih Jenis --</option>
    <option value="Souvenir Nikahan">Souvenir Nikahan</option>
    <option value="Souvenir Kantor">Souvenir Kantor</option>
    <option value="Souvenir Custom">Souvenir Custom</option>
  </select>
</section>

<!-- STEP 3 -->
<section class="card">
  <h3>3️⃣ Jumlah & Catatan</h3>
  <input type="number" id="jumlah" placeholder="Jumlah Pesanan">
  <textarea id="catatan" placeholder="Catatan tambahan (opsional)"></textarea>
</section>

<!-- STEP 4 -->
<section class="card">
  <h3>4️⃣ Pembayaran</h3>
  <p class="info">
    Silakan lakukan pembayaran melalui link berikut sebelum pesanan diproses.
  </p>
  <a href="https://contoh-link-pembayaran.com" target="_blank" class="pay">
    💳 Link Pembayaran
  </a>
</section>

<!-- STEP 5 -->
<section class="card">
  <h3>5️⃣ Kirim Pesanan</h3>
  <button class="wa" onclick="kirimWA()">Kirim Pesanan via WhatsApp</button>
</section>

<footer>
  © 2026 Markas Cetak Custom<br>
  Proses Manual • Aman • Legal
</footer>

<script src="body"></script>
</body>
</html>
