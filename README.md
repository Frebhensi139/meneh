<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kursus Olahraga</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #777B7E;
            overflow-x: hidden;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        .header {
            background-color: #0000009c;
            color: white;
            padding: 20px;
            text-align: center;
            animation: slideIn 1s ease-out;
            text-shadow: 2px 2px 4px rgba(255, 255, 255, 0.5);
        }
        @keyframes slideIn {
            from {
                transform: translateY(-100%);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
        .container {
            padding: 20px;
            flex: 1;
        }
        .course {
            background-color: #999DA0;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            display: flex;
            align-items: center;
        }
        .course:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        .course img {
            width: 100px;
            height: 100px;
            margin-right: 20px;
        }
        .course h2 {
            color: #fffffff6;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.836);
        }
        .course p {
            color: #fffffff6;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 836);
        }
        .course .price {
            color: #4CAF50;
            font-weight: bold;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 836);
        }
        .cta {
            text-align: center;
            margin: 20px 0;
        }
        .cta button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 836s);
        }
        .cta button:hover {
            background-color: #45a049;
        }
        /* Simple Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #ffffff;
        }
        ::-webkit-scrollbar-thumb {
            background: #000000;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #777B7E;
        }
         /* Footer */
         .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1px 0;
            position:static;
            width: 100%;
            bottom: 0;
        }
        .footer a {
            color: #4CAF50;
            margin: 0 10px;
            text-decoration: none;
            transition: color 0.3s;
        }
        .footer a:hover {
            color: #45a049;
        }
        .footer .social-icons {
            margin-top: 10px;
        }
        .footer .social-icons img {
            width: 30px;
            height: 30px;
            margin: 0 5px;
            transition: transform 0.3s;
        }
        .footer .social-icons img:hover {
            transform: scale(1.2);
        }
    </style>
    <script>
        function navigateTo(page) {
            window.location.href = page;
        }
    </script>
</head>
<body>
    <div class="header">
        <h1>Selamat Datang di Kursus Olahraga Kami!</h1>
        <p>Tingkatkan kesehatan dan kebugaran Anda bersama kami.</p>
    </div>
    <div class="container">
        <div class="course" onclick="navigateTo('Yoga_Untuk_Pemula.html')">
            <img src="https://cdn.pixabay.com/photo/2017/07/17/15/41/silhouette-2512805_1280.jpg" alt="Yoga">
            <div>
                <h2>Yoga untuk Pemula</h2>
                <p>Pelajari dasar-dasar yoga dan tingkatkan fleksibilitas serta keseimbangan Anda.</p>
                <p class="price">Harga: Rp 500.000</p>
            </div>
        </div>
        <div class="course" onclick="navigateTo('Latihan_Kekuatan.html')">
            <img src="https://cdn.pixabay.com/photo/2016/11/29/09/10/man-1868632_960_720.jpg" alt="Latihan Kekuatan">
            <div>
                <h2>Latihan Kekuatan</h2>
                <p>Program latihan kekuatan untuk membangun otot dan meningkatkan kekuatan tubuh.</p>
                <p class="price">Harga: Rp 600.000</p>
            </div>
        </div>
        <div class="course" onclick="navigateTo('Cardio_Intensif.html')">
            <img src="https://media.istockphoto.com/id/482767585/id/foto/berjalan-di-treadmill.webp?s=1024x1024&w=is&k=20&c=YPZm3uN8eqMz1o-rONIrEZJGE7O1V24SDIQOuQbUsUw=" alt="Cardio Intensif">
            <div>
                <h2>Cardio Intensif</h2>
                <p>Latihan kardio intensif untuk membakar kalori dan meningkatkan stamina.</p>
                <p class="price">Harga: Rp 550.000</p>
            </div>
        </div>
        <div class="cta">
            <button onclick="navigateTo('Daftar.html')">Daftar Sekarang</button>
        </div>
    </div>
    <div class="footer">
        <p>Ikuti kami di media sosial:</p>
        <div class="social-icons">
        <a href="https://www.facebook.com/share/8sUVX6eJDBaYSwfy/?mibextid=qi2Omg"><img src="https://cdn.pixabay.com/photo/2017/06/22/06/22/facebook-2429746_1280.png" alt="Facebook"></a>
        <a href="https://www.tiktok.com/@_sabat.2_sola?is_from_webapp=1&sender_device=pc"><img src="https://cdn.pixabay.com/photo/2021/06/15/12/28/tiktok-6338429_960_720.png" alt="Tiktok"></a>
        <a href="https://www.instagram.com/n_sabat.sn?igsh=cTIvb3MOazRjMzN5"><img src="https://cdn.pixabay.com/photo/2022/04/01/05/40/app-7104075_1280.png" alt="Instagram"></a>
        </div>
    </div>
</body>
</html>
    
