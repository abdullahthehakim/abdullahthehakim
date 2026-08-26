<?xml version="1.0" encoding="UTF-8"?>
<svg width="850" height="820" viewBox="0 0 850 820" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      .h { font-family: 'Segoe UI', Helvetica, Arial, sans-serif; }
      .m { font-family: 'SFMono-Regular', Consolas, 'Courier New', monospace; }
    </style>
    <filter id="glowSoft" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glowStrong" x="-100%" y="-100%" width="300%" height="300%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <linearGradient id="sheenGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0"/>
      <stop offset="50%" stop-color="#FFFFFF" stop-opacity="0.05"/>
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0"/>
    </linearGradient>
  </defs>

  <rect x="0" y="0" width="850" height="820" fill="#000000"/>

  <!-- outer frame + corner ticks -->
  <rect x="14" y="14" width="822" height="792" fill="none" stroke="#1E1E1E" stroke-width="1"/>
  <g stroke="#FFFFFF" stroke-width="1.5" opacity="0.8">
    <path d="M14,26 L14,14 L26,14"/>
    <path d="M824,14 L836,14 L836,26"/>
    <path d="M14,794 L14,806 L26,806"/>
    <path d="M836,794 L836,806 L824,806"/>
  </g>

  <!-- ===== HEADER ===== -->
  <text x="30" y="34" class="h" font-size="18" font-weight="700" fill="#FFFFFF" filter="url(#glowSoft)">DEVOPS METRICS</text>
  <text x="30" y="52" class="h" font-size="11" fill="#8F8F8F">a running snapshot of what I'm building, learning, and shipping</text>
  <rect x="30" y="60" width="0" height="2" fill="#FFFFFF">
    <animate attributeName="width" from="0" to="160" dur="0.6s" begin="0.1s" fill="freeze"/>
  </rect>
  <line x1="30" y1="66" x2="820" y2="66" stroke="#161616" stroke-width="1"/>

  <!-- ===== HERO : DEPLOYMENT ACTIVITY (isometric) ===== -->
  <text x="30" y="96" class="h" font-size="13" font-weight="700" fill="#FFFFFF">DEPLOYMENT ACTIVITY</text>
  <text x="30" y="110" class="h" font-size="10" fill="#8F8F8F">pipeline runs, visualized</text>

  <g id="isometric">
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.00s" fill="freeze"/><polygon points="30,175 62,175 62,210 30,210" fill="#9E9E9E"/><polygon points="30,175 62,175 72,168 40,168" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="62,175 72,168 72,203 62,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.03s" fill="freeze"/><polygon points="84,158 116,158 116,210 84,210" fill="#9E9E9E"/><polygon points="84,158 116,158 126,151 94,151" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="116,158 126,151 126,203 116,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.06s" fill="freeze"/><polygon points="138,182 170,182 170,210 138,210" fill="#9E9E9E"/><polygon points="138,182 170,182 180,175 148,175" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="170,182 180,175 180,203 170,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.09s" fill="freeze"/><polygon points="192,150 224,150 224,210 192,210" fill="#9E9E9E"/><polygon points="192,150 224,150 234,143 202,143" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="224,150 234,143 234,203 224,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.12s" fill="freeze"/><polygon points="246,165 278,165 278,210 246,210" fill="#9E9E9E"/><polygon points="246,165 278,165 288,158 256,158" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="278,165 288,158 288,203 278,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.15s" fill="freeze"/><polygon points="300,138 332,138 332,210 300,210" fill="#9E9E9E"/><polygon points="300,138 332,138 342,131 310,131" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="332,138 342,131 342,203 332,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.18s" fill="freeze"/><polygon points="354,172 386,172 386,210 354,210" fill="#9E9E9E"/><polygon points="354,172 386,172 396,165 364,165" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="386,172 396,165 396,203 386,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.21s" fill="freeze"/><polygon points="408,145 440,145 440,210 408,210" fill="#9E9E9E"/><polygon points="408,145 440,145 450,138 418,138" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="440,145 450,138 450,203 440,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.24s" fill="freeze"/><polygon points="462,160 494,160 494,210 462,210" fill="#9E9E9E"/><polygon points="462,160 494,160 504,153 472,153" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="494,160 504,153 504,203 494,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.27s" fill="freeze"/><polygon points="516,130 548,130 548,210 516,210" fill="#9E9E9E"/><polygon points="516,130 548,130 558,123 526,123" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="548,130 558,123 558,203 548,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.30s" fill="freeze"/><polygon points="570,168 602,168 602,210 570,210" fill="#9E9E9E"/><polygon points="570,168 602,168 612,161 580,161" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="602,168 612,161 612,203 602,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.33s" fill="freeze"/><polygon points="624,152 656,152 656,210 624,210" fill="#9E9E9E"/><polygon points="624,152 656,152 666,145 634,145" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="656,152 666,145 666,203 656,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.36s" fill="freeze"/><polygon points="678,180 710,180 710,210 678,210" fill="#9E9E9E"/><polygon points="678,180 710,180 720,173 688,173" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="710,180 720,173 720,203 710,210" fill="#4A4A4A"/></g>
    <g opacity="0"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.39s" fill="freeze"/><polygon points="732,190 764,190 764,210 732,210" fill="#9E9E9E"/><polygon points="732,190 764,190 774,183 742,183" fill="#E8E8E8" filter="url(#glowSoft)"/><polygon points="764,190 774,183 774,203 764,210" fill="#4A4A4A"/></g>
  </g>

  <line x1="30" y1="236" x2="820" y2="236" stroke="#161616" stroke-width="1"/>

  <!-- ===== LEFT COLUMN ===== -->
  <g class="h" font-size="11.5" fill="#FFFFFF">
    <circle cx="33" cy="273" r="6" fill="none" stroke="#8F8F8F" stroke-width="1.3"/>
    <line x1="33" y1="273" x2="33" y2="269.5" stroke="#8F8F8F" stroke-width="1.3"/>
    <line x1="33" y1="273" x2="36" y2="275" stroke="#8F8F8F" stroke-width="1.3"/>
    <text x="48" y="278">Learning DevOps since 2024</text>

    <circle cx="30.5" cy="295" r="3.2" fill="none" stroke="#8F8F8F" stroke-width="1.3"/>
    <circle cx="36.5" cy="298" r="3.2" fill="none" stroke="#8F8F8F" stroke-width="1.3"/>
    <text x="48" y="300">Open-source &amp; self-directed projects</text>

    <rect x="27" y="316" width="11" height="9" rx="1.5" fill="none" stroke="#8F8F8F" stroke-width="1.3"/>
    <text x="48" y="322">7 core tools in the belt</text>

    <path d="M27,338 L32,333 L39,333 L39,340 L32,345 Z" fill="none" stroke="#8F8F8F" stroke-width="1.3" stroke-linejoin="round"/>
    <text x="48" y="344">CI/CD · IaC · Cloud focus</text>
  </g>

  <line x1="30" y1="362" x2="410" y2="362" stroke="#161616" stroke-width="1"/>

  <text x="30" y="386" class="h" font-size="12" font-weight="700" fill="#FFFFFF">WEEKLY BUILD RHYTHM</text>
  <text x="30" y="400" class="h" font-size="9.5" fill="#8F8F8F">relative focus time across the week</text>

  <g id="weekbars">
    <rect x="38" y="442" width="18" height="18" rx="2" fill="#E6E6E6" opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.4s" begin="0.10s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.4s" begin="0.10s" fill="freeze"/></rect>
    <rect x="90" y="405" width="18" height="55" rx="2" fill="#E6E6E6" opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.4s" begin="0.18s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.4s" begin="0.18s" fill="freeze"/></rect>
    <rect x="142" y="428" width="18" height="32" rx="2" fill="#E6E6E6" opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.4s" begin="0.26s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.4s" begin="0.26s" fill="freeze"/></rect>
    <rect x="194" y="412" width="18" height="48" rx="2" fill="#E6E6E6" opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.4s" begin="0.34s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.4s" begin="0.34s" fill="freeze"/></rect>
    <rect x="246" y="420" width="18" height="40" rx="2" fill="#E6E6E6" opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.4s" begin="0.42s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.4s" begin="0.42s" fill="freeze"/></rect>
    <rect x="298" y="400" width="18" height="60" rx="2" fill="#E6E6E6" opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.4s" begin="0.50s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.4s" begin="0.50s" fill="freeze"/></rect>
    <rect x="350" y="435" width="18" height="25" rx="2" fill="#E6E6E6" opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.4s" begin="0.58s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.4s" begin="0.58s" fill="freeze"/></rect>
  </g>
  <g class="h" font-size="9" fill="#8F8F8F" text-anchor="middle">
    <text x="47" y="474">SUN</text>
    <text x="99" y="474">MON</text>
    <text x="151" y="474">TUE</text>
    <text x="203" y="474">WED</text>
    <text x="255" y="474">THU</text>
    <text x="307" y="474">FRI</text>
    <text x="359" y="474">SAT</text>
  </g>

  <line x1="30" y1="496" x2="410" y2="496" stroke="#161616" stroke-width="1"/>

  <text x="30" y="520" class="h" font-size="12" font-weight="700" fill="#FFFFFF">TOOL FOCUS</text>
  <text x="30" y="534" class="h" font-size="9.5" fill="#8F8F8F">time invested by tool (self-rated)</text>

  <g class="h" font-size="10" fill="#8F8F8F">
    <text x="30" y="559">DOCKER</text>
    <rect x="130" y="550" width="230" height="7" rx="3.5" fill="#161616"/>
    <rect x="130" y="550" width="0" height="7" rx="3.5" fill="#E6E6E6"><animate attributeName="width" from="0" to="69" dur="0.7s" begin="0.3s" fill="freeze"/></rect>
    <text x="372" y="558" fill="#FFFFFF">30%</text>

    <text x="30" y="583">KUBERNETES</text>
    <rect x="130" y="574" width="230" height="7" rx="3.5" fill="#161616"/>
    <rect x="130" y="574" width="0" height="7" rx="3.5" fill="#FFFFFF"><animate attributeName="width" from="0" to="51" dur="0.7s" begin="0.38s" fill="freeze"/></rect>
    <text x="372" y="582" fill="#FFFFFF">22%</text>

    <text x="30" y="607">TERRAFORM</text>
    <rect x="130" y="598" width="230" height="7" rx="3.5" fill="#161616"/>
    <rect x="130" y="598" width="0" height="7" rx="3.5" fill="#CFCFCF"><animate attributeName="width" from="0" to="41" dur="0.7s" begin="0.46s" fill="freeze"/></rect>
    <text x="372" y="606" fill="#FFFFFF">18%</text>

    <text x="30" y="631">AWS</text>
    <rect x="130" y="622" width="230" height="7" rx="3.5" fill="#161616"/>
    <rect x="130" y="622" width="0" height="7" rx="3.5" fill="#B8B8B8"><animate attributeName="width" from="0" to="35" dur="0.7s" begin="0.54s" fill="freeze"/></rect>
    <text x="372" y="630" fill="#FFFFFF">15%</text>

    <text x="30" y="655">CI/CD</text>
    <rect x="130" y="646" width="230" height="7" rx="3.5" fill="#161616"/>
    <rect x="130" y="646" width="0" height="7" rx="3.5" fill="#9A9A9A"><animate attributeName="width" from="0" to="23" dur="0.7s" begin="0.62s" fill="freeze"/></rect>
    <text x="372" y="654" fill="#FFFFFF">10%</text>

    <text x="30" y="679">LINUX</text>
    <rect x="130" y="670" width="230" height="7" rx="3.5" fill="#161616"/>
    <rect x="130" y="670" width="0" height="7" rx="3.5" fill="#D9D9D9"><animate attributeName="width" from="0" to="11" dur="0.7s" begin="0.7s" fill="freeze"/></rect>
    <text x="372" y="678" fill="#FFFFFF">5%</text>
  </g>

  <text x="30" y="714" class="h" font-size="12" font-weight="700" fill="#FFFFFF">TOOLS &amp; TECHNOLOGIES</text>

  <g class="h" font-size="11" font-weight="700" text-anchor="middle">
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.75s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="0.75s" fill="freeze"/>
    <rect x="30" y="726" width="60" height="32" rx="6" fill="#FFFFFF"/>
    <text x="60" y="747" fill="#000000">DK</text></g>
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.81s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="0.81s" fill="freeze"/>
    <rect x="98" y="726" width="60" height="32" rx="6" fill="#000000" stroke="#3A3A3A"/>
    <text x="128" y="747" fill="#FFFFFF">K8</text></g>
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.87s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="0.87s" fill="freeze"/>
    <rect x="166" y="726" width="60" height="32" rx="6" fill="#FFFFFF"/>
    <text x="196" y="747" fill="#000000">TF</text></g>
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.93s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="0.93s" fill="freeze"/>
    <rect x="234" y="726" width="60" height="32" rx="6" fill="#000000" stroke="#3A3A3A"/>
    <text x="264" y="747" fill="#FFFFFF">AWS</text></g>
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.99s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="0.99s" fill="freeze"/>
    <rect x="302" y="726" width="58" height="32" rx="6" fill="#FFFFFF"/>
    <text x="331" y="747" fill="#000000">LX</text></g>

    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.05s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="1.05s" fill="freeze"/>
    <rect x="30" y="766" width="60" height="32" rx="6" fill="#000000" stroke="#3A3A3A"/>
    <text x="60" y="787" fill="#FFFFFF">GIT</text></g>
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.11s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="1.11s" fill="freeze"/>
    <rect x="98" y="766" width="60" height="32" rx="6" fill="#FFFFFF"/>
    <text x="128" y="787" fill="#000000">SH</text></g>
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.17s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="1.17s" fill="freeze"/>
    <rect x="166" y="766" width="60" height="32" rx="6" fill="#000000" stroke="#3A3A3A"/>
    <text x="196" y="787" fill="#FFFFFF">GHA</text></g>
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.23s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="1.23s" fill="freeze"/>
    <rect x="234" y="766" width="60" height="32" rx="6" fill="#FFFFFF"/>
    <text x="264" y="787" fill="#000000">PY</text></g>
    <g opacity="0" transform="translate(0,10)"><animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.29s" fill="freeze"/><animateTransform attributeName="transform" type="translate" from="0,10" to="0,0" dur="0.35s" begin="1.29s" fill="freeze"/>
    <rect x="302" y="766" width="58" height="32" rx="6" fill="#000000" stroke="#3A3A3A"/>
    <text x="331" y="787" fill="#FFFFFF">YML</text></g>
  </g>

  <!-- ===== RIGHT COLUMN ===== -->
  <text x="440" y="280" class="h" font-size="12" font-weight="700" fill="#FFFFFF">SKILL CONFIDENCE <tspan fill="#8F8F8F" font-weight="400" font-size="10">(self-rated)</tspan></text>

  <g class="h" text-anchor="middle">
    <circle cx="480" cy="340" r="34" fill="none" stroke="#161616" stroke-width="6"/>
    <circle cx="480" cy="340" r="42" fill="none" stroke="#FFFFFF" stroke-width="1" opacity="0">
      <animate attributeName="opacity" values="0;0.35;0" dur="2.2s" begin="1.3s" repeatCount="indefinite"/>
      <animate attributeName="r" values="36;46;36" dur="2.2s" begin="1.3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="480" cy="340" r="34" fill="none" stroke="#E6E6E6" stroke-width="6" stroke-linecap="round" filter="url(#glowSoft)"
            stroke-dasharray="192.3" stroke-dashoffset="192.3" transform="rotate(-90 480 340)">
      <animate attributeName="stroke-dashoffset" from="192.3" to="19.2" dur="1.1s" begin="0.1s" fill="freeze"/>
    </circle>
    <text x="480" y="346" font-size="16" font-weight="700" fill="#FFFFFF">90</text>
    <text x="480" y="392" font-size="9.5" font-weight="700" fill="#8F8F8F">DOCKER</text>

    <circle cx="570" cy="340" r="34" fill="none" stroke="#161616" stroke-width="6"/>
    <circle cx="570" cy="340" r="42" fill="none" stroke="#FFFFFF" stroke-width="1" opacity="0">
      <animate attributeName="opacity" values="0;0.35;0" dur="2.2s" begin="1.45s" repeatCount="indefinite"/>
      <animate attributeName="r" values="36;46;36" dur="2.2s" begin="1.45s" repeatCount="indefinite"/>
    </circle>
    <circle cx="570" cy="340" r="34" fill="none" stroke="#FFFFFF" stroke-width="6" stroke-linecap="round" filter="url(#glowSoft)"
            stroke-dasharray="192.3" stroke-dashoffset="192.3" transform="rotate(-90 570 340)">
      <animate attributeName="stroke-dashoffset" from="192.3" to="48.1" dur="1.1s" begin="0.25s" fill="freeze"/>
    </circle>
    <text x="570" y="346" font-size="16" font-weight="700" fill="#FFFFFF">75</text>
    <text x="570" y="392" font-size="9.5" font-weight="700" fill="#8F8F8F">KUBERNETES</text>

    <circle cx="660" cy="340" r="34" fill="none" stroke="#161616" stroke-width="6"/>
    <circle cx="660" cy="340" r="42" fill="none" stroke="#FFFFFF" stroke-width="1" opacity="0">
      <animate attributeName="opacity" values="0;0.35;0" dur="2.2s" begin="1.6s" repeatCount="indefinite"/>
      <animate attributeName="r" values="36;46;36" dur="2.2s" begin="1.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="660" cy="340" r="34" fill="none" stroke="#B8B8B8" stroke-width="6" stroke-linecap="round" filter="url(#glowSoft)"
            stroke-dasharray="192.3" stroke-dashoffset="192.3" transform="rotate(-90 660 340)">
      <animate attributeName="stroke-dashoffset" from="192.3" to="57.7" dur="1.1s" begin="0.4s" fill="freeze"/>
    </circle>
    <text x="660" y="346" font-size="16" font-weight="700" fill="#FFFFFF">70</text>
    <text x="660" y="392" font-size="9.5" font-weight="700" fill="#8F8F8F">AWS</text>

    <circle cx="750" cy="340" r="34" fill="none" stroke="#161616" stroke-width="6"/>
    <circle cx="750" cy="340" r="42" fill="none" stroke="#FFFFFF" stroke-width="1" opacity="0">
      <animate attributeName="opacity" values="0;0.35;0" dur="2.2s" begin="1.75s" repeatCount="indefinite"/>
      <animate attributeName="r" values="36;46;36" dur="2.2s" begin="1.75s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="340" r="34" fill="none" stroke="#CFCFCF" stroke-width="6" stroke-linecap="round" filter="url(#glowSoft)"
            stroke-dasharray="192.3" stroke-dashoffset="192.3" transform="rotate(-90 750 340)">
      <animate attributeName="stroke-dashoffset" from="192.3" to="28.8" dur="1.1s" begin="0.55s" fill="freeze"/>
    </circle>
    <text x="750" y="346" font-size="16" font-weight="700" fill="#FFFFFF">85</text>
    <text x="750" y="392" font-size="9.5" font-weight="700" fill="#8F8F8F">LINUX</text>
  </g>

  <line x1="440" y1="414" x2="820" y2="414" stroke="#161616" stroke-width="1"/>

  <text x="440" y="438" class="h" font-size="12" font-weight="700" fill="#FFFFFF">CONSISTENCY</text>
  <circle cx="525" cy="434" r="3" fill="#E6E6E6">
    <animate attributeName="opacity" values="1;0.3;1" dur="1.6s" repeatCount="indefinite"/>
  </circle>
  <text x="440" y="452" class="h" font-size="9.5" fill="#8F8F8F">practicing a little, every day</text>

  <g id="heatmap">
    <!-- twinkle accents -->
    <rect x="521" y="473" width="7" height="7" rx="1.3" fill="#FFFFFF">
      <animate attributeName="opacity" values="1;0.25;1" dur="1.8s" begin="0s" repeatCount="indefinite"/>
    </rect>
    <rect x="593" y="482" width="7" height="7" rx="1.3" fill="#FFFFFF">
      <animate attributeName="opacity" values="1;0.25;1" dur="1.8s" begin="0.6s" repeatCount="indefinite"/>
    </rect>
    <rect x="557" y="491" width="7" height="7" rx="1.3" fill="#FFFFFF">
      <animate attributeName="opacity" values="1;0.25;1" dur="1.8s" begin="1.2s" repeatCount="indefinite"/>
    </rect>
    <rect x="440" y="464" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="449" y="464" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="458" y="464" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="467" y="464" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="476" y="464" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="485" y="464" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="494" y="464" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="503" y="464" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="512" y="464" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="521" y="464" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="530" y="464" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="539" y="464" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="548" y="464" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="557" y="464" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="566" y="464" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="575" y="464" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="584" y="464" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="593" y="464" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="602" y="464" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="611" y="464" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="440" y="473" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="449" y="473" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="458" y="473" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="467" y="473" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="476" y="473" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="485" y="473" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="494" y="473" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="503" y="473" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="512" y="473" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="521" y="473" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="530" y="473" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="539" y="473" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="548" y="473" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="557" y="473" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="566" y="473" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="575" y="473" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="584" y="473" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="593" y="473" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="602" y="473" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="611" y="473" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="440" y="482" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="449" y="482" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="458" y="482" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="467" y="482" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="476" y="482" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="485" y="482" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="494" y="482" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="503" y="482" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="512" y="482" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="521" y="482" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="530" y="482" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="539" y="482" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="548" y="482" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="557" y="482" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="566" y="482" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="575" y="482" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="584" y="482" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="593" y="482" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="602" y="482" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="611" y="482" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="440" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="449" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="458" y="491" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="467" y="491" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="476" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="485" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="494" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="503" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="512" y="491" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="521" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="530" y="491" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="539" y="491" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="548" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="557" y="491" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="566" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="575" y="491" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="584" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="593" y="491" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="602" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="611" y="491" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="440" y="500" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="449" y="500" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="458" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="467" y="500" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="476" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="485" y="500" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="494" y="500" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="503" y="500" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="512" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="521" y="500" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="530" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="539" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="548" y="500" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="557" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="566" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="575" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="584" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="593" y="500" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="602" y="500" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="611" y="500" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="440" y="509" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="449" y="509" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="458" y="509" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="467" y="509" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="476" y="509" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="485" y="509" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="494" y="509" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="503" y="509" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="512" y="509" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="521" y="509" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="530" y="509" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="539" y="509" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="548" y="509" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="557" y="509" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="566" y="509" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="575" y="509" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="584" y="509" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="593" y="509" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="602" y="509" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="611" y="509" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="440" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="449" y="518" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="458" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="467" y="518" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="476" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="485" y="518" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="494" y="518" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="503" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="512" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="521" y="518" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="530" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="539" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="548" y="518" width="7" height="7" rx="1.3" fill="#232323"/>
    <rect x="557" y="518" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="566" y="518" width="7" height="7" rx="1.3" fill="#9E9E9E"/>
    <rect x="575" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="584" y="518" width="7" height="7" rx="1.3" fill="#E8E8E8" filter="url(#glowSoft)"/>
    <rect x="593" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="602" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
    <rect x="611" y="518" width="7" height="7" rx="1.3" fill="#0A0A0A"/>
  </g>

  <line x1="440" y1="549" x2="820" y2="549" stroke="#161616" stroke-width="1"/>

  <text x="440" y="573" class="h" font-size="12" font-weight="700" fill="#FFFFFF">CURRENTLY EXPLORING</text>

  <g class="h">
    <rect x="440" y="584" width="26" height="26" rx="5" fill="#161616" stroke="#3A3A3A"/>
    <text x="453" y="601" text-anchor="middle" font-size="12" fill="#B8B8B8">$</text>
    <text x="476" y="596" font-size="11.5" font-weight="600" fill="#FFFFFF">Cloud cost optimization</text>
    <text x="476" y="609" font-size="9.5" fill="#8F8F8F">AWS Cost Explorer &amp; budgets</text>

    <rect x="440" y="618" width="26" height="26" rx="5" fill="#161616" stroke="#3A3A3A"/>
    <text x="453" y="635" text-anchor="middle" font-size="12" fill="#FFFFFF">◎</text>
    <text x="476" y="630" font-size="11.5" font-weight="600" fill="#FFFFFF">Observability &amp; monitoring</text>
    <text x="476" y="643" font-size="9.5" fill="#8F8F8F">Grafana &amp; Prometheus basics</text>
  </g>

  <line x1="440" y1="662" x2="820" y2="662" stroke="#161616" stroke-width="1"/>

  <text x="440" y="686" class="h" font-size="12" font-weight="700" fill="#FFFFFF">SELECTED BUILDS</text>

  <g class="h" font-size="10.5" fill="#FFFFFF">
    <text x="440" y="707">Automated CI/CD Pipeline</text>
    <rect x="440" y="714" width="300" height="6" rx="3" fill="#161616"/>
    <rect x="440" y="714" width="0" height="6" rx="3" fill="#E6E6E6"><animate attributeName="width" from="0" to="300" dur="0.8s" begin="0.5s" fill="freeze"/></rect>

    <text x="440" y="738">Cloud Infra with Terraform</text>
    <rect x="440" y="745" width="300" height="6" rx="3" fill="#161616"/>
    <rect x="440" y="745" width="0" height="6" rx="3" fill="#E6E6E6"><animate attributeName="width" from="0" to="270" dur="0.8s" begin="0.6s" fill="freeze"/></rect>
  </g>

  <!-- slow resting light sweep — one gentle pass every ~7s, mostly at rest -->
  <rect x="-260" y="0" width="260" height="820" fill="url(#sheenGrad)" pointer-events="none">
    <animate attributeName="x" values="-260;850;850" keyTimes="0;0.3;1" dur="7s" begin="2s" repeatCount="indefinite"/>
  </rect>
</svg>




<!--
**abdullahthehakim/abdullahthehakim** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
