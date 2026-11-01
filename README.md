# tokokita<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Toko Online Yeyen</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>🛒 Toko Online Yeyen</h1>
    <nav>
      <a href="#produk">Produk</a>
      <a href="#tentang">Tentang Kami</a>
      <a href="#kontak">Kontak</a>
    </nav>
  </header>

  <section id="produk">
    <h2>Produk Unggulan</h2>
    <div class="item">
      <img src="kelor.jpg" alt="Teh Kelor Jawi">
      <h3>Teh Kelor Jawi</h3>
      <p>Harga: Rp25.000</p>
      <button>Beli Sekarang</button>
    </div>
    <div class="item">
      <img src="jahe.jpg" alt="Jahe Jawi">
      <h3>Jahe Jawi</h3>
      <p>Harga: Rp30.000</p>
      <button>Beli Sekarang</button>
    </div>
  </section>

  <section id="tentang">
    <h2>Tentang Kami</h2>
    <p>Kami menjual produk herbal alami khas Jawa dengan kualitas terbaik untuk kesehatan keluarga.</p>
  </section>

  <section id="kontak">
    <h2>Hubungi Kami</h2>
    <form>
      <input type="text" placeholder="Nama">
      <input type="email" placeholder="Email">
      <textarea placeholder="Pesan"></textarea>
      <button type="submit">Kirim</button>
    </form>
  </section>

  <footer>
    <p>© 2026 Toko Online Yeyen</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f9f9f9;
  color: #333;
}
header {
  background: #2c3e50;
  color: white;
  padding: 20px;
  text-align: center;
}
nav a {
  margin: 0 10px;
  color: #00ffcc;
  text-decoration: none;
}
section {
  padding: 40px;
}
.item {
  display: inline-block;
  width: 200px;
  margin: 20px;
  text-align: center;
  background: #fff;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 10px;
}
.item img {
  width: 100%;
  border-radius: 8px;
}
button {
  background: #00ffcc;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
  margin-top: 10px;
}
button:hover {
  background: #00ffaa;
}
footer {
  background: #2c3e50;
  color: white;
  text-align: center;
  padding: 10px;
}
