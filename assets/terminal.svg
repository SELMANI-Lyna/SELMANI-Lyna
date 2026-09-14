<img width="1200" height="900" alt="lyna_interactive_terminal_profile" src="https://github.com/user-attachments/assets/b75e1967-1d3c-4f2c-998f-841c51c2683a" />
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="900" viewBox="0 0 1200 900" role="img" aria-label="Lyna's animated interactive terminal profile">
<defs>
  <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0" stop-color="#07040d"/>
    <stop offset=".48" stop-color="#12081b"/>
    <stop offset="1" stop-color="#05030a"/>
  </linearGradient>
  <linearGradient id="bar" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0" stop-color="#ff4fd8"/>
    <stop offset=".55" stop-color="#c66cff"/>
    <stop offset="1" stop-color="#7f6cff"/>
  </linearGradient>
  <filter id="glow">
    <feGaussianBlur stdDeviation="3.5" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <clipPath id="screen"><rect x="28" y="78" width="1144" height="790" rx="15"/></clipPath>

  <style>
    .mono{font-family:"JetBrains Mono","Fira Code","Courier New",monospace}
    .prompt{fill:#ff70dc;font-size:22px;font-weight:700}
    .cmd{fill:#f3d9ff;font-size:22px;font-weight:600}
    .out{fill:#eee7f5;font-size:20px}
    .muted{fill:#9f8dab;font-size:19px}
    .pink{fill:#ff70dc}
    .purple{fill:#c78bff}
    .cyan{fill:#72e9ff}
    .green{fill:#83f7c5}
    .yellow{fill:#ffd778}
    .red{fill:#ff6d9f}
    .project{fill:#72e9ff;font-size:20px;font-weight:600;text-decoration:underline}
    .small{font-size:16px}

    /* Each scene is a complete terminal session. Nothing is visible at first.
       The command itself is revealed character-by-character with a stepped
       clip, then its output appears afterwards. */
    .scene{opacity:0}
    .s1{animation:scene1 54s linear infinite}
    .s2{animation:scene2 54s linear infinite}
    .s3{animation:scene3 54s linear infinite}
    .s4{animation:scene4 54s linear infinite}
    .s5{animation:scene5 54s linear infinite}
    .s6{animation:scene6 54s linear infinite}
    .s7{animation:scene7 54s linear infinite}

    .typing1{clip-path:inset(0 100% 0 0);animation:type1 54s steps(30,end) infinite}
    .typing2{clip-path:inset(0 100% 0 0);animation:type2 54s steps(34,end) infinite}
    .typing3{clip-path:inset(0 100% 0 0);animation:type3 54s steps(36,end) infinite}
    .typing4{clip-path:inset(0 100% 0 0);animation:type4 54s steps(34,end) infinite}
    .typing5{clip-path:inset(0 100% 0 0);animation:type5 54s steps(39,end) infinite}
    .typing6{clip-path:inset(0 100% 0 0);animation:type6 54s steps(44,end) infinite}
    .typing7{clip-path:inset(0 100% 0 0);animation:type7 54s steps(28,end) infinite}

    .cursor{animation:blink .8s steps(1,end) infinite}
    .scan{animation:scan 7s linear infinite}
    .pulse{animation:pulse 2.8s ease-in-out infinite}

    @keyframes blink{0%,49%{opacity:1}50%,100%{opacity:0}}
    @keyframes scan{0%{transform:translateY(0);opacity:0}20%{opacity:.25}100%{transform:translateY(790px);opacity:0}}
    @keyframes pulse{0%,100%{opacity:.45}50%{opacity:1}}

    /* Scene windows. Each gets a long reading pause. */
    @keyframes scene1{0%,1%{opacity:0}2%,13%{opacity:1}15%,100%{opacity:0}}
    @keyframes scene2{14%,15%{opacity:0}16%,27%{opacity:1}29%,100%{opacity:0}}
    @keyframes scene3{28%,29%{opacity:0}30%,42%{opacity:1}44%,100%{opacity:0}}
    @keyframes scene4{43%,44%{opacity:0}45%,59%{opacity:1}61%,100%{opacity:0}}
    @keyframes scene5{60%,61%{opacity:0}62%,75%{opacity:1}77%,100%{opacity:0}}
    @keyframes scene6{76%,77%{opacity:0}78%,91%{opacity:1}93%,100%{opacity:0}}
    @keyframes scene7{92%,93%{opacity:0}94%,100%{opacity:1}}

    @keyframes type1{0%,1%{clip-path:inset(0 100% 0 0)}2%,8%{clip-path:inset(0 0 0 0)}13%,100%{clip-path:inset(0 0 0 0)}}
    @keyframes type2{0%,14%,15%{clip-path:inset(0 100% 0 0)}16%,22%{clip-path:inset(0 0 0 0)}27%,100%{clip-path:inset(0 0 0 0)}}
    @keyframes type3{0%,28%,29%{clip-path:inset(0 100% 0 0)}30%,37%{clip-path:inset(0 0 0 0)}42%,100%{clip-path:inset(0 0 0 0)}}
    @keyframes type4{0%,43%,44%{clip-path:inset(0 100% 0 0)}45%,52%{clip-path:inset(0 0 0 0)}59%,100%{clip-path:inset(0 0 0 0)}}
    @keyframes type5{0%,60%,61%{clip-path:inset(0 100% 0 0)}62%,70%{clip-path:inset(0 0 0 0)}75%,100%{clip-path:inset(0 0 0 0)}}
    @keyframes type6{0%,76%,77%{clip-path:inset(0 100% 0 0)}78%,87%{clip-path:inset(0 0 0 0)}91%,100%{clip-path:inset(0 0 0 0)}}
    @keyframes type7{0%,92%,93%{clip-path:inset(0 100% 0 0)}94%,99%{clip-path:inset(0 0 0 0)}100%{clip-path:inset(0 0 0 0)}}
  </style>
</defs>

<!-- terminal shell -->
<rect width="1200" height="900" rx="24" fill="url(#bg)"/>
<rect x="28" y="28" width="1144" height="840" rx="15" fill="#0a0610" stroke="#4d3159" stroke-width="2"/>
<rect x="28" y="28" width="1144" height="50" rx="15" fill="#150b1d"/>
<circle cx="58" cy="53" r="8" fill="#ff639f"/>
<circle cx="84" cy="53" r="8" fill="#ffd66b"/>
<circle cx="110" cy="53" r="8" fill="#72f5b5"/>
<text x="600" y="59" text-anchor="middle" class="mono muted small">lyna@github: ~/profile</text>

<g clip-path="url(#screen)">
  <rect x="28" y="78" width="1144" height="2" fill="url(#bar)" class="scan"/>

  <!-- Scene 1: whoami -->
  <g class="scene s1 mono">
    <text x="58" y="130" class="prompt">lyna@github:~$</text>
    <text x="270" y="130" class="cmd typing1"> whoami</text>
    <text x="58" y="172" class="out">Lyna Selmani</text>
    <text x="58" y="215" class="muted">Cybae Security Student</text>
    <text x="58" y="250" class="muted">building • learning • breaking • fixing</text>
  </g>

  <!-- Scene 2: about -->
  <g class="scene s2 mono">
    <text x="58" y="130" class="prompt">lyna@github:~$</text>
    <text x="270" y="130" class="cmd typing2"> cat about.txt</text>
    <text x="58" y="177" class="out">I build software, explore cybersecurity,</text>
    <text x="58" y="212" class="out">and learn by turning ideas into projects.</text>
    <text x="58" y="260" class="purple">focus:</text>
    <text x="155" y="260" class="out">Cybersecurity • AI / LLMs • Full-Stack</text>
    <text x="58" y="295" class="purple">currently:</text>
    <text x="170" y="295" class="out">SCADA / ICS Security • Linux • Networking</text>
  </g>

  <!-- Scene 3: interests -->
  <g class="scene s3 mono">
    <text x="58" y="130" class="prompt">lyna@github:~$</text>
    <text x="270" y="130" class="cmd typing3"> cat interests.txt</text>
    <text x="58" y="180" class="green">01</text><text x="105" y="180" class="out">Cybersecurity</text>
    <text x="58" y="220" class="green">02</text><text x="105" y="220" class="out">SCADA / ICS Security</text>
    <text x="58" y="260" class="green">03</text><text x="105" y="260" class="out">Artificial Intelligence / LLMs</text>
    <text x="58" y="300" class="green">04</text><text x="105" y="300" class="out">Linux &amp; Networking</text>
    <text x="58" y="340" class="green">05</text><text x="105" y="340" class="out">Web &amp; Full-Stack Development</text>
  </g>

  <!-- Scene 4: projects, clickable -->
  <g class="scene s4 mono">
    <text x="58" y="130" class="prompt">lyna@github:~$</text>
    <text x="270" y="130" class="cmd typing4"> ls ~/projects</text>

    <a href="https://github.com/SELMANI-Lyna/Lit" target="https://github.com/SELMANI-Lyna/Lit">
      <text x="75" y="185" class="project">LITAN-LLM/</text>
    </a>
    <text x="290" y="185" class="muted">LLM interaction tracking &amp; experimentation</text>

    <a href="https://github.com/SELMANI-Lyna/ComandBase" target="https://github.com/SELMANI-Lyna/CommandBase">
      <text x="75" y="230" class="project">ComandBase/</text>
    </a>
    <text x="290" y="230" class="muted">cybersecurity commands &amp; tools knowledge base</text>

    <a href="https://github.com/SELMANI-Lyna/DZ-Fit" target="https://github.com/SELMANI-Lyna/Glproject">
      <text x="75" y="275" class="project">DZ-Fit/</text>
    </a>
    <text x="290" y="275" class="muted">gym finder • maps • FastAPI • Next.js</text>

    <a href="https://github.com/SELMANI-Lyna/E-commerce" target="_blank">
      <text x="75" y="320" class="project">E-commerce/</text>
    </a>
    <text x="290" y="320" class="muted">freelance store • Email • EcoTrack</text>

    <a href="https://github.com/SELMANI-Lyna/Network-Labs" target="_blank">
      <text x="75" y="365" class="project">Network-Labs/</text>
    </a>
    <text x="290" y="365" class="muted">routing • DNS • NAT • Wireshark</text>

    <a href="https://github.com/SELMANI-Lyna/Security-Labs" target="_blank">
      <text x="75" y="410" class="project">Security-Labs/</text>
    </a>
    <text x="290" y="410" class="muted">CTF • forensics • security experiments</text>

    <text x="75" y="462" class="purple">13 repositories</text>
    <text x="265" y="462" class="muted">click a project to open its repository ↗</text>
  </g>

  <!-- Scene 5: status -->
  <g class="scene s5 mono">
    <text x="58" y="130" class="prompt">lyna@github:~$</text>
    <text x="270" y="130" class="cmd typing5"> systemctl status lyna</text>
    <text x="58" y="180" class="green">● lyna.service - learning &amp; building</text>
    <text x="58" y="220" class="out">Loaded: <tspan class="green">active</tspan></text>
    <text x="58" y="260" class="out">Focus: <tspan class="purple">cybersecurity + SCADA/ICS + AI</tspan></text>
    <text x="58" y="300" class="out">Projects: <tspan class="cyan">13 repositories</tspan></text>
    <text x="58" y="340" class="out">Mood: <tspan class="pink">terminal gremlin</tspan></text>
  </g>

  <!-- Scene 6: cyber joke / learning -->
  <g class="scene s6 mono">
    <text x="58" y="130" class="prompt">lyna@github:~$</text>
    <text x="270" y="130" class="cmd typing6"> sudo nmap --open learning-path</text>
    <text x="58" y="178" class="muted">Starting scan...</text>
    <text x="58" y="218" class="green">22/tcp    OPEN    Linux</text>
    <text x="58" y="258" class="green">80/tcp    OPEN    Web Development</text>
    <text x="58" y="298" class="green">443/tcp   OPEN    Cybersecurity</text>
    <text x="58" y="338" class="green">502/tcp   OPEN    SCADA / ICS</text>
    <text x="58" y="390" class="yellow">Scan complete: more things to learn.</text>
  </g>

  <!-- Scene 7: git status -->
  <g class="scene s7 mono">
    <text x="58" y="130" class="prompt">lyna@github:~$</text>
    <text x="270" y="130" class="cmd typing7"> git status</text>
    <text x="58" y="180" class="green">On branch main</text>
    <text x="58" y="220" class="out">Your branch is up to date with <tspan class="purple">learning</tspan>.</text>
    <text x="58" y="270" class="muted">Changes not staged for commit:</text>
    <text x="80" y="310" class="red">modified:  skills.txt</text>
    <text x="80" y="345" class="red">modified:  projects.txt</text>
    <text x="80" y="380" class="red">modified:  future.plans</text>
    <text x="58" y="435" class="out">nothing is ever really finished <tspan class="pink">♥</tspan></text>
  </g>
</g>

<!-- persistent bottom prompt -->
<text x="58" y="835" class="mono prompt">lyna@github:~$ <tspan class="cursor">█</tspan></text>
<text x="1120" y="835" text-anchor="end" class="mono muted small pulse">ONLINE</text>
</svg>
