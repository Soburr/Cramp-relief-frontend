# 🌸 For Mayrie

A small, personal web app built for my girlfriend to help her through period pain. No frameworks to install, no build step — just one HTML file.

It has three tools:

- **Heat Belt Timer** — alternates between a 20-minute heat session and a 10-minute rest, with a ring progress indicator so she always knows where she is in the cycle
- **Breathing Guide** — walks through the 4-7-8 breathing technique with an animated orb that expands and contracts with each phase
- **Love Notes** — eight little notes from me to her, for the moments when she just needs a reminder that she's not alone

---

## Usage

No install. No dependencies. No internet required after the first load (except for Google Fonts).

```bash
# Just open it
open index.html
```

Or drop it anywhere — a phone, a USB drive, a GitHub Pages site. It works everywhere.

---

## Stack

| Thing | What |
|---|---|
| [Vue 3](https://vuejs.org/) | Loaded via CDN, Composition API |
| [DM Serif Display + DM Sans](https://fonts.google.com/) | Typography via Google Fonts |
| Vanilla CSS | All styling, no frameworks |

---

## Structure

Everything lives in `index.html`. The Vue app is mounted on `#app` and uses `setup()` with `ref` and `computed` for all state. No components, no router, no build tooling — intentionally kept simple.

---

## Deploying to GitHub Pages

1. Push `index.html` to a repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Done — she gets a link she can bookmark on her phone

---

*Made with love by Adewunmi 🧡*
