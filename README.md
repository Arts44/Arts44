<img src="assets/banner.svg" alt="Arts44 — web & app development" width="100%">

# Arthur

Self-taught developer based in Belgium. Starting formal web and app development studies in September 2026.

## Featured project — F1 UNO Élite

A progressive web app for tracking an *F1 UNO Élite* trading-card collection: 101 cards from the 2025 season, each in up to 16 variants, with owned/doubles/wishlist tracking, a six-level rarity system, badges and completion stats.

**[Live app](https://arts44.github.io/f1-uno-elite/)** · **[Source](https://github.com/Arts44/f1-uno-elite)**

- Vanilla JavaScript with **zero runtime dependencies** — no framework, no SDK, no CDN. esbuild is the only build-time dependency.
- **Offline-first service worker**: versioned precache, and a new version is picked up in the background and applied from a one-tap banner rather than a forced reload.
- **Optional Supabase cloud sync** over pure REST `fetch()` — no SDK — with email OTP authentication, chosen because magic links break inside an installed PWA.
- **7 languages** (English, French, Spanish, Chinese, Italian, Dutch, German), every string included.
- **166 automated tests** on Node's built-in test runner, run in GitHub Actions along with a check that the committed bundle matches the sources.

<sub>Unofficial fan project, non-commercial. Not affiliated with Formula 1 or Mattel/UNO.</sub>

## Currently learning

Java, web fundamentals, and the basics of cybersecurity.

## Contact

Reach me through GitHub — [@Arts44](https://github.com/Arts44).
