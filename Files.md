# Codebase Map: Crush's Date-Ask Web App 💖

## 📂 Directory Tree

```
/home/jagdish/Desktop/Sandbox/Zara/Hello/
├── Work_Step.md       # Step tracking & progress checklist
├── Files.md           # Architecture directory tree & component index
├── README.md          # Project showcase, features & GitHub Pages deployment guide
├── CNAME              # Custom domain configuration (askher.jagdishsah.com.np)
├── index.html         # Main web application structure & semantic layout
├── style.css          # Dark-mode coder aesthetic, gradients, neon glows, responsive layouts
└── script.js          # Interactive terminal typing, runaway button, audio synth, confetti canvas
```

---

## 📄 File Details & Component Overview

### 1. [`index.html`](file:///home/jagdish/Desktop/Sandbox/Zara/Ask%20Her/index.html)
- **`<div id="terminal-loader">`**: Interactive terminal simulation window checking IOE WRC Pokhara status and feelings deployment.
- **`<header class="status-bar">`**: Branch pill (`main*`), live status pulse indicator, and sound vibe toggle.
- **`<section class="hero-section">`**: Greeting with wave emoji, code snippet by Jagdish (BCT, WRC Pokhara), and smooth CTA anchor.
- **`<section class="specs-section">`**: Dev candidate profile cards (Lakeside Coffee & Snack Pipeline, Pokhara Scooter Cruising API, Aesthetic Photo Skills, Date Itinerary Engine).
- **`<section class="changelog-section">`**: Release notes format highlighting reasons for asking them out (`ADDED`, `FIXED`, `OPTIMIZED`).
- **`<section id="the-big-ask">`**: The interactive proposal card featuring the YES / Runaway NO button arena.
- **`<div id="success-screen">`**: Modal overlay appearing upon saying "YES", letting her choose a real Pokhara vibe, select a day, and generate a date pass with direct WhatsApp integration.

### 2. [`style.css`](file:///home/jagdish/Desktop/Sandbox/Zara/Hello/style.css)
- **CSS Variables (`:root`)**: Vibrant dark-theme palette (`#0f111a`, `#ff5e97`, `#9d4edd`, `#05d550`, `#38bdf8`).
- **Typography**: Paired Google Fonts (`Plus Jakarta Sans` for modern UI, `Fira Code` for terminal/code snippets).
- **Animations**: Terminal cursor blink, pulsing status dot, pulsing heart, pop-in modals, and responsive layout queries.

### 3. [`script.js`](file:///home/jagdish/Desktop/Sandbox/Zara/Hello/script.js)
- **`typeTerminalLine()` / `launchApp()`**: Simulates terminal character-by-character typing with delay variances.
- **`moveNoButton()`**: Calculates boundary physics to jump the "NO" button away on `mouseover` or `touchstart`, cycles playful error messages, and scales the "YES" button larger.
- **`playCuteBeep()` / `playSuccessChime()`**: Zero-dependency Web Audio API synthesizer for retro 8-bit interactive audio feedback.
- **`initBackgroundCanvas()` / `animateHearts()`**: Background canvas rendering floating hearts and stars.
- **`launchConfetti()` / `updateConfetti()`**: Custom physics-based confetti engine with gravity and spin effects.
- **Date Ticket Generator**: Listens for the date planning form submission, formats the date nicely, and renders an official confirmation pass.
