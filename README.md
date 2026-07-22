<img src="assets/banner.svg" width="100%" alt="Arts44 — web & app development, Belgium">

Arthur, from Belgium. Self-taught developer, starting formal web and app development studies in September 2026.

I build things end to end and keep the stack as small as the problem allows.

## Featured project — F1 UNO Élite

A progressive web app for tracking an *F1 UNO Élite* trading-card collection: 101 cards from the 2025 season, each in up to 16 variants, with a six-level rarity system, badges and completion stats.

**[Live app](https://arts44.github.io/f1-uno-elite/)** · **[Source](https://github.com/Arts44/f1-uno-elite)**

- Vanilla JavaScript, **zero runtime dependencies** — no framework, no SDK, no CDN. esbuild is the only build-time dependency.
- Offline-first service worker with a versioned precache. New versions download in the background and are applied from a one-tap banner instead of a forced reload.
- Optional Supabase sync over pure REST `fetch()` — no SDK — using email OTP codes, because magic links break inside an installed PWA.
- Seven languages, every user-facing string included.
- 166 tests on Node's built-in runner, run in GitHub Actions alongside a check that the committed bundle still matches the sources.

<sub>Unofficial fan project, non-commercial. Not affiliated with Formula 1 or Mattel/UNO.</sub>

## Currently learning

Java, web fundamentals, and the basics of cybersecurity.

## Contact

Through GitHub — [@Arts44](https://github.com/Arts44).
