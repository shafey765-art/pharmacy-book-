# pharmacy-book-<روشتة الامتياز في صيدلة>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#f7f8f2">
  <meta name="description" content="روشتة الامتياز في صيدلة: دليل عملي لتنظيم المذاكرة وفهم الفارما والاستعداد للامتحانات العملية.">
  <title>روشتة الامتياز في صيدلة | الدليل الصيدلي الشامل</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Alexandria:wght@400;500;600;700;800&family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      color-scheme: light;
      --ink: #172b2b;
      --muted: #596c68;
      --paper: #f7f8f2;
      --white: #fff;
      --green: #146e5b;
      --green-dark: #104c43;
      --mint: #d9eee2;
      --coral: #d85b46;
      --yellow: #e9b94e;
      --line: #dce5dc;
      --font: "Alexandria", "Cairo", sans-serif;
    }

    *, *::before, *::after { box-sizing: border-box; }
    html { scroll-behavior: smooth; scroll-padding-top: 6rem; }
    body {
      margin: 0;
      color: var(--ink);
      background: var(--paper);
      font-family: var(--font);
      line-height: 1.75;
      overflow-x: hidden;
    }
    a { color: inherit; text-decoration: none; }
    a:focus-visible, summary:focus-visible { outline: 3px solid var(--coral); outline-offset: 4px; }
    .wrap { width: min(1160px, calc(100% - 40px)); margin-inline: auto; }
    .announcement {
      padding: 9px 16px;
      color: #fff;
      background: var(--green-dark);
      text-align: center;
      font-size: 12px;
      font-weight: 600;
    }
    .announcement strong { color: #f2ce72; }
    .site-header {
      position: sticky;
      top: 0;
      z-index: 5;
      background: rgb(247 248 242 / 94%);
      border-bottom: 1px solid rgb(20 110 91 / 12%);
      backdrop-filter: blur(12px);
    }
    .nav { min-height: 72px; display: flex; align-items: center; justify-content: space-between; gap: 24px; }
    .brand { display: flex; align-items: center; gap: 11px; flex-shrink: 0; }
    .brand-mark {
      width: 42px; aspect-ratio: 1; display: grid; place-items: center;
      border-radius: 13px; color: #fff; background: var(--green); font-size: 20px; font-weight: 800;
    }
    .brand-name { display: block; font-size: 15px; font-weight: 800; line-height: 1.4; }
    .brand-note { display: block; color: var(--muted); font-size: 10px; }
    .nav-links { display: flex; align-items: center; gap: clamp(12px, 2.2vw, 28px); color: #435651; font-size: 12px; font-weight: 600; }
    .nav-links a:hover { color: var(--green); }
    .button {
      display: inline-flex; min-height: 48px; align-items: center; justify-content: center; gap: 9px;
      padding: 11px 20px; border: 0; border-radius: 9px; color: #fff; background: var(--green);
      font: 700 13px var(--font); transition: background .2s ease, transform .2s ease;
    }
    .button:hover { background: var(--green-dark); transform: translateY(-2px); }
    .button-light { color: var(--green-dark); background: #fff; }
    .button-light:hover { color: #fff; }
    .nav .button { min-height: 42px; padding: 9px 15px; font-size: 11px; }

    .hero {
      position: relative; isolation: isolate; overflow: hidden;
      padding: clamp(62px, 8vw, 108px) 0 90px;
      background:
        radial-gradient(ellipse at 8% 5%, rgb(233 185 78 / 23%), transparent 30%),
        radial-gradient(ellipse at 87% 76%, rgb(217 238 226 / 85%), transparent 32%),
        var(--paper);
    }
    .hero::after {
      position: absolute; z-index: -1; inset: 0; content: ""; opacity: .24; pointer-events: none;
      background-image: radial-gradient(#78958a 0.7px, transparent 0.7px); background-size: 20px 20px;
      mask-image: linear-gradient(90deg, #000, transparent 65%);
    }
    .hero-grid { display: grid; grid-template-columns: 1.12fr .88fr; align-items: center; gap: clamp(38px, 7vw, 96px); }
    .hero-copy { animation: enter .7s both; }
    .eyebrow { display: inline-flex; align-items: center; gap: 8px; color: var(--green); font-size: 11px; font-weight: 700; }
    .eyebrow::before { width: 23px; height: 2px; content: ""; background: var(--coral); }
    h1 { max-width: 690px; margin: 18px 0; font-size: clamp(33px, 5.1vw, 62px); line-height: 1.34; letter-spacing: 0; font-weight: 800; }
    h1 em { color: var(--green); font-style: normal; }
    .hero-copy > p { max-width: 640px; margin: 0; color: var(--muted); font-size: clamp(14px, 1.4vw, 16px); line-height: 2; }
    .hero-copy > p strong { color: var(--ink); }
    .benefits { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 11px 18px; margin: 27px 0; padding: 0; list-style: none; }
    .benefits li { display: flex; align-items: center; gap: 9px; color: #40534d; font-size: 12px; font-weight: 600; }
    .check { flex: 0 0 19px; display: grid; place-items: center; width: 19px; height: 19px; border-radius: 50%; color: #fff; background: var(--green); font-size: 11px; }
    .purchase-row { display: flex; flex-wrap: wrap; align-items: center; gap: 14px; }
    .purchase-row .button { min-height: 54px; padding-inline: 24px; }
    .price { display: flex; align-items: center; gap: 12px; padding: 7px 14px; border-right: 1px solid var(--line); }
    .price-old { display: block; color: #87918b; font-size: 11px; text-decoration: line-through; }
    .price-now { color: var(--green-dark); font-size: 20px; font-weight: 800; }
    .discount { padding: 4px 8px; border-radius: 4px; color: #9b3b2e; background: #f8dfd7; font-size: 10px; font-weight: 700; }
    .delivery-note { display: flex; align-items: center; gap: 8px; margin-top: 14px; color: var(--muted); font-size: 10px; }
    .delivery-note span { color: var(--coral); font-size: 16px; }

    .book-scene { position: relative; display: grid; min-height: 490px; place-items: center; perspective: 1100px; animation: enter .8s .1s both; }
    .book-scene::before { position: absolute; width: 370px; height: 370px; border: 1px solid rgb(20 110 91 / 15%); border-radius: 50%; content: ""; }
    .book-scene::after { position: absolute; width: 295px; height: 295px; border: 1px dashed rgb(20 110 91 / 22%); border-radius: 50%; content: ""; }
    .book {
      position: relative; z-index: 1; width: min(280px, 70vw); height: 390px; display: flex; flex-direction: column; justify-content: space-between;
      padding: 27px 24px; overflow: hidden; color: #fff; border: 1px solid rgb(255 255 255 / 25%);
      border-radius: 5px 13px 13px 5px;
      background: linear-gradient(145deg, #1a745f, #104c43 66%, #133c39);
      box-shadow: 19px 22px 32px rgb(23 43 43 / 24%), inset 7px 0 0 rgb(255 255 255 / 9%), inset 9px 0 0 rgb(8 50 43 / 30%);
      transform: rotateY(12deg) rotateZ(-2deg); transition: transform .45s ease;
    }
    .book-scene:hover .book { transform: rotateY(4deg) rotateZ(0); }
    .book::before { position: absolute; inset: 0 auto 0 14px; width: 1px; content: ""; background: rgb(255 255 255 / 18%); }
    .book-kicker { color: #c8e5d0; font-size: 9px; font-weight: 700; letter-spacing: 1.2px; }
    .book-rule { width: 39px; height: 3px; margin: 12px 0 22px; background: var(--yellow); }
    .book-label { display: inline-block; padding: 4px 7px; border: 1px solid rgb(255 255 255 / 28%); border-radius: 3px; color: #d6ebd9; font-size: 9px; }
    .book h2 { margin: 16px 0 8px; font-size: 31px; line-height: 1.45; font-weight: 800; }
    .book h2 span { color: #f2ce72; }
    .book-description { max-width: 210px; color: #d4e1d9; font-size: 10px; line-height: 1.9; }
    .book-footer { display: flex; align-items: end; justify-content: space-between; padding-top: 15px; border-top: 1px solid rgb(255 255 255 / 20%); }
    .book-footer small { display: block; color: #b7c9c0; font-size: 8px; }
    .book-footer strong { font-size: 10px; }
    .book-seal { display: grid; place-items: center; width: 35px; aspect-ratio: 1; border: 1px solid #b4d8c1; border-radius: 50%; color: #f2ce72; font-size: 15px; }
    .edition { position: absolute; z-index: 2; top: 52px; right: 6%; padding: 8px 13px; border: 1px solid #fff; border-radius: 4px; color: #493b18; background: var(--yellow); box-shadow: 0 5px 16px rgb(23 43 43 / 13%); font-size: 10px; font-weight: 800; transform: rotate(4deg); }
    .edition::before { content: "★  "; }

    .trust { padding: 30px 0; background: #fff; border-block: 1px solid var(--line); }
    .trust-grid { display: grid; grid-template-columns: repeat(4, 1fr); }
    .trust-item { padding: 4px 24px; border-left: 1px solid var(--line); }
    .trust-item:last-child { border-left: 0; }
    .trust-item strong { display: block; margin-bottom: 3px; font-size: 12px; }
    .trust-item p { margin: 0; color: var(--muted); font-size: 10px; }
    .trust-mark { display: inline-grid; place-items: center; width: 25px; height: 25px; margin-bottom: 6px; border-radius: 7px; color: var(--green); background: var(--mint); font-size: 12px; font-weight: 800; }

    .section { padding-block: clamp(68px, 8vw, 100px); }
    .section-heading { max-width: 620px; margin: 0 auto 42px; text-align: center; }
    .section-heading .eyebrow { justify-content: center; }
    .section-heading h2 { margin: 10px 0 8px; font-size: clamp(25px, 3.4vw, 38px); line-height: 1.5; font-weight: 800; }
    .section-heading p { margin: 0; color: var(--muted); font-size: 13px; }
    .audience-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 17px; }
    .audience-card { padding: 25px; border: 1px solid var(--line); border-radius: 8px; background: #fff; transition: transform .2s ease, border-color .2s ease; }
    .audience-card:hover { transform: translateY(-4px); border-color: #9bbfae; }
    .audience-icon { display: grid; place-items: center; width: 43px; height: 43px; margin-bottom: 17px; border-radius: 11px; color: var(--green-dark); background: var(--mint); font-size: 18px; font-weight: 800; }
    .audience-card:nth-child(2) .audience-icon { color: #984638; background: #f8e2d9; }
    .audience-card:nth-child(3) .audience-icon { color: #756021; background: #f6edce; }
    .audience-card h3 { margin: 0 0 8px; font-size: 15px; line-height: 1.65; }
    .audience-card p { margin: 0; color: var(--muted); font-size: 11px; line-height: 2; }

    .contents { background: #edf2eb; border-block: 1px solid var(--line); }
    .chapter-list { max-width: 820px; margin-inline: auto; border-top: 1px solid #cbd8ce; }
    .chapter { display: grid; grid-template-columns: 48px 1fr; gap: 16px; padding: 21px 8px; border-bottom: 1px solid #cbd8ce; }
    .chapter-number { display: grid; place-items: center; width: 38px; height: 38px; border-radius: 50%; color: var(--green-dark); background: #d8e8dc; font-size: 15px; font-weight: 700; }
    .chapter h3 { margin: 0 0 4px; font-size: 13px; }
    .chapter p { margin: 0; color: var(--muted); font-size: 11px; }

    .reviews { background: #fff; }
    .reviews-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px; }
    .review { padding: 22px; border: 1px solid var(--line); border-radius: 7px; }
    .stars { color: #c18b1e; font-size: 13px; letter-spacing: 2px; }
    .review blockquote { margin: 12px 0 17px; color: #40534d; font-size: 12px; line-height: 2; }
    .review cite { color: var(--ink); font-size: 10px; font-style: normal; font-weight: 700; }

    .faq { background: #edf2eb; border-top: 1px solid var(--line); }
    .faq-list { max-width: 780px; margin-inline: auto; border-top: 1px solid #cbd8ce; }
    .faq details { border-bottom: 1px solid #cbd8ce; }
    .faq summary { position: relative; padding: 19px 4px; cursor: pointer; list-style: none; font-size: 13px; font-weight: 700; }
    .faq summary::-webkit-details-marker { display: none; }
    .faq summary::after { position: absolute; left: 6px; content: "+"; color: var(--green); font-size: 20px; font-weight: 500; }
    .faq details[open] summary::after { content: "−"; }
    .faq details p { max-width: 700px; margin: -3px 0 19px; color: var(--muted); font-size: 11px; line-height: 2; }

    .buy { position: relative; overflow: hidden; padding-block: 78px; color: #fff; background: var(--green-dark); }
    .buy::before { position: absolute; inset: -140px auto auto -110px; width: 380px; height: 380px; content: ""; border: 1px solid rgb(255 255 255 / 13%); border-radius: 50%; box-shadow: 0 0 0 36px rgb(255 255 255 / 3%), 0 0 0 72px rgb(255 255 255 / 2%); }
    .buy-inner { position: relative; max-width: 760px; margin-inline: auto; text-align: center; }
    .buy .eyebrow { color: #b9dfc7; }
    .buy .eyebrow::before { background: var(--yellow); }
    .buy h2 { margin: 12px 0; font-size: clamp(27px, 4.5vw, 45px); line-height: 1.45; }
    .buy p { max-width: 590px; margin: 0 auto 26px; color: #d0dfd6; font-size: 13px; }
    .buy .purchase-row { justify-content: center; }
    .buy .price { border-right-color: rgb(255 255 255 / 25%); text-align: right; }
    .buy .price-old { color: #c1d0c8; }
    .buy .price-now { color: #f2ce72; }
    .buy .button { color: var(--green-dark); background: #f2ce72; }
    .buy .button:hover { background: #ffdc7a; }
    footer { padding: 21px 16px; color: #afc0b6; background: #102f2b; text-align: center; font-size: 10px; }

    @keyframes enter { from { opacity: 0; transform: translateY(14px); } to { opacity: 1; transform: translateY(0); } }
    @media (max-width: 850px) {
      .nav-links { display: none; }
      .hero-grid { grid-template-columns: 1fr .78fr; gap: 25px; }
      .book-scene { min-height: 420px; }
      .book { height: 350px; padding: 23px 20px; }
      .book h2 { font-size: 27px; }
      .book-scene::before { width: 310px; height: 310px; }
      .book-scene::after { width: 250px; height: 250px; }
      .trust-item { padding-inline: 15px; }
    }
    @media (max-width: 620px) {
      .wrap { width: min(100% - 32px, 480px); }
      .announcement { font-size: 10px; }
      .nav { min-height: 64px; gap: 8px; }
      .brand-mark { width: 37px; }
      .brand-name { font-size: 12px; }
      .brand-note { font-size: 9px; }
      .nav .button { min-height: 39px; padding: 8px 10px; font-size: 10px; }
      .hero { padding: 52px 0 45px; }
      .hero-grid { grid-template-columns: 1fr; gap: 20px; }
      .hero-copy { text-align: center; }
      .hero-copy .eyebrow { justify-content: center; }
      h1 { margin: 13px 0; font-size: clamp(31px, 9vw, 42px); }
      .hero-copy > p { font-size: 13px; }
      .benefits { text-align: right; gap: 10px 8px; margin: 21px 0; }
      .benefits li { font-size: 10px; line-height: 1.7; }
      .check { flex-basis: 17px; width: 17px; height: 17px; font-size: 10px; }
      .purchase-row { justify-content: center; }
      .purchase-row .button { width: 100%; min-height: 50px; font-size: 12px; }
      .price { border: 0; }
      .delivery-note { justify-content: center; font-size: 9px; }
      .book-scene { min-height: 365px; }
      .book { width: 232px; height: 322px; padding: 22px 19px; }
      .book h2 { margin-top: 12px; font-size: 25px; }
      .book-description { font-size: 9px; }
      .book-scene::before { width: 285px; height: 285px; }
      .book-scene::after { width: 230px; height: 230px; }
      .edition { top: 20px; right: 4%; font-size: 9px; }
      .trust { padding: 22px 0; }
      .trust-grid { grid-template-columns: repeat(2, 1fr); gap: 21px 0; }
      .trust-item { padding-inline: 11px; }
      .trust-item:nth-child(2) { border-left: 0; }
      .trust-item strong { font-size: 11px; }
      .trust-item p { font-size: 9px; }
      .section { padding-block: 60px; }
      .section-heading { margin-bottom: 29px; }
      .section-heading h2 { font-size: 25px; }
      .section-heading p { font-size: 11px; }
      .audience-grid, .reviews-grid { grid-template-columns: 1fr; gap: 11px; }
      .audience-card { padding: 19px; }
      .audience-card p { font-size: 10px; }
      .chapter { grid-template-columns: 38px 1fr; gap: 11px; padding: 17px 0; }
      .chapter-number { width: 34px; height: 34px; font-size: 13px; }
      .chapter h3 { font-size: 11px; }
      .chapter p { font-size: 10px; line-height: 1.9; }
      .review { padding: 18px; }
      .review blockquote { font-size: 11px; }
      .faq summary { padding: 17px 2px; padding-left: 28px; font-size: 11px; }
      .faq details p { font-size: 10px; }
      .buy { padding-block: 60px; }
      .buy h2 { font-size: 28px; }
      .buy p { font-size: 11px; }
      .buy .purchase-row { gap: 9px; }
      .buy .price { justify-content: center; }
      .buy .button { width: 100%; }
    }
    @media (prefers-reduced-motion: reduce) {
      *, *::before, *::after { scroll-behavior: auto !important; animation-duration: .01ms !important; animation-iteration-count: 1 !important; transition-duration: .01ms !important; }
    }
  </style>
</head>
<body>
  <div class="announcement"><strong>عرض محدود</strong> · خصم 50% للدفعة الجديدة، واستلام ملف PDF فور تأكيد الدفع</div>

  <header class="site-header">
    <div class="wrap nav">
      <a class="brand" href="#top" aria-label="روشتة الامتياز في صيدلة، الصفحة الرئيسية">
        <span class="brand-mark" aria-hidden="true">ر</span>
        <span><span class="brand-name">روشتة الامتياز في صيدلة</span><span class="brand-note">الدليل الصيدلي الشامل</span></span>
      </a>
      <nav class="nav-links" aria-label="التنقل الرئيسي">
        <a href="#about">عن الكتاب</a><a href="#audience">لمن الكتاب</a><a href="#toc">المحتويات</a><a href="#testimonials">آراء الطلاب</a><a href="#faq">الأسئلة الشائعة</a>
      </nav>
      <a class="button" href="https://wa.me/201030754508?text=%D8%A3%D8%B1%D9%8A%D8%AF%20%D8%B4%D8%B1%D8%A7%D8%A1%20%D9%83%D8%AA%D8%A7%D8%A8%20%D8%B1%D9%88%D8%B4%D8%AA%D8%A9%20%D8%A7%D9%84%D8%A7%D9%85%D8%AA%D9%8A%D8%A7%D8%B2%20%D9%81%D9%8A%20%D8%B5%D9%8A%D8%AF%D9%84%D8%A9" target="_blank" rel="noopener noreferrer">اطلب كتابك <span aria-hidden="true">↗</span></a>
    </div>
  </header>

  <main id="top">
    <section class="hero" id="about">
      <div class="wrap hero-grid">
        <div class="hero-copy">
          <span class="eyebrow">دليلك العملي لرحلة صيدلة</span>
          <h1>خطوة أهدأ نحو <em>الامتياز</em> في صيدلة</h1>
          <p>دليل يساعدك على بناء طريقة مذاكرة تناسبك: من فهم <strong>الفارماكولوجي</strong> والكيمياء الدوائية إلى الاستعداد للعملي وتنظيم وقتك خلال الترم.</p>
          <ul class="benefits">
            <li><span class="check" aria-hidden="true">✓</span>خرائط ذهنية لعائلات الأدوية</li>
            <li><span class="check" aria-hidden="true">✓</span>استراتيجيات للمذاكرة العملية</li>
            <li><span class="check" aria-hidden="true">✓</span>تنظيم وقت المحاضرات والسكاشن</li>
            <li><span class="check" aria-hidden="true">✓</span>جداول وقوالب تلخيص مرفقة</li>
          </ul>
          <div class="purchase-row">
            <a class="button" href="https://wa.me/201030754508?text=%D8%A3%D8%B1%D9%8A%D8%AF%20%D8%B4%D8%B1%D8%A7%D8%A1%20%D9%83%D8%AA%D8%A7%D8%A8%20%D8%B1%D9%88%D8%B4%D8%AA%D8%A9%20%D8%A7%D9%84%D8%A7%D9%85%D8%AA%D9%8A%D8%A7%D8%B2%20%D9%81%D9%8A%20%D8%B5%D9%8A%D8%AF%D9%84%D8%A9" target="_blank" rel="noopener noreferrer">اطلب نسختك عبر واتساب <span aria-hidden="true">↗</span></a>
            <div class="price"><div><span class="price-old">300 جنيه</span><span class="price-now">150 جنيه</span></div><span class="discount">خصم 50%</span></div>
          </div>
          <div class="delivery-note"><span aria-hidden="true">✳</span> نسخة إلكترونية PDF تُرسل بعد تأكيد الدفع</div>
        </div>
        <div class="book-scene" aria-label="غلاف كتاب روشتة الامتياز في صيدلة">
          <span class="edition">النسخة الشاملة · 2026</span>
          <div class="book">
            <div><div class="book-kicker">PHARMACY GUIDE</div><div class="book-rule"></div><span class="book-label">دليل الطالب العملي</span><h2>روشتة<br><span>الامتياز</span><br>في صيدلة</h2><div class="book-description">أفكار للمذاكرة، وفهم الأدوية، والاستعداد للاختبارات العملية.</div></div>
            <div class="book-footer"><div><small>إعداد وتأليف</small><strong>د. صيدلي / شهاب</strong></div><span class="book-seal" aria-hidden="true">✳</span></div>
          </div>
        </div>
      </div>
    </section>

    <section class="trust" aria-label="مميزات الكتاب">
      <div class="wrap trust-grid">
        <div class="trust-item"><span class="trust-mark" aria-hidden="true">PDF</span><strong>نسخة رقمية سهلة</strong><p>اقرأها على الهاتف أو الكمبيوتر</p></div>
        <div class="trust-item"><span class="trust-mark" aria-hidden="true">↗</span><strong>تواصل مباشر</strong><p>للاستفسارات عبر واتساب</p></div>
        <div class="trust-item"><span class="trust-mark" aria-hidden="true">ج</span><strong>وسائل دفع متنوعة</strong><p>فودافون كاش أو إنستاباي أو تحويل</p></div>
        <div class="trust-item"><span class="trust-mark" aria-hidden="true">+</span><strong>ملحقات إضافية</strong><p>جداول تنظيم وقوالب تلخيص</p></div>
      </div>
    </section>

    <section class="section" id="audience">
      <div class="wrap">
        <div class="section-heading"><span class="eyebrow">صُمّم لرحلتك الدراسية</span><h2>لمن هذا الدليل؟</h2><p>من بدايات الدراسة إلى سنوات التخصص، ستجد أفكاراً عملية تساعدك على بناء نظامك الخاص.</p></div>
        <div class="audience-grid">
          <article class="audience-card"><div class="audience-icon" aria-hidden="true">١</div><h3>طلاب السنة الأولى</h3><p>ابدأ بفهم طبيعة الدراسة الجامعية والمصطلحات الطبية، وابنِ عادات مذاكرة ثابتة من أول يوم.</p></article>
          <article class="audience-card"><div class="audience-icon" aria-hidden="true">٢</div><h3>طلاب العملي والـ OSPE</h3><p>راجع خطوات الاستعداد للسكاشن والاختبارات العملية، وتعرّف على طرق التعامل مع العينات والتقارير.</p></article>
          <article class="audience-card"><div class="audience-icon" aria-hidden="true">٣</div><h3>من يريد تثبيت المعلومات</h3><p>جرّب أساليب التكرار المتباعد والربط لتسهيل مراجعة الأدوية والمصطلحات على مدار الفصل.</p></article>
        </div>
      </div>
    </section>

    <section class="section contents" id="toc">
      <div class="wrap">
        <div class="section-heading"><span class="eyebrow">نظرة على المحتوى</span><h2>ماذا ستجد داخل الكتاب؟</h2></div>
        <div class="chapter-list">
          <article class="chapter"><span class="chapter-number">١</span><div><h3>التأقلم الأكاديمي وبدايات الدراسة</h3><p>التعامل مع المصطلحات الطبية وطرق تدوين الملاحظات أثناء المحاضرات.</p></div></article>
          <article class="chapter"><span class="chapter-number">٢</span><div><h3>مذاكرة الفارماكولوجي والكيمياء</h3><p>ربط الأسماء العلمية والتجارية، وتبسيط آليات عمل الأدوية بالخرائط الذهنية.</p></div></article>
          <article class="chapter"><span class="chapter-number">٣</span><div><h3>الاستعداد للمعامل والامتحانات العملية</h3><p>خطوات عملية للتعامل مع العينات والتقارير والاستعداد لاختبارات الـ OSPE.</p></div></article>
          <article class="chapter"><span class="chapter-number">٤</span><div><h3>إدارة الوقت والتوازن خلال الترم</h3><p>تنظيم أسبوعك للموازنة بين الدراسة والسكاشن والراحة الشخصية.</p></div></article>
        </div>
      </div>
    </section>

    <section class="section reviews" id="testimonials">
      <div class="wrap">
        <div class="section-heading"><span class="eyebrow">تجارب الطلاب</span><h2>ماذا يقول زملاؤك؟</h2></div>
        <div class="reviews-grid">
          <article class="review"><div class="stars" aria-label="5 من 5 نجوم">★★★★★</div><blockquote>«الكتاب فرق معايا جداً خصوصاً في طريقة حفظ الفارما. الخرائط الذهنية خلت المراجعة أوضح وأسهل.»</blockquote><cite>سارة محمود · صيدلة، السنة الثالثة</cite></article>
          <article class="review"><div class="stars" aria-label="5 من 5 نجوم">★★★★★</div><blockquote>«أكتر حاجة استفدت منها طريقة الاستعداد للعملي والـ OSPE، وبقيت أرتب مذاكرتي بشكل أحسن.»</blockquote><cite>محمد علي · طالب صيدلة</cite></article>
          <article class="review"><div class="stars" aria-label="5 من 5 نجوم">★★★★★</div><blockquote>«كنت محتاجة خطة واضحة في أول سنة، والكتاب ساعدني أفهم أبدأ منين وأقسم وقتي.»</blockquote><cite>نور الهدى · صيدلة، السنة الأولى</cite></article>
        </div>
      </div>
    </section>

    <section class="section faq" id="faq">
      <div class="wrap">
        <div class="section-heading"><span class="eyebrow">إجابات سريعة</span><h2>الأسئلة الشائعة</h2></div>
        <div class="faq-list">
          <details><summary>كيف سأستلم الكتاب بعد الدفع؟</summary><p>بعد تأكيد التحويل عبر واتساب، يُرسل الكتاب في ملف PDF يمكنك فتحه على الهاتف أو الكمبيوتر.</p></details>
          <details><summary>هل يناسب الكتاب طلاب PharmD العام والإكلينيكي؟</summary><p>يركز الدليل على استراتيجيات المذاكرة والتعامل مع المواد والعملي، وهي أفكار يمكن لطلاب الصيدلة بمساراتهم المختلفة الاستفادة منها.</p></details>
          <details><summary>هل يمكنني طباعة الكتاب؟</summary><p>النسخة PDF قابلة للطباعة. يمكنك مراجعة إعدادات الطباعة المناسبة من جهازك أو المكتبة.</p></details>
          <details><summary>ما وسائل الدفع المتاحة؟</summary><p>يمكنك الاستفسار والتنسيق عبر واتساب بشأن فودافون كاش أو إنستاباي أو التحويل البنكي.</p></details>
        </div>
      </div>
    </section>

    <section class="buy" id="buy">
      <div class="wrap buy-inner">
        <span class="eyebrow">ابدأ رحلتك الآن</span>
        <h2>روشتة الامتياز في صيدلة</h2>
        <p>نسخة PDF مع الجداول والملحقات بسعر العرض الحالي. راسلنا عبر واتساب لمعرفة تفاصيل الطلب والدفع.</p>
        <div class="purchase-row">
          <div class="price"><div><span class="price-old">السعر الأصلي: 300 جنيه</span><span class="price-now">150 جنيه فقط</span></div><span class="discount">خصم 50%</span></div>
          <a class="button" href="https://wa.me/201030754508?text=%D8%A3%D8%B1%D9%8A%D8%AF%20%D8%B4%D8%B1%D8%A7%D8%A1%20%D9%83%D8%AA%D8%A7%D8%A8%20%D8%B1%D9%88%D8%B4%D8%AA%D8%A9%20%D8%A7%D9%84%D8%A7%D9%85%D8%AA%D9%8A%D8%A7%D8%B2%20%D9%81%D9%8A%20%D8%B5%D9%8A%D8%AF%D9%84%D8%A9" target="_blank" rel="noopener noreferrer">اطلب الملف عبر واتساب <span aria-hidden="true">↗</span></a>
        </div>
      </div>
    </section>
  </main>
  <footer>© 2026 كتاب روشتة الامتياز في صيدلة. جميع الحقوق محفوظة.</footer>
</body>
</html>
