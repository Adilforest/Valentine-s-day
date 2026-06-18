# Valentine's Day Card

An interactive single-page Valentine's Day card built with pure HTML, CSS, and JavaScript — no dependencies, no build step.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Overview

A playful "Will you be my Valentine?" interaction. When the visitor clicks **No**, the button runs away and the Yes button grows larger after each dodge. After four dodges the No button disappears and a fullscreen celebration state kicks in — animated heart confetti, a cupid SVG, a soft audio arpeggio via the Web Audio API, and background music.

Everything lives in a single `index.html` file with inline CSS and JavaScript.

## Features

- "No" button dodges mouse/touch — repositions randomly while avoiding overlap with the "Yes" button
- "Yes" button scales up with each dodge attempt
- On the 4th dodge: No disappears, card goes fullscreen, hearts rain down
- Confetti hearts built with CSS `clip-path` shapes and keyframe animations
- Soft romantic arpeggio generated with the Web Audio API (no audio library needed)
- Background MP3 track plays on confirmation
- Works on mobile (viewport-aware positioning via `visualViewport`)

## Tech Stack

- HTML5 / CSS3 / Vanilla JavaScript
- Web Audio API (`OscillatorNode`, `GainNode`)
- No external libraries or build tools

## Getting Started

```bash
# Clone and open directly in a browser
git clone https://github.com/Adilforest/Valentine-s-day.git
cd Valentine-s-day
open index.html   # macOS
# or just double-click index.html in your file manager
```

No server required — it is a static file.

---

Adil Ormanov — [GitHub](https://github.com/Adilforest)
