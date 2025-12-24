<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الخـفـاجي - الصفحة الرئيسية</title>
    <meta name="description" content="موقع الخفاجي - منصة لنشر المقالات والمحتوى الفخم.">
    <style>
        /* إعدادات عامة */
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #000000, #4b0000); /* أسود + أحمر غامق */
            color: #ffd700; /* ذهبي */
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: #ffd700; /* ذهبي */
        }

        a:hover {
            color: #ffdd57;
        }

        /* الرأس */
        header {
            background: linear-gradient(90deg, #220000, #550000);
            padding: 20px 0;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 90%;
            margin: 0 auto;
        }

        header h1 {
            font-size: 2.5em;
            color: #ffd700;
            font-weight: bold;
        }

        /* تأثير متحرك للاسم */
        .animated-logo {
            display: inline-block;
            animation: bounce 2s infinite alternate;
        }

        @keyframes bounce {
            0% { transform: translateY(0); color: #ffd700; }
            50% { transform: translateY(-10px); color: #ffdd57; }
            100% { transform: translateY(0); color: #ffd700; }
        }

        /* قائمة التنقل */
        header nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
            font-weight: bold;
            font-size: 1.1em;
        }

        /* قسم الترحيب */
        .hero {
            background: linear-gradient(135deg, #1a0000, #330000);
            text-align: center;
            padding: 120px 20px;
            border-bottom-left-radius: 50px;
            border-bottom-right-radius: 50px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.5);
        }

        .hero h2 {
            font-size: 2.8em;
        }

        .hero p {
            font-size: 1.3em;
        }

        /* قسم الميزات */
        .features {
            display: flex;
            gap: 20px;
            justify-content: space-around;
            padding: 60px 20px;
            flex-wrap: wrap;
        }

        .feature {
            background: rgba(255, 215, 0, 0.05);
            padding: 25px;
            border-radius: 15px;
            flex: 1 1 250px;
            text-align: center;
            transition: transform 0.3s, background 0.3s;
            border: 1px solid rgba(255, 215, 0, 0.2);
        }

        .feature:hover {
            transform: translateY(-10px);
            background: rgba(255, 215, 0, 0.1);
        }

        /* تذييل الصفحة */
        footer {
            text-align: center;
            padding: 25px;
            background: #220000;
            font-size: 0.9em;
            color: #ffd700;
        }

        /* استجابة الهواتف */
        @media (max-width: 768px) {
            .features {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1 class="animated-logo">الخـفـاجي</h1>
            <nav>
                <ul>
                    <li><a href="index.html">الرئيسية</a></li>
                    <li><a href="articles.html">المقالات</a></li>
                    <li><a href="about.html">عن الموقع</a></li>
                    <li><a href="contact.html">تواصل معنا</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h2>مرحبًا بك في موقع الخـفـاجي</h2>
            <p>منصة فخمة لنشر مقالاتك ومحتواك المميز.</p>
        </div>
    </section>

    <section class="features container">
        <div class="feature">
            <h3>مقالات مميزة</h3>
            <p>أضف مقالاتك بسهولة وشارك محتواك مع العالم.</p>
        </div>
        <div class="feature">
            <h3>تصميم فخم</h3>
            <p>واجهة جذابة وألوان متناسقة تبرز المحتوى بشكل جميل.</p>
        </div>
        <div class="feature">
            <h3>توافق مع جميع الأجهزة</h3>
            <p>الموقع متجاوب ويعمل بشكل ممتاز على الهواتف والحواسيب.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 الخـفـاجي. جميع الحقوق محفوظة.</p>
    </footer>
</body>
</html>
