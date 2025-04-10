<html lang="ru" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ремонт и Строительство</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
  <style>
    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans" id="body">
  <!-- Header -->
  <header class="p-6 bg-gray-800 shadow-lg">
    <div class="max-w-7xl mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold" id="title">СтройРемГрупп</h1>
      <nav class="space-x-6" id="nav">
        <a href="#about" class="hover:text-yellow-400" id="nav-about">О нас</a>
        <a href="#services" class="hover:text-yellow-400" id="nav-services">Услуги</a>
        <a href="#portfolio" class="hover:text-yellow-400" id="nav-portfolio">Портфолио</a>
        <a href="#contact" class="hover:text-yellow-400" id="nav-contact">Контакты</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="about" class="bg-gray-950 py-20 text-center" data-aos="fade-up">
    <h2 class="text-4xl font-bold mb-4" id="hero-title">Ремонт квартир и строительство домов из металлоконструкций</h2>
    <p class="text-gray-400 max-w-xl mx-auto" id="hero-subtitle">Профессионально. Надёжно. В срок.</p>
  </section>

  <!-- Services -->
  <section id="services" class="py-16 px-4 max-w-7xl mx-auto" data-aos="fade-up">
    <h3 class="text-3xl font-bold mb-8 text-center" id="services-title">Наши услуги</h3>
    <div class="grid md:grid-cols-2 gap-10">
      <div class="bg-gray-800 p-6 rounded-xl shadow-md">
        <h4 class="text-xl font-semibold mb-2" id="service-1-title">Ремонт квартир</h4>
        <p class="text-gray-400" id="service-1-desc">Косметический и капитальный ремонт под ключ с гарантией качества.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-xl shadow-md">
        <h4 class="text-xl font-semibold mb-2" id="service-2-title">Строительство домов</h4>
        <p class="text-gray-400" id="service-2-desc">Современные дома из металлоконструкций — быстро, надёжно, энергоэффективно.</p>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio" class="py-16 bg-gray-950 px-4" data-aos="fade-up">
    <h3 class="text-3xl font-bold mb-8 text-center" id="portfolio-title">Портфолио</h3>
    <div class="grid md:grid-cols-3 gap-6 max-w-7xl mx-auto">
      <img src="https://source.unsplash.com/400x300/?interior" class="rounded-xl" alt="Пример работы">
      <img src="https://source.unsplash.com/400x300/?construction" class="rounded-xl" alt="Пример работы">
      <img src="https://source.unsplash.com/400x300/?architecture" class="rounded-xl" alt="Пример работы">
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-4 max-w-2xl mx-auto" data-aos="fade-up">
    <h3 class="text-3xl font-bold mb-6 text-center" id="contact-title">Связаться с нами</h3>
    <form class="space-y-4">
      <input type="text" placeholder="Ваше имя" class="w-full p-3 rounded bg-gray-800 text-white placeholder-gray-500">
      <input type="tel" placeholder="Телефон" class="w-full p-3 rounded bg-gray-800 text-white placeholder-gray-500">
      <textarea placeholder="Ваше сообщение" rows="4" class="w-full p-3 rounded bg-gray-800 text-white placeholder-gray-500"></textarea>
      <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-3 px-6 rounded" id="submit-button">Отправить</button>
    </form>
  </section>

  <!-- Map -->
  <section class="py-16 bg-gray-900">
    <h3 class="text-3xl font-bold mb-6 text-center" id="map-title">Где мы находимся</h3>
    <div class="w-full h-96 max-w-4xl mx-auto">
      <iframe class="w-full h-full rounded-xl" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d10873.62814648255!2d34.8516125!3d32.1093331!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x151d4c6189f8c0c3%3A0xf84c8e0b40c55de!2z0J_QvtC70YzRidCw0Y8g0J_QvtGB0L_QtdGA0LXQvdC40Y8!5e0!3m2!1sru!2sil!4v1611234567890" frameborder="0" allowfullscreen="" loading="lazy"></iframe>
    </div>
  </section>

  <!-- Language Switch (RU / HE) -->
  <div class="fixed bottom-4 right-4">
    <button onclick="switchLang()" class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-2 px-4 rounded shadow" id="lang-button">Ivrit / Русский</button>
  </div>

  <!-- Footer -->
  <footer class="bg-gray-800 text-center p-4 text-gray-500">
    &copy; 2025 СтройРемГрупп. Все права защищены.
  </footer>

  <script>
    AOS.init();

    const translations = {
      ru: {
        title: "СтройРемГрупп",
        "nav-about": "О нас",
        "nav-services": "Услуги",
        "nav-portfolio": "Портфолио",
        "nav-contact": "Контакты",
        "hero-title": "Ремонт квартир и строительство домов из металлоконструкций",
        "hero-subtitle": "Профессионально. Надёжно. В срок.",
        "services-title": "Наши услуги",
        "service-1-title": "Ремонт квартир",
        "service-1-desc": "Косметический и капитальный ремонт под ключ с гарантией качества.",
        "service-2-title": "Строительство домов",
        "service-2-desc": "Современные дома из металлоконструкций — быстро, надёжно, энергоэффективно.",
        "portfolio-title": "Портфолио",
        "contact-title": "Связаться с нами",
        "submit-button": "Отправить",
        "map-title": "Где мы находимся",
        "lang-button": "Ivrit / Русский"
      },
      he: {
        title: "שטרוי-רם גרופ",
        "nav-about": "עלינו",
        "nav-services": "שירותים",
        "nav-portfolio": "תיק עבודות",
        "nav-contact": "צור קשר",
        "hero-title": "שיפוץ דירות ובניית בתים ממבני פלדה",
        "hero-subtitle": "מקצועי. אמין. בזמן.",
        "services-title": "השירותים שלנו",
        "service-1-title": "שיפוץ דירות",
        "service-1-desc": "שיפוץ קוסמטי וכללי עם אחריות לאיכות.",
        "service-2-title": "בנייה ממבני פלדה",
        "service-2-desc": "בתים מודרניים ממבני פלדה — מהיר, אמין וחסכוני באנרגיה.",
        "portfolio-title": "תיק עבודות",
        "contact-title": "צור קשר",
        "submit-button": "שלח",
        "map-title": "המיקום שלנו",
        "lang-button": "Русский / Ivrit"
      }
    };

    let currentLang = "ru";
    function switchLang() {
      currentLang = currentLang === "ru" ? "he" : "ru";
      const trans = translations[currentLang];
      Object.keys(trans).forEach(id => {
        const el = document.getElementById(id);
        if (el) el.textContent = trans[id];
      });
      document.documentElement.lang = currentLang;
      document.documentElement.dir = currentLang === "he" ? "rtl" : "ltr";
    }
  </script>
</body>
</html>
