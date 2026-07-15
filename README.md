<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg">
<defs>
  <style>
    .pill-hover:hover rect { stroke-opacity: 1; }
  </style>

  <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%" stop-color="#FFFFFF"/>
    <stop offset="100%" stop-color="#F8FAFC"/>
  </linearGradient>

  <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%" stop-color="#2563EB"/>
    <stop offset="50%" stop-color="#06B6D4"/>
    <stop offset="100%" stop-color="#10B981"/>
    <animate attributeName="x1" values="0%;100%;0%" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="100%;200%;100%" dur="8s" repeatCount="indefinite"/>
  </linearGradient>

  <linearGradient id="roleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
    <stop offset="0%" stop-color="#2563EB"/>
    <stop offset="100%" stop-color="#06B6D4"/>
  </linearGradient>

  <linearGradient id="borderGrad" x1="0%" y1="0%" x2="100%" y2="100%">
    <stop offset="0%" stop-color="#2563EB" stop-opacity="0.9"/>
    <stop offset="50%" stop-color="#06B6D4" stop-opacity="0.9"/>
    <stop offset="100%" stop-color="#10B981" stop-opacity="0.9"/>
    <animateTransform attributeName="gradientTransform" type="rotate" from="0 590 305" to="360 590 305" dur="10s" repeatCount="indefinite"/>
  </linearGradient>

  <radialGradient id="glowBlue" cx="15%" cy="10%" r="60%">
    <stop offset="0%" stop-color="#2563EB" stop-opacity="0.25"/>
    <stop offset="100%" stop-color="#2563EB" stop-opacity="0"/>
  </radialGradient>
  <radialGradient id="glowCyan" cx="90%" cy="85%" r="60%">
    <stop offset="0%" stop-color="#06B6D4" stop-opacity="0.20"/>
    <stop offset="100%" stop-color="#06B6D4" stop-opacity="0"/>
  </radialGradient>

  <filter id="asciiGlow" x="-20%" y="-20%" width="140%" height="140%">
    <feGaussianBlur stdDeviation="0.35" result="blur"/>
    <feMerge>
      <feMergeNode in="blur"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>

  <filter id="pillGlow" x="-40%" y="-40%" width="180%" height="180%">
    <feGaussianBlur stdDeviation="1.2" result="blur"/>
    <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>

  <clipPath id="roundedCanvas">
    <rect x="0" y="0" width="1180" height="610" rx="24"/>
  </clipPath>
</defs>

<g clip-path="url(#roundedCanvas)">
  <rect width="1180" height="610" fill="url(#bgGrad)"/>
  <rect width="1180" height="610" fill="url(#glowBlue)"/>
  <rect width="1180" height="610" fill="url(#glowCyan)"/>

  <!-- floating particles -->
  <g fill="#06B6D4" opacity="0.5">
    <circle cx="120" cy="90" r="1.6"><animate attributeName="cy" values="90;70;90" dur="6s" repeatCount="indefinite"/></circle>
    <circle cx="360" cy="480" r="1.3"><animate attributeName="cy" values="480;455;480" dur="7s" repeatCount="indefinite"/></circle>
    <circle cx="900" cy="120" r="1.5"><animate attributeName="cy" values="120;100;120" dur="5.5s" repeatCount="indefinite"/></circle>
    <circle cx="1050" cy="500" r="1.4"><animate attributeName="cy" values="500;520;500" dur="6.5s" repeatCount="indefinite"/></circle>
    <circle cx="700" cy="60" r="1.2"><animate attributeName="cy" values="60;80;60" dur="5s" repeatCount="indefinite"/></circle>
  </g>

  <!-- outer border shimmer -->
  <rect x="2" y="2" width="1176" height="606" rx="22" fill="none" stroke="url(#borderGrad)" stroke-width="1.4"/>

  <!-- LEFT PANEL -->
  <g>
    <rect x="24" y="24" width="408" height="562" rx="16" fill="#F8FAFC" fill-opacity="0.55" stroke="rgba(15,23,42,.08)" stroke-width="1"/>
    <text x="34" y="34" font-family="Consolas, monospace" font-size="11" fill="#475569">ascii_portrait.render()</text>
    <g font-family="Consolas, Menlo, monospace" font-size="8.6" fill="url(#asciiGrad)" filter="url(#asciiGlow)">
<text x="34" y="60.0" opacity="0" xml:space="preserve">@@@@@@@@@@@@@@@@@@@@@@@@%*+=-::........::-=+*%@@@@@@@@@@@@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.0s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="73.3" opacity="0" xml:space="preserve">@@@@@@@@@@@@@@@@@@@%#+-:......................:-+#%@@@@@@@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.045s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="86.6" opacity="0" xml:space="preserve">@@@@@@@@@@@@@@@@%*-.. .......................... ..-*%@@@@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.09s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="99.9" opacity="0" xml:space="preserve">@@@@@@@@@@@@@@*-. ........... ...................... .-*@@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.135s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="113.2" opacity="0" xml:space="preserve">@@@@@@@@@@@@*:. ............-+******+=--:. ........... .:*@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.18s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="126.5" opacity="0" xml:space="preserve">@@@@@@@@@@*: .............=#@@%%#%%@%%%%%#+:............. :*@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.225s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="139.8" opacity="0" xml:space="preserve">@@@@@@@@%- .............:#@@@%##*+=---+#@@@%:.............. -%@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.27s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="153.10000000000002" opacity="0" xml:space="preserve">@@@@@@@+. ..............#@@#+=-::::::---+%@@*............... .+@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.315s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="166.4" opacity="0" xml:space="preserve">@@@@@@- .............. =@%*=--:::::::---+%@%*................. =@@@@@@<animate attributeName="opacity" from="0" to="1" begin="0.36s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="179.7" opacity="0" xml:space="preserve">@@@@%- ................:@%+==--::::=++++=*@%-.................. -%@@@@<animate attributeName="opacity" from="0" to="1" begin="0.405s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="193.0" opacity="0" xml:space="preserve">@@@@: ..................+%+#%%%#+=*%@%%#+-#*:................... :@@@@<animate attributeName="opacity" from="0" to="1" begin="0.45s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="206.3" opacity="0" xml:space="preserve">@@@- ....................**###**+-+++*++=-++-.................... -@@@<animate attributeName="opacity" from="0" to="1" begin="0.495s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="219.60000000000002" opacity="0" xml:space="preserve">@@= ....................:+=------:---:::--++:..................... +@@<animate attributeName="opacity" from="0" to="1" begin="0.54s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="232.9" opacity="0" xml:space="preserve">@#.......................=+--:-+*+##+---=+*=........................#@<animate attributeName="opacity" from="0" to="1" begin="0.585s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="246.20000000000002" opacity="0" xml:space="preserve">@-.......................:*+=+*%%#####*=+*#:....................... -@<animate attributeName="opacity" from="0" to="1" begin="0.63s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="259.5" opacity="0" xml:space="preserve">#.........................=#+*#*+=+++*#*#%#..........................#<animate attributeName="opacity" from="0" to="1" begin="0.675s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="272.8" opacity="0" xml:space="preserve">-..........................*%#*++#%#+*#%@%-..........................=<animate attributeName="opacity" from="0" to="1" begin="0.72s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="286.1" opacity="0" xml:space="preserve">............................+@@%#%%#%@@@%= ..........................:<animate attributeName="opacity" from="0" to="1" begin="0.765s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="299.4" opacity="0" xml:space="preserve">............................**#%@@@@@%%#*#=...........................<animate attributeName="opacity" from="0" to="1" begin="0.81s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="312.70000000000005" opacity="0" xml:space="preserve">........................ ..+%++*#%%%%##**%%=:.........................<animate attributeName="opacity" from="0" to="1" begin="0.855s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="326.0" opacity="0" xml:space="preserve">......................:-=*#%%*=+**###***#%%%##*=-:...................:<animate attributeName="opacity" from="0" to="1" begin="0.9s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="339.3" opacity="0" xml:space="preserve">-................:-=*#%%%@%#%%++=+****#%@@%#%%%%%##*=-:..............=<animate attributeName="opacity" from="0" to="1" begin="0.945s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="352.6" opacity="0" xml:space="preserve">*.............:=*#%%@%%%%%%@@@%*=-==+#@@@@@%%%%%%%%%%%##+-...........*<animate attributeName="opacity" from="0" to="1" begin="0.99s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="365.90000000000003" opacity="0" xml:space="preserve">@:..........:*%%%%%%%%%%%%@@%@@@@*-+%@@@@@%@%%%%%%%%%%%%%%=.........:@<animate attributeName="opacity" from="0" to="1" begin="1.035s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="379.20000000000005" opacity="0" xml:space="preserve">@* ........:#%%%%%%%%%%%%%%%%%%%%@%%@%%%%%%%%%%%%%%%%%%%%%%=....... *@<animate attributeName="opacity" from="0" to="1" begin="1.08s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="392.5" opacity="0" xml:space="preserve">@@- ......:#%%%%%%%%%%%%%%%%%%%%%%@%%%%%%%%%%%%%%%%%%%%%%%%#:..... -@@<animate attributeName="opacity" from="0" to="1" begin="1.125s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="405.8" opacity="0" xml:space="preserve">@@%:......+%%%%%%%%%%%%%%%%%%%##%%%%%%%#%%%#%%%%%%%%%%%%%%%%=.....:%@@<animate attributeName="opacity" from="0" to="1" begin="1.17s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="419.1" opacity="0" xml:space="preserve">@@@%.....-%%%%%%%%%%%%%#%%%%%%#%%%%#%%%#%%#####%%%%%%%%%%%%%+.....%@@@<animate attributeName="opacity" from="0" to="1" begin="1.215s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="432.40000000000003" opacity="0" xml:space="preserve">@@@@%: ..*%%%%%%%%%%%%%##%####%%%%%%%%%%%%#####%%%%%%%%%%%%%*.. :%@@@@<animate attributeName="opacity" from="0" to="1" begin="1.26s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="445.70000000000005" opacity="0" xml:space="preserve">@@@@@%- :#%%%%%%%@%%%%%%%####%%%%%#%%%%#######%%%%@%%%%%%%%%#. -%@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.305s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="459.0" opacity="0" xml:space="preserve">@@@@@@@==%%%%%%%%@@@%%%%####%%%%%###%%%####%%%%%%@%%%%%%%%%%#:+@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.35s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="472.3" opacity="0" xml:space="preserve">@@@@@@@@@%%%%%%%%%@@%%%%%%%%%%%%%%%%%%###%%%%%%%%@%%%%%%%%%#%%@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.395s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="485.6" opacity="0" xml:space="preserve">@@@@@@@@@@@%%%%%%%@@%%%%%%%%%%%%%%%%%%%%%%%%%%%%@%%%%%#%##%@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.44s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="498.90000000000003" opacity="0" xml:space="preserve">@@@@@@@@@@@@@%%%%%@@%@%%%%%%%%%%%%%%%%%%%%%%%%%@@%%%####%@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.485s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="512.2" opacity="0" xml:space="preserve">@@@@@@@@@@@@@@@%%%@@@@@@@@%%@%%%%%%%%%%%%%%%%@@@%%%##%%@@@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.53s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="525.5" opacity="0" xml:space="preserve">@@@@@@@@@@@@@@@@@@@@@@@@@%@@%%%@%##%%%%%%%@@@@@@%%%%@@@@@@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.575s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="538.8" opacity="0" xml:space="preserve">@@@@@@@@@@@@@@@@@@@@@@@@%%%%%%%%%%%%%%%%%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.62s" dur="0.35s" fill="freeze"/></text>
<text x="34" y="552.1" opacity="0" xml:space="preserve">@@@@@@@@@@@@@@@@@@@@@@@@@%@%%%%%%%%%%%%%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@<animate attributeName="opacity" from="0" to="1" begin="1.665s" dur="0.35s" fill="freeze"/></text>
</g>
    <!-- scanline -->
    <rect x="24" y="24" width="408" height="2" fill="#06B6D4" opacity="0.25">
      <animate attributeName="y" values="30;570;30" dur="5s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- RIGHT PANEL: terminal window -->
  <g>
    <rect x="464" y="24" width="692" height="562" rx="16" fill="#F8FAFC" fill-opacity="0.55" stroke="rgba(15,23,42,.08)" stroke-width="1"/>
    <!-- title bar -->
    <circle cx="492" cy="52" r="5" fill="#FF5F56"/>
    <circle cx="510" cy="52" r="5" fill="#FFBD2E"/>
    <circle cx="528" cy="52" r="5" fill="#27C93F"/>
    <text x="1110" y="57" text-anchor="end" font-family="Consolas, monospace" font-size="11" fill="#475569">profile.sh</text>
    <line x1="464" y1="70" x2="1156" y2="70" stroke="rgba(15,23,42,.08)" stroke-width="1"/>

    <text x="504" y="110" font-family="Segoe UI, sans-serif" font-size="17" fill="#475569">Hi 👋</text>
    <text x="504" y="140" font-family="Segoe UI, sans-serif" font-size="26" font-weight="700" fill="#0F172A">I'm Pratik Kumar Prajapati</text>

    <g id="role0" opacity="0"><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.28;0.78;1" dur="2.6s" begin="0s;role4.end" fill="freeze"/><text x="504" y="168" font-family="Consolas, Menlo, monospace" font-size="20" font-weight="600" fill="url(#roleGrad)">Python Developer</text><rect x="700.0" y="152" width="9" height="20" fill="#10B981"><animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/></rect></g>
<g id="role1" opacity="0"><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.28;0.78;1" dur="2.6s" begin="role0.end" fill="freeze"/><text x="504" y="168" font-family="Consolas, Menlo, monospace" font-size="20" font-weight="600" fill="url(#roleGrad)">Automation Engineer</text><rect x="736.0" y="152" width="9" height="20" fill="#10B981"><animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/></rect></g>
<g id="role2" opacity="0"><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.28;0.78;1" dur="2.6s" begin="role1.end" fill="freeze"/><text x="504" y="168" font-family="Consolas, Menlo, monospace" font-size="20" font-weight="600" fill="url(#roleGrad)">REST API Developer</text><rect x="724.0" y="152" width="9" height="20" fill="#10B981"><animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/></rect></g>
<g id="role3" opacity="0"><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.28;0.78;1" dur="2.6s" begin="role2.end" fill="freeze"/><text x="504" y="168" font-family="Consolas, Menlo, monospace" font-size="20" font-weight="600" fill="url(#roleGrad)">AI Tools Explorer</text><rect x="712.0" y="152" width="9" height="20" fill="#10B981"><animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/></rect></g>
<g id="role4" opacity="0"><animate attributeName="opacity" values="0;1;1;0" keyTimes="0;0.28;0.78;1" dur="2.6s" begin="role3.end" fill="freeze"/><text x="504" y="168" font-family="Consolas, Menlo, monospace" font-size="20" font-weight="600" fill="url(#roleGrad)">Open Source Learner</text><rect x="736.0" y="152" width="9" height="20" fill="#10B981"><animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/></rect></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="2.2s" dur="0.5s" fill="freeze"/><text x="504" y="210" font-family="Segoe UI, Helvetica, sans-serif" font-size="15" fill="#0F172A"><tspan>📍</tspan> <tspan fill="#475569">Ballia, Uttar Pradesh, India</tspan></text></g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="2.45s" dur="0.5s" fill="freeze"/><text x="504" y="237" font-family="Segoe UI, Helvetica, sans-serif" font-size="15" fill="#0F172A"><tspan>🎓</tspan> <tspan fill="#475569">B.Tech, Computer Science (2026)</tspan></text></g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="2.7s" dur="0.5s" fill="freeze"/><text x="504" y="264" font-family="Segoe UI, Helvetica, sans-serif" font-size="15" fill="#0F172A"><tspan>⚡</tspan> <tspan fill="#475569">Automation · REST APIs · AI Tools</tspan></text></g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="2.95s" dur="0.5s" fill="freeze"/><text x="504" y="291" font-family="Segoe UI, Helvetica, sans-serif" font-size="15" fill="#0F172A"><tspan>🌐</tspan> <tspan fill="#475569">github.com/pikuwa</tspan></text></g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.2s" dur="0.5s" fill="freeze"/><text x="504" y="318" font-family="Segoe UI, Helvetica, sans-serif" font-size="15" fill="#0F172A"><tspan>✉</tspan> <tspan fill="#475569">pratik689prajapati@gmail.com</tspan></text></g>

    <line x1="504" y1="345" x2="1110" y2="345" stroke="rgba(15,23,42,.08)" stroke-width="1"/>
    <text x="504" y="365" font-family="Segoe UI, sans-serif" font-size="13" font-weight="700" fill="#475569" letter-spacing="1">SKILLS</text>

    <g font-family="Segoe UI, Helvetica, sans-serif" font-size="12.5" font-weight="600">
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="2.4s" dur="0.4s" fill="freeze"/><rect x="504" y="372" width="60.8" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="2.4s" repeatCount="indefinite"/></rect><text x="534.4" y="389" text-anchor="middle" fill="#0F172A">Python</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="2.48s" dur="0.4s" fill="freeze"/><rect x="574.8" y="372" width="53.5" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="2.48s" repeatCount="indefinite"/></rect><text x="601.5" y="389" text-anchor="middle" fill="#0F172A">Flask</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="2.56s" dur="0.4s" fill="freeze"/><rect x="638.3" y="372" width="75.4" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="2.56s" repeatCount="indefinite"/></rect><text x="676.0" y="389" text-anchor="middle" fill="#0F172A">REST API</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="2.64s" dur="0.4s" fill="freeze"/><rect x="723.6999999999999" y="372" width="60.8" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="2.64s" repeatCount="indefinite"/></rect><text x="754.1" y="389" text-anchor="middle" fill="#0F172A">Pandas</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="2.72s" dur="0.4s" fill="freeze"/><rect x="794.4999999999999" y="372" width="75.4" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="2.72s" repeatCount="indefinite"/></rect><text x="832.2" y="389" text-anchor="middle" fill="#0F172A">Selenium</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="2.8s" dur="0.4s" fill="freeze"/><rect x="879.8999999999999" y="372" width="38.9" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="2.8s" repeatCount="indefinite"/></rect><text x="899.3" y="389" text-anchor="middle" fill="#0F172A">SQL</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="2.88s" dur="0.4s" fill="freeze"/><rect x="928.7999999999998" y="372" width="38.9" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="2.88s" repeatCount="indefinite"/></rect><text x="948.2" y="389" text-anchor="middle" fill="#0F172A">Git</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="2.96s" dur="0.4s" fill="freeze"/><rect x="977.6999999999998" y="372" width="60.8" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="2.96s" repeatCount="indefinite"/></rect><text x="1008.1" y="389" text-anchor="middle" fill="#0F172A">Docker</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="3.04s" dur="0.4s" fill="freeze"/><rect x="1048.4999999999998" y="372" width="75.4" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="3.04s" repeatCount="indefinite"/></rect><text x="1086.2" y="389" text-anchor="middle" fill="#0F172A">Power BI</text></g>
<g opacity="0" style="cursor:pointer" filter="url(#pillGlow)"><animate attributeName="opacity" from="0" to="1" begin="3.12s" dur="0.4s" fill="freeze"/><rect x="504" y="406" width="82.7" height="26" rx="13" fill="#FFFFFF" stroke="#2563EB" stroke-width="1"><animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="3s" begin="3.12s" repeatCount="indefinite"/></rect><text x="545.4" y="423" text-anchor="middle" fill="#0F172A">AI Agents</text></g>
</g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="2.9s" dur="0.4s" fill="freeze"/><circle cx="516" cy="474" r="17" fill="#F1F5F9" stroke="#2563EB" stroke-width="1.2"><animate attributeName="r" values="17;18;17" dur="2.6s" begin="2.9s" repeatCount="indefinite"/></circle><text x="516" y="479" text-anchor="middle" font-family="Segoe UI, sans-serif" font-size="13" font-weight="700" fill="#0F172A">GH</text></g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.0s" dur="0.4s" fill="freeze"/><circle cx="568" cy="474" r="17" fill="#F1F5F9" stroke="#2563EB" stroke-width="1.2"><animate attributeName="r" values="17;18;17" dur="2.6s" begin="3.0s" repeatCount="indefinite"/></circle><text x="568" y="479" text-anchor="middle" font-family="Segoe UI, sans-serif" font-size="13" font-weight="700" fill="#0F172A">in</text></g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.1s" dur="0.4s" fill="freeze"/><circle cx="620" cy="474" r="17" fill="#F1F5F9" stroke="#2563EB" stroke-width="1.2"><animate attributeName="r" values="17;18;17" dur="2.6s" begin="3.1s" repeatCount="indefinite"/></circle><text x="620" y="479" text-anchor="middle" font-family="Segoe UI, sans-serif" font-size="13" font-weight="700" fill="#0F172A">𝕏</text></g>
<g opacity="0"><animate attributeName="opacity" from="0" to="1" begin="3.2s" dur="0.4s" fill="freeze"/><circle cx="672" cy="474" r="17" fill="#F1F5F9" stroke="#2563EB" stroke-width="1.2"><animate attributeName="r" values="17;18;17" dur="2.6s" begin="3.2s" repeatCount="indefinite"/></circle><text x="672" y="479" text-anchor="middle" font-family="Segoe UI, sans-serif" font-size="13" font-weight="700" fill="#0F172A">🔗</text></g>
  </g>
</g>
</svg>

<div align="center">

# Hi 👋, I'm Pratik Kumar Prajapati

### Python Developer • Automation Engineer • REST API Enthusiast • AI Tools Explorer

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00C2FF&center=true&vCenter=true&width=700&lines=Python+Developer;Automation+Engineer;REST+API+Developer;AI+Tools+Explorer;Open+Source+Learner" />

![Profile Views](https://komarev.com/ghpvc/?username=pikuwa&color=00C2FF&style=flat-square)

</div>

---

## 🚀 About Me

- 🎓 B.Tech in Computer Science & Engineering (2026)
- 💻 Passionate about building real-world Python applications
- 📍 Ballia, Uttar Pradesh, India

**⚡ Interested in**
Automation · REST APIs · AI Tools · Data Analytics · Data Visualization

**🌱 Currently Learning**
SQL · Power BI · AI Agents · AI Tools 

---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Libraries**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-000000?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?style=for-the-badge&logo=python&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)

**Backend**

![REST API](https://img.shields.io/badge/REST%20API-005571?style=for-the-badge&logo=fastapi&logoColor=white)

**Database**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)

---

## 🚀 Featured Projects

### 📌 [Habit Tracker](https://github.com/pikuwa/habit-tracker)
✔ Pixela API · ✔ REST API · ✔ Python
Track daily habits with beautiful graphs.

### 📌 [Workout Tracker](https://github.com/pikuwa/workout-tracker)
✔ Nutritionix API · ✔ Sheety API · ✔ Python
Natural language workout logger.

### 📌 [Vocabulary Flash Card App](https://github.com/pikuwa/Vocabulary-Flash-Card-App)
✔ Tkinter · ✔ Pandas · ✔ CSV Database
Interactive vocabulary learning application.

> 💡 Update the links above with your actual repo URLs if these differ.

---

## 📈 GitHub Stats

<p align="center">
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=pikuwa&show_icons=true&theme=tokyonight"/>
<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=pikuwa&theme=tokyonight"/>
</p>

## 📊 Most Used Languages

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pikuwa&layout=compact&theme=tokyonight"/>
</p>

## 🏆 GitHub Trophies

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=pikuwa&theme=algolia&column=4&margin-w=15"/>
</p>

---

## 🌐 Connect with Me

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pikuwa)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pratikxdev)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pratik689prajapati@gmail.com)

---

<div align="center">

> "Consistency beats talent when talent doesn't stay consistent."

⭐ Thanks for visiting my profile!

</div>
