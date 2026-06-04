# VANTA — Rapper & Lyricist Website (Demo)

[![Live site](https://img.shields.io/badge/Live%20demo-subchibeats.github.io-FF4438?style=flat-square)](https://subchibeats.github.io/vanta-artist-website/)
[![Made with](https://img.shields.io/badge/Built%20with-HTML%20%C2%B7%20CSS%20%C2%B7%20JS-111?style=flat-square)](#tech-stack)
[![No build step](https://img.shields.io/badge/Dependencies-0-2ea44f?style=flat-square)](#tech-stack)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

> **▶ Live demo: https://subchibeats.github.io/vanta-artist-website/**
> &nbsp;·&nbsp; also at https://vantamusic.netlify.app/

A five-page demo artist website for **Vanta**, a fictional rapper and lyricist
who "builds every track bars-first — no filler, no wasted space." It's a
styling/branding demo built on a shared, dependency-free template and themed with
a high-energy red accent over a near-black, cinematic base.

Every page is a single self-contained `.html` file with all CSS and JavaScript
inlined — no build step, no framework, no dependencies. Open a file directly,
host it on any static CDN, or view it on a phone; it behaves identically.

---

## Demo / Screenshots

**▶ Live demo:** https://subchibeats.github.io/vanta-artist-website/

> Open the live demo above for the full experience — animated hero, marquees,
> and the audio-reactive visualiser. _Screenshots: see `docs/`._

---

## Tech stack

| Area | Details |
|------|---------|
| Markup / styling | Hand-written **HTML5** + **CSS3** — CSS custom properties, fluid `clamp()` type, grid/flex, `backdrop-filter`, blend modes |
| Theme | Monochrome near-black base (`#0B0B0C`) with a **red accent** (`#FF4438`) |
| Scripting | **Vanilla JavaScript** (ES6+), no frameworks or libraries |
| Audio | **Web Audio API** for the audio-reactive hero visualiser |
| Typography | **Google Fonts** — Anton (display), Archivo (body), Space Mono (mono) |
| Media | **SoundCloud** embedded players |
| Assets | Logo / favicon embedded as inline base64 PNGs — no external image requests |
| Tooling | **None.** Fully static, zero build step |

---

## Features

- **Five pages** — Home, Music, About, Bookings, EPK — each fully self-contained.
- **Audio-reactive hero** powered by the Web Audio API.
- **Counting preloader**, **custom cursor** (pointer-fine devices), and a
  full-screen animated **mobile menu**.
- **Scroll-triggered animations**, film-grain + vignette overlays, marquees.
- **SoundCloud** embeds for streaming.
- **Booking flow** — client-side validated form that opens the visitor's mail app
  pre-filled (no backend required).
- **Responsive** across mobile, tablet and desktop.
- **SEO/social ready** — descriptive meta + theme-color.

---

## Run locally

No build tools required.

```bash
# Just open it
#   double-click index.html

# Or serve it (recommended)
python -m http.server 8000
#   then visit http://localhost:8000
```

### Deploy

Upload all `.html` files to any static host — Netlify drop, Vercel, GitHub
Pages, Cloudflare Pages, or your own hosting. `index.html` is the home page.

---

## Project structure

```
.
├── index.html      # Home — hero + audio-reactive visualiser
├── music.html      # Music — SoundCloud players
├── about.html      # About — bio + sound tags
├── bookings.html   # Bookings — offer cards + validated booking form
├── epk.html        # Electronic press kit — bio, stats, contact
└── README.md
```

Each HTML file embeds its own `<style>` and `<script>`, so pages share no
external files and can be edited or deployed independently.

---

## License

Released under the [MIT License](LICENSE).

---

## Built by

Designed and developed by **Sahib Singh** — custom websites and creative web
apps for musicians and artists. *Vanta* is a demo concept showcasing one of
several artist-site themes.

- 🌐 Live demo: https://subchibeats.github.io/vanta-artist-website/ &nbsp;·&nbsp; https://vantamusic.netlify.app/
- 📸 Instagram: [@subchibeats](https://instagram.com/subchibeats)
- ✉️ Web work & bookings: `subchibeats@gmail.com`

> Want a site like this for your project? Get in touch.
