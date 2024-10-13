<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Helmy Purnomo Hidayat</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <!-- Font Awesome untuk ikon -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #2b2b2b; /* Warna dark grey */
            color: #f1c40f; /* Warna gold */
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
            display: grid;
            grid-template-columns: 1fr 3fr;
            gap: 20px;
            background-color: #333333;
            border-radius: 15px;
            box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.2);
        }

        /* Animasi muncul dari bawah */
        .animate-up {
            animation: slideUp 1.2s ease-out;
        }

        @keyframes slideUp {
            from {
                transform: translateY(100px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        /* Profil Header */
        .profile-header {
            background-color: #1a1a1a;
            color: #f1c40f; /* Gold */
            text-align: center;
            padding: 50px 20px;
            border-radius: 10px;
            position: relative;
        }

        .profile-header h1 {
            font-size: 2.5rem;
            margin-top: 30px;
        }

        .profile-header h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
        }

        .profile-header img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            position: absolute;
            top: -50px;
            left: calc(50% - 60px);
            border: 4px solid #f1c40f; /* Border gold */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }

        /* Side Bar */
        .side-bar {
            background-color: #1a1a1a;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }

        .side-bar h2 {
            font-size: 1.2rem;
            color: #f1c40f;
            margin-bottom: 15px;
        }

        .skills ul, .education ul {
            list-style-type: none;
            padding-left: 0;
        }

        .skills ul li, .education ul li {
            margin-bottom: 10px;
            font-size: 0.9rem;
        }

        .contact-info p {
            font-size: 0.9rem;
            margin-bottom: 10px;
        }

        .contact-info a {
            color: #f1c40f;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .contact-info i {
            margin-right: 10px;
            color: #f1c40f;
        }

        /* Main Content */
        .main-content {
            background-color: #1a1a1a;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
        }

        .main-content h2 {
            color: #f1c40f;
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        .project-card {
            background-color: #444444;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
        }

        .project-card h5 {
            font-size: 1.2rem;
            margin-bottom: 10px;
        }

        .project-card p {
            font-size: 0.9rem;
            line-height: 1.4;
        }

        footer {
            background-color: #1a1a1a;
            color: #f1c40f;
            text-align: center;
            padding: 10px 0;
            margin-top: 40px;
            border-radius: 10px;
        }

        footer p {
            margin: 0;
        }

        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
            }
        }

        /* Link hover efek */
        .social-icons a {
            color: #f1c40f;
            font-size: 1.5rem;
            margin-right: 15px;
        }

        .social-icons a:hover {
            color: #ffeb3b;
        }
    </style>
</head>
<body>

    <div class="container animate-up">
        <!-- Side Bar -->
        <div class="side-bar">
            <div class="profile-header">
                <img src="foto.jpeg" alt="Profil Helmy">
                <h1>Helmy Purnomo Hidayat</h1>
                <h3>Informatic Engineering </h3>
                <p>Email: <a href="mailto:helmypurnomo234@gmail.com">helmypurnomo234@gmail.com</a></p>
                <p>Telepon: <a href="tel:+6285713833954">085713833954</a></p>
                <p>Lokasi: Sragen, Jawa Tengah</p>
                <div class="social-icons">
                    <a href="https://www.linkedin.com/in/HelmyPurnomoHidayat" target="_blank"><i class="fab fa-linkedin"></i></a>
                    <a href="https://www.instagram.com/iam_myph" target="_blank"><i class="fab fa-instagram"></i></a>
                    <a href="https://github.com/HelmyPurnomoHidayat22" target="_blank"><i class="fab fa-github"></i></a>
                </div>
            </div>

            <div class="skills">
                <h2>Keahlian Saya</h2>
                <ul>
                    <li>Adobe Photoshop, Lightroom, Canva</li>
                    <li>Adobe Premiere Pro, Final Cut Pro</li>
                    <li>Python, HTML, CSS,Java,Php</li>
                    <li>Kerja Tim, Komunikasi Efektif</li>
                </ul>
            </div>

            <div class="education">
                <h2>Pendidikan</h2>
                <ul>
                    <li>S1 Teknik Informatika - Universitas Muhammadiyah Surakarta (2020 - sekarang, IPK: 3.58)</li>
                </ul>
            </div>
        </div>

        <!-- Main Content -->
        <div class="main-content">
            <section>
                <h2>Informasi Pribadi</h2>
                <p>Saya mahasiswa Teknik Informatika semester IV dengan keahlian dalam desain grafis dan editing video. Saya memiliki pengalaman menggunakan Adobe Photoshop, Premiere Pro, serta mampu berkomunikasi dan bekerja sama dengan baik dalam tim. Saya sangat bersemangat untuk membantu bisnis dengan konten visual yang kreatif dan efektif.</p>
            </section>

            <!-- Sorotan Proyek -->
            <section>
                <h2>Proyek</h2>
                <div class="project-card">
                    <h5>Videografi dan Editing Video (2022)</h5>
                    <p>Membuat video berjudul <strong>4K CINEMATIC VIDEO (copyright inspiring cinematic)</strong> menggunakan Adobe Premiere Pro dan CapCut di channel YouTube HelmyPurnomoHidayat.</p>
                </div>

                <div class="project-card">
                    <h5>Pembuatan Website Sederhana (2024)</h5>
                    <p>Mengerjakan proyek akhir membuat website sederhana menggunakan PHP dan CSS untuk keperluan penilaian akhir mata kuliah di universitas.</p>
                </div>
            </section>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Helmy Purnomo Hidayat</p>
    </footer>

    <!-- Bootstrap JS dan jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
