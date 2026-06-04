<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 300" width="100%" height="100%">
  <defs>
    <linearGradient id="groundGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#21262d" stop-opacity="0" />
      <stop offset="50%" stop-color="#30363d" stop-opacity="1" />
      <stop offset="100%" stop-color="#21262d" stop-opacity="0" />
    </linearGradient>
  </defs>

  <style>
    :root {
      --loop-duration: 4s;
    }
    
    /* Overall running animation for both groups */
    .runner-group {
      animation: runLoop var(--loop-duration) infinite linear;
    }
    
    /* Bobbing motion to simulate running */
    .bob {
      animation: runBob 0.3s infinite ease-in-out alternate;
    }

    /* Leg animations for both mechanical entities */
    .leg {
      transform-origin: top center;
      animation: legSwing 0.3s infinite ease-in-out alternate;
    }

    /* Keyframes */
    @keyframes runLoop {
      0% { transform: translateX(-200px); }
      100% { transform: translateX(1200px); }
    }
    @keyframes runBob {
      0% { transform: translateY(0px); }
      100% { transform: translateY(-15px); }
    }
    @keyframes legSwing {
      0% { transform: rotate(-15deg); }
      100% { transform: rotate(15deg); }
    }
  </style>

  <line x1="0" y1="250" x2="1000" y2="250" stroke="url(#groundGrad)" stroke-width="3" stroke-dasharray="8 8" />

  <g class="runner-group" style="animation-delay: -0.2s;">
    <g class="bob" style="animation-delay: -0.1s;">
      <g class="leg" transform="translate(140, 205)">
        <ellipse cx="0" cy="20" rx="10" ry="30" fill="#e48113" />
      </g>
      <g class="leg" transform="translate(180, 205)" style="animation-delay: 0.15s;">
        <ellipse cx="0" cy="20" rx="10" ry="30" fill="#e48113" />
      </g>
      <ellipse cx="160" cy="180" rx="40" ry="30" fill="#ff9e2c" />
      <circle cx="160" cy="180" r="15" fill="#30363d" />
      <circle cx="160" cy="180" r="10" fill="#21262d" />
      <path d="M150,170 Q160,180 170,170" fill="none" stroke="#6e7681" stroke-width="2" />
      <ellipse cx="210" cy="150" rx="20" ry="18" fill="#ff9e2c" />
      <path d="M210,135 Q220,120 230,135" fill="none" stroke="#21262d" stroke-width="3" /> <circle cx="215" cy="150" r="6" fill="#30363d" /> <circle cx="215" cy="150" r="2" fill="#58a6ff" /> </g>
  </g>

  <g class="runner-group" style="animation-delay: 0.2s;">
    <g class="bob" style="animation-delay: 0.1s;">
      <g class="leg" transform="translate(420, 180)">
        <ellipse cx="0" cy="20" rx="10" ry="35" fill="#8b949e" />
      </g>
      <g class="leg" transform="translate(460, 180)" style="animation-delay: 0.15s;">
        <ellipse cx="0" cy="20" rx="10" ry="35" fill="#8b949e" />
      </g>
      <ellipse cx="440" cy="130" rx="45" ry="35" fill="#6e7681" />
      <ellipse cx="495" cy="130" rx="10" ry="25" fill="#8b949e" />
      <ellipse cx="440" cy="130" rx="35" ry="25" fill="#30363d" />
      <path d="M420,110 Q440,120 460,110" fill="none" stroke="#6e7681" stroke-width="2" />
      <path d="M420,150 Q440,140 460,150" fill="none" stroke="#6e7681" stroke-width="2" />
      <ellipse cx="440" cy="80" rx="18" ry="22" fill="#6e7681" />
      <circle cx="440" cy="80" r="10" fill="#30363d" /> <circle cx="440" cy="80" r="4" fill="#58a6ff" /> <line x1="440" y1="58" x2="440" y2="40" stroke="#8b949e" stroke-width="3" /> </g>
  </g>
</svg>
