<p align="center">
  <svg width="100%" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="MoNsT3R-code banner">
    <defs>
      <!-- Background gradient -->
      <linearGradient id="bgGrad" x1="0" x2="1">
        <stop offset="0%" stop-color="#071023"/>
        <stop offset="100%" stop-color="#071a2b"/>
      </linearGradient>
      <!-- Colorful animated gradient for text -->
      <linearGradient id="textGrad">
        <stop offset="0%" stop-color="#00eaff" id="t0"/>
        <stop offset="50%" stop-color="#8a2be2" id="t1"/>
        <stop offset="100%" stop-color="#ff5fa2" id="t2"/>
      </linearGradient>
      <!-- Soft blurred backdrop -->
      <filter id="softBlur" x="-30%" y="-30%" width="160%" height="160%">
        <feGaussianBlur stdDeviation="12" result="blur"/>
        <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <!-- Drop shadow for text -->
      <filter id="ds" x="-50%" y="-50%" width="200%" height="200%">
        <feOffset dx="0" dy="6" result="off"/>
        <feGaussianBlur in="off" stdDeviation="10" result="blur2"/>
        <feFlood flood-color="#000000" flood-opacity="0.45"/>
        <feComposite in2="blur2" operator="in"/>
        <feMerge><feMergeNode/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <!-- animated blob path as background -->
      <radialGradient id="blobGrad" cx="50%" cy="35%">
        <stop offset="0%" stop-color="#00EAFF" stop-opacity="0.18"/>
        <stop offset="60%" stop-color="#8A2BE2" stop-opacity="0.12"/>
        <stop offset="100%" stop-color="#FF5FA2" stop-opacity="0"/>
      </radialGradient>
      <!-- Animate color stops (SMIL) -->
      <animate xlink:href="#t0" attributeName="stop-color" values="#00eaff;#00ff9c;#00eaff" dur="6s" repeatCount="indefinite"/>
      <animate xlink:href="#t1" attributeName="stop-color" values="#8a2be2;#ff5fa2;#8a2be2" dur="6s" repeatCount="indefinite"/>
      <animate xlink:href="#t2" attributeName="stop-color" values="#ff5fa2;#00eaff;#ff5fa2" dur="6s" repeatCount="indefinite"/>
    </defs>
    <!-- background -->
    <rect width="1200" height="320" fill="url(#bgGrad)"/>
    <!-- animated colorful background blobs -->
    <g filter="url(#softBlur)" opacity="0.9">
      <circle cx="920" cy="80" r="160" fill="url(#blobGrad)">
        <animate attributeName="cx" dur="10s" values="920;1020;900;920" repeatCount="indefinite"/>
        <animate attributeName="cy" dur="12s" values="80;60;100;80" repeatCount="indefinite"/>
        <animate attributeName="r" dur="8s" values="160;130;170;160" repeatCount="indefinite"/>
      </circle>
      <ellipse cx="260" cy="160" rx="220" ry="120" fill="#062a44" opacity="0.55">
        <animate attributeName="rx" dur="12s" values="220;240;200;220" repeatCount="indefinite"/>
      </ellipse>
    </g>
    <!-- translucent rounded backdrop behind name -->
    <rect x="120" y="68" rx="22" ry="22" width="960" height="120" fill="rgba(255,255,255,0.02)" stroke="rgba(255,255,255,0.03)" />
    <g filter="url(#softBlur)" opacity="0.06">
      <rect x="140" y="80" rx="18" width="920" height="96" fill="url(#blobGrad)"/>
    </g>
    <!-- Main username (very large, centered) -->
    <text x="50%" y="140" text-anchor="middle" dominant-baseline="middle"
          font-family="'Inter', 'Montserrat', 'Segoe UI', system-ui, -apple-system, Arial"
          font-size="86" font-weight="900"
          fill="url(#textGrad)" filter="url(#ds)" style="letter-spacing: -2px;">
      MoNsT3R-code
    </text>
    <!-- underline accent (animated) -->
    <line x1="360" x2="840" y1="170" y2="170" stroke="url(#textGrad)" stroke-width="6" stroke-linecap="round" opacity="0.9">
      <animate attributeName="opacity" values="0.6;1;0.6" dur="4s" repeatCount="indefinite"/>
    </line>
    <!-- Tagline -->
    <text x="50%" y="200" text-anchor="middle" font-family="Inter, Arial, sans-serif" font-size="18" fill="#bfc9d6" opacity="0.95">
      I don't wait for opportunities. I <tspan fill="#00eaff" font-weight="700">build</tspan> them.
    </text>
    <!-- Tech badges (widgets) from shields.io -->
    <g transform="translate(420,220)" style="cursor:default">
      <image href="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" x="0" y="-6" width="160" height="34"/>
      <image href="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" x="170" y="-6" width="160" height="34"/>
      <image href="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" x="340" y="-6" width="160" height="34"/>
    </g>
    <!-- small floating particles for subtle motion -->
    <g fill="#00eaff" opacity="0.06">
      <circle cx="110" cy="40" r="6">
        <animate attributeName="cy" dur="8s" values="40;20;40" repeatCount="indefinite"/>
      </circle>
      <circle cx="1060" cy="60" r="4">
        <animate attributeName="cx" dur="9s" values="1060;1080;1060" repeatCount="indefinite"/>
      </circle>
      <circle cx="700" cy="30" r="5">
        <animate attributeName="cy" dur="7s" values="30;10;30" repeatCount="indefinite"/>
      </circle>
    </g>
    <!-- subtle hover hint (if supported) -->
    <style>
      svg:hover text { transform-origin: 50% 50%; transform-box: fill-box; transition: transform 0.35s ease; }
      svg:hover text:first-of-type { transform: scale(1.02); }
    </style>
  </svg>
</p>

---

# 💫 About Me
🎓 Computer Science student focused on backend systems, AI, secure software engineering and practical cybersecurity. I build full‑stack platforms, interactive 3D simulations and homelabs — then harden and document them.

**Core:** DevSecOps mindset · Linux · Web security · Documentation-first approach

---

## 🌐 Socials
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/monst3r12e_24793)  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MoNsT3R-code)

---

## 💻 Tech Stack

<!-- Languages / Core -->
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

<!-- Web / Frontend -->
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

<!-- Backend / Databases -->
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)

<!-- AI / Data -->
![Jupyter](https://img.shields.io/badge/Jupyter-F37726?style=for-the-badge&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

<!-- Security & Tools -->
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6B35?style=for-the-badge&logo=portswigger&logoColor=white)

---

## 🚀 Featured Projects
- [EduQuest-AI-Platform](https://github.com/MoNsT3R-code/EduQuest-AI-Platform) — AI learning & interactive Jupyter notebooks  
- [fintech-tycoon-game](https://github.com/MoNsT3R-code/fintech-tycoon-game) — 3D FinTech educational game (Three.js)  
- [WaqfApp](https://github.com/MoNsT3R-code/WaqfApp) — Full‑stack TypeScript application  
- [scientific-calculator-app](https://github.com/MoNsT3R-code/scientific-calculator-app) — SPA: calculator, notes, and graph plotter

---

## 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MoNsT3R-code&theme=dark&show_icons=true&count_private=true" alt="GitHub stats" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MoNsT3R-code&theme=dark&layout=compact" alt="Top languages" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com?user=MoNsT3R-code&theme=dark" alt="GitHub streak" />
</div>

---

[![Profile views](https://komarev.com/ghpvc/?username=MoNsT3R-code&color=0)](https://komarev.com/)

---

### Notes / Upload tips
- Paste this into README.md directly (do NOT leave it inside triple-backtick code fences in README — that causes it to render as code).
- GitHub may sanitize some SVG features (filters/SMIL animations). If animation or glow is stripped, save the SVG as `assets/banner.svg` and embed it with:
  `<img src="./assets/banner.svg" alt="MoNsT3R-code banner" />`
- If you want, I can create and commit `assets/banner.svg` and a PNG fallback to your repo — say "commit banner" and I will prepare and push the files for you.
