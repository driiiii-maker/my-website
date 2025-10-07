<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pengenalan Diri - Andrian Narja</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #f8f9fc;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                  url('https://picsum.photos/1600/900?blur=2') no-repeat center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid #fff;
      margin-bottom: 20px;
      box-shadow: 0 0 15px rgba(0,0,0,0.5);
      animation: fadeIn 2s;
    }

    header h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2em;
      opacity: 0.9;
    }

    section {
      max-width: 1000px;
      margin: 50px auto;
      padding: 20px;
      background: #fff;
      border-radius: 20px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    section:hover {
      transform: translateY(-5px);
    }

    section h2 {
      font-size: 2em;
      margin-bottom: 15px;
      color: #2575fc;
      border-left: 5px solid #2575fc;
      padding-left: 10px;
    }

    ul {
      list-style: none;
      padding-left: 10px;
    }

    ul li {
      padding: 8px 0;
      border-bottom: 1px solid #eee;
    }

    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }

    .skill-card {
      background: #f1f4ff;
      padding: 15px;
      border-radius: 15px;
      text-align: center;
      transition: 0.3s;
    }

    .skill-card:hover {
      background: #e0e7ff;
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 30px;
      background: #2575fc;
      color: white;
      margin-top: 40px;
    }

    a {
      color: #2575fc;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.8);}
      to { opacity: 1; transform: scale(1);}
    }
  </style>
</head>
<body>

  <header>
    <img src="drian.jpg" alt="Foto Profil">
    <h1>Halo, Saya Andrian Narja</h1>
    <p>Siswa SMK | Desainer Grafis | Life Enjoyer</p>
  </header>

  <section>
    <h2>Tentang Saya</h2>
    <p>
      Saya adalah seorang siswa yang penuh semangat dalam dunia kreatif dan digital. 
      Saya suka eksplor dunia desain, belajar hal-hal kreatif dan mencoba hal baru.
      Saya juga menjalani hidup dengan santai, asalkan kewajiban saya sudah terlaksana.
      Saya ingin terus berkembang menjadi pribadi yang kreatif dan lebih produktif, supaya 
      saya bisa lebih bermanfaat bagi orang lain, terutama keluarga saya.
      
    </p>
  </section>

  <section>
    <h2>Keterampilan</h2>
    <div class="skills">
      <div class="skill-card">🎨 Desain Grafis (Photoshop, Illustrator) Lumayan </div>
      <div class="skill-card">💻 Web Development (HTML, CSS) Pemula </div>
      <div class="skill-card">📱 UI Design (Figma) Lumayan</div>
      <div class="skill-card">📸 Fotografi & Editing (DaVinci Resolve) Pemula</div>
      <div class="skill-card">📺 Animasi (Blender) Lumayan</div>
    </div>
  </section>

  <section>
    <h2>Riwayat Pendidikan</h2>
    <ul>
      <li>TK Strada Santa Maria 1</li>
      <li>SD Strada Santa Maria 1</li>
      <li>SMP Strada Santa Maria 1</li>
      <li>SMKN 1 Tangerang</li>

    </ul>
  </section>

  <section>
    <h2>Hobi</h2>
    <p>
     
    </p>
    <ul>
      <li>Menonton video edukasi/entertaiment di Youtube</li>
      <li>Bermain game</li>
      <li>Membaca buku quality of life</li>
      <li>Olahraga lari</li>
    </ul>
  </section>

    <section>
    <h2>Prestasi</h2>
    <ul>
      <li>Juara Lomba Mewarnai (TK)</li>
    </ul>
    <p>
      Satu-satunya prestasi saya dalam hal perlombaan. Saya juga ada beberapa hal-hal
      yang menurut saya prestasi tersendiri bagi saya. Seperti mendapat nilai yang cukup baik, 
      jarang berkata kasar, bisa memasak makanan-makanan mudah.
    </p>
  </section>
  
<section>
    <h2>Makanan Kesukaan</h2>
    <ul>
      <li>Nasi Goreng</li>
       <li>Mie Kuah</li>
        <li>Kentang</li>
    </ul>
  </section>

  <footer>
    <p>© 2025 Andrian Narja | Tentang Saya</p>
  </footer>

</body>
</html>
