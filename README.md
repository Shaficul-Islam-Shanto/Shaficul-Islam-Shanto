<svg width="1200" height="400" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Main gradient background -->
    <linearGradient id="mainGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1e3a8a"/>
      <stop offset="50%" style="stop-color:#3b82f6"/>
      <stop offset="100%" style="stop-color:#06b6d4"/>
    </linearGradient>
<!-- Grid pattern -->
<pattern id="grid" width="20" height="20" patternUnits="userSpaceOnUse">
  <path d="M 20 0 L 0 0 0 20" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="0.5"/>
</pattern>

<!-- Glassmorphism filter -->
<filter id="blur">
  <feGaussianBlur stdDeviation="3"/>
</filter>
  </defs>
  <!-- Background -->
  <rect width="1200" height="400" rx="16" fill="url(#mainGradient)"/>
  <!-- Grid overlay -->
  <rect width="1200" height="400" rx="16" fill="url(#grid)" opacity="0.3"/>
  <!-- Floating shapes -->
  <rect x="1050" y="60" width="60" height="60" rx="12" fill="rgba(255,255,255,0.1)">
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-20; 0,0" dur="6s" repeatCount="indefinite"/>
  </rect>
  <circle cx="1080" cy="250" r="20" fill="rgba(255,255,255,0.1)">
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-15; 0,0" dur="8s" repeatCount="indefinite"/>
  </circle>
  <polygon points="950,80 970,110 930,110" fill="rgba(255,255,255,0.1)">
    <animateTransform attributeName="transform" type="translate" values="0,0; 0,-25; 0,0" dur="7s" repeatCount="indefinite"/>
  </polygon>
  <!-- Main content -->
  <!-- Greeting text -->
<text x="60" y="120" font-family="Arial, sans-serif" font-size="24" font-weight="300" fill="rgba(255,255,255,0.9)">Hi there, I'm</text>
  <!-- Name -->
<text x="60" y="170" font-family="Arial, sans-serif" font-size="48" font-weight="700" fill="white">Shaficul Islam Shanto</text>
  <!-- Title -->
<text x="60" y="210" font-family="Arial, sans-serif" font-size="28" font-weight="400" fill="rgba(255,255,255,0.95)">Full Stack Developer</text>
  <!-- Skill tags background -->
  <rect x="60" y="240" width="120" height="32" rx="16" fill="rgba(255,255,255,0.15)" stroke="rgba(255,255,255,0.2)"/>
  <rect x="190" y="240" width="80" height="32" rx="16" fill="rgba(255,255,255,0.15)" stroke="rgba(255,255,255,0.2)"/>
  <rect x="280" y="240" width="110" height="32" rx="16" fill="rgba(255,255,255,0.15)" stroke="rgba(255,255,255,0.2)"/>
  <rect x="400" y="240" width="130" height="32" rx="16" fill="rgba(255,255,255,0.15)" stroke="rgba(255,255,255,0.2)"/>
  <rect x="60" y="280" width="90" height="32" rx="16" fill="rgba(255,255,255,0.15)" stroke="rgba(255,255,255,0.2)"/>
  <rect x="160" y="280" width="110" height="32" rx="16" fill="rgba(255,255,255,0.15)" stroke="rgba(255,255,255,0.2)"/>
  <rect x="280" y="280" width="100" height="32" rx="16" fill="rgba(255,255,255,0.15)" stroke="rgba(255,255,255,0.2)"/>
  <!-- Skill tags text -->
<text x="120" y="260" font-family="Arial, sans-serif" font-size="14" font-weight="500" fill="white" text-anchor="middle">HTML</text>
<text x="230" y="260" font-family="Arial, sans-serif" font-size="14" font-weight="500" fill="white" text-anchor="middle">CSS</text>
<text x="335" y="260" font-family="Arial, sans-serif" font-size="14" font-weight="500" fill="white" text-anchor="middle">JavaScript</text>
<text x="465" y="260" font-family="Arial, sans-serif" font-size="14" font-weight="500" fill="white" text-anchor="middle">Tailwind CSS</text>
<text x="105" y="300" font-family="Arial, sans-serif" font-size="14" font-weight="500" fill="white" text-anchor="middle">Node.js</text>
<text x="215" y="300" font-family="Arial, sans-serif" font-size="14" font-weight="500" fill="white" text-anchor="middle">Express.js</text>
<text x="330" y="300" font-family="Arial, sans-serif" font-size="14" font-weight="500" fill="white" text-anchor="middle">MongoDB</text>
  <!-- Code box background -->
  <rect x="700" y="80" width="320" height="160" rx="12" fill="rgba(0,0,0,0.3)" stroke="rgba(255,255,255,0.1)"/>
  <!-- Code text -->
<text x="720" y="110" font-family="Monaco, monospace" font-size="14" fill="#ff79c6">const</text>
<text x="770" y="110" font-family="Monaco, monospace" font-size="14" fill="#8be9fd">developer</text>
<text x="850" y="110" font-family="Monaco, monospace" font-size="14" fill="white">= {</text>
<text x="720" y="130" font-family="Monaco, monospace" font-size="14" fill="white">  name:</text>
<text x="780" y="130" font-family="Monaco, monospace" font-size="14" fill="#50fa7b">"Shaficul Islam Shanto"</text>
<text x="980" y="130" font-family="Monaco, monospace" font-size="14" fill="white">,</text>
<text x="720" y="150" font-family="Monaco, monospace" font-size="14" fill="white">  passion:</text>
<text x="790" y="150" font-family="Monaco, monospace" font-size="14" fill="#50fa7b">"Coding"</text>
<text x="850" y="150" font-family="Monaco, monospace" font-size="14" fill="white">,</text>
<text x="720" y="170" font-family="Monaco, monospace" font-size="14" fill="white">  skills: [</text>
<text x="790" y="170" font-family="Monaco, monospace" font-size="14" fill="#50fa7b">"MERN Stack"</text>
<text x="880" y="170" font-family="Monaco, monospace" font-size="14" fill="white">,</text>
<text x="900" y="170" font-family="Monaco, monospace" font-size="14" fill="#50fa7b">"Web Dev"</text>
<text x="970" y="170" font-family="Monaco, monospace" font-size="14" fill="white">],</text>
<text x="720" y="190" font-family="Monaco, monospace" font-size="14" fill="#6272a4">  // Always learning...</text>
<text x="720" y="210" font-family="Monaco, monospace" font-size="14" fill="white">};</text>
</svg>
