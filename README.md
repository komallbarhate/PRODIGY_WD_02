# Stopwatch Web App

A clean, minimal stopwatch web application built with HTML, CSS, and JavaScript — no frameworks, no dependencies.

## Live Demo

[View Live →](https://komallbarhate.github.io/PRODIGY_WD_02/)

---

## Features

- **Start / Pause / Resume** — seamless timer control with a single button
- **Lap tracking** — record split times and overall elapsed time per lap
- **Best & slowest lap** — automatically highlights your fastest and slowest laps
- **Animated progress ring** — visual sweep around the clock face every 60 seconds
- **Dark mode support** — automatically adapts to your system preference
- **Zero dependencies** — pure HTML, CSS, and JavaScript in a single file

---

## Screenshots

| Running | Laps Recorded |
|--------|---------------|
| Timer running with animated ring | Lap table with best/slow highlights |
<img width="563" height="507" alt="task 2 " src="https://github.com/user-attachments/assets/a8237dff-508e-446d-9c76-1eeed76b8ea8" />
<img width="793" height="612" alt="task 2 1" src="https://github.com/user-attachments/assets/b41cdca5-fedf-4f3b-8040-1dd3721bc18e" />


---

## Getting Started

### Option 1 — Open directly in browser

1. Download `index.html`
2. Double-click to open in any browser

### Option 2 — Clone the repository

```bash
git clone https://github.com/komallbarhatee/stopwatch-app.git
cd stopwatch-app
open index.html
```

---

## How to Use

| Action | How |
|--------|-----|
| Start the timer | Click the centre button |
| Pause | Click the centre button again |
| Record a lap | Click the **Lap** button while running |
| Reset everything | Click the **Reset** button |

Lap times are listed newest-first. Once you have two or more laps, the fastest split is highlighted in green and the slowest in red.

---

## Project Structure

```
stopwatch-app/
└── index.html      # Complete app — HTML, CSS, and JS in one file
└── README.md       # This file
```

---

## Built With

- **HTML5** — structure and semantics
- **CSS3** — styling, animations, and dark mode via `prefers-color-scheme`
- **Vanilla JavaScript** — timer logic using `requestAnimationFrame` for smooth updates
- **SVG** — animated circular progress ring

---

## Browser Support

Works in all modern browsers — Chrome, Firefox, Safari, and Edge.

---

## License

This project is open source and available under the [MIT License](LICENSE).

