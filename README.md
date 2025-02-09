<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>إنكيد - استوديو الألعاب العراقي المستقل</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #ffd700;
            text-align: center;
            direction: rtl;
        }
        .header {
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #111;
            box-shadow: 0px 4px 10px rgba(255, 215, 0, 0.3);
        }
        .header img {
            width: 150px;
            max-width: 100%;
            height: auto;
        }
        .about {
            padding: 50px 5%;
            background: url('gaming-background.jpg') no-repeat center center/cover;
            color: #fff;
        }
        .about h1, .about p {
            background: rgba(0, 0, 0, 0.7);
            display: inline-block;
            padding: 10px;
            border-radius: 5px;
        }
        .games {
            padding: 50px 5%;
            background-color: #222;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .game {
            flex: 1 1 300px;
            max-width: 320px;
            padding: 20px;
            background-color: #333;
            border-radius: 10px;
            text-align: center;
        }
        .game img {
            width: 100%;
            border-radius: 5px;
        }
        .footer {
            padding: 20px;
            background-color: #111;
            font-size: 0.9em;
        }
        .footer a {
            color: #ffd700;
            text-decoration: none;
            margin: 0 10px;
        }
        @media (max-width: 768px) {
            .about {
                padding: 30px 5%;
            }
            .games {
                flex-direction: column;
                align-items: center;
            }
            .game {
                width: 90%;
            }
        }
        @media (max-width: 480px) {
            .header img {
                width: 120px;
            }
            .about, .games, .footer {
                padding: 20px 5%;
            }
            .game {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="Logo.png" alt="شعار إنكيد">
    </div>
    <div class="about">
        <h1>من نحن</h1>
        <p>إنكيد هو استوديو ألعاب عراقي مستقل مكرس لإنشاء تجارب ألعاب فريدة وغامرة.</p>
    </div>
    <div class="games">
        <h2>ألعابنا</h2>
        <div class="game">
            <img src="High.jpg" alt="اللعبة 1">
            <p>HIGH - مغامرة مثيرة عبر عالم غامض.</p>
        </div>
        <div class="game">
            <img src="Risk.jpg" alt="اللعبة 2">
            <p>RISK - انطلق في مغامرة لكش اسرار الغاباة المضلمة</p>
        </div>
        <div class="game">
            <img src="Dark.jpg" alt="اللعبة 3">
            <p>Dark&Night - انطلق في مغامرة جميلة و مليئة بالغموض و الاثارة</p>
        </div>
    </div>
    <div class="footer">
        <h2>تواصل معنا</h2>
        <p>تابعونا على:</p>
        <a href="#">إنستغرام</a> |
        <a href="#">تيليغرام</a> |
        <a href="mailto:contact@enkidestudio.com">راسلنا عبر البريد الإلكتروني</a>
        <p>&copy; 2025 استوديو إنكيد للألعاب. جميع الحقوق محفوظة.</p>
    </div>
</body>
</html>
