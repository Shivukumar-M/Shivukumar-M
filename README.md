
<div align="center">
  <!-- ULTRA CREATIVE HEADER -->
  <svg width="100%" height="320" viewBox="0 0 1200 320" style="background: linear-gradient(180deg, #0f172a 0%, #1a3a3a 35%, #0a2e2e 70%, #051f1f 100%);" preserveAspectRatio="xMidYMid slice">
    <defs>
      <linearGradient id="nodeGradient" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#10b981;stop-opacity:1" />
        <stop offset="50%" style="stop-color:#06b6d4;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#059669;stop-opacity:1" />
      </linearGradient>
      <linearGradient id="textGradient" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#10b981;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:1" />
      </linearGradient>
      <linearGradient id="wavyGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#10b981;stop-opacity:0.6" />
        <stop offset="50%" style="stop-color:#06b6d4;stop-opacity:0.6" />
        <stop offset="100%" style="stop-color:#10b981;stop-opacity:0.6" />
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <filter id="strongGlow">
        <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <filter id="shadow">
        <feDropShadow dx="0" dy="2" stdDeviation="3" flood-opacity="0.5"/>
      </filter>
    </defs>

    <!-- Animated Tech Grid Background -->
    <g opacity="0.08" stroke="#10b981" stroke-width="0.5">
      <line x1="0" y1="0" x2="1200" y2="0"/>
      <line x1="0" y1="30" x2="1200" y2="30"/>
      <line x1="0" y1="60" x2="1200" y2="60"/>
      <line x1="0" y1="90" x2="1200" y2="90"/>
      <line x1="0" y1="120" x2="1200" y2="120"/>
      <line x1="0" y1="150" x2="1200" y2="150"/>
      <line x1="0" y1="180" x2="1200" y2="180"/>
      <line x1="0" y1="210" x2="1200" y2="210"/>
      <line x1="0" y1="240" x2="1200" y2="240"/>
      <line x1="0" y1="270" x2="1200" y2="270"/>
      <line x1="0" y1="300" x2="1200" y2="300"/>
      <line x1="0" y1="330" x2="1200" y2="330"/>
      <line x1="0" y1="360" x2="1200" y2="360"/>
      
      <line x1="0" y1="0" x2="0" y2="380"/>
      <line x1="120" y1="0" x2="120" y2="380"/>
      <line x1="240" y1="0" x2="240" y2="380"/>
      <line x1="360" y1="0" x2="360" y2="380"/>
      <line x1="480" y1="0" x2="480" y2="380"/>
      <line x1="600" y1="0" x2="600" y2="380"/>
      <line x1="720" y1="0" x2="720" y2="380"/>
      <line x1="840" y1="0" x2="840" y2="380"/>
      <line x1="960" y1="0" x2="960" y2="380"/>
      <line x1="1080" y1="0" x2="1080" y2="380"/>
      <line x1="1200" y1="0" x2="1200" y2="380"/>
    </g>

    <!-- DNA Helix Animation (Left) -->
    <g opacity="0.5">
      <path d="M 100 80 Q 140 60 180 80 Q 220 100 260 80 Q 300 60 340 80" stroke="#10b981" stroke-width="2" fill="none">
        <animate attributeName="stroke-dashoffset" from="0" to="30" dur="3s" repeatCount="indefinite" stroke-dasharray="20,10"/>
      </path>
      <path d="M 100 120 Q 140 100 180 120 Q 220 140 260 120 Q 300 100 340 120" stroke="#06b6d4" stroke-width="2" fill="none">
        <animate attributeName="stroke-dashoffset" from="15" to="45" dur="3s" repeatCount="indefinite" stroke-dasharray="20,10"/>
      </path>
      <line x1="100" y1="80" x2="100" y2="120" stroke="#10b981" stroke-width="1" opacity="0.4" stroke-dasharray="5,5"/>
      <line x1="180" y1="80" x2="180" y2="120" stroke="#06b6d4" stroke-width="1" opacity="0.4" stroke-dasharray="5,5"/>
      <line x1="260" y1="80" x2="260" y2="120" stroke="#10b981" stroke-width="1" opacity="0.4" stroke-dasharray="5,5"/>
    </g>

    <!-- DNA Helix Animation (Right) -->
    <g opacity="0.5">
      <path d="M 860 80 Q 900 60 940 80 Q 980 100 1020 80 Q 1060 60 1100 80" stroke="#06b6d4" stroke-width="2" fill="none">
        <animate attributeName="stroke-dashoffset" from="0" to="30" dur="3s" repeatCount="indefinite" stroke-dasharray="20,10"/>
      </path>
      <path d="M 860 120 Q 900 100 940 120 Q 980 140 1020 120 Q 1060 100 1100 120" stroke="#10b981" stroke-width="2" fill="none">
        <animate attributeName="stroke-dashoffset" from="15" to="45" dur="3s" repeatCount="indefinite" stroke-dasharray="20,10"/>
      </path>
      <line x1="860" y1="80" x2="860" y2="120" stroke="#06b6d4" stroke-width="1" opacity="0.4" stroke-dasharray="5,5"/>
      <line x1="940" y1="80" x2="940" y2="120" stroke="#10b981" stroke-width="1" opacity="0.4" stroke-dasharray="5,5"/>
      <line x1="1020" y1="80" x2="1020" y2="120" stroke="#06b6d4" stroke-width="1" opacity="0.4" stroke-dasharray="5,5"/>
    </g>

    <!-- Wavy Data Streams -->
    <path d="M 0 160 Q 150 140 300 160 T 600 160 T 900 160 T 1200 160" stroke="url(#wavyGrad)" stroke-width="2" fill="none">
      <animate attributeName="d" from="M 0 160 Q 150 140 300 160 T 600 160 T 900 160 T 1200 160" to="M 0 160 Q 150 180 300 160 T 600 160 T 900 160 T 1200 160" dur="4s" repeatCount="indefinite"/>
    </path>

    <!-- Vertical Data Flows with Particles -->
    <g filter="url(#strongGlow)">
      <line x1="250" y1="50" x2="250" y2="200" stroke="#10b981" stroke-width="3" opacity="0.4">
        <animate attributeName="opacity" from="0.2" to="0.6" dur="2s" repeatCount="indefinite"/>
      </line>
      <line x1="600" y1="50" x2="600" y2="200" stroke="#06b6d4" stroke-width="3" opacity="0.4">
        <animate attributeName="opacity" from="0.2" to="0.6" dur="2s" repeatCount="indefinite"/>
      </line>
      <line x1="950" y1="50" x2="950" y2="200" stroke="#10b981" stroke-width="3" opacity="0.4">
        <animate attributeName="opacity" from="0.2" to="0.6" dur="2s" repeatCount="indefinite"/>
      </line>
    </g>

    <!-- Floating Hexagons -->
    <g opacity="0.6" filter="url(#glow)">
      <polygon points="150,80 170,70 190,80 190,100 170,110 150,100" fill="none" stroke="#10b981" stroke-width="2">
        <animate attributeName="transform" from="translate(0,0) rotate(0 170 90)" to="translate(0,-20) rotate(360 170 90)" dur="6s" repeatCount="indefinite"/>
      </polygon>
      <polygon points="600,140 620,130 640,140 640,160 620,170 600,160" fill="none" stroke="#06b6d4" stroke-width="2">
        <animate attributeName="transform" from="translate(0,0) rotate(0 620 150)" to="translate(0,20) rotate(-360 620 150)" dur="6s" repeatCount="indefinite"/>
      </polygon>
      <polygon points="1050,80 1070,70 1090,80 1090,100 1070,110 1050,100" fill="none" stroke="#10b981" stroke-width="2">
        <animate attributeName="transform" from="translate(0,0) rotate(0 1070 90)" to="translate(0,-20) rotate(360 1070 90)" dur="6s" repeatCount="indefinite"/>
      </polygon>
    </g>

    <!-- Central Network Hub -->
    <g filter="url(#strongGlow)">
      <!-- Outer rotating ring -->
      <circle cx="600" cy="150" r="45" fill="none" stroke="#10b981" stroke-width="2" opacity="0.5">
        <animate attributeName="r" from="45" to="65" dur="3s" repeatCount="indefinite"/>
        <animate attributeName="opacity" from="0.5" to="0" dur="3s" repeatCount="indefinite"/>
      </circle>
      
      <!-- Middle ring -->
      <circle cx="600" cy="150" r="35" fill="none" stroke="#06b6d4" stroke-width="2" opacity="0.6">
        <animate attributeName="transform" from="rotate(0 600 150)" to="rotate(360 600 150)" dur="4s" repeatCount="indefinite"/>
      </circle>

      <!-- Inner core -->
      <circle cx="600" cy="150" r="25" fill="url(#nodeGradient)" opacity="0.9"/>
      <circle cx="600" cy="150" r="20" fill="url(#textGradient)" opacity="0.7"/>

      <!-- Core nodes -->
      <circle cx="625" cy="150" r="4" fill="#10b981" opacity="0.9">
        <animate attributeName="cy" from="150" to="130" dur="2s" repeatCount="indefinite"/>
      </circle>
      <circle cx="575" cy="150" r="4" fill="#06b6d4" opacity="0.9">
        <animate attributeName="cy" from="150" to="170" dur="2s" repeatCount="indefinite"/>
      </circle>
      <circle cx="600" cy="175" r="4" fill="#10b981" opacity="0.9">
        <animate attributeName="cx" from="600" to="620" dur="2s" repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- Orbiting Elements -->
    <g opacity="0.8">
      <circle cx="550" cy="100" r="3" fill="#10b981">
        <animate attributeName="cx" from="550" to="650" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="cy" from="100" to="180" dur="4s" repeatCount="indefinite"/>
      </circle>
      <circle cx="650" cy="200" r="3" fill="#06b6d4">
        <animate attributeName="cx" from="650" to="550" dur="4s" repeatCount="indefinite"/>
        <animate attributeName="cy" from="200" to="120" dur="4s" repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- Main Title with Neon Effect -->
    <text x="600" y="220" font-size="78" font-weight="900" text-anchor="middle" fill="url(#textGradient)" font-family="Arial, sans-serif" letter-spacing="3" filter="url(#strongGlow)">
      SHIVU KUMAR
    </text>

    <!-- Animated Subtitle with Code Blocks -->
    <rect x="380" y="245" width="440" height="50" fill="none" stroke="#10b981" stroke-width="2" rx="5" opacity="0.6">
      <animate attributeName="opacity" from="0.3" to="0.8" dur="2s" repeatCount="indefinite"/>
    </rect>
    
    
    
    <text x="600" y="288" font-size="13" text-anchor="middle" fill="#10b981" font-family="Courier New, monospace" letter-spacing="1">
      ⦿ Building • Securing • Scaling ⦿
    </text>

    <!-- Pulsing Status -->
    <circle cx="385" cy="270" r="5" fill="#10b981">
      <animate attributeName="r" from="5" to="8" dur="1s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0.2" dur="1s" repeatCount="indefinite"/>
    </circle>
    <text x="405" y="260" font-size="12" fill="#06b6d4" font-family="Courier New, monospace">● SYSTEM ONLINE</text>
  </svg>

  <br>

  <div align="center">
    <a href="https://git.io/typing-svg">
      <img src="https://readme-typing-svg.demolab.com?font=Courier+Prime&weight=600&size=22&pause=1000&color=10b981&center=true&vCenter=true&width=700&lines=%3E+Initializing+Advanced+Protocols...;%3E+Scanning+Cloud_Infrastructure...;%3E+Deploying_Secure_Containers...;%3E+Establishing_Quantum_Network...;%3E+All_Systems_Optimal_%E2%9C%93" alt="Typing SVG" />
    </a>
  </div>
</div>

<br><br>

<h2 align="center" style="color: #10b981; ">🌐 The Tech Stack (OSI Model)</h2>

<div align="center">
  
  <img src="https://img.shields.io/badge/LAYER_1-APPLICATION_%26_WEB-10b981?style=for-the-badge&logo=react&logoColor=white"/>
  <br>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,html,css,js,tailwind,bootstrap,django,fastapi,php&theme=dark" />
  </a>
  <br><br>

  <img src="https://img.shields.io/badge/LAYER_2-SYSTEMS_%26_CORE-06b6d4?style=for-the-badge&logo=python&logoColor=white"/>
  <br>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,java,c,mysql,postgres,sqlite,bash&theme=dark" />
  </a>
  <br><br>

  <img src="https://img.shields.io/badge/LAYER_3-NETWORK_%26_DEPLOYMENT-0d9488?style=for-the-badge&logo=linux&logoColor=white"/>
  <br>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=linux,docker,git,vscode,vercel,aws,render&theme=dark" />
  </a>

</div>

<br><br>

<h2 align="center" style="color: #10b981; ">🚀 Project Command Center</h2>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=10b981,06b6d4&height=4" width="100%"/>
</div>
<br>

<div align="center">
  
  <table>
    <tr>
      <td width="50%">
        <h3 align="center" style="color: #10b981;">🌐 Civic Connect</h3>
        <div align="center">
            <img src="https://img.shields.io/badge/Status-Online-10b981?style=flat-square" />
            <br>
            Geolocation platform for citizens to report local issues to authorities.
            <br><br>
            <code>Django</code> <code>React</code> <code>PostgreSQL</code>
        </div>
      </td>
      <td width="50%">
        <h3 align="center" style="color: #06b6d4;">🚗 DreamCars Rental</h3>
        <div align="center">
            <img src="https://img.shields.io/badge/Status-Active-06b6d4?style=flat-square" />
            <br>
            Full-featured car booking portal with fleet management.
            <br><br>
            <code>PHP</code> <code>MySQL</code> <code>HTML/CSS</code>
        </div>
      </td>
    </tr>
  </table>

  <table>
    <tr>
      <td width="50%">
        <h3 align="center" style="color: #10b981;">🛡️ AI Security Dashboard</h3>
        <div align="center">
            <img src="https://img.shields.io/badge/Focus-Malware_Analysis-10b981?style=flat-square" />
            <br>
            <b>(Academic)</b> NIDS & URL Phishing detection using Machine Learning.
            <br><br>
            <code>Python</code> <code>ML</code> <code>Network Security</code>
        </div>
      </td>
      <td width="50%">
        <h3 align="center" style="color: #06b6d4;">🔐 ShadowSurf Vault</h3>
        <div align="center">
             <img src="https://img.shields.io/badge/Focus-Encryption-06b6d4?style=flat-square" />
            <br>
            Secure AES-encrypted data vault deployed via Docker.
            <br><br>
            <code>Java</code> <code>Docker</code> <code>PostgreSQL</code>
        </div>
      </td>
    </tr>
  </table>

  <table>
    <tr>
      <td width="50%">
        <h3 align="center" style="color: #10b981;">📝 Django TaskMaster</h3>
        <div align="center">
            <img src="https://img.shields.io/badge/Type-Auth_System-10b981?style=flat-square" />
            <br>
            Task management app with User Authentication (Login/Register) & CRUD.
            <br><br>
            <code>Django</code> <code>SQLite</code> <code>Bootstrap</code>
        </div>
      </td>
      <td width="50%">
        <h3 align="center" style="color: #06b6d4;">🎮 2048 Game Clone</h3>
        <div align="center">
             <img src="https://img.shields.io/badge/Type-Game_Logic-06b6d4?style=flat-square" />
            <br>
            Complex logic implementation of the classic sliding tile puzzle game.
            <br><br>
            <code>JavaScript</code> <code>HTML5</code> <code>CSS3</code>
        </div>
      </td>
    </tr>
  </table>

</div>

<br><br>

<h2 align="center" style="color: #10b981;">📊 System Diagnostics</h2>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Shivukumar-M&show_icons=true&theme=transparent&hide_border=false&title_color=10b981&icon_color=06b6d4&text_color=b5b5b5&border_color=10b981" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shivukumar-M&layout=compact&theme=transparent&hide_border=false&title_color=10b981&icon_color=06b6d4&text_color=b5b5b5&border_color=10b981" height="150" />
  <br><br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Shivukumar-M&theme=transparent&hide_border=false&background=0D1117&sideNums=10b981&currStreakLabel=06b6d4&fire=10b981&ring=06b6d4&currStreakNum=ffffff&border=10b981" />
</div>

<br><br>

<!-- ULTRA CREATIVE FOOTER -->
<svg width="100%" height="280" viewBox="0 0 1200 280" style="background: linear-gradient(180deg, #051f1f 0%, #0a2e2e 40%, #051f1f 100%);" preserveAspectRatio="xMidYMid slice">
  <defs>
    <linearGradient id="footerGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#10b981;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#06b6d4;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="footerGrad2" x1="100%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#06b6d4;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#10b981;stop-opacity:1" />
    </linearGradient>
    <filter id="footerGlow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Top animated border -->
  <line x1="0" y1="5" x2="1200" y2="5" stroke="url(#footerGrad1)" stroke-width="4" opacity="0.8"/>
  <line x1="0" y1="10" x2="1200" y2="10" stroke="url(#footerGrad2)" stroke-width="2" opacity="0.5"/>

  <!-- Flowing Particles Left Side -->
  <g opacity="0.7">
    <circle cx="60" cy="60" r="3" fill="#10b981">
      <animate attributeName="cx" from="60" to="200" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="80" cy="90" r="2.5" fill="#06b6d4">
      <animate attributeName="cx" from="80" to="250" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="100" cy="70" r="2" fill="#10b981">
      <animate attributeName="cx" from="100" to="280" dur="4.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0" dur="4.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="120" cy="100" r="3" fill="#06b6d4">
      <animate attributeName="cx" from="120" to="300" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0" dur="6s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Flowing Particles Right Side -->
  <g opacity="0.7">
    <circle cx="1140" cy="60" r="3" fill="#06b6d4">
      <animate attributeName="cx" from="1140" to="1000" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1120" cy="90" r="2.5" fill="#10b981">
      <animate attributeName="cx" from="1120" to="950" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1100" cy="70" r="2" fill="#06b6d4">
      <animate attributeName="cx" from="1100" to="920" dur="4.5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0" dur="4.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1080" cy="100" r="3" fill="#10b981">
      <animate attributeName="cx" from="1080" to="900" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" from="0.8" to="0" dur="6s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Central Rotating Hub -->
  <g filter="url(#footerGlow)">
    <!-- Rotating outer ring -->
    <circle cx="600" cy="80" r="25" fill="none" stroke="#10b981" stroke-width="2" opacity="0.6">
      <animate attributeName="transform" from="rotate(0 600 80)" to="rotate(360 600 80)" dur="5s" repeatCount="indefinite"/>
    </circle>

    <!-- Counter-rotating ring -->
    <circle cx="600" cy="80" r="35" fill="none" stroke="#06b6d4" stroke-width="1.5" opacity="0.4">
      <animate attributeName="transform" from="rotate(0 600 80)" to="rotate(-360 600 80)" dur="7s" repeatCount="indefinite"/>
    </circle>

    <!-- Central node -->
    <circle cx="600" cy="80" r="12" fill="url(#footerGrad1)" opacity="0.9"/>
    
    <!-- Orbiting dots -->
    <circle cx="625" cy="80" r="2" fill="#10b981" opacity="0.8">
      <animate attributeName="transform" from="rotate(0 600 80)" to="rotate(360 600 80)" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="575" cy="80" r="2" fill="#06b6d4" opacity="0.8">
      <animate attributeName="transform" from="rotate(180 600 80)" to="rotate(540 600 80)" dur="5s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Quote Section with Enhanced Style -->
  <rect x="250" y="130" width="700" height="80" fill="none" stroke="url(#footerGrad1)" stroke-width="2" rx="8" opacity="0.5">
    <animate attributeName="opacity" from="0.3" to="0.7" dur="3s" repeatCount="indefinite"/>
  </rect>

  <text x="600" y="160" font-size="18" text-anchor="middle" fill="url(#footerGrad1)" font-family="Georgia, serif" font-style="italic" font-weight="bold" letter-spacing="1">
    "Code is like humor. When you have to explain it, it's bad."
  </text>

  <!-- Tech Stack Footer -->
  <text x="600" y="195" font-size="13" text-anchor="middle" fill="#10b981" font-family="Courier New, monospace" letter-spacing="2">
    ◆ Building Robust Solutions ◆ Securing Digital Futures ◆
  </text>

  <!-- Multi-line Status Indicator -->
  <g filter="url(#footerGlow)">
    <circle cx="300" cy="220" r="4" fill="#10b981">
      <animate attributeName="opacity" from="0.3" to="1" dur="1.2s" repeatCount="indefinite"/>
    </circle>
    <text x="320" y="225" font-size="11" fill="#06b6d4" font-family="Courier New, monospace" letter-spacing="0.5">

