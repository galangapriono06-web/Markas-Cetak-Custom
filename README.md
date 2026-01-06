<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Markas Cetak Custom</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Markas Cetak Custom</h1>
  <p>Custom Souvenir • Profesional • Sesuai Kebutuhan Anda</p>
  <a href="#order" class="btn-primary">Order Sekarang</a>
</header>

<section class="about">
  <h2>Tentang Markas Cetak Custom</h2>
  <p>Kami melayani pembuatan souvenir custom untuk berbagai kebutuhan: event, kantor, komunitas, dan personal dengan kualitas profesional.</p>
</section>

<section class="produk">
  <h2>Produk Populer</h2>
  <div class="grid">
    <div class="card">
      <h3>Souvenir Event</h3>
      <p>Custom logo & desain</p>
    </div>
    <div class="card">
      <h3>Souvenir Kantor</h3>
      <p>Elegan & berkelas</p>
    </div>
    <div class="card">
      <h3>Souvenir Custom</h3>
      <p>Sesuai request</p>
    </div>
  </div>
</section>

<section class="order" id="order">
  <h2>Form Pemesanan</h2>

  <input type="text" id="nama" placeholder="Nama Anda">
  <input type="text" id="produk" placeholder="Jenis Souvenir">
  <input type="number" id="jumlah" placeholder="Jumlah">
  <textarea id="catatan" placeholder="Catatan / request desain"></textarea>

  <button onclick="kirimWA()">Pesan via WhatsApp</button>
</section>

<footer>
  <p>© 2026 MARKAS CETAK CUSTOM</p>
</footer>

<script src="script.js"></script>
</body>
</html>
