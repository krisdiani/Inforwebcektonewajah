
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Website Pribadi</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #fdfdfd;
      color: #333;
    }

    header {
      background: linear-gradient(90deg, #ff8aa3, #ffd3b6);
      color: #fff;
      padding: 2em 1em;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2em;
    }

    nav {
      display: flex;
      justify-content: center;
      background: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    nav a {
      padding: 1em;
      text-decoration: none;
      color: #ff5e78;
      font-weight: bold;
      transition: background 0.3s;
    }

    nav a:hover {
      background: #ffeff2;
    }

    main {
      max-width: 900px;
      margin: auto;
      padding: 2em;
    }

    section {
      margin-bottom: 3em;
    }

    section img {
      max-width: 100%;
      border-radius: 10px;
      margin-top: 1em;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    footer {
      background: #ff8aa3;
      color: white;
      text-align: center;
      padding: 1em;
      margin-top: 3em;
    }

    h2 {
      color: #ff5e78;
    }

    p {
      line-height: 1.6;
    }

    ul {
      list-style-type: disc;
      padding-left: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Website CekToneWajah & JenisKulit</h1>
  <p>Selamat datang di website kami</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="hal4.html">Profil</a>
  <a href="hal2.html">Isi 1</a>
  <a href="hal5.html">Isi 2</a>
  <a href="hal9.html">Galeri</a>
  <a href="hal10.html">Form</a>
</nav>

<main>
  <section id="home">
    <h2>Tips Menjaga Kulit Wajah & Memilih Warna Baju Sesuai Tone Kulit</h2>

    <h3>Bagian 1: Cara Menjaga Kulit Wajah Agar Tetap Sehat dan Cerah</h3>
    <ul>
      <li><strong>Bersihkan wajah secara rutin:</strong> Gunakan pembersih wajah sesuai jenis kulit dua kali sehari.</li>
      <li><strong>Gunakan pelembap:</strong> Pilih pelembap dengan hyaluronic acid atau ceramide.</li>
      <li><strong>Lindungi kulit dari sinar matahari:</strong> Gunakan sunscreen minimal SPF 30 setiap hari.</li>
      <li><strong>Eksfoliasi secara berkala:</strong> Lakukan 1–2 kali seminggu dengan scrub lembut atau AHA/BHA.</li>
      <li><strong>Hidrasi dari dalam:</strong> Minum air dan konsumsi makanan tinggi antioksidan.</li>
      <li><strong>Tidur yang cukup:</strong> Tidur 7–9 jam setiap malam membantu regenerasi kulit.</li>
    </ul>

    <img src="gambar7.jpg" alt="Ilustrasi perawatan kulit" width="300" height="300" />

    <h3>Bagian 2: Rekomendasi Warna Baju Sesuai Tone Kulit</h3>
    <p>Langkah pertama adalah memahami skin tone dan undertone kulit Anda:</p>

    <ul>
      <li><strong>Kulit Terang</strong>
        <ul>
          <li>Cool: biru muda, ungu, toska, abu-abu, marun</li>
          <li>Warm: peach, coral, olive, kuning keemasan</li>
        </ul>
      </li>
      <li><strong>Kulit Sawo Matang</strong>
        <ul>
          <li>Cool: navy, burgundy, lavender</li>
          <li>Warm: mustard, merah bata, olive</li>
        </ul>
      </li>
      <li><strong>Kulit Gelap</strong>
        <ul>
          <li>Cool: emerald, royal blue, ungu tua</li>
          <li>Warm: oranye, merah terang, terracotta</li>
        </ul>
      </li>
    </ul>
  </section>
</main>

<footer>
  <p>&copy; 2025 Website ini dibuat untuk memenuhi tugas mata pelajaran Informatika</p>
</footer>

</body>
</html>
