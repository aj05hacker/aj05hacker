<!-- README.md — portfolio-style animated profile for aj05hacker -->

<div align="center">

<!-- Hero image (your uploaded PNG) -->
<img src="/mnt/data/5d44005e-ff3d-4763-b44a-0318c8c5ef66.png" alt="Abdul Hajees - Hero" width="100%" style="border-radius:12px;box-shadow:0 10px 30px rgba(12,18,26,0.12)"/>

</div>

# 👋 Hi — I'm **Abdul Hajees**
**B.Tech (IT)** · Web Developer · Freelancer · Founder of Pludo AI  
Crafting modern, responsive web experiences with luxury aesthetics and practical code.

[Portfolio](https://me.abdulhajees.in) • [LinkedIn](https://linkedin.com/in/abdulhajees) • [Email](mailto:me@abdulhajees.in) • [AH Web Crafts](https://ahwebcrafts.abdulhajees.in)

---

<!-- Inline animated SVG hero-card (pure SVG + CSS; GitHub preserves SVG/CSS in READMEs) -->
<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="100%" height="320" preserveAspectRatio="xMidYMid slice" role="img" aria-label="Hero">
  <defs>
    <linearGradient id="grad" x1="0" x2="1">
      <stop offset="0" stop-color="#06b6d4"/>
      <stop offset="0.5" stop-color="#8b5cf6"/>
      <stop offset="1" stop-color="#ef4444"/>
    </linearGradient>
    <filter id="blur">
      <feGaussianBlur stdDeviation="14" result="b"/>
      <feBlend in="SourceGraphic" in2="b"/>
    </filter>
  </defs>
  <style>
    .bg { fill: url(#grad); opacity:0.12; }
    .card { fill:#fff; stroke:rgba(2,6,23,0.04); rx:18; ry:18; filter:url(#blur); }
    .title { font-family: Inter, system-ui, Roboto, Arial; font-weight:700; font-size:42px; fill:#0f172a; }
    .subtitle { font-family: Inter, system-ui, Roboto, Arial; font-size:16px; fill:#475569; }
    .dot { fill:#fff; opacity:0.12; }
    .float { animation:float 6s ease-in-out infinite; transform-origin:center; }
    .pulse { animation:pulse 4.5s ease-in-out infinite; transform-origin:center; }
    @keyframes float { 0%{transform:translateY(0)}50%{transform:translateY(-8px)}100%{transform:translateY(0)} }
    @keyframes pulse { 0%{opacity:0.08;transform:scale(1)}50%{opacity:0.24;transform:scale(1.06)}100%{opacity:0.08;transform:scale(1)} }
    .cta { font-family: Inter, system-ui, Roboto, Arial; font-size:15px; fill:#064e3b; font-weight:600; }
    .small { font-family: Inter, system-ui, Roboto, Arial; font-size:12px; fill:#64748b; }
  </style>

  <rect class="bg" x="-200" y="-120" width="650" height="650" rx="200" transform="rotate(18)"/>
  <rect class="bg" x="700" y="-120" width="650" height="650" rx="200" transform="rotate(-12)"/>

  <g transform="translate(20,30)">
    <rect class="card" width="1160" height="260" rx="18" ry="18"/>
    <g>
      <circle class="dot float" cx="60" cy="60" r="22"/>
      <circle class="dot" cx="260" cy="90" r="8"/>
      <circle class="dot pulse" cx="520" cy="60" r="14"/>
      <circle class="dot" cx="980" cy="90" r="10"/>
      <circle class="dot float" cx="1050" cy="200" r="24"/>
    </g>

    <text x="56" y="110" class="title">Abdul Hajees</text>
    <text x="56" y="148" class="subtitle">B.Tech (IT) · Web Developer · Freelancer · Founder of Pludo AI</text>

    <g transform="translate(56,170)">
      <rect x="0" y="0" width="170" height="36" rx="8" fill="rgba(2,6,23,0.03)"/>
      <text x="18" y="24" class="small">Frontend · React · Tailwind</text>
      <rect x="190" y="0" width="160" height="36" rx="8" fill="rgba(2,6,23,0.03)"/>
      <text x="208" y="24" class="small">Design · Figma</text>
      <rect x="370" y="0" width="170" height="36" rx="8" fill="rgba(2,6,23,0.03)"/>
      <text x="388" y="24" class="small">SEO · Performance</text>
    </g>

    <g transform="translate(780,120)">
      <rect x="0" y="0" width="320" height="58" rx="12" fill="url(#grad)" opacity="0.14"/>
      <text x="24" y="36" class="cta">Visit portfolio → me.abdulhajees.in</text>
    </g>
  </g>

  <text x="40" y="310" class="small">Portfolio · Web Development · UI/UX · AH Web Crafts</text>
</svg>
</div>

---

## 🎯 Summary
I design and build modern, responsive sites focused on performance, accessibility, and clean UX. Currently building **Pludo AI** — a no-code agent & frontend generator.

---

<!-- Animated SVG skill bars -->
<div align="center">
<svg viewBox="0 0 780 180" width="780" height="180" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Skills">
  <style>
    .label { font-family: Inter, system-ui, Roboto, Arial; font-size:14px; fill:#0f172a; }
    .sub { font-size:12px; fill:#475569; font-family: Inter, system-ui, Roboto, Arial; }
    .bg { fill:#eef6fb; rx:10; ry:10; }
    .p1 { fill:#06b6d4; rx:10; ry:10; width:0; animation:grow1 1.6s forwards; }
    .p2 { fill:#8b5cf6; rx:10; ry:10; width:0; animation:grow2 1.6s 0.12s forwards; }
    .p3 { fill:#ef4444; rx:10; ry:10; width:0; animation:grow3 1.6s 0.24s forwards; }
    @keyframes grow1 { from { width:0 } to { width:520px } }
    @keyframes grow2 { from { width:0 } to { width:600px } }
    @keyframes grow3 { from { width:0 } to { width:430px } }
  </style>

  <g transform="translate(20,10)">
    <text class="label" x="0" y="16">Frontend (React · Tailwind)</text>
    <rect class="bg" x="0" y="22" width="740" height="18" rx="9"/>
    <rect class="p1" x="0" y="22" height="18" width="520"/>
    <text class="sub" x="752" y="36">87%</text>
  </g>

  <g transform="translate(20,60)">
    <text class="label" x="0" y="16">Design (Figma · UI)</text>
    <rect class="bg" x="0" y="22" width="740" height="18" rx="9"/>
    <rect class="p2" x="0" y="22" height="18" width="600"/>
    <text class="sub" x="752" y="36">90%</text>
  </g>

  <g transform="translate(20,110)">
    <text class="label" x="0" y="16">Performance / SEO</text>
    <rect class="bg" x="0" y="22" width="740" height="18" rx="9"/>
    <rect class="p3" x="0" y="22" height="18" width="430"/>
    <text class="sub" x="752" y="36">71%</text>
  </g>
</svg>
</div>

---

## 💼 Experience
**Freelance Web Developer** · 2023 – Present  
- Built and launched 10+ responsive sites.  
- Luxury-themed UI, smooth CSS animations, and SEO-first approaches.  
- Full project lifecycle: discovery → design → build → deploy.

**Founder — Pludo AI**  
- No-code AI agent builder and frontend generator (Pludo Coder).

---

## 🚀 Featured Projects
- **Portfolio** — https://me.abdulhajees.in  
- **AH Web Crafts** — https://ahwebcrafts.abdulhajees.in  
- **Project Gallery** — https://gallery.abdulhajees.in

---

## 📊 GitHub
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aj05hacker&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aj05hacker&layout=compact&theme=default&hide_border=true" alt="Top Languages" />
</div>

---

## 🎓 Education
**B.Tech — Information Technology**  
M.A.M College of Engineering and Technology · 2025

---

## 📫 Contact
Website: https://me.abdulhajees.in • LinkedIn: https://linkedin.com/in/abdulhajees • Email: me@abdulhajees.in

---

> ⚡ Turning ideas into exceptional digital experiences, one line of code at a time.
