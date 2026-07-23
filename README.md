<div align="center">
  <svg viewBox="0 0 800 200" width="100%" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <style>
        @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&amp;display=swap');
        
        .dot-font {
          font-family: 'Press Start 2P', monospace;
          font-size: 26px;
          fill: #00F0FF;
          letter-spacing: 2px;
        }
        .sub-font {
          font-family: monospace;
          font-size: 13px;
          fill: #FF0055;
          letter-spacing: 4px;
        }
        .glow {
          filter: drop-shadow(0px 0px 8px #00F0FF);
        }
        .pulse {
          animation: pulseAnim 2s infinite ease-in-out;
        }
        @keyframes pulseAnim {
          0% { opacity: 0.3; }
          50% { opacity: 1; }
          100% { opacity: 0.3; }
        }
      </style>
      
      <linearGradient id="hudGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#0a0a16"/>
        <stop offset="100%" stop-color="#12122c"/>
      </linearGradient>
    </defs>

    <rect width="800" height="200" rx="12" fill="url(#hudGrad)" stroke="#00F0FF" stroke-width="2"/>
    <rect x="10" y="10" width="780" height="180" rx="8" fill="none" stroke="#FF0055" stroke-width="1" stroke-dasharray="8 4"/>

    <polygon points="10,30 30,10 10,10" fill="#00F0FF"/>
    <polygon points="790,30 770,10 790,10" fill="#00F0FF"/>
    <polygon points="10,170 30,190 10,190" fill="#FF0055"/>
    <polygon points="790,170 770,190 790,190" fill="#FF0055"/>

    <text x="400" y="90" class="dot-font glow" text-anchor="middle">SYSTEM_OPERATOR</text>
    <text x="400" y="130" class="sub-font" text-anchor="middle">> ARCHITECT_MODE // ONLINE</text>

    <circle cx="50" cy="50" r="4" fill="#39FF14" class="pulse"/>
    <circle cx="750" cy="50" r="4" fill="#00F0FF" class="pulse"/>
  </svg>
</div>

<br/>

<div align="center">
  <svg viewBox="0 0 800 24" width="100%" xmlns="http://www.w3.org/2000/svg">
    <style>
      .laser {
        animation: laserScan 3s infinite linear;
      }
      @keyframes laserScan {
        0% { x1: 0; x2: 100; }
        50% { x1: 700; x2: 800; }
        100% { x1: 0; x2: 100; }
      }
    </style>
    <line x1="0" y1="12" x2="800" y2="12" stroke="#1f293d" stroke-width="4"/>
    <circle cx="400" cy="12" r="8" fill="#0a0a16" stroke="#00F0FF" stroke-width="2"/>
    <polygon points="396,12 404,8 404,16" fill="#FF0055"/>
    
    <line class="laser" y1="12" y2="12" stroke="#00F0FF" stroke-width="4" filter="drop-shadow(0px 0px 5px #00F0FF)"/>
  </svg>
</div>

<br/>

<table width="100%">
  <tr>
    <td width="60%" valign="top">
      <h3><code>> STATUS: OPERATIONAL</code></h3>
      <p>Building high-performance reactive web systems, dynamic UI components, and modern architectures.</p>
      <ul>
        <li>⚡ <b>Core Focus:</b> Interactive Web Interfaces &amp; 3D Engine Systems</li>
        <li>🛠️ <b>Architecture:</b> Custom Scalable APIs &amp; Modern Frameworks</li>
        <li>📫 <b>Signal Terminal:</b> <code>user@domain.com</code></li>
      </ul>
    </td>
    <td width="40%" align="center">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=synthwave&hide_border=true&bg_color=0a0a16&title_color=00F0FF&text_color=FF0055" width="100%" />
    </td>
  </tr>
</table>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/React-00F0FF?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
</div>

<br/>

<div align="center">
  <p><code>[ CPU_LIQUID_COOLING_SYSTEM // ACTIVE ]</code></p>
  
  <svg viewBox="0 0 800 160" width="100%" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <radialGradient id="coolerGlow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#00F0FF" stop-opacity="0.6"/>
        <stop offset="100%" stop-color="#000" stop-opacity="0"/>
      </radialGradient>
    </defs>

    <rect x="50" y="20" width="700" height="120" rx="10" fill="#0d0d1a" stroke="#00F0FF" stroke-width="2"/>
    
    <path d="M 50 50 Q 20 50 20 80 T 50 110" fill="none" stroke="#FF0055" stroke-width="8"/>
    <path d="M 50 50 Q 20 50 20 80 T 50 110" fill="none" stroke="#00F0FF" stroke-width="3" stroke-dasharray="10 5">
      <animate attributeName="stroke-dashoffset" from="30" to="0" dur="1s" repeatCount="indefinite"/>
    </path>

    <g transform="translate(250, 80)">
      <circle cx="0" cy="0" r="45" fill="none" stroke="#1f293d" stroke-width="6"/>
      <circle cx="0" cy="0" r="45" fill="url(#coolerGlow)"/>
      <g>
        <path d="M -8 -35 C 10 -35 20 -20 0 0 C -20 20 -10 35 8 35 C -5 15 5 -15 -8 -35 Z" fill="#00F0FF"/>
        <path d="M -35 8 C -35 -10 -20 -20 0 0 C 20 20 35 10 35 -8 C 15 5 -15 -5 -35 8 Z" fill="#00F0FF"/>
        <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="0.8s" repeatCount="indefinite"/>
      </g>
      <circle cx="0" cy="0" r="12" fill="#12122c" stroke="#FF0055" stroke-width="2"/>
    </g>

    <g transform="translate(550, 80)">
      <circle cx="0" cy="0" r="45" fill="none" stroke="#1f293d" stroke-width="6"/>
      <circle cx="0" cy="0" r="45" fill="url(#coolerGlow)"/>
      <g>
        <path d="M -8 -35 C 10 -35 20 -20 0 0 C -20 20 -10 35 8 35 C -5 15 5 -15 -8 -35 Z" fill="#00F0FF"/>
        <path d="M -35 8 C -35 -10 -20 -20 0 0 C 20 20 35 10 35 -8 C 15 5 -15 -5 -35 8 Z" fill="#00F0FF"/>
        <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="0.8s" repeatCount="indefinite"/>
      </g>
      <circle cx="0" cy="0" r="12" fill="#12122c" stroke="#FF0055" stroke-width="2"/>
    </g>

    <text x="400" y="85" font-family="monospace" font-size="14" fill="#39FF14" text-anchor="middle">32°C // FLOW_OPTIMAL</text>
  </svg>
</div>