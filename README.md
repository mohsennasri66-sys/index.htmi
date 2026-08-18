<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mohsen Nasri | Industrial Engineering</title>
  <style>
    :root{
      --bg:#0f172a;
      --card:#111827;
      --text:#e5e7eb;
      --muted:#9ca3af;
      --accent:#22c55e;
      --line:rgba(255,255,255,.08);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:Arial, sans-serif;
      background:linear-gradient(180deg,#0b1220,#111827 45%,#0f172a);
      color:var(--text);
      line-height:1.7;
    }
    a{color:inherit;text-decoration:none}
    .container{max-width:1200px;margin:auto;padding:24px}
    header{
      background:rgba(255,255,255,.03);
      border-bottom:1px solid var(--line);
      position:sticky;
      top:0;
      backdrop-filter:blur(10px);
      z-index:10;
    }
    .nav{
      display:flex;
      gap:16px;
      flex-wrap:wrap;
      justify-content:space-between;
      align-items:center;
    }
    .brand{font-weight:700;font-size:1.1rem}
    .menu{display:flex;gap:14px;flex-wrap:wrap;color:var(--muted)}
    .hero{
      padding:56px 0 24px;
      display:grid;
      grid-template-columns:1.2fr .8fr;
      gap:24px;
      align-items:center;
    }
    .hero-card{
      background:rgba(255,255,255,.04);
      border:1px solid var(--line);
      border-radius:20px;
      padding:28px;
    }
    .hero h1{margin:0 0 12px;font-size:2.3rem}
    .hero p{color:var(--muted);margin:0 0 18px}
    .btn{
      display:inline-block;
      background:var(--accent);
      color:#04110a;
      padding:12px 18px;
      border-radius:12px;
      font-weight:700;
      margin-left:10px;
      margin-top:8px;
    }
    .btn.secondary{background:transparent;color:var(--text);border:1px solid var(--line)}
    .hero-img{
      width:100%;
      max-height:360px;
      object-fit:cover;
      border-radius:20px;
      border:1px solid var(--line);
    }
    section{padding:24px 0}
    h2{margin:0 0 18px;font-size:1.6rem}
    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
      gap:18px;
    }
    .card{
      background:rgba(255,255,255,.04);
      border:1px solid var(--line);
      border-radius:18px;
      overflow:hidden;
    }
    .card img{
      width:100%;
      height:180px;
      object-fit:cover;
      display:block;
    }
    .card-body{padding:16px}
    .card h3{margin:0 0 8px}
    .card p{margin:0;color:var(--muted)}
    .list{
      background:rgba(255,255,255,.04);
      border:1px solid var(--line);
      border-radius:18px;
      padding:20px;
    }
    .list ul{margin:0;padding-right:18px;color:var(--muted)}
    footer{
      border-top:1px solid var(--line);
      margin-top:24px;
      padding:20px 0 34px;
      color:var(--muted);
      text-align:center;
    }
    @media (max-width: 800px){
      .hero{grid-template-columns:1fr}
      .hero h1{font-size:1.8rem}
    }
  </style>
</head>
<body>

<header>
  <div class="container nav">
    <div class="brand">Mohsen Nasri | Industrial Engineering</div>
    <nav class="menu">
      <a href="#about">درباره</a>
      <a href="#industries">صنایع</a>
      <a href="#services">خدمات</a>
      <a href="#contact">تماس</a>
    </nav>
  </div>
</header>

<main class="container">
  <section class="hero">
    <div class="hero-card">
      <h1>خوش آمدید</h1>
      <p>
        این سایت برای معرفی تجربه‌ها، پروژه‌ها و محتواهای صنعتی شما طراحی شده
        و می‌توانی برای هر صنعت، مطالب و تصاویر جدید اضافه کنی.
      </p>
      <a class="btn" href="#industries">دیدن صنایع</a>
      <a class="btn secondary" href="#contact">تماس</a>
    </div>
    <img class="hero-img" src="images/hero.jpg" alt="Industrial engineering" />
  </section>

  <section id="about">
    <h2>درباره من</h2>
    <div class="list">
      <p>
        این بخش را برای معرفی سابقه کاری، مهارت‌ها، پروژه‌ها و حوزه تخصصی خودت استفاده کن.
        متن قبلی هم می‌تواند اینجا نگه داشته شود و به‌روزرسانی شود.
      </p>
      <ul>
        <li>مهندسی صنعتی</li>
        <li>اتوماسیون و بهینه‌سازی</li>
        <li>مستندسازی فنی</li>
        <li>تحلیل داده و گزارش‌نویسی</li>
      </ul>
    </div>
  </section>

  <section id="industries">
    <h2>۵ صنعت قابل ویرایش</h2>
    <div class="grid">
      <article class="card">
        <img src="images/industry1.jpg" alt="Industry 1" />
        <div class="card-body">
          <h3>صنعت ۱</h3>
          <p>اینجا می‌توانی متن، پروژه، عکس و توضیحات مربوط به این صنعت را بنویسی.</p>
        </div>
      </article>

      <article class="card">
        <img src="images/industry2.jpg" alt="Industry 2" />
        <div class="card-body">
          <h3>صنعت ۲</h3>
          <p>برای معرفی محصولات، خدمات یا تجربه‌های فنی این صنعت استفاده کن.</p>
        </div>
      </article>

      <article class="card">
        <img src="images/industry3.jpg" alt="Industry 3" />
        <div class="card-body">
          <h3>صنعت ۳</h3>
          <p>می‌توانی نمونه‌کار، توضیح خط تولید یا عکس تجهیزات را اینجا بگذاری.</p>
        </div>
      </article>

      <article class="card">
        <img src="images/industry4.jpg" alt="Industry 4" />
        <div class="card-body">
          <h3>صنعت ۴</h3>
          <p>این قسمت برای محتوای جدید، مقاله کوتاه یا معرفی یک پروژه مناسب است.</p>
        </div>
      </article>

      <article class="card">
        <img src="images/industry5.jpg" alt="Industry 5" />
        <div class="card-body">
          <h3>صنعت ۵</h3>
          <p>محتوای این بخش را هر زمان خواستی می‌توانی عوض کنی و عکس جدید بگذاری.</p>
        </div>
      </article>
    </div>
  </section>

  <section id="services">
    <h2>خدمات و محتوا</h2>
    <div class="list">
      <ul>
        <li>افزودن مقاله و توضیحات جدید برای هر صنعت</li>
        <li>تغییر عکس‌ها با فایل‌های جدید در پوشه images</li>
        <li>اضافه کردن لینک، فرم تماس یا گالری</li>
        <li>ویرایش متن و عنوان‌ها بدون نیاز به ساخت سایت جدید</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <h2>تماس</h2>
    <div class="list">
      <p>Email: your@email.com</p>
      <p>GitHub: your-github</p>
    </div>
  </section>
</main>

<footer>
  <div class="container">
    © 2026 Mohsen Nasri. All rights reserved.
  </div>
</footer>

</body>
</html>
