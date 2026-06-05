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



# 💫 About Me:
🎓 Academic Path: Computer Science student passionate about backend systems, AI solutions, and software architecture.<br><br>💻 What I Build: Everything from complex Data Structures & Algorithms labs to full-stack web platforms and interactive 3D simulations.<br><br>🛡️ What I Break: Actively studying cybersecurity, configuring secure Linux environments, and working through web application vulnerabilities on PortSwigger.<br><br>⚡ Core Philosophy: "The best way to understand a complex system is to build it yourself, test its limits, and leave no edge case undocumented."


## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/monst3r12e_24793) 

# 💻 Tech Stack:

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)

![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)
![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black)

![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

![Adobe Acrobat Reader](https://img.shields.io/badge/Adobe%20Acrobat%20Reader-EC1C24.svg?style=for-the-badge&logo=Adobe%20Acrobat%20Reader&logoColor=white)
![Adobe Illustrator](https://img.shields.io/badge/adobe%20illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobe%20illustrator&logoColor=white)
![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

![TOR](https://img.shields.io/badge/tor-%237E4798.svg?style=for-the-badge&logo=tor-project&logoColor=white)
![PortSwigger](https://img.shields.io/badge/PortSwigger-Labs-orange?style=for-the-badge&logo=burpsuite&logoColor=white)

# 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=MoNsT3R-code&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://streak-stats.demolab.com/?user=MoNsT3R-code&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.shion.dev/api/top-langs/?username=MoNsT3R-code&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

---
[![](https://komarev.com/ghpvc/?username=MoNsT3R-code&icon=2&color=0)](https://visitcount.itsvg.in)
