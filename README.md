<!doctype html>
<html lang="kk">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Алихан бөкейхан — Өмірбаяны және шығармашылығы
Өмірбаяны
Ата тегі Шыңғыс ханның үлкен ұлы Жошыдан тарайтын төре тұқымы. Арғы атасы – атақты Барақ сұлтан. Қазақтың соңғы хандарының бірі Бөкей осы Барақ сұлтанның баласы. Бөкейден Батыр, одан Мырзатай, одан Әлиханның әкесі Нұрмұхамед.

Әлиханды әкесі тоғыз жасында Қарқаралыға апарып, жергілікті молданың қолына оқуға береді. Бірақ зерделі бала молдадан оқығандардан гөрі осындағы мектепте оқып жүргендердің сауаттылығын аңғарып, қаладағы үш кластық бастауыш мектепке өз еркімен ауысып алады. Оны бітіргеннен кейін, 1879 жылы Қарқаралы қаласындағы қазақ балаларына арналған мектепке түсіп, 1886-ге дейін оқиды.

1886-1890 жылдар аралығында Омбыдағы техникалық училищеде оқып, оны "техник" мамандығы бойынша бітіріп шықты.

1890-1894 жылдар аралығында Санкт-Петербургтегі Орман технологиялық институтының экономика факультетінде оқыды. Дала генерал-губернатор кеңсесінің ұсыныс хаты мен қазақ қауымдастығының 200 сом стипендиясын алып, 1894 жылы Ресей империясының елордасы Петерборға барып, Орман шаруашылығы институтының экономика факультетіне түседі. Ол мұнда жүріп күнделікті сабақтарына қоса студенттердің саяси, әдеби, экономикалық және тағы басқа үйірмелердің жұмысына қызу араласып, студенттік толқуларға қатысады.</title>
  <style>
    :root{
      --bg: #f6f9fc;
      --card: #ffffff;
      --accent: #0b76ef;
      --muted: #556074;
      --radius: 12px;
      --maxw: 980px;
    }
    body{
      margin:0;
      font-family: "Inter", system-ui, sans-serif;
      background: var(--bg);
      color:#0d1721;
      padding:28px;
      display:flex;
      justify-content:center;
    }
    .wrap{ width:100%; max-width:var(--maxw); }

    header.top{
      display:flex; gap:24px; align-items:center; margin-bottom:20px;
    }
    .photo-card img{
      width:260px; border-radius:12px; border:3px solid #fff;
      box-shadow:0 6px 20px rgba(0,0,0,0.1);
      cursor:pointer;
    }
    .hero{ flex:1; background:var(--card); border-radius:var(--radius); padding:18px; box-shadow:0 4px 14px rgba(0,0,0,0.05);}
    .hero h1{ margin:0 0 6px 0; font-size:28px; color:var(--accent);}
    .lead{ color:var(--muted); }
    .btn{
      display:inline-block; background:var(--accent); color:#fff; padding:10px 14px;
      border-radius:10px; text-decoration:none; font-weight:600; margin-top:8px;
    }

    .card{ background:var(--card); border-radius:var(--radius); padding:16px; box-shadow:0 4px 14px rgba(0,0,0,0.05); margin-bottom:16px;}
    h2{ color:var(--accent); font-size:18px; border-bottom:1px solid rgba(11,118,239,0.15); padding-bottom:6px;}
    .muted{ color:var(--muted); font-size:15px; line-height:1.6;}

    .quote-box{
      margin-top:16px; background:#eef6ff; border-left:4px solid var(--accent);
      padding:10px 14px; border-radius:8px; font-style:italic; color:#17457a;
    }

    footer{
      text-align:center; color:var(--muted); font-size:13px;
      margin-top:18px;
    }

    /* Түнгі режим */
    body.dark{
      --bg:#0d1117; --card:#161b22; --muted:#8b949e; --accent:#58a6ff; color:#e6edf3;
    }
    body.dark a{color:#58a6ff;}

    @media (max-width:900px){
      header.top{flex-direction:column; align-items:stretch;}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header class="top">
      <div class="photo-card">
        <img id="mainPhoto" src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Mukhtar_Shakhanov.jpg/480px-Mukhtar_Shakhanov.jpg" alt="Мұхтар Шаханов">
      </div>
      <div class="hero">
        <h1>Алихан Бөкейхан</h1>
        <p class="lead">Қазақтың көрнекті ақыны, қоғам қайраткері, ұлт рухының жаршысы.</p>
        <a href="#bio" class="btn">Өмірбаяны</a>
        <button id="speakBtn" class="btn" style="background:#0a66e0; margin-left:6px;">🎧 Дыбыстау</button>
        <button id="darkMode" class="btn" style="background:#222; margin-left:6px;">🌙 Түнгі режим</button>
      </div>
    </header>

    <section id="bio" class="card">
      <h2>Өмірбаяны</h2>
      <p class="muted">
        Мұхтар Шаханов — 1942 жылы Оңтүстік Қазақстанда туған.  
        Ақын, қоғам және мемлекет қайраткері, қазақ тілінің мәртебесі мен ұлттық рух мәселелерін көтерген тұлға.
      </p>

      <div class="quote-box" id="quoteBox">«Адамның ең үлкен қасіреті — өз ұлтының рухани тамырынан ажырау.»</div>

      <h2 style="margin-top:16px;">Негізгі еңбектері</h2>
      <ul class="muted">
        <li>«Төрт ана»</li>
        <li>«Өркениет пен руханият»</li>
        <li>«Жұмыр жерде қалған із»</li>
      </ul>
    </section>

    <footer>
      © <span id="year"></span> — Мұхтар Шаханов туралы бет.  
      <br><span id="clock"></span>
    </footer>
  </div>

  <script>
    // жыл
    document.getElementById("year").textContent = new Date().getFullYear();

    // Түнгі режим
    const toggle = document.getElementById("darkMode");
    toggle.onclick = () => document.body.classList.toggle("dark");

    // Дыбыстық оқу (SpeechSynthesis)
    document.getElementById("speakBtn").addEventListener("click", () => {
      const msg = new SpeechSynthesisUtterance("Мұхтар Шаханов — қазақ халқының ар-ожданы, ұлт намысын жырлаған ақын.");
      msg.lang = "kk-KZ";
      window.speechSynthesis.speak(msg);
    });

    // Уақыт көрсету
    function updateClock(){
      const now = new Date();
      document.getElementById("clock").textContent =
        now.toLocaleTimeString("kk-KZ", {hour:'2-digit', minute:'2-digit', second:'2-digit'});
    }
    setInterval(updateClock, 1000);
    updateClock();

    // Кездейсоқ цитата ауыстыру
    const quotes = [
      "«Тілінен айрылған жұрт – жойылған жұрт.»",
      "«Адамның ең үлкен қасіреті – рухани құлдық.»",
      "«Ұлттың ұлы болу – өз тілін, жерін және рухын сақтау.»"
    ];
    setInterval(()=>{
      const q = quotes[Math.floor(Math.random()*quotes.length)];
      document.getElementById("quoteBox").textContent = q;
    }, 7000);
  </script>
</body>
</html>
