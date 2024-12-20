
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Materi belajar fungsi linier untuk kelas 8. Pelajari konsep dasar fungsi linier dengan contoh dan latihan.">
    <meta name="keywords" content="fungsi linier, matematika, kelas 8, belajar, contoh soal, latihan">
    <title>Fungsi Linier Kelas 8</title>
    <style>
        /* Global styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
        }

        header {
            background: linear-gradient(90deg, #4a90e2, #003366);
            padding: 1rem 0;
            color: white;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 1rem;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 1rem;
        }

        .nav-links li {
            position: relative;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-size: 1rem;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: #ffdd57;
        }

        .burger {
            display: none;
            cursor: pointer;
            flex-direction: column;
            gap: 0.3rem;
        }

        .burger div {
            width: 25px;
            height: 3px;
            background: white;
            transition: all 0.3s;
        }

        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .home {
            text-align: justify;
            padding: 2rem 0;
        }

        .content {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .home h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .home p {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        footer {
            background: #4a90e2;
            color: white;
            text-align: center;
            padding: 0.5rem 0;
            position: relative;
            width: 100%;
            bottom: 0;
        }

        @media (max-width: 768px) {
            /* Adjust navigation for mobile */
            nav {
                flex-direction: column;
                align-items: flex-start;
                padding: 0.5rem;
            }

            .nav-links {
                display: none;
                flex-direction: column;
                background: #4a90e2;
                position: absolute;
                top: 60px;
                right: 0;
                width: 100%;
                padding: 1rem;
            }

            .nav-links.active {
                display: flex;
            }

            .burger {
                display: flex;
            }

            .burger.toggle .line1 {
                transform: rotate(-45deg) translate(-5px, 6px);
            }

            .burger.toggle .line2 {
                opacity: 0;
            }

            .burger.toggle .line3 {
                transform: rotate(45deg) translate(-5px, -6px);
            }

            .home h1 {
                font-size: 2rem;
            }

            .home p {
                font-size: 1rem;
            }

            .container {
                padding: 0 0.5rem;
            }
        }

        @media (max-width: 480px) {
            .home h1 {
                font-size: 1.8rem;
            }

            .home p {
                font-size: 0.9rem;
            }

            nav {
                flex-direction: column;
                align-items: flex-start;
                padding: 0.5rem;
            }

            .burger {
                margin-left: auto;
            }

            .nav-links {
                flex-direction: column;
                align-items: flex-start;
                padding-left: 1rem;
                width: 100%;
            }

            .container {
                padding: 0 0.5rem;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>

<body>

    <!-- Header with Navigation -->
    <header>
        <nav>
            <div class="logo">Fungsi Linier Kelas 8</div>
            <ul class="nav-links">
                <li><a href="beranda 2.html"><i class="fas fa-home"></i> Beranda2</a></li>
                <li><a href="materi.html"><i class="fas fa-book"></i> Materi</a></li>
                <li><a href="contoh soal.html"><i class="fas fa-pencil-alt"></i> Contoh Soal</a></li>
                <li><a href="latihan soal.html"><i class="fas fa-edit"></i> Latihan Soal</a></li>
                <li><a href="geogebra.html"><i class="fas fa-edit"></i> Geogebra</a></li>
                <li><a href="kuis.html"><i class="fas fa-question-circle"></i> Kuis</a></li>
                <li><a href="kontak.html"><i class="fas fa-envelope"></i> Kontak</a></li>
            </ul>
            <div class="burger">
                <div class="line1"></div>
                <div class="line2"></div>
                <div class="line3"></div>
            </div>
        </nav>
    </header>

    <!-- Main Content Section -->
    <main>
        <section class="home">
            <div class="container content">
                <div class="bg-image">
                    <img src="fkip1.jpg" alt="Mathematics Image">
                </div>
                <header>
                    <h1>Pembelajaran Fungsi Linier Kelas 8 SMP</h1>
                </header>
                <section id="pengantar">
                    <div class="line"></div>
                    <h2>Pengantar Fungsi Linear</h2>
                    <div class="Pengertian">
                        <p>Fungsi linear adalah suatu jenis fungsi matematis yang menggambarkan hubungan antara dua variabel, yaitu variabel independen (sering disebut 𝑥) dan variabel dependen (sering disebut 𝑦).</p>
                    </div>
                </section>
            </div>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Fungsi Linier Kelas 8. M.Taqqiudin.</p>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const burger = document.querySelector('.burger');
            const navLinks = document.querySelector('.nav-links');

            burger.addEventListener('click', () => {
                navLinks.classList.toggle('active');
                burger.classList.toggle('toggle');
            });

            navLinks.addEventListener('click', (event) => {
                if (event.target.tagName === 'A') {
                    navLinks.classList.remove('active');
                    burger.classList.remove('toggle');
                }
            });
        });
    </script>

</body>

</html>
