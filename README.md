# Sistem_spt_parkir
<html lang="id">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard - SPT Parkir</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            padding-top: 50px;
            background-color: #f4f4f9;
            margin: 0;
        }

        .dashboard-box {
            background-color: #fff;
            padding: 30px 40px;
            display: inline-block;
            border-radius: 12px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .dashboard-box:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
        }

        h1 {
            color: #4CAF50;
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2em;
            color: #333;
            margin-bottom: 30px;
        }

        .menu-link {
            display: inline-block;
            text-decoration: none;
            color: white;
            background-color: #4CAF50;
            padding: 15px 30px;
            border-radius: 8px;
            font-size: 1.1em;
            width: 250px;
            margin: 10px 0;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        .menu-link:hover {
            background-color: #45a049;
            transform: scale(1.1);
        }

        .menu-link:active {
            transform: scale(0.95);
        }

        /* Animasi untuk menu */
        .menu-link:before {
            content: "👉 ";
            padding-right: 10px;
        }

        /* Responsif */
        @media (max-width: 600px) {
            .dashboard-box {
                width: 90%;
                padding: 20px;
            }

            .menu-link {
                width: 100%;
                font-size: 1em;
                padding: 12px;
            }
        }
    </style>
</head>

<body>

    <div class="dashboard-box">
        <h1>Selamat Datang di Dashboard SPT Parkir</h1>
        <p>Silakan pilih menu di bawah untuk mengelola data parkir Anda.</p>

        <a href="table.html" class="menu-link">📊 Lihat Data Pembayaran Zona 6</a>
    </div>

</body>

</html>
