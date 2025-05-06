<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Yayasan Al Kahfi</title>
    <link rel="icon" href="logo al akfdi.ico" type="image/x-icon">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet"> <!-- Menambahkan font Poppins -->
    <style>
      * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: 'Poppins', sans-serif;
      }
      body {
        background: #f9f9f9;
        line-height: 1.6;
        scroll-behavior: smooth;
      }
      header {
        background: #2E8B57;
        color: white;
        padding: 20px 10px;
        text-align: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }
      header img {
        width: 120px;
        height: auto;
        margin-bottom: 10px;
        border-radius: 10px;
      }
      header h1 {
        font-size: 36px;
        font-weight: 600;
        letter-spacing: 1px;
      }
      nav ul {
        list-style: none;
        padding: 0;
        margin: 10px 0 0;
      }
      nav ul li {
        display: inline-block;
        margin: 0 20px;
      }
      nav ul li a {
        color: white;
        text-decoration: none;
        font-weight: bold;
        font-size: 18px;
        transition: color 0.3s ease-in-out;
      }
      nav ul li a:hover {
        color: #FFD700;
      }
      h2 {
        color: #2E8B57;
        text-align: center;
        margin-bottom: 20px;
        font-size: 28px;
        font-weight: 600;
      }
      .content-block {
        padding: 35px;
        margin: 35px auto;
        max-width: 1000px;
        background: white;
        border-radius: 10px;
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease;
      }
      .content-block:hover {
        transform: scale(1.02);
      }
      .content-block img {
        width: 100%;
        height: auto;
        border-radius: 12px;
        margin-top: 15px;
        transition: transform 0.3s ease;
      }
      .content-block img:hover {
        transform: scale(1.03);
      }
      ul {
        padding-left: 20px;
        margin-top: 10px;
      }
      #kontak p {
        margin: 10px 0;
        font-size: 16px;
      }
      #kontak p::before {
        content: "📍 ";
        display: inline-block;
      }
      #kontak p:nth-child(2)::before {
        content: "📞 ";
      }
      #kontak p:nth-child(3)::before {
        content: "✉️ ";
      }
      .button-kontak {
        display: inline-block;
        background: #2E8B57;
        color: white;
        padding: 12px 24px;
        border-radius: 8px;
        margin-top: 15px;
        text-decoration: none;
        font-size: 16px;
        font-weight: 600;
        transition: background 0.3s;
      }
      .button-kontak:hover {
        background: #246b45;
      }
      footer {
        text-align: center;
        padding: 20px;
        background: #2E8B57;
        color: white;
        margin-top: 40px;
      }

      
      @media (max-width: 768px) {
        header h1 {
          font-size: 28px;
        }
        .content-block {
          margin: 15px;
          padding: 25px;
        }
        nav ul li {
          display: block;
          margin: 10px 0;
        }
        .content-block img {
          width: 90%;
          margin: 20px auto;
        }
      }

      @media (max-width: 480px) {
        nav ul li a {
          font-size: 16px;
        }
        .content-block {
          margin: 10px;
          padding: 20px;
        }
        .button-kontak {
          font-size: 14px;
        }
      }
    </style>
  </head>
  <body>
    <!--Start of Tawk.to Script-->
<script type="text/javascript">
  var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
  (function(){
  var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
  s1.async=true;
  s1.src='https://embed.tawk.to/6819d580f496ef1910abfd2c/1iqiejvq8';
  s1.charset='UTF-8';
  s1.setAttribute('crossorigin','*');
  s0.parentNode.insertBefore(s1,s0);
  })();
  </script>
  <!--End of Tawk.to Script-->
    <header>
      <img src="logo al akfdi.jpg" alt="Logo Yayasan Al Kahfi">
      <h1>Yayasan Al Kahfi</h1>
      <nav>
        <ul>
          <li><a href="beranda.html" target="_blank">Beranda</a></li>
          <li><a href="visimisi.html" target="_blank">tentang kami</a></li>
          <li><a href="metodebelajar.html" target="_blank">metode belajar</a></li>
          <li><a href="program.html" target="_blank">Program</a></li>
          <li><a href="fasilitas.html" target="_blank">Fasilitas</a></li>
          <li><a href="kegiatan.html" target="_blank">gallery</a></li>
          <li><a href="registrasi.html" target="_blank">Registrasi</a></li>
          <li><a href="kontak.html" target="_blank">Kontak Kami</a></li>
        </ul>
      </nav>
    </header>

    <div id="beranda" class="content-block">
      <h2>Selamat Datang di Yayasan Al Kahfi</h2>
      <img src="yayasan.png" alt="Foto Yayasan Al Kahfi">
      <p>
        Yayasan Al Kahfi adalah lembaga pendidikan dan dakwah Islam yang fokus pada pembinaan generasi muda melalui kegiatan belajar mengaji dan pendidikan karakter Islami. Kami berkomitmen untuk mencetak generasi yang cerdas secara intelektual dan spiritual, serta berakhlak mulia sesuai dengan nilai-nilai Islam.
      </p>
    </div>

    

    <footer>
      <p>&copy; 2025 Yayasan Al Kahfi. All rights reserved.</p>
    </footer>
  </body>
</html>
