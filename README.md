<head>
    <title>Perpustakaan Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: palevioletred;
            color: white;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        header img {
            height: 150px;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 15px;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        
       

        <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: #f4f4f4;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }

        body {
  font-family: Arial, sans-serif;
  text-align: center;
  background-color: #f8f9fa;
  margin: 20px;
  padding: 10px;
}

.container {
  padding: 25px;
}

h1 {
  font-size: 24px;
  color: #003366;
  margin-bottom: 20px;
}

.menu {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
  margin-bottom: 20px;
}

.item {
  text-align: center;
  width: 200px;
}

.item img {
  width: 100%;
  height: auto;
  max-height: 100px;
}

.item p {
  margin-top: 10px;
  font-size: 13px;
  font-weight: bold;
}
button:hover {
  background-color: #00509e;
}
    </style>
    </style>
</head>
<body>
    <header>
        <img src="perpustakaan digital nusantara.webp" alt="Logo Perpustakaan">
    </div>
    <div class="info">
      <h1>PERPUSTAKAAN DIGITAL NUSANTARA</h1>
      <p>Jl. Kemajuan Digital No. 88
        Kawasan Inovasi Nusantara</p>
      <p>Email: info@digitalnusantara.id</p>
    </div>

        <nav>
            <ul>
                <li><a href="#home">Beranda</a></li>
                <li><a href="halamantransaksi.html">Transaksi</a></li>
                <li><a href="halamanprofil.html">Profil</a></li>
                <li><a href="halamanlogin.html">Login</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <div class="container">
                <h1>"PERJALANAN DALAM SETIAP HALAMAN"</h1>
                <div class="menu">
                  <div class="item">
                    <img src="profil.gif" alt="Profil">
                    <p>PROFIL</p>
                  </div>
                  <div class="item">
                    <img src="layanan.gif" alt="Layanan">
                    <p>LAYANAN</p>
                  </div>
                  <div class="item">
                    <img src="keanggotaan.gif" alt="Keanggotaan">
                    <p>KEANGGOTAAN</p>
                  </div>
                  <div class="item">
                    <img src="katalog.gif" alt="Katalog Online">
                    <p>KATALOG ONLINE</p>
                  </div>
                </div>
        </section>


        <style>
        .container {
            max-width: 2000px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 100px;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.1);
        }
        </style>
        <div class="container">
            <div class="library-info">
                </div>
            </div>
        </div>

        <h2>Apa itu Perpustakaan Digital Nusantara?</h2>
            <p>Tak kenal maka tak sayang, kenalan dulu yuk platform kami</p>
            
        <img src="phone-profile.webp"  width="300" height="350" alt="Logo Perpustakaan"><img src="phone-tidur.webp"  width="500" height="150" alt="Logo Perpustakaan"><p align="center">Perpustakaan Digital Nusantara merupakan pangkalan data intelektual yang mempersembahkan dunia literasi modern di ujung jari. 
            Menyediakan koleksi yang luas, mulai dari e-book, artikel ilmiah, 
            hingga sumber daya pengetahuan yang beragam, platform ini memberikan kenyamanan tanpa batasan geografis. 
            Dengan fokus pada aksesibilitas yang lebih mudah, Perpustakaan Platform Nusantara membebaskan penggunanya dari keharusan menginstal aplikasi tambahan, 
            sehingga mengatasi kekhawatiran terkait penggunaan memori pada perangkat. 
            Dengan fitur berbasis web, pengguna dapat menikmati literasi tanpa kendala, dapat diakses dari berbagai perangkat, 
            termasuk ponsel pintar, dan tetap memiliki kemampuan untuk menyimpan ikon atau shortcut langsung di layar perangkat Anda.</p><br><br>


    <h1>Jadwal Waktu Pelayanan</h1>
    <table>
        <thead>
            <tr>
                <th>Hari</th>
                <th>Jam Buka</th>
                <th>Jam Tutup</th>
                <th>Keterangan</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Senin - Kamis</td>
                <td>08:00</td>
                <td>16:00</td>
                <td>Pelayanan Umum</td>
            </tr>
            <tr>
                <td>Jumat</td>
                <td>08:00</td>
                <td>14:00</td>
                <td>Pelayanan Setengah Hari</td>
            </tr>
            <tr>
                <td>Sabtu</td>
                <td>09:00</td>
                <td>12:00</td>
                <td>Pelayanan Terbatas</td>
            </tr>
            <tr>
                <td>Minggu</td>
                <td colspan="3">Libur</td>
            </tr>
            <br>
    <script>
        document.getElementById('transactionForm').addEventListener('submit', function(event) {
            event.preventDefault();

            const nama = document.getElementById('nama').value;
            const jumlah = document.getElementById('jumlah').value;
            const kategori = document.getElementById('kategori').value;

            if (!nama || !jumlah || !kategori) {
                alert('Semua input harus diisi!');
                return;
            }

            const tbody = document.querySelector('table tbody');
            const row = document.createElement('tr');

            row.innerHTML = `
                <td>${nama}</td>
                <td>${jumlah}</td>
                <td>${kategori}</td>
            `;

            tbody.appendChild(row);

            this.reset();
        });
    </script>

</body>
</html>
