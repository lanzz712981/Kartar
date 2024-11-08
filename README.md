<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kartar VBT</title>
    <style>
        /* Global Styles */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        body {
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f9;
        }
        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header Styles */
        header {
            background: linear-gradient(135deg, #4CAF50, #388E3C);
            color: #fff;
            padding: 40px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        /* Navigation Styles */
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            margin: 0 10px;
            font-weight: bold;
            border-radius: 5px;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #4CAF50;
        }

        /* Section Styling */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            padding: 40px 0;
        }
        .section-title {
            font-size: 2em;
            color: #4CAF50;
            margin-bottom: 20px;
            text-align: center;
        }
        section {
            margin-bottom: 40px;
        }
        .section-content {
            text-align: center;
            font-size: 1.1em;
            color: #555;
        }

        /* Card Styles for News & Activities */
        .card {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
        }
        .card-item {
            background: white;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            max-width: 280px;
            text-align: left;
        }
        .card-item h3 {
            font-size: 1.2em;
            color: #333;
            margin-bottom: 10px;
        }
        .card-item p {
            color: #666;
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            font-size: 0.9em;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav a {
                padding: 10px 15px;
            }
            .card {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Karang Taruna VBT</h1>
        <p>Bergerak Bersama untuk Masa Depan yang Lebih Baik</p>
    </header>

    <!-- Navigation Menu -->
    <nav>
        <a href="#home">Beranda</a>
        <a href="#tentang">Tentang Kami</a>
        <a href="#kegiatan">Kegiatan</a>
        <a href="#berita">Berita</a>
    </nav>

    <!-- Main Content -->
    <div class="container">
        <!-- Home Section -->
        <section id="home">
            <div class="section-title">Selamat Datang di Karang Taruna VBT</div>
            <div class="section-content">
                <p>Karang Taruna VBT adalah organisasi pemuda yang berfokus pada pemberdayaan dan pengembangan masyarakat melalui berbagai kegiatan sosial, edukasi, dan lingkungan.</p>
            </div>
        </section>

        <!-- About Section -->
        <section id="tentang">
            <div class="section-title">Tentang Kami</div>
            <div class="section-content">
                <p>Karang Taruna VBT berdiri dengan misi untuk menciptakan pemuda yang aktif, kreatif, dan berdaya saing dalam membangun desa. Kami bekerja sama untuk mewujudkan desa yang sejahtera, mandiri, dan berkelanjutan.</p>
            </div>
        </section>

        <!-- Activities Section -->
        <section id="kegiatan">
            <div class="section-title">Kegiatan Kami</div>
            <div class="card">
                <div class="card-item">
                    <h3>Kerja Bakti Lingkungan</h3>
                    <p>Bersama-sama menjaga kebersihan dan keindahan lingkungan desa.</p>
                </div>
                <div class="card-item">
                    <h3>Pelatihan Keterampilan</h3>
                    <p>Meningkatkan keterampilan pemuda .</p>
                </div>
            </div>
        </section>

        <!-- News Section -->
        <section id="berita">
            <div class="section-title">Berita Terbaru</div>
            <div class="card">
                <div class="card-item">
                    <h3>Lomba-lomba sumpah pemuda</h3>
                    <p>Lomba-lomba untuk memeriah Hari sumpah pemuda pada 28 oktober & 2 november.</p>
                </div>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Karang Taruna Desa . Semua hak dilindungi undang-undang.</p>
    </footer>

</body>
</html>
