---
permalink: /
title: "Junhao Zhuang"
layout: null
redirect_from:
  - /about/
  - /about.html
---
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Junhao Zhuang — researcher in audio-visual generative models and interactive world models.">
  <meta name="theme-color" content="#f7f8fa">
  <title>Junhao Zhuang</title>
  <link rel="icon" type="image/jpeg" href="https://zhuang2002.github.io/images/zhuang.jpg?v=20260906">
  <link rel="apple-touch-icon" href="https://zhuang2002.github.io/images/zhuang.jpg?v=20260906">
  <style>
    :root {
      --ink: #152235;
      --muted: #5f6c7b;
      --soft: #8b96a5;
      --line: #dfe4ea;
      --paper: #ffffff;
      --canvas: #ffffff;
      --accent: #2459a9;
      --accent-strong: #163f79;
      --accent-wash: #eef4fc;
      --serif: Georgia, "Times New Roman", serif;
      --sans: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      --shadow: none;
    }

    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; scroll-padding-top: 82px; }
    body {
      margin: 0;
      color: var(--ink);
      background: var(--canvas);
      font: 15.5px/1.72 var(--sans);
      -webkit-font-smoothing: antialiased;
    }
    a { color: var(--accent); text-decoration: none; }
    a:hover { color: var(--accent-strong); }
    img { display: block; max-width: 100%; }
    .skip-link { position: fixed; left: 16px; top: -60px; z-index: 100; padding: 10px 14px; background: var(--ink); color: white; border-radius: 8px; }
    .skip-link:focus { top: 12px; }

    .topbar {
      position: sticky;
      top: 0;
      z-index: 20;
      border-bottom: 1px solid rgba(223, 228, 234, .92);
      background: rgba(255, 255, 255, .94);
      backdrop-filter: blur(16px);
    }
    .nav {
      width: min(1040px, calc(100% - 40px));
      min-height: 58px;
      margin: auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 24px;
    }
    .brand { color: var(--ink); font-weight: 760; letter-spacing: -.02em; font-size: 16px; }
    .nav-links { display: flex; align-items: center; gap: 24px; }
    .nav-links a { color: var(--muted); font-size: 13px; font-weight: 620; letter-spacing: .01em; }
    .nav-links a:hover { color: var(--ink); }

    .page { width: min(980px, calc(100% - 40px)); margin: 0 auto; padding: 34px 0 64px; }
    .hero {
      display: grid;
      grid-template-columns: 152px 1fr;
      gap: 34px;
      align-items: center;
      padding: 18px 0 30px;
    }
    .portrait-wrap { position: relative; }
    .portrait-wrap::after { content: none; }
    .portrait {
      position: relative;
      z-index: 1;
      width: 152px;
      aspect-ratio: 4/5;
      object-fit: cover;
      object-position: center top;
      border-radius: 8px;
      background: #e7ebf0;
    }
    .eyebrow { margin: 0 0 6px; color: var(--accent); font-size: 10.5px; font-weight: 760; letter-spacing: .14em; text-transform: uppercase; }
    h1 { margin: 0; font: 700 clamp(31px, 4vw, 44px)/1.06 var(--serif); letter-spacing: -.035em; }
    .chinese-name { margin-left: 10px; color: var(--soft); font: 400 .54em/1 var(--sans); letter-spacing: .02em; white-space: nowrap; }
    .role { margin: 10px 0 14px; color: var(--muted); font-size: 15px; }
    .motto { margin: 0 0 12px; color: var(--soft); font: italic 13px/1.5 var(--serif); }
    .intro { max-width: 720px; margin: 0; color: #344154; font-size: 14px; }
    .intro strong { color: var(--ink); font-weight: 680; }
    .profile-meta { display: flex; flex-wrap: wrap; gap: 6px 18px; margin-top: 11px; color: var(--muted); font-size: 12.5px; }
    .profile-meta span::before { content: "·"; margin-right: 7px; color: var(--accent); font-weight: 800; }
    .actions { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 18px; }
    .button {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      min-height: 36px;
      padding: 7px 12px;
      border: 1px solid var(--line);
      border-radius: 9px;
      color: var(--ink);
      background: var(--paper);
      font-size: 13px;
      font-weight: 660;
      transition: transform .18s ease, border-color .18s ease, box-shadow .18s ease;
    }
    .button:hover { transform: translateY(-1px); border-color: #aebdce; color: var(--ink); box-shadow: 0 6px 18px rgba(25, 42, 66, .08); }
    .button.primary { color: white; background: var(--accent); border-color: var(--accent); }
    .button.primary:hover { color: white; background: var(--accent-strong); border-color: var(--accent-strong); }
    .button svg { width: 16px; height: 16px; fill: currentColor; }

    .about-section { padding-top: 30px; }
    .about-section .section-head { grid-template-columns: 170px 1fr; align-items: start; margin-bottom: 22px; }
    .about-section h2 { font: 720 21px/1.3 var(--sans); letter-spacing: -.015em; white-space: nowrap; }
    .about-copy { color: #344154; font-size: 14.5px; }
    .about-copy p { margin: 0 0 10px; }
    .about-copy strong { color: var(--ink); font-weight: 680; }

    .focus-strip {
      display: grid;
      grid-template-columns: 132px 1fr;
      gap: 22px;
      margin: 0;
      padding: 14px 0;
      border-top: 1px solid var(--line);
      border-bottom: 1px solid var(--line);
    }
    .focus-strip b { font-size: 10.5px; letter-spacing: .1em; text-transform: uppercase; }
    .focus-strip span { color: var(--muted); font-size: 13.5px; }

    section { padding-top: 52px; }
    .section-head { display: grid; grid-template-columns: 220px minmax(0, 1fr); gap: 26px; margin-bottom: 24px; align-items: end; }
    .section-kicker { color: var(--accent); font-size: 11px; font-weight: 760; letter-spacing: .15em; text-transform: uppercase; }
    h2 { margin: 4px 0 0; font: 700 clamp(28px, 4vw, 39px)/1.12 var(--serif); letter-spacing: -.025em; }
    .section-note { margin: 0; color: var(--muted); max-width: 680px; }

    .news-list { list-style: none; margin: 0; padding: 0; border-top: 1px solid var(--line); }
    .news-item { display: grid; grid-template-columns: 98px 1fr; gap: 24px; padding: 15px 0; border-bottom: 1px solid var(--line); }
    .news-date { color: var(--soft); font: 650 12px/1.72 var(--sans); letter-spacing: .04em; }
    .news-item strong { color: var(--ink); }
    details.news-more { margin-top: 14px; }
    details.news-more summary { cursor: pointer; color: var(--accent); font-weight: 650; font-size: 13px; }
    details.news-more[open] summary { margin-bottom: 14px; }

    .papers { border-top: 1px solid var(--line); }
    .paper {
      display: grid;
      grid-template-columns: 205px 1fr;
      min-height: 160px;
      padding: 22px 0;
      border-bottom: 1px solid var(--line);
      background: var(--paper);
    }
    .paper:hover { background: #fbfcfe; }
    .paper-media { min-height: 150px; padding: 4px 20px 4px 0; display: grid; place-items: center; }
    .paper-media img { width: 100%; max-height: 145px; object-fit: contain; border-radius: 5px; }
    .paper-body { padding: 0; }
    .paper-topline { display: flex; justify-content: space-between; gap: 16px; align-items: flex-start; }
    .paper h3 { margin: 0; font: 700 18px/1.34 var(--serif); letter-spacing: -.01em; }
    .venue { flex: 0 0 auto; padding: 4px 8px; border-radius: 6px; background: var(--accent-wash); color: var(--accent-strong); font-size: 11px; font-weight: 760; letter-spacing: .03em; }
    .authors { margin: 8px 0 0; color: var(--muted); font-size: 12.5px; line-height: 1.55; }
    .authors b { color: var(--ink); font-weight: 720; }
    .paper-desc { margin: 8px 0 0; color: #455267; font-size: 13px; line-height: 1.58; }
    .paper-links { display: flex; flex-wrap: wrap; gap: 8px 14px; margin-top: 12px; }
    .paper-links a { font-size: 12.5px; font-weight: 680; }
    .paper-links a::after { content: " ↗"; font-size: 10px; }
    .repo-stats { display: flex; flex-wrap: wrap; align-items: center; gap: 5px; margin-top: 9px; }
    .repo-stats a { display: inline-flex; line-height: 1; }
    .repo-stats img { width: auto; height: 18px; border-radius: 3px; }
    .equal-note { margin: -14px 0 18px; color: var(--soft); font-size: 13.5px; line-height: 1.55; }

    .timeline { border-left: 1px solid #cfd7e1; margin-left: 8px; }
    .timeline-item { position: relative; display: grid; grid-template-columns: 135px 1fr; gap: 28px; padding: 0 0 32px 30px; }
    .timeline-item::before { content: ""; position: absolute; width: 9px; height: 9px; left: -5px; top: 8px; border-radius: 50%; background: var(--paper); border: 2px solid var(--accent); }
    .timeline-date { color: var(--soft); font-size: 12px; font-weight: 650; }
    .timeline-item h3 { margin: 0; font: 700 18px/1.35 var(--serif); }
    .timeline-item .position { color: var(--accent); font-size: 13px; font-weight: 680; }
    .timeline-item p { margin: 5px 0 0; color: var(--muted); font-size: 13.5px; }

    .honors { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 12px; }
    .honor { padding: 18px 20px; border: 1px solid var(--line); border-radius: 12px; background: var(--paper); }
    .honor b { display: block; font: 700 16px/1.35 var(--serif); }
    .honor span { display: block; margin-top: 4px; color: var(--muted); font-size: 12.5px; }

    .visitor-map { display: flex; flex-direction: column; align-items: center; gap: 8px; min-height: 180px; padding: 14px 0; border-top: 1px solid var(--line); border-bottom: 1px solid var(--line); }
    #visitors h2 { font: 720 21px/1.3 var(--sans); letter-spacing: -.015em; white-space: nowrap; }
    .map-widget { width: min(100%, 320px); aspect-ratio: 2 / 1; overflow: hidden; border: 1px solid var(--line); border-radius: 9px; background: #f6f8fb; }
    .map-widget iframe { display: block; width: 100% !important; height: 100% !important; border: 0 !important; }
    .visitor-link { font-size: 12.5px; font-weight: 680; }

    footer { margin-top: 76px; padding-top: 22px; border-top: 1px solid var(--line); display: flex; justify-content: space-between; gap: 20px; color: var(--soft); font-size: 12px; }

    @media (max-width: 780px) {
      .nav { min-height: 58px; }
      .nav-links { gap: 14px; }
      .nav-links a:nth-child(4) { display: none; }
      .page { padding-top: 24px; }
      .hero { grid-template-columns: 1fr; gap: 24px; padding: 16px 0 24px; }
      .portrait-wrap { width: 142px; }
      .portrait { width: 142px; }
      .focus-strip, .section-head { grid-template-columns: 1fr; gap: 10px; }
      .about-section .section-head { grid-template-columns: 1fr; }
      .paper { grid-template-columns: 1fr; }
      .paper { padding: 22px 0; }
      .paper-media { min-height: 0; height: 176px; padding: 0 0 16px; }
      .paper-media img { max-height: 164px; }
      .timeline-item { grid-template-columns: 1fr; gap: 4px; }
      .honors { grid-template-columns: 1fr; }
    }
    @media (max-width: 520px) {
      body { font-size: 15px; }
      .nav, .page { width: min(100% - 28px, 1040px); }
      .brand { font-size: 15px; }
      .nav-links a:nth-child(3) { display: none; }
      .hero { padding: 22px; border-radius: 16px; }
      .chinese-name { display: block; margin: 10px 0 0; font-size: 19px; }
      .news-item { grid-template-columns: 78px 1fr; gap: 12px; }
      .paper-body { padding: 19px; }
      .paper-topline { display: block; }
      .venue { display: inline-block; margin-top: 8px; }
      footer { display: block; }
    }
    @media (prefers-reduced-motion: reduce) {
      html { scroll-behavior: auto; }
      *, *::before, *::after { transition: none !important; }
    }
  </style>
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>
  <header class="topbar">
    <nav class="nav" aria-label="Primary navigation">
      <a class="brand" href="#top">Junhao Zhuang</a>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#news">News</a>
        <a href="#research">Research</a>
        <a href="#experience">Experience</a>
      </div>
    </nav>
  </header>

  <main id="main" class="page">
    <article class="hero" id="top">
      <div class="portrait-wrap">
        <img class="portrait" src="https://zhuang2002.github.io/images/zhuang.jpg" alt="Portrait of Junhao Zhuang">
      </div>
      <div>
        <p class="eyebrow">Researcher · Generative Intelligence</p>
        <h1>Junhao Zhuang <span class="chinese-name">庄俊豪</span></h1>
        <p class="role">JD Future Academy · Tech Genius Team (TGT)</p>
        <p class="motto">Curiosity fuels discovery.<br>Persistence unlocks the unknown.</p>
        <p class="intro">My research focuses on <strong>large-scale audio-visual generative models</strong> and <strong>interactive world models</strong> for games and real-world environments.</p>
        <div class="profile-meta" aria-label="Profile details">
          <span>China</span><span>Tsinghua University</span>
        </div>
        <div class="actions" aria-label="Contact and profiles">
          <a class="button primary" href="mailto:zhuangjh23@tsinghua.org.cn" aria-label="Email Junhao Zhuang">
            <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M20 4H4a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h16a2 2 0 0 0 2-2V6c0-1.1-.9-2-2-2Zm0 4-8 5-8-5V6l8 5 8-5v2Z"/></svg>
            Email
          </a>
          <a class="button" href="https://github.com/zhuang2002" target="_blank" rel="noopener">
            <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 .7a12 12 0 0 0-3.8 23.4c.6.1.8-.3.8-.6v-2.3c-3.3.7-4-1.4-4-1.4-.5-1.4-1.3-1.8-1.3-1.8-1.1-.7.1-.7.1-.7 1.2.1 1.8 1.2 1.8 1.2 1.1 1.8 2.8 1.3 3.5 1 .1-.8.4-1.3.8-1.6-2.7-.3-5.5-1.3-5.5-5.9 0-1.3.5-2.4 1.2-3.2-.1-.3-.5-1.5.1-3.2 0 0 1-.3 3.3 1.2a11.4 11.4 0 0 1 6 0C16.6 5.5 17.6 5.8 17.6 5.8c.7 1.7.3 2.9.1 3.2.8.8 1.2 1.9 1.2 3.2 0 4.6-2.8 5.6-5.5 5.9.4.4.8 1.1.8 2.2v3.2c0 .3.2.7.8.6A12 12 0 0 0 12 .7Z"/></svg>
            GitHub
          </a>
          <a class="button" href="https://scholar.google.co.in/citations?user=J3olRccAAAAJ&amp;hl=en" target="_blank" rel="noopener">Google Scholar</a>
        </div>
      </div>
    </article>

    <section class="about-section" id="about" aria-labelledby="about-title">
      <div class="section-head">
        <div><span class="section-kicker">Profile</span><h2 id="about-title">👋 About Me</h2></div>
        <div class="about-copy">
          <p>I am currently a <strong>Researcher</strong> at <strong>JD Future Academy, JD.com</strong>, as a member of the <strong>Tech Genius Team (TGT)</strong>.</p>
          <p>I received my Master’s degree in Computer Technology from <strong>Tsinghua University</strong> in 2026, under the supervision of <strong>Prof. Chun Yuan</strong>. I obtained my Bachelor’s degree in Computer Science and Technology from the <strong>Yingcai Honors College at the University of Electronic Science and Technology of China</strong> in 2023, where I was fortunate to be advised by <strong>Prof. Xile Zhao</strong>.</p>
          <p>Previously, I worked as a <strong>Research Assistant</strong> at <strong>MMLab, The Chinese University of Hong Kong (CUHK)</strong>, under the supervision of <strong>Prof. Tianfan Xue</strong>.</p>
          <p>My research focuses on large-scale audio-visual generative models and interactive world models for games and real-world environments.</p>
        </div>
      </div>
    </section>

    <div class="focus-strip">
      <b>Research focus</b>
      <span>Audio-visual generation · Interactive world models · Autoregressive video diffusion models · Long video generation · Efficient visual synthesis</span>
    </div>

    <section id="news" aria-labelledby="news-title">
      <div class="section-head">
        <div><span class="section-kicker">Updates</span><h2 id="news-title">News</h2></div>
        <p class="section-note">Recent releases, publications, and research milestones.</p>
      </div>
      <ul class="news-list">
        <li class="news-item"><span class="news-date">2026 · 07</span><span>Two papers accepted to <a href="https://asia.siggraph.org/2026/"><strong>SIGGRAPH Asia 2026</strong></a>.</span></li>
        <li class="news-item"><span class="news-date">2026 · 06</span><span>One paper accepted to <a href="https://eccv.ecva.net/"><strong>ECCV 2026</strong></a>.</span></li>
        <li class="news-item"><span class="news-date">2026 · 05</span><span>Released <a href="https://echo-team-joy-future-academy-jd.github.io/Echo-LongVideo-Page/" target="_blank" rel="noopener"><strong>JoyAI-Echo</strong></a>.</span></li>
        <li class="news-item"><span class="news-date">2026 · 05</span><span>One paper accepted to <a href="https://icml.cc/"><strong>ICML 2026</strong></a>.</span></li>
        <li class="news-item"><span class="news-date">2026 · 04</span><span>One paper accepted to <a href="https://www.computer.org/csdl/journal/tp"><strong>IEEE TPAMI</strong></a>.</span></li>
        <li class="news-item"><span class="news-date">2026 · 02</span><span>One paper accepted to <a href="https://cvpr.thecvf.com/"><strong>CVPR 2026</strong></a>.</span></li>
      </ul>
      <details class="news-more">
        <summary>Earlier news</summary>
        <ul class="news-list">
          <li class="news-item"><span class="news-date">2025 · 09</span><span>One paper accepted to <a href="https://neurips.cc/"><strong>NeurIPS 2025</strong></a>.</span></li>
          <li class="news-item"><span class="news-date">2025 · 04</span><span>Two papers accepted to <a href="https://www.siggraph.org/siggraph-events/conferences/"><strong>SIGGRAPH 2025</strong></a>.</span></li>
          <li class="news-item"><span class="news-date">2024 · 12</span><span>One paper accepted to <a href="https://2025.ieeeicassp.org/important-dates/"><strong>ICASSP 2025</strong></a>.</span></li>
          <li class="news-item"><span class="news-date">2024 · 07</span><span>One paper accepted to <a href="https://eccv.ecva.net/"><strong>ECCV 2024</strong></a>.</span></li>
          <li class="news-item"><span class="news-date">2022 · 06</span><span>One paper accepted to <a href="https://2022.acmmm.org/"><strong>ACM MM 2022</strong></a>.</span></li>
        </ul>
      </details>
    </section>

    <section id="research" aria-labelledby="research-title">
      <div class="section-head">
        <div><span class="section-kicker">Selected work</span><h2 id="research-title">Research</h2></div>
        <p class="section-note">Research spanning persistent audio-visual worlds, long-form video generation, visual editing, and restoration.</p>
      </div>
      <p class="equal-note">* indicates equal contribution.</p>
      <div class="papers">
        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/echo1p5.png" alt="JoyAI-Echo-1.5 project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>JoyAI-Echo-1.5: Long-Horizon Audio-Visual Generation for Persistent Stories and Interactive Worlds</h3><span class="venue">Tech Report · 2026</span></div>
            <p class="authors">Nan Duan, Haoyang Huang, Weiyang Jin, Haoran Li, Yaowei Li, Yuming Li, Yijun Liu, Xin Lu, Xiaoxiao Ma, Yanwen Ma, Yaofeng Su, Yilang Sun, Haoyu Wang, Zeyue Xue, Songchun Zhang, <b>Junhao Zhuang</b></p>
            <p class="paper-desc">JoyAI‑Echo‑1.5 is a unified audio‑visual generation system featuring two purpose‑built variants: a long‑video variant with composable cross‑shot memory for sustained identity consistency, and a world‑model variant with geometry‑aware 6‑DoF camera control for interactive viewpoint navigation.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2608.23383">Paper</a><a href="https://echo-team-joy-future-academy-jd.github.io/Echo-1.5-Page">Project</a><a href="https://github.com/jd-opensource/JoyAI-Echo">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/jd-opensource/JoyAI-Echo"><img src="https://img.shields.io/github/stars/jd-opensource/JoyAI-Echo?style=social" alt="GitHub stars for JoyAI-Echo"></a><a href="https://github.com/jd-opensource/JoyAI-Echo/forks"><img src="https://img.shields.io/github/forks/jd-opensource/JoyAI-Echo?style=social" alt="GitHub forks for JoyAI-Echo"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/EchoWM.png" alt="EchoWM project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>EchoWM: Open and Enterable Omnimodal World Models</h3><span class="venue">Tech Report · 2026</span></div>
            <p class="authors">Songchun Zhang*, Yaowei Li*, <b>Junhao Zhuang*</b>, Weiyang Jin*, Haoyu Wang, Xin Lu, Shiyi Zhang, Haoran Li, Xiaoxiao Ma, Yumin Li, Yijun Liu, Yaofeng Su, Yanwen Ma, Haoyu Wu, Zihan Su, Yue Ma, Lvmin Zhang, Haoyang Huang, Zeyue Xue, Anyi Rao, Nan Duan</p>
            <p class="paper-desc">An omnimodal world model for generative media that responds to continuous navigation while video, environmental sound, music, and speech evolve together. I proposed <strong>Short-Horizon and Long-Horizon Audio-Visual Self-Gradient Forcing</strong> and was responsible for EchoWM’s <strong>causal training</strong>.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2608.23189">Paper</a><a href="https://echo-team-joy-future-academy-jd.github.io/Echo-1.5-Page">Project</a><a href="https://github.com/jd-opensource/JoyAI-Echo">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/jd-opensource/JoyAI-Echo"><img src="https://img.shields.io/github/stars/jd-opensource/JoyAI-Echo?style=social" alt="GitHub stars for JoyAI-Echo"></a><a href="https://github.com/jd-opensource/JoyAI-Echo/forks"><img src="https://img.shields.io/github/forks/jd-opensource/JoyAI-Echo?style=social" alt="GitHub forks for JoyAI-Echo"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/SGF.jpg" alt="Self Gradient Forcing project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>Self Gradient Forcing: Native Long Video Extrapolation</h3><span class="venue">Tech Report · 2026</span></div>
            <p class="authors"><b>Junhao Zhuang</b>, Shiyi Zhang, Yuxuan Bian, Yaowei Li, Yawen Luo, Weiyang Jin, Songchun Zhang, et al.</p>
            <p class="paper-desc">Self Gradient Forcing (SGF) recovers the missing context-gradient path for self-generated causal memory through a bounded two-pass replay, enabling models trained with only a 5-second window to extrapolate to minute-scale videos with stronger identity, layout, and temporal stability. It also supports the causal training of <strong>EchoWM</strong>.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2607.20368">Paper</a><a href="/SelfGradientForcing/">Project</a><a href="https://github.com/zhuang2002/Self_Gradient_Forcing">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/zhuang2002/Self_Gradient_Forcing"><img src="https://img.shields.io/github/stars/zhuang2002/Self_Gradient_Forcing?style=social" alt="GitHub stars for Self Gradient Forcing"></a><a href="https://github.com/zhuang2002/Self_Gradient_Forcing/forks"><img src="https://img.shields.io/github/forks/zhuang2002/Self_Gradient_Forcing?style=social" alt="GitHub forks for Self Gradient Forcing"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/joyai_echo.png" alt="JoyAI-Echo project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>JoyAI-Echo: Pushing the Frontier of Long Audio-Visual Generation</h3><span class="venue">Tech Report · 2026</span></div>
            <p class="authors">Haoran Li, Fredreic Li, …, <b>Junhao Zhuang</b>, …, Zeyue Xue, Nan Duan</p>
            <p class="paper-desc">JoyAI-Echo is an interactive long video generation framework with boosted speed, stable audio-visual consistency and real-time editing, outperforming baseline models.</p>
            <div class="paper-links"><a href="https://www.researchgate.net/publication/405770309_JoyAI-Echo_Pushing_the_Frontier_of_Long_Audio-Visual_Generation">Paper</a><a href="https://echo-team-joy-future-academy-jd.github.io/Echo-LongVideo-Page/">Project</a><a href="https://github.com/jd-opensource/JoyAI-Echo">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/jd-opensource/JoyAI-Echo"><img src="https://img.shields.io/github/stars/jd-opensource/JoyAI-Echo?style=social" alt="GitHub stars for JoyAI-Echo"></a><a href="https://github.com/jd-opensource/JoyAI-Echo/forks"><img src="https://img.shields.io/github/forks/jd-opensource/JoyAI-Echo?style=social" alt="GitHub forks for JoyAI-Echo"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/shotstream_logo.png" alt="ShotStream project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>ShotStream: Streaming Multi-Shot Video Generation for Interactive Storytelling</h3><span class="venue">ECCV · 2026</span></div>
            <p class="authors">Yawen Luo, Xiaoyu Shi, <b>Junhao Zhuang</b>, Yutian Chen, Quande Liu, Xintao Wang, Pengfei Wan, Tianfan Xue</p>
            <p class="paper-desc">ShotStream is a novel causal multi-shot architecture that enables interactive storytelling and efficient on-the-fly frame generation, achieving 16 FPS on a single NVIDIA GPU.</p>
            <div class="paper-links"><a href="https://arxiv.org/pdf/2603.25746">Paper</a><a href="https://luo0207.github.io/ShotStream/">Project</a><a href="https://github.com/KlingAIResearch/ShotStream">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/KlingAIResearch/ShotStream"><img src="https://img.shields.io/github/stars/KlingAIResearch/ShotStream?style=social" alt="GitHub stars for ShotStream"></a><a href="https://github.com/KlingAIResearch/ShotStream/forks"><img src="https://img.shields.io/github/forks/KlingAIResearch/ShotStream?style=social" alt="GitHub forks for ShotStream"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/FlashVSR/flowchart.jpg" alt="FlashVSR project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>FlashVSR: Towards Real-Time Diffusion-Based Streaming Video Super-Resolution</h3><span class="venue">CVPR · 2026</span></div>
            <p class="authors"><b>Junhao Zhuang</b>, Shi Guo, Xin Cai, Xiaohui Li, Yihao Liu, Chun Yuan, Tianfan Xue</p>
            <p class="paper-desc">FlashVSR is a streaming, one-step diffusion-based video super-resolution framework with block-sparse attention and a Tiny Conditional Decoder. It reaches ~17 FPS at 768×1408 on a single A100 GPU. A Locality-Constrained Attention design further improves generalization and perceptual quality on ultra-high-resolution videos.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2510.12747">Paper</a><a href="/FlashVSR/">Project</a><a href="https://github.com/OpenImagingLab/FlashVSR">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/OpenImagingLab/FlashVSR"><img src="https://img.shields.io/github/stars/OpenImagingLab/FlashVSR?style=social" alt="GitHub stars for FlashVSR"></a><a href="https://github.com/OpenImagingLab/FlashVSR/forks"><img src="https://img.shields.io/github/forks/OpenImagingLab/FlashVSR?style=social" alt="GitHub forks for FlashVSR"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/cobra.png" alt="Cobra project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>Cobra: Efficient Line Art COlorization with BRoAder References</h3><span class="venue">SIGGRAPH · 2025</span></div>
            <p class="authors"><b>Junhao Zhuang</b>, Lingen Li, Xuan Ju, Zhaoyang Zhang, Chun Yuan, Ying Shan</p>
            <p class="paper-desc">Cobra is a novel efficient long-context fine-grained ID preservation framework for line art colorization, achieving high precision, efficiency, and flexible usability for comic colorization. By effectively integrating extensive contextual references, it transforms black-and-white line art into vibrant illustrations.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2504.12240">Paper</a><a href="/Cobra/">Project</a><a href="https://github.com/Zhuang2002/Cobra">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/Zhuang2002/Cobra"><img src="https://img.shields.io/github/stars/Zhuang2002/Cobra?style=social" alt="GitHub stars for Cobra"></a><a href="https://github.com/Zhuang2002/Cobra/forks"><img src="https://img.shields.io/github/forks/Zhuang2002/Cobra?style=social" alt="GitHub forks for Cobra"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/method.jpg" alt="FlexiAct project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>FlexiAct: Towards Flexible Action Control in Heterogeneous Scenarios</h3><span class="venue">SIGGRAPH · 2025</span></div>
            <p class="authors">Shiyi Zhang*, <b>Junhao Zhuang*</b>, Zhaoyang Zhang, Yansong Tang</p>
            <p class="paper-desc">We achieve action transfer in heterogeneous scenarios with varying spatial structures or cross-domain subjects.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2505.03730">Paper</a><a href="https://shiyi-zh0408.github.io/projectpages/FlexiAct/">Project</a><a href="https://github.com/shiyi-zh0408/FlexiAct">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/shiyi-zh0408/FlexiAct"><img src="https://img.shields.io/github/stars/shiyi-zh0408/FlexiAct?style=social" alt="GitHub stars for FlexiAct"></a><a href="https://github.com/shiyi-zh0408/FlexiAct/forks"><img src="https://img.shields.io/github/forks/shiyi-zh0408/FlexiAct?style=social" alt="GitHub forks for FlexiAct"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/ppt.png" alt="PowerPaint project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>A Task is Worth One Word: Learning with Task Prompts for High-Quality Versatile Image Inpainting</h3><span class="venue">ECCV · 2024</span></div>
            <p class="authors"><b>Junhao Zhuang</b>, Yanhong Zeng, Wenran Liu, Chun Yuan, Kai Chen</p>
            <p class="paper-desc">PowerPaint is the first versatile image inpainting model that simultaneously achieves state-of-the-art results in various inpainting tasks such as text-guided object inpainting, context-aware image inpainting, shape-guided object inpainting with controllable shape-fitting, and outpainting.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2312.03594">Paper</a><a href="https://powerpaint.github.io/">Project</a><a href="https://github.com/open-mmlab/PowerPaint">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/open-mmlab/PowerPaint"><img src="https://img.shields.io/github/stars/open-mmlab/PowerPaint?style=social" alt="GitHub stars for PowerPaint"></a><a href="https://github.com/open-mmlab/PowerPaint/forks"><img src="https://img.shields.io/github/forks/open-mmlab/PowerPaint?style=social" alt="GitHub forks for PowerPaint"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/BrushEdit.jpg" alt="BrushEdit project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>BrushEdit: All-In-One Image Inpainting and Editing</h3><span class="venue">TPAMI · 2025</span></div>
            <p class="authors">Yaowei Li, Yuxuan Bian, Xuan Ju, Zhaoyang Zhang, <b>Junhao Zhuang</b>, Ying Shan, Yuexian Zou, Qiang Xu</p>
            <p class="paper-desc">BrushEdit is an all-in-one image inpainting and editing framework that combines multimodal large language models (MLLMs) with the enhanced dual-branch diffusion inpainting model BrushNetX. It supports free-form instruction-guided interactive editing, achieves superior performance in background preservation and text alignment, and provides a user-friendly multi-round editing experience.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2412.10316">Paper</a><a href="https://liyaowei-stu.github.io/project/BrushEdit/">Project</a><a href="https://github.com/TencentARC/BrushEdit">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/TencentARC/BrushEdit"><img src="https://img.shields.io/github/stars/TencentARC/BrushEdit?style=social" alt="GitHub stars for BrushEdit"></a><a href="https://github.com/TencentARC/BrushEdit/forks"><img src="https://img.shields.io/github/forks/TencentARC/BrushEdit?style=social" alt="GitHub forks for BrushEdit"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/safesora.png" alt="Safe-Sora project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>Safe-Sora: Safe Text-to-Video Generation via Graphical Watermarking</h3><span class="venue">NeurIPS · 2025</span></div>
            <p class="authors">Zihan Su, Xuerui Qiu, Hongbin Xu, Tangyu Jiang, <b>Junhao Zhuang</b>, Chun Yuan, Ming Li, Shengfeng He, Fei Richard Yu</p>
            <p class="paper-desc">Safe-Sora: a framework for embedding graphical watermarks into video generation, achieving state-of-the-art quality, fidelity, and robustness through hierarchical adaptive matching and a 3D wavelet-enhanced Mamba architecture.</p>
            <div class="paper-links"><a href="https://arxiv.org/pdf/2505.12667">Paper</a><a href="https://sugewud.github.io/Safe-Sora-project/">Project</a><a href="https://github.com/Sugewud/Safe-Sora">Code</a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/colorflow.png" alt="ColorFlow project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>ColorFlow: Retrieval-Augmented Image Sequence Colorization</h3><span class="venue">arXiv · 2024</span></div>
            <p class="authors"><b>Junhao Zhuang*</b>, Xuan Ju*, Zhaoyang Zhang, Yong Liu, Shiyi Zhang, Chun Yuan, Ying Shan</p>
            <p class="paper-desc">ColorFlow is the first model designed for fine-grained ID preservation in image sequence colorization, utilizing contextual information. Given a reference image pool, ColorFlow accurately generates colors for various elements in black and white image sequences, including the hair color and attire of characters, ensuring color consistency with the reference images.</p>
            <div class="paper-links"><a href="https://arxiv.org/abs/2412.11815">Paper</a><a href="/ColorFlow/">Project</a><a href="https://github.com/TencentARC/ColorFlow">Code</a></div>
            <div class="repo-stats"><a href="https://github.com/TencentARC/ColorFlow"><img src="https://img.shields.io/github/stars/TencentARC/ColorFlow?style=social" alt="GitHub stars for ColorFlow"></a><a href="https://github.com/TencentARC/ColorFlow/forks"><img src="https://img.shields.io/github/forks/TencentARC/ColorFlow?style=social" alt="GitHub forks for ColorFlow"></a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/icassp.png" alt="TextureDiffusion project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>TextureDiffusion: Target Prompt Disentangled Editing for Various Texture Transfer</h3><span class="venue">ICASSP Oral · 2024</span></div>
            <p class="authors">Zihan Su, <b>Junhao Zhuang</b>, Chun Yuan</p>
            <p class="paper-desc">We proposed TextureDiffusion, a tuning-free image editing method applied to various texture transfer.</p>
            <div class="paper-links"><a href="https://arxiv.org/pdf/2409.09610">Paper</a><a href="https://github.com/THU-CVML/TextureDiffusion">Code</a></div>
          </div>
        </article>

        <article class="paper">
          <div class="paper-media"><img src="https://zhuang2002.github.io/images/uconnet.png" alt="UConNet project preview" loading="lazy"></div>
          <div class="paper-body">
            <div class="paper-topline"><h3>UConNet: Unsupervised Controllable Network for Image and Video Deraining</h3><span class="venue">ACM MM · 2022</span></div>
            <p class="authors"><b>Junhao Zhuang</b>, Yisi Luo, Xile Zhao, Taixiang Jiang, Bichuan Guo</p>
            <p class="paper-desc">We propose the UConNet for image and video deraining. Our UConNet learns a relationship between trade-off parameters of the loss function and weightings of feature maps. At the inference stage, the weightings can be adaptively controlled to handle different rain scenarios, resulting in high generalization abilities. Extensive experimental results validate the effectiveness, generalization abilities, and efficiency of UConNet.</p>
            <div class="paper-links"><a href="https://dl.acm.org/doi/10.1145/3503161.3547772">Paper</a><a href="https://github.com/zhuang2002/UConNet">Code</a></div>
          </div>
        </article>
      </div>
    </section>

    <section id="experience" aria-labelledby="experience-title">
      <div class="section-head">
        <div><span class="section-kicker">Background</span><h2 id="experience-title">Experience</h2></div>
        <p class="section-note">Research across generative video, efficient diffusion, visual restoration, and editing.</p>
      </div>
      <div class="timeline">
        <article class="timeline-item"><div class="timeline-date">Present</div><div><h3>JD Future Academy, JD.com</h3><span class="position">Researcher · Tech Genius Team (TGT)</span><p>Large-scale audio-visual generative models and interactive world models.</p></div></article>
        <article class="timeline-item"><div class="timeline-date">Sep 2025 — Present</div><div><h3>Kuaishou / KlingAI</h3><span class="position">Research Intern</span><p>Supervised by <a href="http://home.ustc.edu.cn/~myy2016/">Yunyao Mao</a> and <a href="https://xinntao.github.io/">Xintao Wang</a>.<br>Topics: Video Generation.</p></div></article>
        <article class="timeline-item"><div class="timeline-date">May — Sep 2025</div><div><h3>Shanghai AI Laboratory</h3><span class="position">Research Intern</span><p>Supervised by <a href="https://guoshi28.github.io/">Shi Guo</a> and <a href="https://tianfan.info/">Tianfan Xue</a>.<br>Topics: Video Super-Resolution · Diffusion Acceleration · Sparse Attention.</p></div></article>
        <article class="timeline-item"><div class="timeline-date">May 2024 — Apr 2025</div><div><h3>Tencent ARC Lab</h3><span class="position">Research Intern</span><p>Supervised by <a href="https://zzyfd.github.io/#/">Zhaoyang Zhang</a> and <a href="https://scholar.google.com/citations?user=4oXBp9UAAAAJ&amp;hl=en">Ying Shan</a>.<br>Topics: Comic Colorization · Video Generation · Diffusion.</p></div></article>
        <article class="timeline-item"><div class="timeline-date">Jul 2023 — Feb 2024</div><div><h3>Shanghai AI Laboratory</h3><span class="position">Research Intern</span><p>Supervised by <a href="https://zengyh1900.github.io/">Yanhong Zeng</a> and <a href="https://scholar.google.com/citations?user=eGD0b7IAAAAJ&amp;hl=en&amp;oi=sra">Kai Chen</a>.<br>Topics: Image Inpainting · Diffusion.</p></div></article>
        <article class="timeline-item"><div class="timeline-date">Class of 2026</div><div><h3>Tsinghua University</h3><span class="position">M.E. in Computer Technology</span><p>Advised by Prof. Chun Yuan. Previously a Research Assistant at MMLab, CUHK, advised by Prof. Tianfan Xue.</p></div></article>
        <article class="timeline-item"><div class="timeline-date">Class of 2023</div><div><h3>University of Electronic Science and Technology of China</h3><span class="position">B.E. in Computer Science and Technology · Yingcai Honors College</span><p>Advised by Prof. Xile Zhao.</p></div></article>
      </div>
    </section>

    <section id="honors" aria-labelledby="honors-title">
      <div class="section-head">
        <div><span class="section-kicker">Recognition</span><h2 id="honors-title">Honors</h2></div>
        <p class="section-note">Academic distinctions received during undergraduate and graduate study.</p>
      </div>
      <div class="honors">
        <div class="honor"><b>Excellent Graduate</b><span>Tsinghua University</span></div>
        <div class="honor"><b>Outstanding Master’s Degree Thesis</b><span>Tsinghua University</span></div>
        <div class="honor"><b>Comprehensive Excellence Scholarship</b><span>Tsinghua University · 2024, 2025</span></div>
        <div class="honor"><b>Outstanding Bachelor’s Degree Thesis</b><span>University of Electronic Science and Technology of China</span></div>
        <div class="honor"><b>Outstanding Student Scholarship</b><span>University of Electronic Science and Technology of China · 2020–2022</span></div>
      </div>
    </section>

    <section id="visitors" aria-labelledby="visitors-title">
      <div class="section-head">
        <div><span class="section-kicker">Audience</span><h2 id="visitors-title">Visitor Map</h2></div>
        <p class="section-note">Real-time visitor locations and traffic to this homepage.</p>
      </div>
      <div class="visitor-map">
        <div class="map-widget">
          <script id="_wau___">var _wau = window._wau || []; _wau.push(["map", "58xjuljgae", "___", "320", "160", "natural", "default-blue"]);</script>
          <script async src="https://waust.at/m.js"></script>
          <noscript><a class="visitor-link" href="https://whos.amung.us/stats/58xjuljgae/">View visitor statistics</a></noscript>
        </div>
        <a class="visitor-link" href="https://whos.amung.us/stats/58xjuljgae/">Open live visitor statistics ↗</a>
      </div>
    </section>

    <footer>
      <span>© 2026 Junhao Zhuang</span>
      <span><a href="/sitemap/">Sitemap</a> · Powered by Jekyll &amp; AcademicPages</span>
    </footer>
  </main>
</body>
</html>
