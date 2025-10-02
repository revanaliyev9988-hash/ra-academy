<!DOCTYPE html>  <html lang="az">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>R.A. Academy - Qeydiyyat</title>    <style>  
    /* Ümumi stillər */  
    body {  
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;  
      margin:0;   
      padding:0;  
      background: linear-gradient(180deg, #e6f0ff, #ffffff);  
      color:#333;  
      line-height: 1.6;  
    }  
  
    /* Başlıq (Header) stilləri */  
    header {  
      background: linear-gradient(90deg,#4a90e2,#357ab7);  
      color:white;   
      padding:20px;   
      text-align:center;  
      box-shadow:0 2px 5px rgba(0,0,0,0.2);  
    }  
    header h1 {  
        margin: 0 0 10px 0;  
        font-size: 2.5em;  
    }  
  
    /* Naviqasiya (Navigation) stilləri */  
    nav a {  
      color:white;   
      margin:0 15px;   
      text-decoration:none;   
      font-weight:bold;  
      transition:color 0.3s ease;  
      padding: 5px 0;  
      display: inline-block;  
    }  
    nav a:hover {  
        color:#ffda79;  
    }  
  
    /* Əsas məzmun (Main content) stilləri */  
    main {  
        padding-bottom: 60px;  
    }  
    section {  
        padding:60px 20px;   
        text-align:center;  
        max-width: 1000px;  
        margin: 0 auto;  
    }  
    h2 {  
        color:#4a90e2;  
        margin-bottom:20px;   
        font-size: 2em;  
    }  
  
    /* Kurslar (Courses) stilləri */  
    .courses {  
      display:grid;   
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));  
      gap:20px;  
      margin-top: 30px;  
    }  
    .course {  
      border-radius:15px;   
      padding:25px;  
      background:white;   
      box-shadow:0 4px 8px rgba(0,0,0,0.1);  
      transition:transform 0.3s ease, box-shadow 0.3s ease;  
      text-align: left;  
    }  
    .course:hover {  
        transform:translateY(-5px);  
        box-shadow:0 6px 12px rgba(0,0,0,0.15);  
    }  
    .course h3 {  
        margin-top: 0;   
        font-size: 1.4em;   
        color: #357ab7;  
        display: flex;  
        align-items: center;  
        gap: 10px;  
    }  
  
    /* Forma (Form) stilləri */  
    form {  
      max-width:450px;   
      margin:0 auto;   
      text-align:left;  
      background:white;   
      padding:25px;   
      border-radius:15px;  
      box-shadow:0 4px 10px rgba(0,0,0,0.15);  
    }  
    label {  
        font-weight:bold;   
        color:#444;   
        display: block;   
        margin-top: 15px;  
        margin-bottom: 5px;  
    }  
    input, select, button {  
      width:100%;   
      padding:12px;   
      border:1px solid #ccc;  
      border-radius:8px;   
      font-size:16px;  
      box-sizing: border-box;  
    }  
    /* Fokus zamanı stil */  
    input:focus, select:focus, button:focus {  
        outline: 3px solid #ffda79;  
        border-color: #ffda79;  
        outline-offset: 2px;  
    }  
    button {  
      background:#4a90e2;   
      color:white;   
      border:none;   
      cursor:pointer;  
      font-weight:bold;   
      transition:background-color 0.3s ease;  
      margin-top: 25px;  
      padding: 14px;  
      font-size: 1.1em;  
    }  
    button:hover {  
        background:#357ab7;  
    }  
  
    /* Footer stilləri */  
    footer {  
      background:#222;   
      color:white;   
      text-align:center;   
      padding:20px;   
      margin-top:40px;  
      font-size: 0.9em;  
    }  
  
    /* Media sorğuları (Responsiveness) */  
    @media (max-width: 768px) {  
        nav a {  
            margin: 0 10px;  
            font-size: 0.9em;  
        }  
        .courses {  
            grid-template-columns: 1fr;  
        }  
    }  
    @media (max-width: 480px) {  
        nav a {  
            display: block;   
            margin: 5px 0;  
            padding: 5px 0;  
            border-bottom: 1px solid rgba(255,255,255,0.2);  
        }  
    }  
  </style>  </head>  
<body>  
  <header>  
    <h1>R.A. Academy</h1>  
    <nav>  
      <a href="#about">Haqqımızda</a>  
      <a href="#courses">Kurslar</a>  
      <a href="#register">Qeydiyyat</a>  
      <a href="#contact">Əlaqə</a>  
    </nav>  
  </header>    <main>  
    <section id="about">  
      <h2>Haqqımızda</h2>  
      <p>R.A. Academy – İngilis dili, Riyaziyyat, Azərbaycan dili və İbtidai sinif üçün peşəkar onlayn dərslər təklif edir. Bizimlə biliklərinizi artırın və gələcəyinizə investisiya edin!</p>  
    </section>  <section id="courses">  
  <h2>Kurslarımız</h2>  
  <div class="courses">  
    <div class="course">  
        <h3>🇬🇧 İngilis dili</h3>  
        <p>Sıfırdan mükəmməl danışıq bacarıqlarına yiyələn. Beynəlxalq sertifikatlara hazırlaşmaq üçün ideal seçim.</p>  
    </div>  
    <div class="course">  
        <h3>📐 Riyaziyyat</h3>  
        <p>Ən çətin mövzuları asan üsulla öyrən. Məntiqinizi inkişaf etdirin və imtahanlarda yüksək nəticələr əldə edin.</p>  
    </div>  
    <div class="course">  
        <h3>📖 Azərbaycan dili</h3>  
        <p>Dil qaydalarını əyləncəli və effektiv şəkildə öyrən. Doğru yazışma və qrammatika bacarıqlarınızı təkmilləşdirin.</p>  
    </div>  
    <div class="course">  
        <h3>📚 İbtidai sinif</h3>  
        <p>Uşaqlar üçün əsas biliklər. Oxuma, yazma və hesablama bacarıqlarını peşəkar müəllimlər ilə öyrənin.</p>  
    </div>  
  </div>  
</section>  

<section id="register">  
  <h2>Qeydiyyat</h2>  
  <form action="https://formspree.io/f/mnqwejkl" method="POST">  
      
    <label for="adsoyad_input">Ad Soyad:</label>  
    <input type="text" id="adsoyad_input" name="Ad Soyad" placeholder="Adınızı və Soyadınızı daxil edin" required>  

    <label for="telefon_input">Telefon:</label>  
    <input type="tel" id="telefon_input" name="Telefon" pattern="[0-9]{9,15}" placeholder="Məs: +994 XX XXX XX XX" required>  
    <small style="color: #666; display: block; margin-top: -5px;">Nömrəni beynəlxalq formatda daxil edin.</small>  

    <label for="email_input">Email:</label>  
    <input type="email" id="email_input" name="Email" placeholder="email@example.com" required>  

    <label for="kurs_select">Kurs seçin:</label>  
    <select id="kurs_select" name="Kurs" required>  
        <option value="" disabled selected>Zəhmət olmasa bir kurs seçin</option>   
        <option value="İngilis dili">İngilis dili</option>  
        <option value="Riyaziyyat">Riyaziyyat</option>  
        <option value="Azərbaycan dili">Azərbaycan dili</option>  
        <option value="İbtidai sinif">İbtidai sinif</option>  
    </select>  

    <button type="submit">Qeydiyyatdan keç</button>  
  </form>  
</section>  

<section id="contact">  
  <h2>Əlaqə</h2>  
  <p>Hər hansı bir sualınız olarsa, bizimlə əlaqə saxlayın:</p>  
  <p>📞 **Telefon:** <a href="tel:+994XXXXXXXXX">+994 XX XXX XX XX</a></p>  
  <p>📱 **WhatsApp:** <a href="https://wa.me/994XXXXXXXXX" target="_blank">WhatsApp vasitəsilə yazın</a></p>  
  <p>📷 **Instagram:** <a href="https://instagram.com/ra.academy" target="_blank">@ra.academy</a></p>  
</section>

  </main>    <footer>  
    © 2025 R.A. Academy. Bütün hüquqlar qorunur.  
  </footer>  
</body>  
</html>  
