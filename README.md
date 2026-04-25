<div align="center">

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   ANIMATED SVG BANNER                   -->
<!-- ═══════════════════════════════════════════════════════ -->

<svg width="100%" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#020810"/>
      <stop offset="40%" stop-color="#050d1a"/>
      <stop offset="100%" stop-color="#020810"/>
    </linearGradient>
    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00ff88">
        <animate attributeName="offset" values="0;0.5;0" dur="5s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#00d4ff">
        <animate attributeName="offset" values="0.5;1;0.5" dur="5s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#00ff88">
        <animate attributeName="offset" values="1;1.5;1" dur="5s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="softGlow" x="-30%" y="-30%" width="160%" height="160%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="titleGlow" x="-20%" y="-30%" width="140%" height="160%">
      <feGaussianBlur stdDeviation="10" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="220" fill="url(#bgGrad)" rx="14"/>

  <!-- Subtle grid -->
  <g stroke="#00ff8806" stroke-width="0.6">
    <line x1="0" y1="55" x2="900" y2="55"/>
    <line x1="0" y1="110" x2="900" y2="110"/>
    <line x1="0" y1="165" x2="900" y2="165"/>
    <line x1="180" y1="0" x2="180" y2="220"/>
    <line x1="360" y1="0" x2="360" y2="220"/>
    <line x1="540" y1="0" x2="540" y2="220"/>
    <line x1="720" y1="0" x2="720" y2="220"/>
  </g>

  <!-- Animated scan line -->
  <rect x="0" y="0" width="900" height="1.5" fill="#00ff8818" rx="1">
    <animateTransform attributeName="transform" type="translate" values="0,0;0,220;0,0" dur="4s" repeatCount="indefinite"/>
  </rect>

  <!-- Corner brackets -->
  <polyline points="0,36 0,0 36,0" stroke="#00ff88" stroke-width="2.5" fill="none" filter="url(#softGlow)"/>
  <polyline points="864,0 900,0 900,36" stroke="#00d4ff" stroke-width="2.5" fill="none" filter="url(#softGlow)"/>
  <polyline points="0,184 0,220 36,220" stroke="#00d4ff" stroke-width="2.5" fill="none" filter="url(#softGlow)"/>
  <polyline points="864,220 900,220 900,184" stroke="#00ff88" stroke-width="2.5" fill="none" filter="url(#softGlow)"/>

  <!-- Pulsing dots top corners -->
  <circle cx="18" cy="18" r="4" fill="#00ff88">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="r" values="4;6;4" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="882" cy="18" r="4" fill="#00d4ff">
    <animate attributeName="opacity" values="1;0.2;1" dur="2.4s" repeatCount="indefinite"/>
    <animate attributeName="r" values="4;6;4" dur="2.4s" repeatCount="indefinite"/>
  </circle>

  <!-- Main ATHEX title -->
  <text x="450" y="112" text-anchor="middle"
        font-family="'Courier New', Courier, monospace"
        font-size="82" font-weight="900"
        fill="url(#titleGrad)"
        filter="url(#titleGlow)"
        letter-spacing="18">ATHEX</text>

  <!-- Blinking cursor after title -->
  <rect x="762" y="74" width="9" height="52" fill="#00ff88" rx="1">
    <animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/>
  </rect>

  <!-- Subtitle line -->
  <text x="450" y="148" text-anchor="middle"
        font-family="'Courier New', Courier, monospace"
        font-size="12" fill="#00ff8880" letter-spacing="5">
    SECURITY RESEARCHER  ·  WEB DEVELOPER  ·  TOOLS ENGINEER
  </text>

  <!-- Bottom tag line -->
  <rect x="290" y="170" width="320" height="28" fill="#00ff8810" rx="4" stroke="#00ff8825" stroke-width="0.5"/>
  <text x="450" y="188" text-anchor="middle"
        font-family="'Courier New', Courier, monospace"
        font-size="11" fill="#00ff8899" letter-spacing="3">
    [ PAKISTAN 🇵🇰  ·  ALLAH FIRST 🤲  ·  ONLINE ]
  </text>

  <!-- Animated side particles -->
  <circle cx="60" cy="110" r="2" fill="#00ff88" opacity="0.5">
    <animate attributeName="cy" values="80;140;80" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="840" cy="110" r="2" fill="#00d4ff" opacity="0.5">
    <animate attributeName="cy" values="140;80;140" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="110" cy="60" r="1.5" fill="#00ff88" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="790" cy="160" r="1.5" fill="#00d4ff" opacity="0.3">
    <animate attributeName="opacity" values="0.3;0.9;0.3" dur="2.2s" repeatCount="indefinite"/>
  </circle>
</svg>

<!-- TYPING SVG -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&pause=800&color=00FF88&background=00000000&center=true&vCenter=true&width=780&height=40&lines=%5B+root%40athex+~%23+%5D+Cybersecurity+Researcher+%26+Ethical+Hacker;%5B+root%40athex+~%23+%5D+Full-Stack+Web+Developer;%5B+root%40athex+~%23+%5D+Security+Tools+%26+Automation+Engineer;%5B+root%40athex+~%23+%5D+Exploit+%26+Vulnerability+Researcher;%5B+root%40athex+~%23+%5D+Dark+Web+Threat+Intelligence+Analyst;%5B+root%40athex+~%23+%5D+OSINT+%7C+Digital+Forensics+%7C+Red+Team" />

<!-- BADGES ROW -->
<p>
  <img src="https://komarev.com/ghpvc/?username=Athexblackhat&label=Profile+Views&color=00ff88&style=flat-square&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Security%20Researcher-%2300ff88?style=flat-square&logo=hackthebox&logoColor=00ff88&labelColor=0d1117&color=0d1117"/>
  <img src="https://img.shields.io/badge/Web%20Developer-%2300d4ff?style=flat-square&logo=webcomponents&logoColor=00d4ff&labelColor=0d1117&color=0d1117"/>
  <img src="https://img.shields.io/badge/Tools%20Engineer-%23a78bfa?style=flat-square&labelColor=0d1117&color=0d1117"/>
  <img src="https://img.shields.io/badge/Status-Online%20%E2%97%8F-00ff88?style=flat-square&labelColor=0d1117"/>
</p>

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                      ABOUT ME                           -->
<!-- ═══════════════════════════════════════════════════════ -->

<img align="right" width="340" src="https://media.giphy.com/media/RDZo7znAdn2u7sAcWH/giphy.gif"/>

## `$ cat identity.yaml`

```yaml
┌─────────────────────────────────────────────┐
│              ATHEX  ::  PROFILE             │
├─────────────────────────────────────────────┤
│  name     : ATHEX                           │
│  alias    : AthexBlackHat · inziXploit      │
│  origin   : Pakistan 🇵🇰                    │
│  faith    : ALLAH first. Always. 🤲         │
├─────────────────────────────────────────────┤
│  roles:                                     │
│    ▸ Cybersecurity Researcher               │
│    ▸ Ethical Hacker / Penetration Tester    │
│    ▸ Full-Stack Web Developer               │
│    ▸ Security Tools & CLI Engineer          │
│    ▸ Exploit & Vulnerability Researcher     │
│    ▸ Dark Web Threat Intelligence Analyst   │
│    ▸ OSINT & Digital Forensics Specialist   │
├─────────────────────────────────────────────┤
│  studying:                                  │
│    ▸ Kernel Security & Rootkit Research     │
│    ▸ AI-Augmented Security Tooling          │
│    ▸ 0-Day Vulnerability Research           │
│    ▸ Advanced Evasion & Persistence Tech    │
├─────────────────────────────────────────────┤
│  contact  : @itx_athex86                   │
└─────────────────────────────────────────────┘
```

<br clear="right"/>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   SKILL MATRIX SVG                      -->
<!-- ═══════════════════════════════════════════════════════ -->

## `$ ./skill_matrix.sh`

<div align="center">

<svg width="100%" viewBox="0 0 860 380" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="panelBg2" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#080d14"/>
    </linearGradient>
    <linearGradient id="greenBar" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00ff88"/>
      <stop offset="100%" stop-color="#00cc66"/>
    </linearGradient>
    <linearGradient id="blueBar" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d4ff"/>
      <stop offset="100%" stop-color="#0088cc"/>
    </linearGradient>
    <linearGradient id="purpleBar" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#a78bfa"/>
      <stop offset="100%" stop-color="#7c3aed"/>
    </linearGradient>
    <linearGradient id="redBar" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff6644"/>
      <stop offset="100%" stop-color="#cc3322"/>
    </linearGradient>
  </defs>

  <!-- Panel -->
  <rect width="860" height="380" fill="url(#panelBg2)" rx="12" stroke="#00ff8825" stroke-width="1"/>

  <!-- Title bar -->
  <rect x="0" y="0" width="860" height="48" fill="#00ff8808" rx="12"/>
  <rect x="0" y="36" width="860" height="12" fill="#00ff8808"/>
  <circle cx="26" cy="24" r="7" fill="#ff5f57"/>
  <circle cx="48" cy="24" r="7" fill="#febc2e"/>
  <circle cx="70" cy="24" r="7" fill="#28c840"/>
  <text x="430" y="30" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#00ff8888" letter-spacing="4">ATHEX :: SKILL MATRIX v4.0</text>

  <!-- Divider line (vertical) -->
  <line x1="430" y1="60" x2="430" y2="348" stroke="#ffffff0a" stroke-width="1" stroke-dasharray="4,3"/>

  <!-- LEFT COLUMN -->
  <g font-family="'Courier New', monospace">
    <!-- Col header -->
    <text x="30" y="80" font-size="10" fill="#00ff8855" letter-spacing="3">OFFENSIVE &amp; WEB</text>

    <!-- Row 1 -->
    <text x="30" y="110" font-size="12" fill="#00ff88cc">Penetration Testing</text>
    <rect x="30" y="116" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="30" y="116" width="351" height="10" fill="url(#greenBar)" rx="3">
      <animate attributeName="width" from="0" to="351" dur="1.2s" fill="freeze"/>
    </rect>
    <text x="406" y="126" font-size="10" fill="#00ff88" text-anchor="end">95%</text>

    <!-- Row 2 -->
    <text x="30" y="150" font-size="12" fill="#00ff88cc">Web Development</text>
    <rect x="30" y="156" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="30" y="156" width="333" height="10" fill="url(#greenBar)" rx="3">
      <animate attributeName="width" from="0" to="333" dur="1.4s" fill="freeze"/>
    </rect>
    <text x="406" y="166" font-size="10" fill="#00ff88" text-anchor="end">90%</text>

    <!-- Row 3 -->
    <text x="30" y="190" font-size="12" fill="#00ff88cc">Vulnerability Research</text>
    <rect x="30" y="196" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="30" y="196" width="325" height="10" fill="url(#greenBar)" rx="3">
      <animate attributeName="width" from="0" to="325" dur="1.6s" fill="freeze"/>
    </rect>
    <text x="406" y="206" font-size="10" fill="#00ff88" text-anchor="end">88%</text>

    <!-- Row 4 -->
    <text x="30" y="230" font-size="12" fill="#00ff88cc">Tools Engineering</text>
    <rect x="30" y="236" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="30" y="236" width="325" height="10" fill="url(#greenBar)" rx="3">
      <animate attributeName="width" from="0" to="325" dur="1.7s" fill="freeze"/>
    </rect>
    <text x="406" y="246" font-size="10" fill="#00ff88" text-anchor="end">88%</text>

    <!-- Row 5 -->
    <text x="30" y="270" font-size="12" fill="#00ff88cc">Social Engineering</text>
    <rect x="30" y="276" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="30" y="276" width="344" height="10" fill="url(#greenBar)" rx="3">
      <animate attributeName="width" from="0" to="344" dur="1.5s" fill="freeze"/>
    </rect>
    <text x="406" y="286" font-size="10" fill="#00ff88" text-anchor="end">93%</text>

    <!-- Row 6 -->
    <text x="30" y="310" font-size="12" fill="#00ff88cc">Exploit Research</text>
    <rect x="30" y="316" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="30" y="316" width="296" height="10" fill="url(#greenBar)" rx="3">
      <animate attributeName="width" from="0" to="296" dur="1.9s" fill="freeze"/>
    </rect>
    <text x="406" y="326" font-size="10" fill="#00ff88" text-anchor="end">80%</text>
  </g>

  <!-- RIGHT COLUMN -->
  <g font-family="'Courier New', monospace">
    <text x="450" y="80" font-size="10" fill="#00d4ff55" letter-spacing="3">INTELLIGENCE &amp; ANALYSIS</text>

    <!-- Row 1 -->
    <text x="450" y="110" font-size="12" fill="#00d4ffcc">OSINT &amp; Recon</text>
    <rect x="450" y="116" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="450" y="116" width="307" height="10" fill="url(#blueBar)" rx="3">
      <animate attributeName="width" from="0" to="307" dur="1.3s" fill="freeze"/>
    </rect>
    <text x="826" y="126" font-size="10" fill="#00d4ff" text-anchor="end">83%</text>

    <!-- Row 2 -->
    <text x="450" y="150" font-size="12" fill="#00d4ffcc">Dark Web Research</text>
    <rect x="450" y="156" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="450" y="156" width="296" height="10" fill="url(#blueBar)" rx="3">
      <animate attributeName="width" from="0" to="296" dur="1.5s" fill="freeze"/>
    </rect>
    <text x="826" y="166" font-size="10" fill="#00d4ff" text-anchor="end">80%</text>

    <!-- Row 3 -->
    <text x="450" y="190" font-size="12" fill="#a78bfacc">Network Security</text>
    <rect x="450" y="196" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="450" y="196" width="277" height="10" fill="url(#purpleBar)" rx="3">
      <animate attributeName="width" from="0" to="277" dur="1.7s" fill="freeze"/>
    </rect>
    <text x="826" y="206" font-size="10" fill="#a78bfa" text-anchor="end">75%</text>

    <!-- Row 4 -->
    <text x="450" y="230" font-size="12" fill="#a78bfacc">Threat Intelligence</text>
    <rect x="450" y="236" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="450" y="236" width="288" height="10" fill="url(#purpleBar)" rx="3">
      <animate attributeName="width" from="0" to="288" dur="1.8s" fill="freeze"/>
    </rect>
    <text x="826" y="246" font-size="10" fill="#a78bfa" text-anchor="end">78%</text>

    <!-- Row 5 -->
    <text x="450" y="270" font-size="12" fill="#ff6644cc">Reverse Engineering</text>
    <rect x="450" y="276" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="450" y="276" width="259" height="10" fill="url(#redBar)" rx="3">
      <animate attributeName="width" from="0" to="259" dur="2s" fill="freeze"/>
    </rect>
    <text x="826" y="286" font-size="10" fill="#ff6644" text-anchor="end">70%</text>

    <!-- Row 6 -->
    <text x="450" y="310" font-size="12" fill="#ff6644cc">Binary Exploitation</text>
    <rect x="450" y="316" width="370" height="10" fill="#ffffff06" rx="3"/>
    <rect x="450" y="316" width="233" height="10" fill="url(#redBar)" rx="3">
      <animate attributeName="width" from="0" to="233" dur="2.1s" fill="freeze"/>
    </rect>
    <text x="826" y="326" font-size="10" fill="#ff6644" text-anchor="end">63%</text>
  </g>

  <!-- Footer -->
  <rect x="0" y="349" width="860" height="31" fill="#00ff8806" rx="4"/>
  <line x1="0" y1="349" x2="860" y2="349" stroke="#00ff8820" stroke-width="0.5"/>
  <text x="430" y="370" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00ff8855" letter-spacing="2">[ ALWAYS LEARNING · ALWAYS BUILDING · ALLAH FIRST 🤲 ]</text>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   DOMAIN CARDS SVG                      -->
<!-- ═══════════════════════════════════════════════════════ -->

## `$ ls /domains/ -la`

<div align="center">

<svg width="100%" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="gc1" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" stop-color="#00ff8818"/><stop offset="100%" stop-color="#00ff8804"/></linearGradient>
    <linearGradient id="gc2" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" stop-color="#00d4ff18"/><stop offset="100%" stop-color="#00d4ff04"/></linearGradient>
    <linearGradient id="gc3" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" stop-color="#a78bfa18"/><stop offset="100%" stop-color="#a78bfa04"/></linearGradient>
    <linearGradient id="gc4" x1="0%" y1="0%" x2="100%" y2="100%"><stop offset="0%" stop-color="#ff664418"/><stop offset="100%" stop-color="#ff664404"/></linearGradient>
  </defs>
  <!-- Card 1 -->
  <rect x="8" y="8" width="200" height="184" fill="url(#gc1)" rx="10" stroke="#00ff8830" stroke-width="1"/>
  <line x1="8" y1="52" x2="208" y2="52" stroke="#00ff8820" stroke-width="0.5"/>
  <text x="108" y="36" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" font-weight="700" fill="#00ff88">⚔  Offensive Sec</text>
  <text x="108" y="72" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00ff8899">▸ Pentesting · Red Team</text>
  <text x="108" y="92" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00ff8899">▸ Exploit Dev · CVE PoC</text>
  <text x="108" y="112" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00ff8899">▸ Social Engineering</text>
  <text x="108" y="132" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00ff8899">▸ AD Attacks · MITM</text>
  <text x="108" y="152" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00ff8860">▸ 0-Day Research</text>
  <text x="108" y="172" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00ff8860">▸ Phishing · Vishing</text>
  <!-- Card 2 -->
  <rect x="220" y="8" width="200" height="184" fill="url(#gc2)" rx="10" stroke="#00d4ff30" stroke-width="1"/>
  <line x1="220" y1="52" x2="420" y2="52" stroke="#00d4ff20" stroke-width="0.5"/>
  <text x="320" y="36" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" font-weight="700" fill="#00d4ff">◈  Web Engineering</text>
  <text x="320" y="72" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00d4ff99">▸ Full-Stack Dev</text>
  <text x="320" y="92" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00d4ff99">▸ REST APIs · Backends</text>
  <text x="320" y="112" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00d4ff99">▸ Security Dashboards</text>
  <text x="320" y="132" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00d4ff99">▸ CLI Security Tools</text>
  <text x="320" y="152" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00d4ff60">▸ Automation Scripts</text>
  <text x="320" y="172" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#00d4ff60">▸ Browser Extensions</text>
  <!-- Card 3 -->
  <rect x="432" y="8" width="200" height="184" fill="url(#gc3)" rx="10" stroke="#a78bfa30" stroke-width="1"/>
  <line x1="432" y1="52" x2="632" y2="52" stroke="#a78bfa20" stroke-width="0.5"/>
  <text x="532" y="36" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" font-weight="700" fill="#a78bfa">⬡  Intelligence</text>
  <text x="532" y="72" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#a78bfa99">▸ OSINT · Footprinting</text>
  <text x="532" y="92" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#a78bfa99">▸ Dark Web Research</text>
  <text x="532" y="112" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#a78bfa99">▸ Threat Intelligence</text>
  <text x="532" y="132" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#a78bfa99">▸ Digital Profiling</text>
  <text x="532" y="152" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#a78bfa60">▸ Threat Actor Study</text>
  <text x="532" y="172" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#a78bfa60">▸ Digital Forensics</text>
  <!-- Card 4 -->
  <rect x="644" y="8" width="208" height="184" fill="url(#gc4)" rx="10" stroke="#ff664430" stroke-width="1"/>
  <line x1="644" y1="52" x2="852" y2="52" stroke="#ff664420" stroke-width="0.5"/>
  <text x="748" y="36" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" font-weight="700" fill="#ff6644">⬢  Reverse Eng.</text>
  <text x="748" y="72" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#ff664499">▸ Binary Analysis</text>
  <text x="748" y="92" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#ff664499">▸ Malware Behavior</text>
  <text x="748" y="112" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#ff664499">▸ Obfuscation Study</text>
  <text x="748" y="132" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#ff664499">▸ Shellcode Analysis</text>
  <text x="748" y="152" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#ff664460">▸ Memory Forensics</text>
  <text x="748" y="172" text-anchor="middle" font-family="'Courier New', monospace" font-size="10" fill="#ff664460">▸ Debugger Workflow</text>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                     LANGUAGES                           -->
<!-- ═══════════════════════════════════════════════════════ -->

## `$ cat languages.conf`

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,c,cpp,rust,java,kotlin,cs,js,php,bash,html,css,sql&theme=dark&perline=13"/>
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nodejs,flask,django,mongodb,postgres,docker,git,linux,vscode&theme=dark&perline=10"/>
</p>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                      ARSENAL                            -->
<!-- ═══════════════════════════════════════════════════════ -->

## `$ ls /opt/arsenal/ --color`

<details>
<summary><b>⚔️ &nbsp;Offensive &amp; Exploitation</b></summary><br>
<p align="center">
<img src="https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&labelColor=0d1117&logo=linux&logoColor=2596CD"/>
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&labelColor=0d1117&logo=linux&logoColor=FF6633"/>
<img src="https://img.shields.io/badge/SQLMap-CC0000?style=flat-square&labelColor=0d1117&logo=linux&logoColor=CC0000"/>
<img src="https://img.shields.io/badge/Hydra-00ff88?style=flat-square&labelColor=0d1117&logo=linux&logoColor=00ff88"/>
<img src="https://img.shields.io/badge/MSFVenom-8B0000?style=flat-square&labelColor=0d1117&logo=linux&logoColor=ee2200"/>
<img src="https://img.shields.io/badge/John_The_Ripper-ff2200?style=flat-square&labelColor=0d1117&logo=linux&logoColor=ff2200"/>
<img src="https://img.shields.io/badge/Aircrack--ng-39ff14?style=flat-square&labelColor=0d1117&logo=linux&logoColor=39ff14"/>
<img src="https://img.shields.io/badge/Impacket-6644ff?style=flat-square&labelColor=0d1117&logo=linux&logoColor=6644ff"/>
<img src="https://img.shields.io/badge/CrackMapExec-ff4488?style=flat-square&labelColor=0d1117&logo=linux&logoColor=ff4488"/>
<img src="https://img.shields.io/badge/Responder-ffaa00?style=flat-square&labelColor=0d1117&logo=linux&logoColor=ffaa00"/>
<img src="https://img.shields.io/badge/Cobalt_Strike-cc0044?style=flat-square&labelColor=0d1117&logo=linux&logoColor=cc0044"/>
</p>
</details>

<details>
<summary><b>🔍 &nbsp;Recon &amp; OSINT</b></summary><br>
<p align="center">
<img src="https://img.shields.io/badge/Nmap-0E83CD?style=flat-square&labelColor=0d1117&logo=linux&logoColor=0E83CD"/>
<img src="https://img.shields.io/badge/Shodan-CC0000?style=flat-square&labelColor=0d1117&logo=linux&logoColor=CC0000"/>
<img src="https://img.shields.io/badge/Maltego-0099CC?style=flat-square&labelColor=0d1117&logo=linux&logoColor=0099CC"/>
<img src="https://img.shields.io/badge/TheHarvester-00ff88?style=flat-square&labelColor=0d1117&logo=linux&logoColor=00ff88"/>
<img src="https://img.shields.io/badge/Recon--ng-a78bfa?style=flat-square&labelColor=0d1117&logo=linux&logoColor=a78bfa"/>
<img src="https://img.shields.io/badge/SpiderFoot-ff6600?style=flat-square&labelColor=0d1117&logo=linux&logoColor=ff6600"/>
<img src="https://img.shields.io/badge/Amass-ff0044?style=flat-square&labelColor=0d1117&logo=linux&logoColor=ff0044"/>
<img src="https://img.shields.io/badge/Subfinder-00d4ff?style=flat-square&labelColor=0d1117&logo=linux&logoColor=00d4ff"/>
<img src="https://img.shields.io/badge/Nuclei-aa44ff?style=flat-square&labelColor=0d1117&logo=linux&logoColor=aa44ff"/>
<img src="https://img.shields.io/badge/FFUF-00ff88?style=flat-square&labelColor=0d1117&logo=linux&logoColor=00ff88"/>
</p>
</details>

<details>
<summary><b>🧬 &nbsp;Reverse Engineering &amp; Forensics</b></summary><br>
<p align="center">
<img src="https://img.shields.io/badge/Ghidra-FF0000?style=flat-square&labelColor=0d1117&logo=linux&logoColor=FF0000"/>
<img src="https://img.shields.io/badge/IDA_Pro-4B0082?style=flat-square&labelColor=0d1117&logo=linux&logoColor=a78bfa"/>
<img src="https://img.shields.io/badge/x64dbg-3344ff?style=flat-square&labelColor=0d1117&logo=linux&logoColor=3344ff"/>
<img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&labelColor=0d1117&logo=wireshark&logoColor=1679A7"/>
<img src="https://img.shields.io/badge/Volatility-00aa88?style=flat-square&labelColor=0d1117&logo=linux&logoColor=00aa88"/>
<img src="https://img.shields.io/badge/Binary_Ninja-ff6600?style=flat-square&labelColor=0d1117&logo=linux&logoColor=ff6600"/>
<img src="https://img.shields.io/badge/Radare2-00ff88?style=flat-square&labelColor=0d1117&logo=linux&logoColor=00ff88"/>
<img src="https://img.shields.io/badge/PEDA--GDB-ffaa00?style=flat-square&labelColor=0d1117&logo=linux&logoColor=ffaa00"/>
<img src="https://img.shields.io/badge/Cutter-cc2200?style=flat-square&labelColor=0d1117&logo=linux&logoColor=cc2200"/>
</p>
</details>

<details>
<summary><b>🌐 &nbsp;Web Dev Stack</b></summary><br>
<p align="center">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Flask-ffffff?style=flat-square&logo=flask&logoColor=black&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white&labelColor=0d1117"/>
</p>
</details>

<details>
<summary><b>🖥️ &nbsp;Operating Systems</b></summary><br>
<p align="center">
<img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kali-linux&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Parrot_OS-15E0ED?style=flat-square&logo=linux&logoColor=15E0ED&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/BlackArch-1793D1?style=flat-square&logo=arch-linux&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Whonix-111111?style=flat-square&logo=linux&logoColor=00ff88&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Tails_OS-56347C?style=flat-square&logo=linux&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Tor_Browser-7D4698?style=flat-square&logo=tor-browser&logoColor=white&labelColor=0d1117"/>
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white&labelColor=0d1117"/>
</p>
</details>

---

## `$ git log --stat`

<div align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Athexblackhat&show_icons=true&theme=github_dark&border_color=00ff8825&bg_color=0d1117&title_color=00ff88&icon_color=00ff88&text_color=aaffcc&border_radius=12&include_all_commits=true&count_private=true"/>
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Athexblackhat&layout=compact&langs_count=8&theme=github_dark&border_color=00ff8825&bg_color=0d1117&title_color=00ff88&text_color=aaffcc&border_radius=12"/>
</div>

<div align="center">
  <img width="72%" src="https://streak-stats.demolab.com/?user=Athexblackhat&theme=github-dark-blue&border=00ff8825&background=0d1117&stroke=00ff88&ring=00ff88&fire=ff4444&currStreakLabel=00ff88&sideLabels=aaffcc&dates=aaffcc&border_radius=12"/>
</div>

---

## `$ tail -f activity.log`

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Athexblackhat&bg_color=0d1117&color=00ff88&line=00ff88&point=00d4ff&area=true&area_color=00ff8812&hide_border=false&border_color=00ff8825&radius=10&custom_title=ATHEX+::+Contribution+Activity+Log"/>
</div>

---

<div align="center">
  <img src="https://github-profile-trophy.zeabur.app/?username=athexblackhat&theme=matrix&no-frame=false&margin-w=6&margin-h=6&column=4"/>
</div>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/Athexblackhat/Athexblackhat/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</div>

---

## `$ ./connect.sh`

<p align="center">
  <a href="https://instagram.com/itx_athex86">
    <img src="https://img.shields.io/badge/Instagram-%40itx__athex86-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0d1117"/>
  </a>
  &nbsp;
  <a href="https://www.youtube.com/@inzixploit444">
    <img src="https://img.shields.io/badge/YouTube-%40inzixploit444-FF0000?style=for-the-badge&logo=youtube&logoColor=white&labelColor=0d1117"/>
  </a>
  &nbsp;
  <a href="https://github.com/Athexblackhat">
    <img src="https://img.shields.io/badge/GitHub-Athexblackhat-00ff88?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117"/>
  </a>
  &nbsp;
  <a href="https://fb.com/athexxinzii">
    <img src="https://img.shields.io/badge/Facebook-athexxinzii-1877F2?style=for-the-badge&logo=facebook&logoColor=white&labelColor=0d1117"/>
  </a>
</p>

---

<!-- ═══════════════════════════════════════════════════════ -->
<!--                   FOOTER SVG                            -->
<!-- ═══════════════════════════════════════════════════════ -->

<div align="center">

<svg width="100%" viewBox="0 0 900 90" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#020810"/>
      <stop offset="50%" stop-color="#060f1e"/>
      <stop offset="100%" stop-color="#020810"/>
    </linearGradient>
  </defs>
  <rect width="900" height="90" fill="url(#footerGrad)" rx="12" stroke="#00ff8818" stroke-width="1"/>
  <!-- Top animated sweep line -->
  <rect x="0" y="0" width="0" height="1.5" fill="#00ff88" rx="1">
    <animate attributeName="width" values="0;900;0" dur="5s" repeatCount="indefinite"/>
  </rect>
  <!-- Bracket corners -->
  <polyline points="0,20 0,0 20,0" stroke="#00ff88" stroke-width="1.5" fill="none" opacity="0.6"/>
  <polyline points="880,0 900,0 900,20" stroke="#00d4ff" stroke-width="1.5" fill="none" opacity="0.6"/>
  <polyline points="0,70 0,90 20,90" stroke="#00d4ff" stroke-width="1.5" fill="none" opacity="0.6"/>
  <polyline points="880,90 900,90 900,70" stroke="#00ff88" stroke-width="1.5" fill="none" opacity="0.6"/>
  <!-- Text -->
  <text x="450" y="38" text-anchor="middle" font-family="'Courier New', monospace" font-size="14" fill="#00ff88aa" letter-spacing="5">ATHEX  ·  Security Researcher  ·  Pakistan 🇵🇰</text>
  <text x="450" y="64" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#00ff8850" letter-spacing="2">// ALLAH first. Knowledge second. Everything else follows. 🤲</text>
  <!-- Pulsing dots -->
  <circle cx="22" cy="45" r="3" fill="#00ff88"><animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/></circle>
  <circle cx="878" cy="45" r="3" fill="#00d4ff"><animate attributeName="opacity" values="0.2;1;0.2" dur="2.6s" repeatCount="indefinite"/></circle>
</svg>

</div>
