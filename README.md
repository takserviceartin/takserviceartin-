📄 فایل: Inbox.html

📄 فایل: index.html

<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tak Service Artin</title>
    <style>
        /* Reset ساده */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Tahoma', sans-serif;
            background-color: #f2f2f2; /* خاکستری روشن */
            color: #000;
            line-height: 1.6;
        }

        header {
            background-color: #336699; /* سورمه‌ای روشن */
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: relative;
        }

        header h1 {
            font-family: 'Nastaliq', cursive; /* فونت نستعلیق */
            font-size: 36px;
            color: #fff; /* سفید */
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            text-decoration: none;
            color: #ffffff; /* سفید */
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffdd00; /* طلایی/زرد برای هاور */
        }

        section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: auto;
        }

        h2 {
            color: #003366;
            margin-bottom: 20px;
            font-size: 28px;
        }

        .about, .services, .contact {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .services ul {
            list-style-type: disc;
            margin-left: 20px;
        }

        .button {
            display: inline-block;
            background-color: #003366; /* سورمه‌ای */
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }

        .button:hover {
            background-color: #0055a5;
        }

        footer {
            background-color: #003366; /* سورمه‌ای */
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        /* دو زبانه */
        .lang-toggle {
            position: absolute;
            top: 20px;
            right: 20px;
        }

        .lang-toggle button {
            background-color: #003366;
            color: #fff;
            border: none;
            padding: 5px 10px;
            margin-left: 5px;
            cursor: pointer;
            border-radius: 3px;
        }

        .lang-toggle button:hover {
            background-color: #0055a5;
        }
    </style>
</head>
<body>

<header>
    <div class="lang-toggle">
        <button onclick="switchLang('fa')">فارسی</button>
        <button onclick="switchLang('en')">EN</button>
    </div>
    <h1>Tak Service Artin</h1>
    <nav>
        <a href="#about">درباره ما</a>
        <a href="#services">خدمات</a>
        <a href="#contact">تماس با ما</a>
    </nav>
</header>

<section id="about" class="about">
    <h2>درباره ما</h2>
    <p>
        Tak Service Artin با کادری مجرب و متعهد آماده ارائه خدمات نصب و تعمیر تمامی لوازم خانگی است.
        تمامی خدمات با استفاده از قطعات اصلی و با نازل‌ترین قیمت ارائه می‌شود و فاکتور رسمی شرکت صادر می‌گردد.
        محدوده فعالیت: شرق و شمال شرق، جنوب شرق، شهرری.
        نمایندگی شرکت‌ها: اخوان، کن، داتیس، استیل البرز، T&D، بیمکث.
    </p>
</section>

<section id="services" class="services">
    <h2>خدمات ما</h2>
    <ul>
        <li>نصب و تعمیر اجاق گاز و هود</li>
        <li>نصب و تعمیر یخچال و فریزر</li>
        <li>نصب و تعمیر ماشین لباسشویی و ظرفشویی</li>
        <li>نصب و تعمیر جاروبرقی و ماکروویو</li>
        <li>خدمات تعمیر با قطعات اصلی و فاکتور رسمی</li>
    </ul>
</section>

<section id="contact" class="contact">
    <h2>تماس با ما</h2>
    <p>شماره تماس: 09194675921 - 09364707854 (نعمت‌زاده)</p>
    <p>آدرس: تهرانپارس، نمایندگی شرکت‌های معتبر</p>
    <a href="tel:09194675921" class="button">تماس سریع</a>
</section>

<footer>
    &copy; 2025 Tak Service Artin | تمامی حقوق محفوظ است
</footer>

<script>
    function switchLang(lang) {
        if(lang === 'fa') {
            alert('نسخه فارسی فعال شد');
        } else {
            alert('English version activated');
        }
    }
</script>

</body>
</html>
