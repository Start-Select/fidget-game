# Fidget Zone

A mindless browser-based fidget toy with satisfying animations and an escalating score system. No installs, no build step — just open `index.html`.

**[Play it →](https://start-select.github.io/fidget-game/)**

## How to play

- **Tap the orb** to score points
- **Pop the floating bubbles** drifting across the screen before they disappear
- Build a **combo** by tapping rapidly — the orb heats from purple to red as your combo climbs
- Reach **combo x25, x50, x100** for a screen shake
- Level up through 12 tiers: Rookie → Cosmic

## Features

- Floating tap targets that spawn, drift, and expire
- Orb colour and pulse speed react to combo (1–100)
- Aurora background speeds up and hue-shifts with your level
- Mixed particle shapes (circles, diamonds, stars) on every burst
- Web Audio tones and level-up fanfare
- Fully playable on mobile — no scroll, instant tap response

## Development

Single self-contained HTML file (`index.html`) — no dependencies, no build tooling.

```bash
# Serve locally
python3 -m http.server 8080
# then open http://localhost:8080
```

Branches:
- `main` — production, auto-deploys to GitHub Pages
- `develop` — active development

## License

MIT
