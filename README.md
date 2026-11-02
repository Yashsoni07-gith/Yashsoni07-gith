<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="260" viewBox="0 0 1200 260">
  <defs>
    <pattern id="dots" width="8" height="8" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1" fill="#8b949e"/>
      <circle cx="6" cy="6" r="0.7" fill="#6e7681"/>
    </pattern>
    <pattern id="dotsFine" width="5" height="5" patternUnits="userSpaceOnUse">
      <circle cx="1.5" cy="1.5" r="0.6" fill="#484f58"/>
    </pattern>
    <linearGradient id="fade" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#0d1117" stop-opacity="1"/>
      <stop offset="35%" stop-color="#0d1117" stop-opacity="0"/>
      <stop offset="65%" stop-color="#0d1117" stop-opacity="0"/>
      <stop offset="100%" stop-color="#0d1117" stop-opacity="1"/>
    </linearGradient>
  </defs>

  <rect width="1200" height="260" fill="#0d1117"/>
  <rect width="1200" height="260" fill="url(#dotsFine)" opacity="0.6"/>
  <rect x="0" y="0" width="1200" height="260" fill="url(#dots)" opacity="0.55"/>

  <rect x="300" y="40" width="600" height="180" fill="none" stroke="#8b949e" stroke-width="0.8" opacity="0.5"/>
  <line x1="300" y1="40" x2="900" y2="40" stroke="#8b949e" stroke-width="0.8" opacity="0.4"/>

  <rect width="1200" height="260" fill="url(#fade)"/>
</svg>
