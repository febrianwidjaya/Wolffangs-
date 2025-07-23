<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WOLFFANGS | Official Website</title>
  <meta name="description" content="Website resmi WOLFFANGS. Bergabunglah dengan kekuatan kami." />
  <link rel="stylesheet" href="style.css" />
  <link rel="icon" href="favicon.ico" />
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">WOLFFANGS</h1>
      <nav>
        <a href="#home">Home</a>
        <a href="#about">Tentang</a>
        <a href="#gallery">Galeri</a>
        <a href="#contact">Kontak</a>
      </nav>
    </div>
  </header>

  <section id="home" class="hero">
    <div class="hero-content">
      <h2>Selamat datang di WOLFFANGS</h2>
      <p>Kami adalah kekuatan di balik bayangan. Bergabunglah sekarang.</p>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <h2>Tentang Kami</h2>
      <p>WOLFFANGS adalah komunitas kreatif / tim e-sports / brand (sesuaikan isi ini sesuai kebutuhan).</p>
    </div>
  </section>

  <section id="gallery">
    <div class="container">
      <h2>Galeri</h2>
      <div class="gallery">
        <img src="img1.jpg" alt="Gambar 1" />
        <img src="img2.jpg" alt="Gambar 2" />
        <img src="img3.jpg" alt="Gambar 3" />
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Hubungi Kami</h2>
      <form action="https://formspree.io/f/yourformid" method="POST">
        <input type="text" name="name" placeholder="Nama" required />
        <input type="email" name="email" placeholder="Email" required />
        <textarea name="message" placeholder="Pesan..." rows="5" required></textarea>
        <button type="submit">Kirim</button>
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 WOLFFANGS. All rights reserved.</p>
  </footer>
</body>
</html>
