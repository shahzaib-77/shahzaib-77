<svg width="100%" viewBox="0 0 1200 500" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#070b16"/>
      <stop offset="100%" stop-color="#10182d"/>
    </linearGradient>

    <linearGradient id="line" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#247bff"/>
      <stop offset="100%" stop-color="#ff354f"/>
    </linearGradient>

    <pattern id="dots" width="24" height="24" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1" fill="#ffffff" opacity=".12"/>
    </pattern>

    <filter id="glow">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="1200" height="500" rx="30" fill="url(#bg)"/>
  <rect width="1200" height="500" rx="30" fill="url(#dots)"/>

  <!-- Gradient border -->
  <rect
    x="2"
    y="2"
    width="1196"
    height="496"
    rx="28"
    fill="none"
    stroke="url(#line)"
    stroke-width="2"
  />

  <!-- Blue glow -->
  <circle cx="100" cy="80" r="90" fill="#247bff" opacity=".15" filter="url(#glow)">
    <animate
      attributeName="opacity"
      values=".08;.20;.08"
      dur="4s"
      repeatCount="indefinite"
    />
  </circle>

  <!-- Crimson glow -->
  <circle cx="1100" cy="420" r="110" fill="#ff354f" opacity=".12" filter="url(#glow)">
    <animate
      attributeName="opacity"
      values=".06;.18;.06"
      dur="5s"
      repeatCount="indefinite"
    />
  </circle>

  <!-- Small label -->
  <text
    x="80"
    y="95"
    fill="#247bff"
    font-family="monospace"
    font-size="18"
    font-weight="700"
    letter-spacing="4"
  >
    GITHUB PROFILE
  </text>

  <!-- Main heading -->
  <text
    x="80"
    y="190"
    fill="#f5f7fb"
    font-family="Arial, sans-serif"
    font-size="72"
    font-weight="800"
  >
    HELLO,
  </text>

  <text
    x="80"
    y="270"
    fill="#f5f7fb"
    font-family="Arial, sans-serif"
    font-size="72"
    font-weight="800"
  >
    I'M SHAHZAIB
  </text>

  <!-- Accent line -->
  <rect x="82" y="300" width="300" height="5" rx="3" fill="url(#line)">
    <animate
      attributeName="width"
      values="80;300;80"
      dur="3s"
      repeatCount="indefinite"
    />
  </rect>

  <!-- Role -->
  <text
    x="80"
    y="350"
    fill="#ffffff"
    opacity=".85"
    font-family="monospace"
    font-size="22"
  >
    Flutter Developer  •  GenAI Engineer
  </text>

  <!-- Location -->
  <text
    x="80"
    y="395"
    fill="#ffffff"
    opacity=".55"
    font-family="monospace"
    font-size="17"
  >
    Islamabad, Pakistan
  </text>

  <!-- Right decorative card -->
  <rect
    x="820"
    y="105"
    width="270"
    height="270"
    rx="30"
    fill="#0d1426"
    stroke="#247bff"
    stroke-opacity=".45"
  />

  <circle
    cx="955"
    cy="205"
    r="65"
    fill="none"
    stroke="#247bff"
    stroke-width="3"
    opacity=".7"
  >
    <animate
      attributeName="r"
      values="55;75;55"
      dur="3s"
      repeatCount="indefinite"
    />
  </circle>

  <text
    x="955"
    y="215"
    text-anchor="middle"
    fill="#ffffff"
    font-family="monospace"
    font-size="42"
    font-weight="700"
  >
    SW
  </text>

  <text
    x="955"
    y="320"
    text-anchor="middle"
    fill="#ff354f"
    font-family="monospace"
    font-size="16"
    font-weight="700"
    letter-spacing="3"
  >
    BUILD • CREATE • SHIP
  </text>
</svg>
