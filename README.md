<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CV Fauzi Adibi</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background:#f4f4f4;
      color:#333;
    }

    .container{
      max-width:900px;
      margin:40px auto;
      background:white;
      border-radius:15px;
      overflow:hidden;
      box-shadow:0 5px 15px rgba(0,0,0,0.2);
    }

    .header{
      background:#1e3a8a;
      color:white;
      text-align:center;
      padding:40px 20px;
    }

    .profile-img{
      width:150px;
      height:150px;
      border-radius:50%;
      border:5px solid white;
      object-fit:cover;
      margin-bottom:15px;
    }

    .content{
      padding:30px;
    }

    .section{
      margin-bottom:30px;
    }

    .section h2{
      color:#1e3a8a;
      margin-bottom:10px;
      border-bottom:2px solid #1e3a8a;
      padding-bottom:5px;
    }

    .social-links{
      margin-top:20px;
    }

    .social-links a{
      display:inline-block;
      margin:10px;
      padding:12px 20px;
      background:#1e3a8a;
      color:white;
      text-decoration:none;
      border-radius:8px;
      transition:0.3s;
    }

    .social-links a:hover{
      background:#2563eb;
    }

    footer{
      text-align:center;
      padding:20px;
      background:#eee;
    }
  </style>
</head>
<body>

  <div class="container">

    <div class="header">

      <!-- FOTO PROFIL -->
      <!-- Ganti link gambar di bawah dengan foto milikmu -->
      <img 
        src="https://via.placeholder.com/150" 
        alt="Foto Profil"
        class="profile-img"
      >

      <h1>Fauzi Adibi</h1>
      <p>Mahasiswa Fakultas Ilmu Komputer dan Teknologi Informasi</p>

    </div>

    <div class="content">

      <div class="section">
        <h2>Tentang Saya</h2>
        <p>
          Saya adalah mahasiswa Universitas Muhammadiyah Sumatera Utara (UMSU)
          Fakultas Ilmu Komputer dan Teknologi Informasi yang memiliki minat
          dalam bidang teknologi, pemrograman, dan pengembangan website.
        </p>
      </div>

      <div class="section">
        <h2>Pendidikan</h2>

        <h3>MAN 2 Model Medan</h3>
        <p>2022 - 2025</p>

        <br>

        <h3>Universitas Muhammadiyah Sumatera Utara (UMSU)</h3>
        <p>Fakultas Ilmu Komputer dan Teknologi Informasi</p>
        <p>2025 - Sekarang</p>
      </div>

      <div class="section">
        <h2>Kontak & Sosial Media</h2>

        <div class="social-links">

          <!-- Ganti link Instagram -->
          <a href="https://instagram.com/usernamekamu" target="_blank">
            Instagram
          </a>

          <!-- Ganti link LinkedIn -->
          <a href="https://linkedin.com/in/usernamekamu" target="_blank">
            LinkedIn
          </a>

        </div>
      </div>

    </div>

    <footer>
      <p>© 2026 Fauzi Adibi</p>
    </footer>

  </div>

</body>
</html>
