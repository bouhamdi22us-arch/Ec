<!DOCTYPE html>
<html lang="en" class="lenis">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Lando Norris — Official</title>
  <meta name="description" content="Lando Norris — Formula 1 Driver, McLaren. Official personal brand site." />

  <!-- Lenis CSS -->
  <link rel="stylesheet" href="https://unpkg.com/lenis@1.3.25/dist/lenis.css" />

  <!-- Google Fonts: Mona Sans -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Mona+Sans:wght@400;600;700&display=swap" rel="stylesheet" />

  <!-- Main CSS -->
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <!-- ████████████████████████████████ LOADER ████████████████████████████████ -->
  <div id="loader">
    <div class="loader__inner">
      <div class="loader__logo">LN4</div>
      <div class="loader__bar"><div class="loader__fill"></div></div>
    </div>
  </div>

  <!-- ████████████████████████████████ NAV ████████████████████████████████ -->
  <nav id="nav" class="nav">
    <div class="nav__logo">
      <span class="nav__logo-ln">LN</span><span class="nav__logo-num">4</span>
    </div>
    <ul class="nav__links">
      <li><a href="#hero"     class="nav__link">Home</a></li>
      <li><a href="#about"    class="nav__link">About</a></li>
      <li><a href="#stats"    class="nav__link">Stats</a></li>
      <li><a href="#helmet"   class="nav__link">Helmet</a></li>
      <li><a href="#calendar" class="nav__link">Calendar</a></li>
      <li><a href="#social"   class="nav__link">Social</a></li>
      <li><a href="#contact"  class="nav__link">Contact</a></li>
    </ul>
    <a href="#contact" class="btn btn--accent nav__cta">Get In Touch</a>
    <button class="nav__burger" aria-label="Menu">
      <span></span><span></span><span></span>
    </button>
  </nav>

  <!-- Mobile Menu -->
  <div class="mobile-menu" id="mobileMenu">
    <ul>
      <li><a href="#hero"     class="mobile-menu__link">Home</a></li>
      <li><a href="#about"    class="mobile-menu__link">About</a></li>
      <li><a href="#stats"    class="mobile-menu__link">Stats</a></li>
      <li><a href="#helmet"   class="mobile-menu__link">Helmet</a></li>
      <li><a href="#calendar" class="mobile-menu__link">Calendar</a></li>
      <li><a href="#social"   class="mobile-menu__link">Social</a></li>
      <li><a href="#contact"  class="mobile-menu__link">Contact</a></li>
    </ul>
  </div>

  <!-- ████████████████████████████████ HERO ████████████████████████████████ -->
  <section id="hero" class="hero">
    <div class="hero__bg-grid"></div>

    <!-- Kinetic top ticker -->
    <div class="ticker" aria-hidden="true">
      <div class="ticker__inner">
        <span>LANDO NORRIS</span><span class="ticker__dot">●</span>
        <span>MCLAREN F1</span><span class="ticker__dot">●</span>
        <span>2025 SEASON</span><span class="ticker__dot">●</span>
        <span>PAPAYA POWER</span><span class="ticker__dot">●</span>
        <span>LANDO NORRIS</span><span class="ticker__dot">●</span>
        <span>MCLAREN F1</span><span class="ticker__dot">●</span>
        <span>2025 SEASON</span><span class="ticker__dot">●</span>
        <span>PAPAYA POWER</span><span class="ticker__dot">●</span>
      </div>
    </div>

    <div class="hero__content container">
      <p class="hero__eyebrow" data-reveal>Formula 1 Driver · McLaren</p>
      <h1 class="hero__title" data-reveal>
        <span class="hero__title-line">LANDO</span>
        <span class="hero__title-line hero__title-line--accent">NORRIS</span>
        <span class="hero__title-line hero__title-line--outline">№4</span>
      </h1>
      <p class="hero__sub" data-reveal>
        Racing at the edge of physics. Living at the intersection of speed and culture.
      </p>
      <div class="hero__actions" data-reveal>
        <a href="#stats"  class="btn btn--accent">View Stats</a>
        <a href="#helmet" class="btn btn--ghost">3D Helmet</a>
      </div>
    </div>

    <!-- Radial glow -->
    <div class="hero__glow" aria-hidden="true"></div>

    <!-- Scroll indicator -->
    <div class="hero__scroll" aria-hidden="true">
      <div class="hero__scroll-line"></div>
      <span>SCROLL</span>
    </div>

    <!-- Signature SVG draw -->
    <div class="hero__signature" aria-hidden="true">
      <svg viewBox="0 0 300 80" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path id="sig-path"
          d="M10,60 C30,20 50,70 70,40 C90,10 110,65 130,35
             C150,5 170,60 190,30 C210,0 230,55 250,25 C270,-5 285,45 295,50"
          stroke="#D2FF00" stroke-width="2" stroke-linecap="round" fill="none"/>
      </svg>
    </div>
  </section>

  <!-- ████████████████████████████████ ABOUT ████████████████████████████████ -->
  <section id="about" class="about section">
    <div class="container about__grid">
      <div class="about__media">
        <div class="about__img-wrapper">
          <div class="about__img-placeholder">
            <!-- Replace with <img src="assets/lando-portrait.webp" alt="Lando Norris portrait" /> -->
            <div class="about__img-mock">
              <span class="about__img-mock-text">LN4</span>
            </div>
          </div>
          <div class="about__tag about__tag--tl">Born 1999</div>
          <div class="about__tag about__tag--br">Bristol, UK</div>
        </div>
      </div>
      <div class="about__copy">
        <p class="section__label" data-reveal>About</p>
        <h2 class="section__title" data-reveal>
          More Than<br/><span class="text--accent">A Driver.</span>
        </h2>
        <p class="about__text" data-reveal>
          Lando Norris is a British Formula 1 driver for the McLaren F1 Team. 
          Known for his raw speed, authenticity and gaming culture crossover, 
          Lando is redefining what it means to be a modern racing driver.
        </p>
        <p class="about__text" data-reveal>
          From British F3 champion to F1 race winner — the journey has only just begun.
        </p>
        <ul class="about__facts" data-reveal>
          <li><span class="fact__num">6+</span><span class="fact__label">F1 Seasons</span></li>
          <li><span class="fact__num">4M+</span><span class="fact__label">Twitch Followers</span></li>
          <li><span class="fact__num">∞</span><span class="fact__label">Passion</span></li>
        </ul>
      </div>
    </div>
  </section>

  <!-- ████████████████████████████████ STATS ████████████████████████████████ -->
  <section id="stats" class="stats section">
    <div class="container">
      <p class="section__label" data-reveal>Performance</p>
      <h2 class="section__title" data-reveal>Race <span class="text--accent">Stats</span></h2>

      <div class="stats__grid">

        <div class="stat-card" data-reveal data-delay="0">
          <div class="stat-card__accent"></div>
          <p class="stat-card__value" data-count="4">0</p>
          <p class="stat-card__label">Driver Number</p>
          <div class="stat-card__bar"><div class="stat-card__fill" data-fill="100"></div></div>
        </div>

        <div class="stat-card" data-reveal data-delay="100">
          <div class="stat-card__accent"></div>
          <p class="stat-card__value" data-count="113">0</p>
          <p class="stat-card__label">Career Points</p>
          <div class="stat-card__bar"><div class="stat-card__fill" data-fill="60"></div></div>
        </div>

        <div class="stat-card" data-reveal data-delay="200">
          <div class="stat-card__accent"></div>
          <p class="stat-card__value" data-count="7">0</p>
          <p class="stat-card__label">Podiums (2024)</p>
          <div class="stat-card__bar"><div class="stat-card__fill" data-fill="70"></div></div>
        </div>

        <div class="stat-card" data-reveal data-delay="300">
          <div class="stat-card__accent"></div>
          <p class="stat-card__value" data-count="5">0</p>
          <p class="stat-card__label">Race Wins</p>
          <div class="stat-card__bar"><div class="stat-card__fill" data-fill="50"></div></div>
        </div>

        <div class="stat-card" data-reveal data-delay="400">
          <div class="stat-card__accent"></div>
          <p class="stat-card__value" data-count="18">0</p>
          <p class="stat-card__label">Pole Positions</p>
          <div class="stat-card__bar"><div class="stat-card__fill" data-fill="40"></div></div>
        </div>

        <div class="stat-card" data-reveal data-delay="500">
          <div class="stat-card__accent"></div>
          <p class="stat-card__value" data-count="25">0</p>
          <p class="stat-card__label">Fastest Laps</p>
          <div class="stat-card__bar"><div class="stat-card__fill" data-fill="55"></div></div>
        </div>

      </div>
    </div>
  </section>

  <!-- ████████████████████████████████ HELMET 3D ████████████████████████████ -->
  <section id="helmet" class="helmet-section section">
    <div class="container">
      <p class="section__label" data-reveal>WebGL</p>
      <h2 class="section__title" data-reveal>
        3D Helmet <span class="text--accent">Viewer</span>
      </h2>
      <p class="helmet-section__hint" data-reveal>Drag to rotate · Scroll to zoom</p>
    </div>

    <!-- Canvas Three.js -->
    <div class="helmet-canvas-wrapper">
      <canvas id="helmetCanvas"></canvas>
      <div class="helmet-overlay">
        <div class="helmet-overlay__tag helmet-overlay__tag--tl">McLaren MCL60</div>
        <div class="helmet-overlay__tag helmet-overlay__tag--br">LN4 Livery</div>
      </div>
    </div>
  </section>

  <!-- ████████████████████████████████ CALENDAR ████████████████████████████ -->
  <section id="calendar" class="calendar-section section">
    <div class="container">
      <p class="section__label" data-reveal>2025 Season</p>
      <h2 class="section__title" data-reveal>Race <span class="text--accent">Calendar</span></h2>

      <div class="calendar__grid">

        <div class="race-card" data-reveal data-delay="0">
          <div class="race-card__round">RD 01</div>
          <div class="race-card__info">
            <h3 class="race-card__gp">Bahrain Grand Prix</h3>
            <p class="race-card__circuit">Bahrain International Circuit</p>
            <p class="race-card__date">2 Mar 2025</p>
          </div>
          <div class="race-card__status race-card__status--done">DONE</div>
        </div>

        <div class="race-card" data-reveal data-delay="100">
          <div class="race-card__round">RD 05</div>
          <div class="race-card__info">
            <h3 class="race-card__gp">Monaco Grand Prix</h3>
            <p class="race-card__circuit">Circuit de Monaco</p>
            <p class="race-card__date">25 May 2025</p>
          </div>
          <div class="race-card__status race-card__status--done">DONE</div>
        </div>

        <div class="race-card race-card--next" data-reveal data-delay="200">
          <div class="race-card__round">RD 12</div>
          <div class="race-card__info">
            <h3 class="race-card__gp">British Grand Prix</h3>
            <p class="race-card__circuit">Silverstone Circuit</p>
            <p class="race-card__date">6 Jul 2025</p>
          </div>
          <div class="race-card__status race-card__status--next">NEXT</div>
        </div>

        <div class="race-card" data-reveal data-delay="300">
          <div class="race-card__round">RD 15</div>
          <div class="race-card__info">
            <h3 class="race-card__gp">Italian Grand Prix</h3>
            <p class="race-card__circuit">Autodromo di Monza</p>
            <p class="race-card__date">7 Sep 2025</p>
          </div>
          <div class="race-card__
