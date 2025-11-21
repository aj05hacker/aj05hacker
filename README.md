<!-- README.md: Single-file portfolio-style profile for aj05hacker -->

<!-- Animated SVG hero (pure SVG + CSS animations — supported in GitHub README) -->
<div align="center">
  <!-- Inline SVG Hero -->
  <svg xmlns="http://www.w3.org/2000/svg" width="100%" height="320" viewBox="0 0 1200 320" preserveAspectRatio="xMidYMid slice">
    <defs>
      <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
        <stop offset="0%" stop-color="#0ea5a3"/>
        <stop offset="50%" stop-color="#7c3aed"/>
        <stop offset="100%" stop-color="#ef4444"/>
      </linearGradient>
      <filter id="f1" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="20" result="b"/>
        <feBlend in="SourceGraphic" in2="b"/>
      </filter>
      <clipPath id="card-clip">
        <rect x="20" y="30" rx="18" ry="18" width="1160" height="260"/>
      </clipPath>
    </defs>

    <style>
      .bg { fill: url(#g1); opacity: 0.12; }
      .card { fill: white; stroke: rgba(0,0,0,0.04); filter: url(#f1); }
      .title { font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; font-weight:700; font-size:42px; fill: #0f172a; }
      .subtitle { font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; font-size:18px; fill:#475569; }
      .accent { fill: url(#g1); }
      .dot { fill:#ffffff; opacity:0.12; }
      .pulse { transform-origin: 50% 50%; animation: pulse 5s linear infinite; }
      .float { animation: float 8s ease-in-out infinite; }
      @keyframes pulse {
        0% { opacity: 0.10; transform: scale(1); }
        50% { opacity: 0.25; transform: scale(1.08); }
        100% { opacity: 0.10; transform: scale(1); }
      }
      @keyframes float {
        0% { transform: translateY(0px); }
        50% { transform: translateY(-8px); }
        100% { transform: translateY(0px); }
      }
      .small { font-size:12px; fill:#64748b; }
      a { text-decoration: none; }
    </style>

    <!-- background decorative blobs -->
    <rect class="bg" x="-200" y="-120" width="650" height="650" rx="180" transform="rotate(15 200 200)"/>
    <rect class="bg" x="700" y="-140" width="650" height="650" rx="180" transform="rotate(-12 1000 200)"/>

    <!-- main card -->
    <g clip-path="url(#card-clip)">
      <rect class="card" x="20" y="30" width="1160" height="260" rx="18"/>

      <!-- decorative particles -->
      <g opacity="0.9">
        <circle class="dot float" cx="70" cy="70" r="22" />
        <circle class="dot" cx="300" cy="100" r="8" />
        <circle class="dot float" cx="520" cy="60" r="14" />
        <circle class="dot" cx="980" cy="90" r="10" />
        <circle class="dot float" cx="1050" cy="200" r="24" />
      </g>

      <!-- text -->
      <text x="60" y="120" class="title">Abdul Hajees</text>
      <text x="60" y="160" class="subtitle">B.Tech (IT) · Web Developer · Freelancer · Founder of Pludo AI</text>

      <!-- badges -->
      <g transform="translate(60,175)">
        <rect x="0" y="0" rx="8" ry="8" width="170" height="36" fill="#0f172a" opacity="0.04"/>
        <text x="18" y="24" class="small">Frontend · React · Tailwind</text>
        <rect x="190" y="0" rx="8" ry="8" width="150" height="36" fill="#0f172a" opacity="0.04"/>
        <text x="208" y="24" class="small">Design · Figma</text>
        <rect x="360" y="0" rx="8" ry="8" width="170" height="36" fill="#0f172a" opacity="0.04"/>
        <text x="378" y="24" class="small">SEO · Performance</text>
      </g>

      <!-- call to action link shapes (visual only) -->
      <g transform="translate(780,120)">
        <rect x="0" y="0" rx="10" ry="10" width="320" height="58" class="accent" opacity="0.16"/>
        <text x="24" y="36" class="subtitle">Visit portfolio → me.abdulhajees.in</text>
      </g>
    </g>

    <!-- footer small text -->
    <text x="40" y="308" class="small">Portfolio · Web Development · UI/UX · AH Web Crafts</text>
  </svg>
</div>

---

# 👋 Hello — I'm **Abdul Hajees**
**B.Tech (IT)** • Web Developer • Freelancer • Founder of Pludo AI

Modern, responsive web experiences with a luxury aesthetic and practical, maintainable code.

[Portfolio](https://me.abdulhajees.in) • [LinkedIn](https://linkedin.com/in/abdulhajees) • [Email](mailto:me@abdulhajees.in) • [AH Web Crafts](https://ahwebcrafts.abdulhajees.in)

---

## 🎯 Quick Summary
I build polished, performance-first websites and frontend products. I focus on modern UI patterns, accessible markup, and fast, SEO-friendly experiences. Currently: building **Pludo AI**, a no-code AI agent builder and Pludo Coder (natural-language → React UI generator).

**Brand brief (local copy):** /mnt/data/pludo-ai-brand-description-updated.pdf

---

## 🛠 Tech Stack (visual)
<!-- Animated SVG skill bars -->
<div align="center">
  <svg width="780" height="180" viewBox="0 0 780 180" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Skill bars">
    <style>
      .bar-bg { fill:#e6eef6; rx:10; ry:10; }
      .bar { rx:10; ry:10; }
      .label { font-family: Inter, system-ui, -apple-system, Roboto, Arial; font-size:14px; fill:#0f172a; }
      .sub { font-size:12px; fill:#475569; }
      .a { fill:#0ea5a3; animation:growA 1.6s ease-out forwards; width:0; }
      .b { fill:#7c3aed; animation:growB 1.6s 0.15s ease-out forwards; width:0; }
      .c { fill:#ef4444; animation:growC 1.6s 0.3s ease-out forwards; width:0; }
      @keyframes growA { from { width:0 } to { width:520px } }
      @keyframes growB { from { width:0 } to { width:600px } }
      @keyframes growC { from { width:0 } to { width:430px } }
    </style>

    <!-- HTML-like rows -->
    <g transform="translate(20,10)">
      <text class="label" x="0" y="16">Frontend (React / Tailwind)</text>
      <rect class="bar-bg" x="0" y="22" width="740" height="18" rx="9" />
      <rect class="bar a" x="0" y="22" width="0" height="18" rx="9" />
      <text class="sub" x="752" y="36">87%</text>
    </g>

    <g transform="translate(20,60)">
      <text class="label" x="0" y="16">Design (Figma / UI)</text>
      <rect class="bar-bg" x="0" y="22" width="740" height="18" rx="9" />
      <rect class="bar b" x="0" y="22" width="0" height="18" rx="9" />
      <text class="sub" x="752" y="36">90%</text>
    </g>

    <g transform="translate(20,110)">
      <text class="label" x="0" y="16">Performance / SEO</text>
      <rect class="bar-bg" x="0" y="22" width="740" height="18" rx="9" />
      <rect class="bar c" x="0" y="22" width="0" height="18" rx="9" />
      <text class="sub" x="752" y="36">71%</text>
    </g>
  </svg>
</div>

---

## 💼 Experience & Achievements
**Freelance Web Developer** · 2023 – Present  
- Delivered 10+ responsive websites for local businesses.  
- Specialty: premium, luxury-themed UI and smooth CSS animations.  
- SEO and performance optimizations (PageSpeed results often 90+ after tuning).

**Founder — Pludo AI**  
- Building a no-code SaaS for creating deployable AI agents and frontend prototypes.  
- See brand brief (local): /mnt/data/pludo-ai-brand-description-updated.pdf

---

## 🚀 Featured Projects
- **Portfolio** — https://me.abdulhajees.in  
  Mobile-first portfolio with custom animations and a performance-first approach.

- **AH Web Crafts** — https://ahwebcrafts.abdulhajees.in  
  Business site focused on conversion and visual storytelling.

- **Project Gallery** — https://gallery.abdulhajees.in  
  Interactive project gallery with filtering and responsive layouts.

---

## 📊 GitHub Stats
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
- Website: https://me.abdulhajees.in  
- LinkedIn: https://linkedin.com/in/abdulhajees  
- Email: me@abdulhajees.in

---

## 📎 Notes & Implementation tips
- This file uses inline SVG blocks for hero and skill visuals. GitHub supports inline SVG in READMEs; it strips scripts but preserves SVG/CSS animations.  
- If any SVG doesn’t render on your profile, move the SVG into the repo (e.g., `assets/hero.svg`) and reference it with `![hero](assets/hero.svg)` or `<img src="assets/hero.svg">`.  
- If you change GitHub username, update `aj05hacker` in the GitHub Stats image URLs.  
- Local brand brief path included above: `/mnt/data/pludo-ai-brand-description-updated.pdf` (your local copy where you store the brief).

---

> ⚡ Turning ideas into exceptional digital experiences, one line of code at a time.
