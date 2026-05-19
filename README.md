<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>BrainRhythm ID | Personalized Brain Rhythm Guide</title>
  <meta name="description" content="BrainRhythm ID is a tool for intentionally guiding your mental states through personalized brain rhythms. Learn how your personal BrainRhythm ID is used for alpha, beta, theta, delta and REM-like states in real-life situations." />
  <meta name="keywords" content="BrainRhythm ID, personalized brain rhythms, brain rhythm profile, alpha rhythm, beta focus, theta state, delta rest, REM-like state, focus rhythm, stress reset, low mood support, sports performance rhythm" />
  <meta name="author" content="BrainRhythm ID" />
  <meta name="robots" content="index, follow" />

  <meta property="og:title" content="BrainRhythm ID | Personalized Brain Rhythm Guide" />
  <meta property="og:description" content="Discover how BrainRhythm ID uses your personal brain rhythm profile to create personalized rhythms for real-life situations." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://your-github-name.github.io/brainrhythm-id/" />
  <meta property="og:image" content="https://your-github-name.github.io/brainrhythm-id/assets/brainrhythm-og-image.png" />

  <link rel="canonical" href="https://your-github-name.github.io/brainrhythm-id/" />
  <link rel="alternate" hreflang="en" href="https://your-github-name.github.io/brainrhythm-id/" />
  <link rel="alternate" hreflang="hr" href="https://your-github-name.github.io/brainrhythm-id/hr.html" />
  <link rel="alternate" hreflang="de" href="https://your-github-name.github.io/brainrhythm-id/de.html" />
  <link rel="alternate" hreflang="fr" href="https://your-github-name.github.io/brainrhythm-id/fr.html" />
  <link rel="alternate" hreflang="es" href="https://your-github-name.github.io/brainrhythm-id/es.html" />

  <style>
    :root {
      --bg-top: #020817;
      --bg-mid: #07122d;
      --bg-bottom: #0b1f4d;
      --card: rgba(255, 255, 255, 0.075);
      --card-strong: rgba(57, 168, 255, 0.13);
      --border: rgba(127, 211, 255, 0.20);
      --border-strong: rgba(127, 211, 255, 0.42);
      --text: #f4f8ff;
      --muted: #b8c6df;
      --soft: #7fd3ff;
      --primary: #39a8ff;
      --accent: #9d7bff;
      --warning: #ffd36e;
      --shadow: rgba(0, 0, 0, 0.35);
      --max-width: 1120px;
    }

    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: var(--text);
      background:
        radial-gradient(circle at top left, rgba(57, 168, 255, 0.18), transparent 34rem),
        radial-gradient(circle at 82% 8%, rgba(157, 123, 255, 0.22), transparent 28rem),
        linear-gradient(180deg, var(--bg-top), var(--bg-mid) 45%, var(--bg-bottom));
      min-height: 100vh;
      line-height: 1.65;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .page {
      overflow: hidden;
    }

    .nav {
      position: sticky;
      top: 0;
      z-index: 10;
      backdrop-filter: blur(16px);
      background: rgba(2, 8, 23, 0.72);
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
    }

    .nav-inner {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 14px 22px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 18px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
      font-weight: 800;
      letter-spacing: 0.2px;
    }

    .brand-mark {
      width: 34px;
      height: 34px;
      border-radius: 50%;
      background: radial-gradient(circle, var(--soft), var(--primary) 45%, rgba(157, 123, 255, 0.4) 78%);
      box-shadow: 0 0 28px rgba(57, 168, 255, 0.55);
    }

    .nav-links {
      display: flex;
      gap: 14px;
      align-items: center;
      flex-wrap: wrap;
      justify-content: flex-end;
      font-size: 13px;
      color: var(--muted);
    }

    .nav-links a {
      padding: 7px 10px;
      border-radius: 999px;
    }

    .nav-links a:hover,
    .nav-links .active {
      background: rgba(255, 255, 255, 0.08);
      color: var(--text);
    }

    .hero {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 84px 22px 46px;
      display: grid;
      grid-template-columns: 1.05fr 0.95fr;
      gap: 34px;
      align-items: center;
    }

    .hero-kicker {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 8px 12px;
      border: 1px solid var(--border);
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.06);
      color: var(--soft);
      font-size: 13px;
      font-weight: 700;
      margin-bottom: 22px;
    }

    h1 {
      margin: 0 0 20px;
      font-size: clamp(42px, 7vw, 76px);
      line-height: 0.96;
      letter-spacing: -2.6px;
    }

    .hero-lead {
      margin: 0 0 18px;
      font-size: clamp(20px, 3vw, 28px);
      line-height: 1.28;
      color: #ffffff;
      font-weight: 750;
    }

    .hero-sub {
      margin: 0;
      color: var(--muted);
      font-size: 18px;
      max-width: 720px;
    }

    .hero-card {
      position: relative;
      padding: 26px;
      border: 1px solid var(--border-strong);
      border-radius: 32px;
      background:
        radial-gradient(circle at 30% 5%, rgba(127, 211, 255, 0.22), transparent 14rem),
        linear-gradient(145deg, rgba(255, 255, 255, 0.12), rgba(255, 255, 255, 0.045));
      box-shadow: 0 26px 70px var(--shadow);
      min-height: 380px;
      overflow: hidden;
    }

    .pulse-orb {
      width: 190px;
      height: 190px;
      border-radius: 50%;
      margin: 22px auto 26px;
      background:
        radial-gradient(circle, #ffffff 0%, var(--soft) 22%, var(--primary) 45%, rgba(157, 123, 255, 0.42) 72%, transparent 73%);
      box-shadow: 0 0 44px rgba(57, 168, 255, 0.70), 0 0 100px rgba(157, 123, 255, 0.28);
      animation: pulse 4.5s ease-in-out infinite;
    }

    @keyframes pulse {
      0%, 100% { transform: scale(0.96); opacity: 0.86; }
      50% { transform: scale(1.05); opacity: 1; }
    }

    .mini-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 12px;
    }

    .mini {
      padding: 12px;
      border-radius: 18px;
      background: rgba(255, 255, 255, 0.075);
      border: 1px solid rgba(255, 255, 255, 0.10);
    }

    .mini strong {
      display: block;
      color: var(--soft);
      font-size: 13px;
      margin-bottom: 2px;
    }

    .mini span {
      font-size: 12px;
      color: var(--muted);
    }

    section {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 54px 22px;
    }

    .section-heading {
      margin-bottom: 24px;
      max-width: 850px;
    }

    .eyebrow {
      color: var(--soft);
      font-size: 13px;
      text-transform: uppercase;
      letter-spacing: 1.6px;
      font-weight: 850;
      margin-bottom: 10px;
    }

    h2 {
      margin: 0 0 14px;
      font-size: clamp(30px, 4.6vw, 50px);
      line-height: 1.07;
      letter-spacing: -1.2px;
    }

    h3 {
      margin: 0 0 10px;
      font-size: 23px;
      line-height: 1.22;
      letter-spacing: -0.2px;
    }

    p {
      color: var(--muted);
      margin: 0 0 14px;
      font-size: 16px;
    }

    .highlight-box {
      padding: 26px;
      border-radius: 28px;
      border: 1px solid var(--border-strong);
      background: linear-gradient(145deg, rgba(57, 168, 255, 0.15), rgba(157, 123, 255, 0.10));
      box-shadow: 0 22px 60px rgba(0, 0, 0, 0.20);
    }

    .highlight-box p {
      font-size: 18px;
      color: #eaf4ff;
    }

    .state-grid,
    .steps-grid,
    .rhythm-grid {
      display: grid;
      gap: 16px;
    }

    .state-grid {
      grid-template-columns: repeat(5, 1fr);
    }

    .steps-grid {
      grid-template-columns: repeat(3, 1fr);
    }

    .rhythm-grid {
      grid-template-columns: repeat(2, 1fr);
    }

    .card {
      border-radius: 24px;
      border: 1px solid var(--border);
      background: var(--card);
      padding: 22px;
      box-shadow: 0 16px 48px rgba(0, 0, 0, 0.16);
    }

    .card.strong {
      background: var(--card-strong);
      border-color: var(--border-strong);
    }

    .state-card strong {
      display: block;
      color: var(--soft);
      font-size: 18px;
      margin-bottom: 8px;
    }

    .state-card p,
    .rhythm-card p {
      font-size: 15px;
    }

    .rhythm-card {
      position: relative;
      overflow: hidden;
    }

    .rhythm-card::before {
      content: "";
      position: absolute;
      inset: 0 auto auto 0;
      width: 5px;
      height: 100%;
      background: linear-gradient(180deg, var(--primary), var(--accent));
      opacity: 0.85;
    }

    .rhythm-card h3,
    .rhythm-card p {
      margin-left: 4px;
    }

    .tag-row {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin: 12px 0 4px;
    }

    .tag {
      font-size: 12px;
      color: var(--soft);
      border: 1px solid rgba(127, 211, 255, 0.26);
      background: rgba(127, 211, 255, 0.08);
      padding: 5px 9px;
      border-radius: 999px;
      font-weight: 700;
    }

    .folder-list {
      display: grid;
      gap: 18px;
    }

    .folder {
      border: 1px solid var(--border-strong);
      border-radius: 28px;
      background: rgba(255, 255, 255, 0.055);
      overflow: hidden;
      box-shadow: 0 18px 54px rgba(0, 0, 0, 0.16);
    }

    .folder summary {
      cursor: pointer;
      list-style: none;
      padding: 22px 24px;
      background: linear-gradient(135deg, rgba(57, 168, 255, 0.16), rgba(157, 123, 255, 0.10));
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 18px;
    }

    .folder summary::-webkit-details-marker {
      display: none;
    }

    .folder summary::after {
      content: "+";
      flex: 0 0 auto;
      width: 34px;
      height: 34px;
      border-radius: 50%;
      display: grid;
      place-items: center;
      color: var(--text);
      background: rgba(255, 255, 255, 0.10);
      border: 1px solid rgba(255, 255, 255, 0.14);
      font-size: 24px;
      line-height: 1;
      font-weight: 400;
    }

    .folder[open] summary::after {
      content: "−";
    }

    .folder summary strong {
      display: block;
      color: #fff;
      font-size: 22px;
      line-height: 1.2;
      margin-bottom: 5px;
    }

    .folder summary em {
      display: block;
      color: var(--muted);
      font-size: 14px;
      font-style: normal;
    }

    .folder .rhythm-grid {
      padding: 18px;
    }

    .rhythm-grid.compact .rhythm-card p {
      margin-bottom: 10px;
    }

    .cta {
      text-align: center;
      padding: 62px 22px 82px;
    }

    .cta-box {
      max-width: 860px;
      margin: 0 auto;
      padding: 34px;
      border-radius: 34px;
      border: 1px solid var(--border-strong);
      background:
        radial-gradient(circle at 20% 0%, rgba(127, 211, 255, 0.20), transparent 18rem),
        linear-gradient(145deg, rgba(255,255,255,0.13), rgba(255,255,255,0.055));
      box-shadow: 0 26px 80px rgba(0,0,0,0.28);
    }

    .button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      margin-top: 18px;
      padding: 15px 22px;
      border-radius: 999px;
      background: linear-gradient(135deg, var(--primary), var(--accent));
      color: #fff;
      font-weight: 850;
      box-shadow: 0 18px 42px rgba(57, 168, 255, 0.28);
    }

    .button:hover {
      transform: translateY(-1px);
    }

    .note {
      border-left: 4px solid var(--warning);
      background: rgba(255, 211, 110, 0.08);
      border-radius: 18px;
      padding: 18px 20px;
    }

    .note p {
      color: #ffe8ad;
      margin: 0;
    }

    footer {
      border-top: 1px solid rgba(255,255,255,0.08);
      padding: 28px 22px 42px;
      text-align: center;
      color: var(--muted);
      font-size: 13px;
    }

    @media (max-width: 980px) {
      .hero {
        grid-template-columns: 1fr;
        padding-top: 58px;
      }

      .state-grid,
      .steps-grid,
      .rhythm-grid {
        grid-template-columns: 1fr;
      }

      .hero-card {
        min-height: auto;
      }
    }

    @media (max-width: 620px) {
      .nav-inner {
        align-items: flex-start;
        flex-direction: column;
      }

      .nav-links {
        justify-content: flex-start;
      }

      h1 {
        letter-spacing: -1.6px;
      }

      .hero {
        padding-top: 38px;
      }

      .pulse-orb {
        width: 150px;
        height: 150px;
      }

      .mini-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>

  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "MobileApplication",
    "name": "BrainRhythm ID",
    "operatingSystem": "Android",
    "applicationCategory": "HealthApplication",
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "EUR"
    },
    "url": "https://play.google.com/store/apps/details?id=com.brainrhythmid.app",
    "description": "BrainRhythm ID helps users discover a personal brain rhythm profile and use personalized rhythms for real-life mental states."
  }
  </script>
</head>

<body>
  <div class="page">
    <nav class="nav" aria-label="Main navigation">
      <div class="nav-inner">
        <a class="brand" href="#top" aria-label="BrainRhythm ID home">
          <span class="brand-mark" aria-hidden="true"></span>
          <span>BrainRhythm ID</span>
        </a>
        <div class="nav-links">
          <a href="index.html" class="active">EN</a>
          <a href="hr.html">HR</a>
          <a href="de.html">DE</a>
          <a href="fr.html">FR</a>
          <a href="es.html">ES</a>
          <a href="#situational-rhythms">Rhythms</a>
          <a href="#full-version">Full Version</a>
        </div>
      </div>
    </nav>

    <header id="top" class="hero">
      <div>
        <div class="hero-kicker">Personalized brain rhythm profile</div>
        <h1>BrainRhythm ID</h1>
        <p class="hero-lead">A tool for intentionally guiding your mental states through personalized brain rhythms.</p>
        <p class="hero-sub">The app helps you discover your personal brain rhythm profile — the rhythms in which your brain enters different states and performs different tasks.</p>
      </div>

      <aside class="hero-card" aria-label="Brain rhythm states overview">
        <div class="pulse-orb" aria-hidden="true"></div>
        <div class="mini-grid">
          <div class="mini"><strong>Alpha</strong><span>Calm stability</span></div>
          <div class="mini"><strong>Beta</strong><span>Focus and action</span></div>
          <div class="mini"><strong>Theta</strong><span>Inner processing</span></div>
          <div class="mini"><strong>Delta / REM</strong><span>Rest and deep imagery</span></div>
        </div>
      </aside>
    </header>

    <main>
      <section id="what-you-received">
        <div class="section-heading">
          <div class="eyebrow">What did you actually receive?</div>
          <h2>Your scan result is only the beginning.</h2>
        </div>
        <div class="highlight-box">
          <p>You received your personal BrainRhythm ID — a brain rhythm profile that shows how your brain responds to different rhythmic states.</p>
          <p>It is not just a scan result. It becomes the foundation for creating personalized rhythms that can be used to intentionally guide mental states: from alpha calm, theta inner processing and delta rest, to beta focus, mental activation and preparation for real-life tasks.</p>
          <p>You received personalized rhythms created from your BrainRhythm ID profile — rhythms that resonate with your brain rhythms and help guide your brain into the desired state.</p>
        </div>
      </section>

      <section id="brain-states">
        <div class="section-heading">
          <div class="eyebrow">Brain rhythm states</div>
          <h2>Alpha, beta, theta, delta and REM-like states</h2>
          <p>Brain rhythms are not just frequencies. They are connected with different modes of brain activity.</p>
        </div>

        <div class="state-grid">
          <div class="card state-card"><strong>Alpha</strong><p>Calmer wakefulness, inner stability and relaxed attention.</p></div>
          <div class="card state-card"><strong>Beta</strong><p>Focus, mental activation, analysis, reaction and task execution.</p></div>
          <div class="card state-card"><strong>Theta</strong><p>Deeper inner processing, creative imagery, intuition and emotional processing.</p></div>
          <div class="card state-card"><strong>Delta</strong><p>Deep slowing down, deep rest and regenerative states.</p></div>
          <div class="card state-card"><strong>REM-like</strong><p>Dynamic inner processing, dreams, imagination and subconscious processing.</p></div>
        </div>
      </section>

      <section id="how-it-works">
        <div class="section-heading">
          <div class="eyebrow">How it works</div>
          <h2>Your profile becomes a practical tool.</h2>
          <p>All situational rhythms in BrainRhythm ID are created from your personal BrainRhythm ID profile. You do not receive a generic sound, but a personalized rhythmic pattern for a specific mental state.</p>
        </div>

        <div class="steps-grid">
          <div class="card strong"><h3>1. Discover your profile</h3><p>The scan helps identify how your brain responds to different rhythm patterns.</p></div>
          <div class="card strong"><h3>2. Create personalized rhythms</h3><p>Your BrainRhythm ID becomes the foundation for alpha, beta, theta, delta and REM-like rhythm use.</p></div>
          <div class="card strong"><h3>3. Apply it in real life</h3><p>Use your rhythms for focus, calm, emotional balance, performance, recovery, sleep preparation and more.</p></div>
        </div>
      </section>

      <section id="situational-rhythms">
        <div class="section-heading">
          <div class="eyebrow">Situational Rhythms</div>
          <h2>Choose the state you want to guide.</h2>
          <p>Instead of scrolling through a long text, open the group that matches your current situation. Each folder contains personalized rhythm modes created from your BrainRhythm ID profile.</p>
        </div>

        <div class="folder-list">
          <details class="folder" open>
            <summary>
              <span>
                <strong>Focus, performance and action</strong>
                <em>Beta focus, activation, readiness, studying, meetings and sports.</em>
              </span>
            </summary>
            <div class="rhythm-grid compact">
              <article class="card rhythm-card">
                <h3>Before Meeting</h3>
                <div class="tag-row"><span class="tag">Alpha calm</span><span class="tag">Beta focus</span><span class="tag">Communication</span></div>
                <p>For the moments before a meeting, conversation, presentation, negotiation or important communication.</p>
                <p>Designed for entering a state of calm mental readiness: calm enough not to react from nervousness, but active enough to think clearly and express yourself well.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Deep Focus / Study</h3>
                <div class="tag-row"><span class="tag">Beta focus</span><span class="tag">Study</span><span class="tag">Mental clarity</span></div>
                <p>For studying, work, reading, analysis, programming, writing and tasks that require sustained attention.</p>
                <p>The goal is a more active beta state with enough inner stability for focus to be sharp, but not nervous.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Performance Mode</h3>
                <div class="tag-row"><span class="tag">Beta performance</span><span class="tag">Reaction speed</span><span class="tag">Sharpness</span></div>
                <p>For moments when you need mental sharpness, reaction speed, activation and strong performance.</p>
                <p>Designed before demanding tasks, performances, presentations, exams, competitions or situations where you need to be mentally fast, precise and present.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Sports Performance</h3>
                <div class="tag-row"><span class="tag">Sports readiness</span><span class="tag">Beta focus</span><span class="tag">Pressure control</span></div>
                <p>For moments before training, a match, competition or physical challenge.</p>
                <p>The goal is a state of sports readiness: sharper beta focus, controlled energy, better timing, faster reaction and more explosive inner preparation.</p>
              </article>

              <article class="card rhythm-card">
                <h3>I Can Do This</h3>
                <div class="tag-row"><span class="tag">Beta activation</span><span class="tag">Courage</span><span class="tag">Action</span></div>
                <p>For moments when you need inner drive, courage and the feeling that you can begin.</p>
                <p>Useful before challenges, decisions, new steps, tasks you keep postponing or situations where you need to feel: “I can do this.”</p>
              </article>

              <article class="card rhythm-card">
                <h3>Motivation Reset</h3>
                <div class="tag-row"><span class="tag">Beta drive</span><span class="tag">Start action</span><span class="tag">Momentum</span></div>
                <p>For moments when you know what you need to do, but you cannot begin.</p>
                <p>Useful before work, studying, training, cleaning, creative tasks or any activity you keep delaying.</p>
              </article>
            </div>
          </details>

          <details class="folder">
            <summary>
              <span>
                <strong>Calm, stress and emotional balance</strong>
                <em>Alpha/theta settling, nervous tension, emotional overload and stress reset.</em>
              </span>
            </summary>
            <div class="rhythm-grid compact">
              <article class="card rhythm-card">
                <h3>Calm Down / Wind Down</h3>
                <div class="tag-row"><span class="tag">Alpha</span><span class="tag">Theta</span><span class="tag">Overactivation</span></div>
                <p>For states of high inner activity, when the brain is still accelerated, the body is tense and thoughts are difficult to stop.</p>
                <p>The goal is a gradual shift from activated beta activity toward calmer alpha/theta patterns.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Stress Reset</h3>
                <div class="tag-row"><span class="tag">Stress overload</span><span class="tag">Reset</span><span class="tag">Calmer clarity</span></div>
                <p>For moments when the nervous system is overloaded — after stress, pressure, conflict, mental chaos or emotional saturation.</p>
                <p>Useful when you want to reset the system before stress fully takes control.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Nervous Tension Relief</h3>
                <div class="tag-row"><span class="tag">Nervousness</span><span class="tag">Alpha/theta settling</span><span class="tag">Inner control</span></div>
                <p>For states of excessive inner energy, such as nervousness, inner tension, irritability, impulsiveness or aggressive charge.</p>
                <p>The goal is a shift from over-arousal toward a calmer alpha/theta rhythm, better inner control and a safer feeling of settling down.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Emotional Balance</h3>
                <div class="tag-row"><span class="tag">Alpha</span><span class="tag">Theta</span><span class="tag">Emotional stability</span></div>
                <p>For moments when emotions feel scattered, heavy, irritable or unstable.</p>
                <p>The goal is a shift from emotional chaos toward a more stable alpha/theta rhythm, calmer clarity and a stronger sense of inner balance.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Recovery / After Stress</h3>
                <div class="tag-row"><span class="tag">After stress</span><span class="tag">Alpha/theta</span><span class="tag">Recovery</span></div>
                <p>For the state after stress, when the event may be over, but the body and brain remain tense.</p>
                <p>Useful when stress is no longer an external event, but a state that stayed in the body, thoughts and nervous system.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Confidence & Social Ease</h3>
                <div class="tag-row"><span class="tag">Social ease</span><span class="tag">Inner safety</span><span class="tag">Presence</span></div>
                <p>For situations where you want to feel more confident, natural and relaxed around other people.</p>
                <p>Useful before social events, conversations, meeting new people, public speaking or situations where you want to appear calmer and more self-assured.</p>
              </article>
            </div>
          </details>

          <details class="folder">
            <summary>
              <span>
                <strong>Low energy, recovery and body support</strong>
                <em>Low mood, fatigue, recovery, pain perception, metabolic and weight balance support.</em>
              </span>
            </summary>
            <div class="rhythm-grid compact">
              <article class="card rhythm-card">
                <h3>Low Mood Support</h3>
                <div class="tag-row"><span class="tag">Low inner energy</span><span class="tag">Emotional lift</span><span class="tag">Reconnection</span></div>
                <p>For states of low inner energy, such as depressive moods, emotional heaviness, emptiness, lack of will or a feeling of inner drop.</p>
                <p>It is not intended as a medical treatment, but as rhythmic support for moments when you want to move out of a heavy inner state.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Deep Fatigue Reset</h3>
                <div class="tag-row"><span class="tag">Fatigue</span><span class="tag">Gentle restart</span><span class="tag">Stability</span></div>
                <p>For deep inner exhaustion, when you do not feel just tired, but as if the whole system has slowed down.</p>
                <p>This rhythm does not force sudden energy. The goal is a gentle shift toward a more stable rhythm, a clearer head and gradual restoration of inner functionality.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Deep Recovery Support</h3>
                <div class="tag-row"><span class="tag">Meditative recovery</span><span class="tag">Theta</span><span class="tag">Inner work</span></div>
                <p>For a meditative state in which you want to use directed thoughts to activate an inner recovery process during difficult states, deep exhaustion or long-term life burden.</p>
                <p>It is designed for the moment when you want to lie down, close your eyes, calm the system and consciously direct your thoughts toward the body, renewal, regeneration and the return of inner strength.</p>
                <p>It is not a replacement for medical care, but rhythmic support for a meditative state in which a person wants to actively participate in their own recovery process.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Pain Relief Support</h3>
                <div class="tag-row"><span class="tag">Body perception</span><span class="tag">Release</span><span class="tag">Calmer state</span></div>
                <p>For moments when physical discomfort, pain, tension or exhaustion from pain takes up too much space in awareness.</p>
                <p>The goal is not medical pain treatment, but helping the brain move from tense focus on pain toward a calmer, more relaxed and more controlled state.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Metabolic Balance Support</h3>
                <div class="tag-row"><span class="tag">Regulation</span><span class="tag">Energy balance</span><span class="tag">Body rhythm</span></div>
                <p>For states of inner imbalance, changing energy, heaviness in the body, appetite swings or the feeling that the system is not working steadily.</p>
                <p>Designed for supporting a more stable inner rhythm, a calmer relationship with the body and better energy regulation.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Weight Balance Support</h3>
                <div class="tag-row"><span class="tag">Appetite balance</span><span class="tag">Motivation</span><span class="tag">Steady energy</span></div>
                <p>For supporting steadier energy, appetite, motivation and a healthier inner rhythm.</p>
                <p>It is not a “weight loss program,” but rhythmic support when you want to move more easily out of heaviness, low will, unstable energy or impulsive cravings.</p>
              </article>
            </div>
          </details>

          <details class="folder">
            <summary>
              <span>
                <strong>Creativity, intimacy and daily transitions</strong>
                <em>Creative flow, romantic presence, morning activation and sleep preparation.</em>
              </span>
            </summary>
            <div class="rhythm-grid compact">
              <article class="card rhythm-card">
                <h3>Creative Flow</h3>
                <div class="tag-row"><span class="tag">Theta</span><span class="tag">Alpha</span><span class="tag">Ideas</span></div>
                <p>For creative work, writing, creating, ideas, planning, music, design and problem solving.</p>
                <p>The goal is a shift toward more creative alpha/theta patterns, where the brain can more easily connect images, ideas, emotions and inner associations.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Romantic / Intimacy</h3>
                <div class="tag-row"><span class="tag">Date readiness</span><span class="tag">Presence</span><span class="tag">Emotional opening</span></div>
                <p>For moments before a romantic meeting, a date, meeting a new girl, or any situation where you want to feel more relaxed, confident and natural in closeness.</p>
                <p>The goal is a shift toward a softer alpha/theta state, with gentle activation, stronger body presence and easier emotional opening toward another person.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Morning Activation</h3>
                <div class="tag-row"><span class="tag">Activation</span><span class="tag">Morning clarity</span><span class="tag">Drive</span></div>
                <p>For morning slowness, mental fog, low energy or the feeling that the brain has not fully switched on yet.</p>
                <p>The goal is a gradual shift from a slower morning state toward clearer activation, wakefulness and presence.</p>
              </article>

              <article class="card rhythm-card">
                <h3>Sleep Preparation</h3>
                <div class="tag-row"><span class="tag">Theta</span><span class="tag">Delta</span><span class="tag">Sleep transition</span></div>
                <p>For the evening transition from a wakeful, mentally active state toward a slower rhythm suitable for sleep.</p>
                <p>The goal is to reduce mental speed and gradually move closer to calmer theta/delta patterns.</p>
              </article>
            </div>
          </details>
        </div>
      </section>

      <section id="special-states">
        <div class="section-heading">
          <div class="eyebrow">Special States</div>
          <h2>Delta and REM-like rhythm modes</h2>
          <p>These modes are universal rhythm states and are not linked to one specific life situation.</p>
        </div>

        <div class="rhythm-grid">
          <article class="card rhythm-card strong">
            <h3>Delta – Universal Regeneration Mode</h3>
            <div class="tag-row"><span class="tag">Delta</span><span class="tag">Deep rest</span><span class="tag">Regenerative calm</span></div>
            <p>Delta is a universal state for deep slowing down, regenerative rest and a very calm inner state.</p>
            <p>This rhythm uses slower delta patterns connected with the deepest levels of rest, body relaxation and inner renewal.</p>
            <p>Useful when you want to slow down the whole system, move out of daily tension and enter a state of deeper rest.</p>
          </article>

          <article class="card rhythm-card strong">
            <h3>REM – Inner Processing Mode</h3>
            <div class="tag-row"><span class="tag">REM-like</span><span class="tag">Imagery</span><span class="tag">Inner processing</span></div>
            <p>REM is a universal state for inner processing, imagination, emotional processing, creative imagery and deeper connection with subconscious material.</p>
            <p>Use it when you want to use directed thoughts to stimulate inner insight, creative images, emotional processing, symbolic thinking or deeper contact with your own subconscious content.</p>
            <p>This rhythm is not meant for ordinary calming. It may feel activating because it uses a more dynamic REM-like pattern connected with dreams, imagination, inner images and deep mental processing.</p>
            <div class="note"><p><strong>Important:</strong> it is not recommended immediately before sleep, because for some users it may increase mental activity, imagery, thoughts or inner wakefulness.</p></div>
          </article>
        </div>
      </section>

      <section id="full-version">
        <div class="section-heading">
          <div class="eyebrow">Free vs Full Version</div>
          <h2>You are not just unlocking more sounds.</h2>
        </div>

        <div class="steps-grid">
          <div class="card">
            <h3>Free version</h3>
            <p>The free version lets you understand the concept of the app, complete the scan and experience how personalized rhythms work.</p>
            <p>It shows the beginning: your personal BrainRhythm ID.</p>
          </div>
          <div class="card strong">
            <h3>Full version</h3>
            <p>The full version unlocks the real use of your BrainRhythm ID profile across all situational rhythms.</p>
            <p>You can use your personal profile for alpha calm, beta focus, theta inner processing, delta rest, REM-like creative processing, sports preparation, low mood states, stress, motivation, sleep and other daily needs.</p>
          </div>
          <div class="card">
            <h3>The real value</h3>
            <p>You are not just unlocking more sounds.</p>
            <p><strong>You are unlocking the use of your own BrainRhythm ID.</strong></p>
          </div>
        </div>
      </section>

      <section id="safe-use">
        <div class="section-heading">
          <div class="eyebrow">Safe use</div>
          <h2>Wellness and self-regulation</h2>
        </div>
        <div class="highlight-box">
          <p>BrainRhythm ID is a wellness and self-regulation app.</p>
          <p>The app is not a medical treatment, does not diagnose conditions and does not replace a doctor, therapy or professional healthcare.</p>
          <p>If you have serious mental or physical symptoms, seek help from a qualified professional.</p>
        </div>
      </section>

      <section class="cta" id="download">
        <div class="cta-box">
          <div class="eyebrow">Download the app</div>
          <h2>Discover your personal BrainRhythm ID.</h2>
          <p>Use your personal brain rhythm profile to create rhythm sessions for real-life mental states.</p>
          <a class="button" href="https://play.google.com/store/apps/details?id=com.brainrhythmid.app" target="_blank" rel="noopener noreferrer">Open on Google Play</a>
        </div>
      </section>
    </main>

    <footer>
      <p>© BrainRhythm ID. All rights reserved.</p>
    </footer>
  </div>
</body>
</html>
