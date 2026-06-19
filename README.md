# Flappy Bird

A classic Flappy Bird clone built with a single HTML file — pure HTML, CSS, and vanilla JavaScript. No external dependencies required.

## Play

Open `index.html` in any modern browser, or visit the [GitHub Pages](#deployment) link (if enabled).

## Features

- **One-file game** — everything (HTML + CSS + JS) lives in a single `index.html`
- **Faithful gameplay** — gravity, jump physics, random pipe generation, collision detection, and scrolling ground
- **Original visual style** — sky gradient, clouds, yellow bird with wing flap animation, classic green pipes with caps, scrolling ground with grass
- **Score tracking** — live score display + best score saved in `localStorage`
- **Bilingual UI** — toggle between English and Chinese at any time via the button in the top-right corner; language preference is persisted
- **Responsive** — canvas scales to fit the viewport on desktop and mobile
- **Game over overlay** — shows your score and best score with a one-click restart

## Controls

| Action | Input |
|--------|-------|
| Jump | Click / Tap the screen **or** press `Space` |
| Switch language | Click the button in the top-right corner |

## Getting Started

### Option 1 — Direct open

```bash
# Clone the repository
git clone https://github.com/vajvip/Flappy-Bird.git
cd Flappy-Bird

# Open in browser
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

### Option 2 — Local server (recommended)

```bash
# Python 3
python -m http.server 8000

# Node.js (if you have npx)
npx serve .
```

Then visit `http://localhost:8000` in your browser.

## Deployment

This project can be deployed for free with GitHub Pages:

1. Go to **Settings → Pages** in your repository
2. Under **Source**, select the `main` branch and `/ (root)` folder
3. Save — your game will be live at `https://vajvip.github.io/Flappy-Bird/`

## Project Structure

```
Flappy-Bird/
├── index.html   # The complete game (HTML + CSS + JS)
└── README.md
```

## Browser Support

Works in all modern browsers:

- Chrome / Edge
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome for Android)

## License

This project is intended for learning and fun. Flappy Bird is originally created by Dong Nguyen.
