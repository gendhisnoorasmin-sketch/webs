<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Web Profile Siswa</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: #f8f6fa;
      color: #333;
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      background: linear-gradient(135deg, #c8a2c8, #a2c2e6);
      color: #fff;
      padding: 60px 20px;
      text-align: center;
      border-radius: 0 0 40px 40px;
      animation: fadeDown 1s ease-in-out;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }

    .profile-card {
      background: #fff;
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      margin-top: -40px;
      text-align: center;
      animation: fadeUp 1.5s ease-in-out;
    }

    .profile-card img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      border: 5px solid #c8a2c8;
      transition: transform 0.4s;
    }

    .profile-card img:hover {
      transform: scale(1.1) rotate(3deg);
    }

    .section {
      margin-top: 50px;
      padding: 20px;
      background: #fff;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      animation: fadeUp 2s ease-in-out;
    }

    .section h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #5a3c5a;
      position: relative;
    }

    .section h2::after {
      content: "";
      display: block;
      width: 60px;
      height: 4px;
      background: #c8a2c8;
      margin: 8px auto 0;
      border-radius: 2px;
    }

    .data-diri table {
      width: 100%;
      border-collapse: collapse;
    }

    .data-diri th, .data-diri td {
      padding: 12px 15px;
      text-align: left;
      border-bottom: 1px solid #eee;
    }

    .data-diri th {
      width: 220px;
      color: #6a4c93;
      background: #f3e8ff;
      border-radius: 8px;
    }

    .hobi-list, .pendidikan-list {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 15px;
    }

    .chip {
      background: #e6d4f5;
      padding: 12px 20px;
      border-radius: 25px;
      font-size: 0.95rem;
      font-weight: 500;
      color: #5a3c5a;
      transition: transform 0.3s;
    }

    .chip:hover {
      transform: scale(1.1);
      background: #c8a2c8;
      color: #fff;
    }

    blockquote {
      font-style: italic;
      color: #5a3c5a;
      text-align: center;
      border-left: 5px solid #c8a2c8;
      padding-left: 15px;
      margin: 20px auto;
      max-width: 700px;
      animation: pulse 3s infinite;
    }

    footer {
      margin-top: 50px;
      background: #c8a2c8;
      color: #fff;
      text-align: center;
      padding: 15px;
      border-radius: 20px 20px 0 0;
    }

    /* Animasi */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(50px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeDown {
      from { opacity: 0; transform: translateY(-50px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.03); }
      100% { transform: scale(1); }

    }
  </style>
</head>
<body>
  <header>
    <h1>WEB PROFILE</h1>
    <p>SISWI• KELAS X • RPL 1</p>
  </header>

  <div class="container">
    <!-- Foto & Nama -->
    <div class="profile-card">
      <img src="https://uploads.onecompiler.io/43w7h5fjp/43w7mpzjj/GENDHIS%20NOOR%20ASMIN.jpg" alt="Foto Gendhis Noor Asmin">
        </div>

      <h2>GENDHIS NOOR ASMIN</h2>
      <h4>Jurusan: Rekayasa Perangkat Lunak</h4>
    </div>

    <!-- Data Diri -->
    <section class="section data-diri">
      <h2>Data Diri</h2>
      <table>
        <tr><th>Nama Lengkap</th><td>GENDHIS NOOR ASMIN</td></tr>
        <tr><th>NISN</th><td>00892*7149</td></tr>
        <tr><th>Tempat, Tanggal Lahir</th><td>BATAM, 15 DESEMBER 200*</td></tr>
        <tr><th>Jenis Kelamin</th><td>PEREMPUAN</td></tr>
        <tr><th>Agama</th><td>ISLAM</td></tr>
        <tr><th>Alamat</th><td>PERUM.TAMAN MEDITERANIA THP 2 BLOK EE* NO 2*</td></tr>
        <tr><th>Email</th><td>gendhis***rasmin@gmail.com</td></tr>
        <tr><th>No. HP</th><td>+62 899-4823-08*</td></tr>
      </table>
    </section>

    <!-- Tentang Saya -->
    <section class="section">
      <h2>Tentang Saya</h2>
      <p style="text-align: center; max-width: 800px; margin: auto;">
        Saya adalah siswa SMK jurusan Rekayasa Perangkat Lunak yang memiliki minat besar dalam pemrograman. 
        Saya aktif mengikuti kegiatan sekolah, ***** bekerja dalam tim, serta gemar mencoba hal-hal baru yang dapat meningkatkan kreativitas.walaupun saya
        juga harus lebih meningkatkan kembali ilmu yang saya peroleh agar lebih memahami materi pemrograman lebih dalam.
      </p>
    </section>

    <!-- Cita-cita -->
    <section class="section">
      <h2>Cita-cita</h2>
      <p style="text-align: center; font-weight: 500;">Menjadi seorang <b>Data Analyst</b> yang dapat menganalisis berbagai data yang dimiliki oleh orang lain
      dan juga bermannfaat bagi banyak orang.</p>
    </section>

    <!-- Hobi -->
    <section class="section">
      <h2>Hobi</h2>
      <div class="hobi-list">
        <span class="chip">Membaca buku novel</span>
        <span class="chip">mendengarkan musik</span>
        <span class="chip">menonton k-drama/c-drama</span>
      </div>
    </section>

    <!-- Quote -->
    <section class="section">
      <h2>Quote</h2>
      <blockquote>"Jangan takut mencoba hal baru,karena kegagalan adalah langkah menuju keberhasilan."</blockquote>
    </section>

    <!-- Pendidikan -->
    <section class="section">
      <h2>Pendidikan</h2>
      <div class="pendidikan-list">
        <span class="chip">SD Negeri 008 Batam (2016 - 2022)</span>
        <span class="chip">SMP Negeri 12 Batam (2022 - 2025)</span>
        <span class="chip">SMK Negeri 07 Batam - RPL (2025 - Sekarang)</span>
      </div>
    </section>
  </div>
  
  <section>
    <!-- Pengalaman Organisasi -->
    <section class="section">
      <h2>Pengalaman organisasi</h2>
      <div class="pendidikan-list">
        <span class="chip">Member English Club (2022)</span>
        <span class="chip">Anggota Pik-r (2022 - 2025 pada bulan febuary)</span>
        <span class="chip">Member tataboga (3 bulan)</span>
      </div>      
    </section>
  </div>
        
  <footer>
    <p>© 2025 Gendhis Noor Asmin | Dibuat dengan ❤️</p>
  </footer>
</body>
</html>
