<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Choi's Nursing Lab | 세명대학교 간호학과</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700&family=Playfair+Display:wght@600&display=swap" rel="stylesheet">
<style>
  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
  :root {
    --primary: #1a3a5c;
    --accent: #2e7d9f;
    --light: #e8f4f8;
    --text: #2c2c2c;
    --muted: #6b7280;
    --white: #ffffff;
    --radius: 14px;
  }
  html { scroll-behavior: smooth; }
  body { font-family: 'Noto Sans KR', sans-serif; color: var(--text); background: #f9fbfd; }

  /* ── NAV ── */
  nav {
    position: fixed; top: 0; width: 100%; background: var(--primary);
    height: 64px; z-index: 1000;
    box-shadow: 0 2px 12px rgba(0,0,0,0.25);
  }
  .nav-inner {
    max-width: 1200px; margin: 0 auto; height: 100%;
    padding: 0 24px; display: flex; align-items: center; justify-content: space-between;
  }
  .nav-logo { color: #fff; font-size: 1.05rem; font-weight: 700; letter-spacing: .4px; text-decoration: none; }
  .nav-logo span { color: #7ec8e3; }
  .nav-links { display: flex; gap: 28px; list-style: none; }
  .nav-links a { color: rgba(255,255,255,.8); text-decoration: none; font-size: .87rem; font-weight: 500; transition: color .2s; }
  .nav-links a:hover { color: #7ec8e3; }

  /* hamburger */
  .hamburger { display: none; flex-direction: column; gap: 5px; cursor: pointer; background: none; border: none; padding: 4px; }
  .hamburger span { display: block; width: 24px; height: 2px; background: #fff; border-radius: 2px; transition: all .3s; }
  .hamburger.open span:nth-child(1) { transform: translateY(7px) rotate(45deg); }
  .hamburger.open span:nth-child(2) { opacity: 0; }
  .hamburger.open span:nth-child(3) { transform: translateY(-7px) rotate(-45deg); }

  /* mobile menu */
  .mobile-menu {
    display: none; position: fixed; top: 64px; left: 0; width: 100%;
    background: var(--primary); padding: 16px 24px 24px; z-index: 999;
    box-shadow: 0 8px 24px rgba(0,0,0,0.2);
  }
  .mobile-menu.open { display: block; }
  .mobile-menu ul { list-style: none; display: flex; flex-direction: column; gap: 4px; }
  .mobile-menu a {
    display: block; color: rgba(255,255,255,.85); text-decoration: none;
    padding: 12px 16px; border-radius: 8px; font-size: .95rem; font-weight: 500;
    transition: background .2s;
  }
  .mobile-menu a:hover { background: rgba(255,255,255,.08); color: #7ec8e3; }

  /* ── HERO ── */
  .hero {
    margin-top: 64px;
    background: linear-gradient(135deg, var(--primary) 0%, #2e5f8a 50%, #1e7fa0 100%);
    padding: clamp(60px, 10vw, 110px) 24px clamp(60px, 8vw, 90px);
    position: relative; overflow: hidden;
  }
  .hero::before, .hero::after {
    content: ''; position: absolute; border-radius: 50%; pointer-events: none;
    background: rgba(255,255,255,.04);
  }
  .hero::before { width: 380px; height: 380px; right: -80px; top: -80px; }
  .hero::after  { width: 240px; height: 240px; right: 120px; bottom: -80px; background: rgba(255,255,255,.03); }
  .hero-inner { max-width: 1200px; margin: 0 auto; position: relative; z-index: 1; }
  .hero-badge {
    display: inline-block; background: rgba(126,200,227,.18);
    border: 1px solid rgba(126,200,227,.5); color: #7ec8e3;
    padding: 5px 16px; border-radius: 20px; font-size: .78rem; margin-bottom: 20px;
  }
  .hero h1 {
    font-family: 'Playfair Display', serif;
    color: #fff; font-size: clamp(1.9rem, 5vw, 3.2rem); line-height: 1.2; margin-bottom: 10px;
  }
  .hero h1 span { color: #7ec8e3; }
  .hero-sub  { color: rgba(255,255,255,.78); font-size: clamp(.95rem, 2vw, 1.1rem); margin-bottom: 6px; }
  .hero-dept { color: rgba(255,255,255,.5); font-size: .88rem; margin-bottom: 36px; }
  .hero-tags { display: flex; flex-wrap: wrap; gap: 10px; }
  .tag {
    background: rgba(255,255,255,.1); border: 1px solid rgba(255,255,255,.22);
    color: rgba(255,255,255,.88); padding: 6px 16px; border-radius: 20px; font-size: .82rem;
  }

  /* ── COMMON SECTION ── */
  section { padding: clamp(56px, 8vw, 88px) 24px; }
  .section-inner { max-width: 1200px; margin: 0 auto; }
  .section-label { color: var(--accent); font-size: .76rem; font-weight: 700; letter-spacing: 2px; text-transform: uppercase; margin-bottom: 8px; }
  .section-title { font-size: clamp(1.4rem, 3vw, 2rem); font-weight: 700; color: var(--primary); margin-bottom: 40px; line-height: 1.3; }
  .section-title::after { content: ''; display: block; width: 44px; height: 3px; background: var(--accent); margin-top: 12px; }
  .bg-light { background: var(--light); }

  /* ── ABOUT ── */
  .about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 56px; align-items: center; }
  .about-text p { color: #444; line-height: 1.95; font-size: .96rem; margin-bottom: 16px; }
  .prof-card {
    background: var(--white); border-radius: var(--radius); padding: 36px;
    box-shadow: 0 4px 24px rgba(0,0,0,.08); border-left: 4px solid var(--accent);
  }
  .prof-name  { font-size: 1.25rem; font-weight: 700; color: var(--primary); margin-bottom: 4px; }
  .prof-title { color: var(--accent); font-size: .88rem; margin-bottom: 16px; }
  .prof-divider { border: none; border-top: 1px solid #eee; margin: 0 0 16px; }
  .prof-info  { font-size: .87rem; color: var(--muted); line-height: 2.1; }
  .prof-info a { color: var(--accent); text-decoration: none; }

  /* ── RESEARCH ── */
  .research-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 24px; }
  .research-card {
    background: var(--white); border-radius: var(--radius); padding: 32px 28px;
    box-shadow: 0 2px 16px rgba(0,0,0,.06); transition: transform .22s, box-shadow .22s;
  }
  .research-card:hover { transform: translateY(-5px); box-shadow: 0 10px 30px rgba(0,0,0,.1); }
  .r-icon  { font-size: 2rem; margin-bottom: 16px; }
  .research-card h3 { font-size: .98rem; font-weight: 700; color: var(--primary); margin-bottom: 10px; }
  .research-card p  { font-size: .84rem; color: var(--muted); line-height: 1.85; }

  /* ── PUBLICATIONS ── */
  .pub-list { display: flex; flex-direction: column; gap: 18px; }
  .pub-item {
    background: var(--white); border-radius: var(--radius); padding: 26px 30px;
    box-shadow: 0 2px 12px rgba(0,0,0,.05); border-left: 4px solid #e0e0e0;
    transition: border-color .2s;
  }
  .pub-item:hover { border-color: var(--accent); }
  .pub-year    { font-size: .76rem; color: var(--accent); font-weight: 700; letter-spacing: 1px; text-transform: uppercase; margin-bottom: 6px; }
  .pub-title   { font-size: .96rem; font-weight: 600; color: var(--primary); margin-bottom: 6px; }
  .pub-journal { font-size: .84rem; color: var(--muted); }
  .pub-note    { display: inline-block; margin-top: 8px; font-size: .74rem; background: #fff3cd; color: #856404; padding: 2px 10px; border-radius: 10px; }

  /* ── MEMBERS ── */
  .members-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 22px; }
  .member-card {
    background: var(--white); border-radius: var(--radius); padding: 28px 18px; text-align: center;
    box-shadow: 0 2px 14px rgba(0,0,0,.06);
  }
  .m-avatar {
    width: 70px; height: 70px; border-radius: 50%;
    background: linear-gradient(135deg, var(--primary), var(--accent));
    display: flex; align-items: center; justify-content: center;
    font-size: 1.5rem; color: #fff; margin: 0 auto 14px;
  }
  .m-name { font-weight: 700; font-size: .94rem; color: var(--primary); margin-bottom: 4px; }
  .m-role { font-size: .8rem; color: var(--muted); }

  /* ── CONTACT ── */
  .contact-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 48px; }
  .contact-list  { display: flex; flex-direction: column; gap: 20px; }
  .contact-item  { display: flex; align-items: flex-start; gap: 16px; }
  .c-icon {
    width: 44px; height: 44px; border-radius: 10px; flex-shrink: 0;
    background: var(--light); display: flex; align-items: center; justify-content: center; font-size: 1.15rem;
  }
  .c-label { font-size: .76rem; color: var(--muted); font-weight: 700; text-transform: uppercase; letter-spacing: 1px; }
  .c-value { font-size: .94rem; color: var(--text); margin-top: 3px; line-height: 1.6; }
  .c-value a { color: var(--accent); text-decoration: none; }
  .contact-cta {
    background: var(--primary); border-radius: var(--radius); padding: 36px;
    color: #fff; display: flex; flex-direction: column; justify-content: center;
  }
  .contact-cta h3 { font-size: 1.15rem; margin-bottom: 12px; }
  .contact-cta p  { font-size: .87rem; color: rgba(255,255,255,.7); line-height: 1.85; margin-bottom: 22px; }
  .btn {
    display: inline-block; background: var(--accent); color: #fff;
    padding: 12px 26px; border-radius: 8px; font-size: .87rem; font-weight: 600;
    text-decoration: none; width: fit-content; transition: background .2s;
  }
  .btn:hover { background: #1e6a87; }

  /* ── FOOTER ── */
  footer {
    background: #111827; color: rgba(255,255,255,.5);
    text-align: center; padding: 32px 24px; font-size: .82rem; line-height: 1.9;
  }
  footer strong { color: rgba(255,255,255,.8); }
  footer a { color: rgba(255,255,255,.5); text-decoration: none; }

  /* ══════════════════════════════
     RESPONSIVE BREAKPOINTS
  ══════════════════════════════ */

  /* Tablet (≤ 960px) */
  @media (max-width: 960px) {
    .nav-links { display: none; }
    .hamburger { display: flex; }
    .about-grid { grid-template-columns: 1fr; gap: 36px; }
    .research-grid { grid-template-columns: repeat(2, 1fr); }
    .members-grid { grid-template-columns: repeat(2, 1fr); }
    .contact-grid { grid-template-columns: 1fr; gap: 32px; }
  }

  /* Mobile (≤ 600px) */
  @media (max-width: 600px) {
    section { padding: 48px 16px; }
    .hero { padding: 56px 16px 52px; }
    .hero h1 { font-size: 1.75rem; }
    .research-grid { grid-template-columns: 1fr; }
    .members-grid { grid-template-columns: repeat(2, 1fr); gap: 14px; }
    .pub-item { padding: 20px 20px; }
    .contact-cta { padding: 28px 24px; }
    .prof-card { padding: 24px; }
    .section-title { font-size: 1.35rem; }
    .hero-tags .tag { font-size: .76rem; padding: 5px 12px; }
    .about-text p { font-size: .92rem; }
  }

  /* Small Mobile (≤ 380px) */
  @media (max-width: 380px) {
    .members-grid { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<!-- ── NAV ── -->
<nav>
  <div class="nav-inner">
    <a class="nav-logo" href="#">Choi's <span>Nursing</span> Lab</a>
    <ul class="nav-links">
      <li><a href="#about">소개</a></li>
      <li><a href="#research">연구 분야</a></li>
      <li><a href="#publications">논문</a></li>
      <li><a href="#members">구성원</a></li>
      <li><a href="#contact">연락처</a></li>
    </ul>
    <button class="hamburger" id="hamburger" aria-label="메뉴 열기">
      <span></span><span></span><span></span>
    </button>
  </div>
</nav>

<!-- Mobile Menu -->
<div class="mobile-menu" id="mobileMenu">
  <ul>
    <li><a href="#about"        onclick="closeMenu()">소개</a></li>
    <li><a href="#research"     onclick="closeMenu()">연구 분야</a></li>
    <li><a href="#publications" onclick="closeMenu()">논문</a></li>
    <li><a href="#members"      onclick="closeMenu()">구성원</a></li>
    <li><a href="#contact"      onclick="closeMenu()">연락처</a></li>
  </ul>
</div>

<!-- ── HERO ── -->
<section class="hero">
  <div class="hero-inner">
    <div class="hero-badge">세명대학교 간호학과</div>
    <h1>Choi's <span>Nursing</span> Lab</h1>
    <p class="hero-sub">최희정 교수 연구실</p>
    <p class="hero-dept">Semyung University · Department of Nursing</p>
    <div class="hero-tags">
      <span class="tag">🧠 발달장애</span>
      <span class="tag">📊 불확실성이론</span>
      <span class="tag">💊 간호민감결과</span>
      <span class="tag">🔗 사회연결망분석</span>
      <span class="tag">🌐 정보연결망</span>
      <span class="tag">🔍 질적연구</span>
    </div>
  </div>
</section>

<!-- ── ABOUT ── -->
<section id="about">
  <div class="section-inner">
    <div class="about-grid">
      <div class="about-text">
        <div class="section-label">About</div>
        <h2 class="section-title">연구실 소개</h2>
        <p>Choi's Nursing Lab은 세명대학교 간호학과 소속 연구실로, 발달장애인의 건강과 삶의 질 향상을 위한 간호학적 접근을 핵심 연구 주제로 삼고 있습니다.</p>
        <p>불확실성이론을 기반으로 한 간호 이론 연구, 사회연결망분석을 활용한 정보 흐름 연구, 그리고 심층적인 질적연구 방법론을 통해 간호 실무의 근거를 마련하고 있습니다.</p>
        <p>본 연구실은 대학원생 및 연구원들이 학문적 성장을 이룰 수 있는 열린 연구 환경을 지향합니다.</p>
      </div>
      <div>
        <div class="prof-card">
          <div class="prof-name">최희정</div>
          <div class="prof-title">Prof. Hee-Jung Choi, Ph.D., RN</div>
          <hr class="prof-divider">
          <div class="prof-info">
            🏫 &nbsp;세명대학교 간호학과<br>
            🔬 &nbsp;Choi's Nursing Lab 지도교수<br>
            ✉️ &nbsp;<a href="mailto:onefruit@semyung.ac.kr">onefruit@semyung.ac.kr</a><br>
            🌐 &nbsp;세명대학교
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ── RESEARCH ── -->
<section id="research" class="bg-light">
  <div class="section-inner">
    <div class="section-label">Research Areas</div>
    <h2 class="section-title">주요 연구 분야</h2>
    <div class="research-grid">
      <div class="research-card">
        <div class="r-icon">🧠</div>
        <h3>발달장애</h3>
        <p>발달장애인 및 가족을 대상으로 한 건강 증진, 돌봄 부담, 지역사회 통합 등 간호학적 관점의 연구를 수행합니다.</p>
      </div>
      <div class="research-card">
        <div class="r-icon">📐</div>
        <h3>불확실성이론</h3>
        <p>Mishel의 불확실성이론을 중심으로 만성질환자 및 취약계층의 심리적 불확실성과 적응 과정을 탐구합니다.</p>
      </div>
      <div class="research-card">
        <div class="r-icon">💊</div>
        <h3>간호민감결과</h3>
        <p>간호 중재에 의해 직접적으로 영향 받는 환자 결과를 측정·분석하여 근거중심 간호 실무의 기반을 구축합니다.</p>
      </div>
      <div class="research-card">
        <div class="r-icon">🔗</div>
        <h3>사회연결망분석</h3>
        <p>SNA(Social Network Analysis) 방법론을 활용하여 보건의료 조직 내 관계 구조 및 정보 흐름을 분석합니다.</p>
      </div>
      <div class="research-card">
        <div class="r-icon">🌐</div>
        <h3>정보연결망</h3>
        <p>환자 및 의료인 간 건강정보 교환 네트워크를 연구하여 정보의 흐름이 건강 결과에 미치는 영향을 분석합니다.</p>
      </div>
      <div class="research-card">
        <div class="r-icon">🔍</div>
        <h3>질적연구</h3>
        <p>현상학, 근거이론, 내용분석 등 다양한 질적 연구 방법론을 통해 간호 현상의 본질을 심층 탐구합니다.</p>
      </div>
    </div>
  </div>
</section>

<!-- ── PUBLICATIONS ── -->
<section id="publications">
  <div class="section-inner">
    <div class="section-label">Publications</div>
    <h2 class="section-title">대표 논문</h2>
    <div class="pub-list">
      <div class="pub-item">
        <div class="pub-year">논문 등록 예정</div>
        <div class="pub-title">대표 논문 정보를 입력해 주세요</div>
        <div class="pub-journal">저자명 · 학술지명 · 권호 · 페이지</div>
        <span class="pub-note">📌 정보 업데이트 예정</span>
      </div>
      <div class="pub-item">
        <div class="pub-year">논문 등록 예정</div>
        <div class="pub-title">프로젝트 및 논문 정보를 제공해 주시면 업데이트합니다</div>
        <div class="pub-journal">저자명 · 학술지명 · 권호 · 페이지</div>
        <span class="pub-note">📌 정보 업데이트 예정</span>
      </div>
    </div>
  </div>
</section>

<!-- ── MEMBERS ── -->
<section id="members" class="bg-light">
  <div class="section-inner">
    <div class="section-label">People</div>
    <h2 class="section-title">연구실 구성원</h2>
    <div class="members-grid">
      <div class="member-card">
        <div class="m-avatar">👩‍🏫</div>
        <div class="m-name">최희정</div>
        <div class="m-role">지도교수</div>
      </div>
      <div class="member-card">
        <div class="m-avatar">👩‍🎓</div>
        <div class="m-name">모집 중</div>
        <div class="m-role">박사연구생</div>
      </div>
      <div class="member-card">
        <div class="m-avatar">👨‍🎓</div>
        <div class="m-name">모집 중</div>
        <div class="m-role">석사연구생</div>
      </div>
      <div class="member-card">
        <div class="m-avatar">🔬</div>
        <div class="m-name">모집 중</div>
        <div class="m-role">학부연구생</div>
      </div>
    </div>
  </div>
</section>

<!-- ── CONTACT ── -->
<section id="contact">
  <div class="section-inner">
    <div class="section-label">Contact</div>
    <h2 class="section-title">연락처 및 오시는 길</h2>
    <div class="contact-grid">
      <div class="contact-list">
        <div class="contact-item">
          <div class="c-icon">✉️</div>
          <div>
            <div class="c-label">이메일</div>
            <div class="c-value"><a href="mailto:onefruit@semyung.ac.kr">onefruit@semyung.ac.kr</a></div>
          </div>
        </div>
        <div class="contact-item">
          <div class="c-icon">🏫</div>
          <div>
            <div class="c-label">소속</div>
            <div class="c-value">세명대학교 간호학과</div>
          </div>
        </div>
        <div class="contact-item">
          <div class="c-icon">📍</div>
          <div>
            <div class="c-label">위치</div>
            <div class="c-value">충청북도 제천시 세명로 65<br>세명대학교 이학관 3층 309호 </div>
          </div>
        </div>
        <div class="contact-item">
          <div class="c-icon">⏰</div>
          <div>
            <div class="c-label">상담 가능 시간</div>
            <div class="c-value">월~금 09:00 – 18:00<br>(사전 이메일 문의 후 방문)</div>
          </div>
        </div>
      </div>
      <div class="contact-cta">
        <h3>🎓 대학원 진학 · 연구 참여 문의</h3>
        <p>저희 연구실에 관심 있으신 분들은 이메일로 먼저 연락 주시기 바랍니다. 연구 주제, 지원 절차, 장학금 등 궁금하신 사항을 편하게 문의해 주세요.</p>
        <a href="mailto:onefruit@semyung.ac.kr" class="btn">이메일 문의하기 →</a>
      </div>
    </div>
  </div>
</section>

<!-- ── FOOTER ── -->
<footer>
  <strong>Choi's Nursing Lab</strong> · 세명대학교 간호학과<br>
  충청북도 제천시 세명로 65 ·
  <a href="mailto:onefruit@semyung.ac.kr">onefruit@semyung.ac.kr</a><br><br>
  © 2025 Choi's Nursing Lab, Semyung University. All rights reserved.
</footer>

<script>
  const hamburger = document.getElementById('hamburger');
  const mobileMenu = document.getElementById('mobileMenu');
  hamburger.addEventListener('click', () => {
    hamburger.classList.toggle('open');
    mobileMenu.classList.toggle('open');
  });
  function closeMenu() {
    hamburger.classList.remove('open');
    mobileMenu.classList.remove('open');
  }
  // close menu on outside click
  document.addEventListener('click', (e) => {
    if (!hamburger.contains(e.target) && !mobileMenu.contains(e.target)) {
      closeMenu();
    }
  });
</script>
</body>
</html>
