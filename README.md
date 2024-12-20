<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beranda - SantapanNUSA</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* General styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Roboto Slab', serif;
        }

        body {
            color: #333;
            background-image: url('background art.jpg'); /* Ganti dengan URL gambar latar belakang Anda */
            background-size: cover; /* Membuat gambar menutupi seluruh halaman */
            background-position: center center; /* Menyelaraskan gambar ke tengah */
            padding: 20px;
        }

        /* Header */
        header {
            background: rgba(76, 175, 80, 0.8); /* Menambahkan latar belakang transparan agar teks lebih jelas */
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            font-size: 2.5rem;
        }

        /* Navigation */
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }

        /* Main Content */
        main {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        main h2 {
            font-size: 2.5rem;
            color: #4CAF50;
            margin-bottom: 20px;
        }

        main p {
            font-size: 1.2rem;
            line-height: 1.8;
            color: #555;
            margin-bottom: 20px;
        }

        /* Back Button */
        .back-btn {
            display: block;
            margin: 30px auto;
            padding: 10px 30px;
            background: #4CAF50;
            color: white;
            text-decoration: none;
            text-align: center;
            border-radius: 8px;
            width: fit-content;
        }

        .back-btn:hover {
            background: #45a049;
        }

        /* Responsive Design */
        @media screen and (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            main {
                padding: 15px;
            }

            main h2 {
                font-size: 1.5rem;
            }

            main p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>SantapanNUSA</h1>
    </header>

    <nav>
        <ul>
            <li><a href="articles.html">Artikel</a></li>
            <li><a href="menu.html">Menu</a></li>
        </ul>
    </nav>

    <main>
        <h2>Selamat datang di SantapanNUSA</h2>
        <p>Selamat datang di SantapanNUSA, tempat di mana Anda bisa menikmati kelezatan makanan khas Nusantara yang tak tertandingi! Indonesia, dengan keberagaman budaya dan tradisinya, menawarkan berbagai sajian yang kaya akan cita rasa. Setiap daerah di Nusantara memiliki hidangan khas yang tak hanya menggugah selera, tetapi juga membawa cerita dan sejarah yang mendalam. Ayo, mari kita bersama-sama menjelajahi kekayaan kuliner Indonesia! Mulai dari rendang yang terkenal dari Sumatera Barat, sate yang menggoda selera dari Madura, hingga nasi goreng yang telah menjadi ikon kuliner nasional. Di SantapanNUSA, kami ingin mengenalkan Anda pada berbagai makanan ikonik dari seluruh penjuru negeri, yang tidak hanya lezat tetapi juga penuh makna dan tradisi.</p>
        <p>Klik menu di atas untuk menemukan berbagai hidangan khas Nusantara yang pasti akan membuat Anda jatuh cinta pada rasa, budaya, dan keindahan kuliner Indonesia!</p>
        <a href="index.html" class="back-btn"></a>
    </main>

</body>
</html>
