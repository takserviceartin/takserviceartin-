doctype html

<!--
**takserviceartin/takserviceartin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
عالی! 😎
من برات قالب سایت HTML/CSS کامل و آماده برای GitHub Pages با آدرس، شماره تماس و خدماتت آماده کردم. فقط کافیه فایل را دانلود و آپلود کنی.


---

قالب آماده سایت (فارسی، واکنش‌گرا)

<!doctype html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Tak Service Artin — خدمات فنی</title>
  <style>
    :root{--accent:#0b74de}
    *{box-sizing:border-box}
    body{margin:0;font-family:Tahoma,Arial;background:#f6f7fb;color:#222;line-height:1.6}
    header{background:linear-gradient(90deg,#0b74de22,#0000);padding:28px 16px}
    .container{max-width:1000px;margin:0 auto;padding:0 16px}
    .brand{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand h1{margin:0;font-size:20px;color:var(--accent)}
    nav a{margin-left:12px;text-decoration:none;color:#333;font-weight:600}
    .hero{display:flex;flex-wrap:wrap;gap:18px;align-items:center;padding:36px 0}
    .hero .text{flex:1 1 320px}
    .hero h2{margin:0 0 8px;font-size:28px}
    .hero p{margin:0 0 14px;color:#555}
    .cta{display:inline-block;padding:10px 16px;border-radius:10px;background:var(--accent);color:#fff;text-decoration:none;font-weight:700}
    .card-row{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin:26px 0}
    .card{background:#fff;padding:14px;border-radius:12px;box-shadow:0 6px 18px rgba(12,18,24,0.06)}
    footer{padding:18px 0;color:#666;font-size:13px}
    .contact{margin-top:12px}
    img.res{max-width:100%;height:auto;border-radius:10px}
    @media(min-width:900px){ .hero{gap:40px} .hero h2{font-size:34px} }
  </style>
</head>
<body>
  <header>
    <div class="container brand">
      <h1>Tak Service Artin</h1>
      <nav>
        <a href="#home">خانه</a>
        <a href="#services">خدمات</a>
        <a href="#contact">تماس</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero" id="home">
      <div class="text">
        <h2>نصب و تعمیر انواع لوازم خانگی</h2>
        <p>خدمات حرفه‌ای نصب و تعمیر انواع اجاق گاز، هود، فر توکار، مایکروویو، جاروبرقی و آبگرمکن. با تجربه و تخصص در خدمت شما هستیم.</p>
        <a class="cta" href="#contact">تماس بگیرید</a>
        <div class="contact">📞 ۰۹۱۹۴۶۷۵۹۲۱ — نعمت‌زاده</div>
      </div>
      <div class="media">
        <img class="res" src="https://via.placeholder.com/560x360?text=تصویر+نمونه" alt="نمونه تصویر">
      </div>
    </section>

    <section id="services">
      <div class="card-row">
        <div class="card">
          <h3>اجاق گاز</h3>
          <p>نصب و تعمیر انواع اجاق گاز خانگی</p>
        </div>
        <div class="card">
          <h3>هود</h3>
          <p>نصب و تعمیر انواع هود آشپزخانه</p>
        </div>
        <div class="card">
          <h3>فرهای توکار</h3>
          <p>نصب و تعمیر فرهای توکار با کیفیت</p>
        </div>
        <div class="card">
          <h3>مایکروویو</h3>
          <p>تعمیر انواع مایکروویو خانگی</p>
        </div>
        <div class="card">
          <h3>جاروبرقی</h3>
          <p>تعمیر و سرویس انواع جاروبرقی</p>
        </div>
        <div class="card">
          <h3>آبگرمکن</h3>
          <p>نصب و تعمیر آبگرمکن‌های خانگی</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="card">
        <h3>تماس با ما</h3>
        <p>نشانی: تهرانپارس فلکه اول، خیابان رمضانی، نبش کیخسروی</p>
        <p>تلفن: ۰۹۱۹۴۶۷۵۹۲۱</p>
        <p>ایمیل: example@domain.com</p>
      </div>
    </section>
  </main>

  <footer class="container">
    © تمام حقوق برای «Tak Service Artin» محفوظ است.
