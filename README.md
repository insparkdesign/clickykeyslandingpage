# ⌨ ClickyKeys — Landing Page

> Press a key. Feel the click.

A dark, terminal-aesthetic landing page for **ClickyKeys** — an open-source keyboard playground that recreates the satisfying joy of mechanical keyboards in the browser.

![ClickyKeys Landing Page](https://clickykeys.space/)

---

## What is this?

This is the **marketing / landing page** for [clickykeys.space](https://clickykeys.space). It's a single `index.html` file — no build tools, no dependencies, no framework. Just HTML, CSS, and vanilla JavaScript.

The page showcases the ClickyKeys keyboard playground with:

- An interactive demo keyboard (click or type on your real keyboard)
- Auto-playing demo that types on its own to show off the feel
- Sound synthesis — each key plays a real click sound via the Web Audio API
- Konami code easter egg (`↑↑↓↓←→←→BA` for rainbow mode)
- Live stats section with animated counters
- Floating, lightning-flashing keycaps
- Scanline + film grain overlay for that retro terminal vibe

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Full-screen keyboard with animated headline and CTA |
| **Why** | 3-card grid explaining why people love clicky keyboards |
| **Playground** | Auto-demo keyboard with terminal output + CTA popup |
| **Facts** | Keyboard nerd science (Cherry MX switches, actuation, etc.) |
| **Stats** | Animated counters — keys pressed, fastest typer, most-smashed key |
| **CTA** | Final call-to-action with floating keycap background |

---

## Tech stack

- **HTML5** — single file, zero dependencies
- **CSS3** — custom properties, grid, keyframe animations, glassmorphism
- **Vanilla JavaScript** — Web Audio API for click sounds, IntersectionObserver for scroll reveals
- **Google Fonts** — JetBrains Mono + Inter

---

## Features

### Sound Engine
Every key press generates a synthesized mechanical click using the Web Audio API — no audio files required. Enter and Space keys have a deeper "thock" tone.

### Auto Demo
The playground section auto-types phrases to show the keyboard in action. It pauses when you interact manually and resumes after 3 seconds.

### Rainbow Mode
Type the Konami code (`↑↑↓↓←→←→BA`) on your keyboard to activate rainbow cycling on all keycaps.

### Lightning Flash
Floating keycaps in the CTA section randomly flash green for ~160ms, simulating a typing burst effect.

---

## Getting started

No build step needed.

```bash
git clone https://github.com/insparkdesign/clicky-keys-landing
cd clicky-keys-landing
open index.html
```

Or just drag `index.html` into any browser.

---

## Related

- **ClickyKeys App** — [`../clicky keys/index.html`](../clicky%20keys/index.html) — the actual keyboard playground
- **Live site** — [clickykeys.space](https://clickykeys.space)

---

## Credits

Built by [Vinay Juneja](https://x.com/vinayjunejaa) · [@vinayjunejaa](https://x.com/vinayjunejaa)

Made with love for keyboard nerds. No keyboards were harmed.

---

## License

MIT — use it, fork it, remix it.
