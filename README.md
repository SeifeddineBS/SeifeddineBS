
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=DM+Sans:wght@300;400;500&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
:root{--accent:#1a7aff;--accent2:#00d2a0;--bg:var(--color-background-primary);--bg2:var(--color-background-secondary);--txt:var(--color-text-primary);--txt2:var(--color-text-secondary);--brd:var(--color-border-tertiary)}
.wrap{padding:2rem 1.5rem;font-family:'DM Sans',sans-serif;color:var(--txt);max-width:700px}
.hero{display:grid;grid-template-columns:1fr auto;align-items:start;gap:1.5rem;margin-bottom:2rem;padding-bottom:2rem;border-bottom:0.5px solid var(--brd)}
.hero-left h1{font-family:'Space Mono',monospace;font-size:22px;font-weight:700;letter-spacing:-0.5px;line-height:1.2;margin-bottom:6px}
.hero-left h1 span{color:var(--accent)}
.hero-left .role{font-size:14px;color:var(--txt2);margin-bottom:1rem;letter-spacing:0.02em}
.tag{display:inline-flex;align-items:center;gap:5px;font-size:12px;padding:4px 10px;border-radius:20px;border:0.5px solid var(--brd);color:var(--txt2);margin-right:6px;margin-bottom:6px}
.tag i{font-size:13px;color:var(--accent)}
.avatar{width:72px;height:72px;border-radius:50%;background:linear-gradient(135deg,#1a7aff22,#00d2a011);border:0.5px solid var(--brd);display:flex;align-items:center;justify-content:center;font-family:'Space Mono',monospace;font-weight:700;font-size:18px;color:var(--accent);flex-shrink:0}
.social a{display:inline-flex;align-items:center;gap:6px;font-size:13px;color:var(--accent);text-decoration:none;border:0.5px solid var(--brd);padding:5px 12px;border-radius:6px;transition:background 0.15s}
.social a:hover{background:var(--bg2)}
.section-title{font-size:11px;font-weight:500;letter-spacing:0.12em;text-transform:uppercase;color:var(--txt2);margin-bottom:1rem}
.section{margin-bottom:2rem}
.tech-grid{display:flex;flex-wrap:wrap;gap:8px}
.tech-pill{display:inline-flex;align-items:center;gap:6px;font-size:12px;font-weight:500;padding:5px 11px;border-radius:20px;border:0.5px solid var(--brd);background:var(--bg2);color:var(--txt);transition:border-color 0.15s,background 0.15s;cursor:default}
.tech-pill:hover{border-color:var(--accent);background:var(--bg)}
.tech-pill .dot{width:6px;height:6px;border-radius:50%;flex-shrink:0}
.fe .dot{background:#61dafb}.be .dot{background:#68a063}.db .dot{background:#f7931e}.lang .dot{background:#a78bfa}.tool .dot{background:#6b7280}
.stats-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
.stat-card{background:var(--bg2);border-radius:10px;padding:1rem;text-align:center}
.stat-card .num{font-family:'Space Mono',monospace;font-size:18px;font-weight:700;color:var(--txt)}
.stat-card .lbl{font-size:11px;color:var(--txt2);margin-top:3px}
.accent2{color:var(--accent2)}
.charts{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.chart-card{background:var(--bg2);border-radius:10px;padding:1rem;border:0.5px solid var(--brd)}
.chart-card img{width:100%;border-radius:6px;opacity:0.85}
.streak-card{background:var(--bg2);border-radius:10px;padding:1rem;border:0.5px solid var(--brd);margin-top:10px}
.streak-card img{width:100%;border-radius:6px;opacity:0.85}
</style>

<div class="wrap">
  <h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">GitHub profile for Seifeddine Bensalah, fullstack web developer</h2>

  <div class="hero">
    <div class="hero-left">
      <h1>Hey, I'm <span>Seifeddine</span> 👋</h1>
      <p class="role">Fullstack Web Developer · Germany</p>
      <div class="social">
        <a href="https://linkedin.com/in/seifeddinebensalah" target="_blank"><i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn</a>
      </div>
    </div>
    <div class="avatar">SB</div>
  </div>

  <div class="section">
    <p class="section-title">Frontend</p>
    <div class="tech-grid">
      <span class="tech-pill fe"><span class="dot"></span>React</span>
      <span class="tech-pill fe"><span class="dot"></span>Angular</span>
      <span class="tech-pill fe"><span class="dot"></span>TypeScript</span>
      <span class="tech-pill fe"><span class="dot"></span>JavaScript</span>
      <span class="tech-pill fe"><span class="dot"></span>Redux</span>
      <span class="tech-pill fe"><span class="dot"></span>SASS</span>
      <span class="tech-pill fe"><span class="dot"></span>Bootstrap</span>
      <span class="tech-pill fe"><span class="dot"></span>Chart.js</span>
    </div>
  </div>

  <div class="section">
    <p class="section-title">Backend</p>
    <div class="tech-grid">
      <span class="tech-pill be"><span class="dot"></span>Node.js</span>
      <span class="tech-pill be"><span class="dot"></span>Express</span>
      <span class="tech-pill be"><span class="dot"></span>Django</span>
      <span class="tech-pill be"><span class="dot"></span>Flask</span>
      <span class="tech-pill be"><span class="dot"></span>Spring</span>
      <span class="tech-pill be"><span class="dot"></span>Laravel</span>
      <span class="tech-pill be"><span class="dot"></span>Symfony</span>
      <span class="tech-pill be"><span class="dot"></span>.NET</span>
      <span class="tech-pill be"><span class="dot"></span>GraphQL</span>
    </div>
  </div>

  <div class="section">
    <p class="section-title">Databases & Cloud</p>
    <div class="tech-grid">
      <span class="tech-pill db"><span class="dot"></span>MongoDB</span>
      <span class="tech-pill db"><span class="dot"></span>MySQL</span>
      <span class="tech-pill db"><span class="dot"></span>Oracle</span>
      <span class="tech-pill db"><span class="dot"></span>Firebase</span>
      <span class="tech-pill db"><span class="dot"></span>Heroku</span>
    </div>
  </div>

  <div class="section">
    <p class="section-title">Languages & Tools</p>
    <div class="tech-grid">
      <span class="tech-pill lang"><span class="dot"></span>Python</span>
      <span class="tech-pill lang"><span class="dot"></span>Java</span>
      <span class="tech-pill lang"><span class="dot"></span>PHP</span>
      <span class="tech-pill lang"><span class="dot"></span>C / C++</span>
      <span class="tech-pill lang"><span class="dot"></span>C#</span>
      <span class="tech-pill tool"><span class="dot"></span>Git</span>
      <span class="tech-pill tool"><span class="dot"></span>Linux</span>
      <span class="tech-pill tool"><span class="dot"></span>Postman</span>
      <span class="tech-pill tool"><span class="dot"></span>Photoshop</span>
      <span class="tech-pill tool"><span class="dot"></span>Illustrator</span>
      <span class="tech-pill tool"><span class="dot"></span>MATLAB</span>
      <span class="tech-pill tool"><span class="dot"></span>Qt</span>
    </div>
  </div>

  <div class="section">
    <p class="section-title">GitHub stats</p>
    <div class="charts">
      <div class="chart-card">
        <p style="font-size:11px;color:var(--txt2);margin-bottom:8px">top languages</p>
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=seifeddinebs&show_icons=true&locale=en&layout=compact&theme=transparent&hide_border=true&title_color=1a7aff&text_color=888" alt="Top languages">
      </div>
      <div class="chart-card">
        <p style="font-size:11px;color:var(--txt2);margin-bottom:8px">activity</p>
        <img src="https://github-readme-stats.vercel.app/api?username=seifeddinebs&show_icons=true&locale=en&theme=transparent&hide_border=true&title_color=1a7aff&text_color=888&icon_color=00d2a0" alt="GitHub stats">
      </div>
    </div>
    <div class="streak-card">
      <p style="font-size:11px;color:var(--txt2);margin-bottom:8px">streak</p>
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=seifeddinebs&theme=transparent&hide_border=true&ring=1a7aff&fire=00d2a0&currStreakLabel=1a7aff" alt="GitHub streak">
    </div>
  </div>
</div>
