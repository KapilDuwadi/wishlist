# WishList

**A quiet place for movies, books, places — anything for someday.**

[**Open the app →**](https://kapilduwadi.github.io/wishlist/)

---

A minimalist offline-first PWA for keeping track of things you want to watch, read, visit, or do. No account needed. Everything lives on your device.

## Features

- **Categories** — pre-seeded with Movies, Books, Places, Series. Add, rename, and reorder your own.
- **Items** — title, notes, source, link, done/not-done toggle, completion date, and 1–5 star rating after finishing.
- **Quick-add** — type a title and hit Enter from any screen.
- **Search & filter** — search across all categories, filter by All / Open / Done.
- **Drag to reorder** — reorder both categories and items within a list.
- **CSV export & import** — export everything to a single CSV for backup or sharing across devices.
- **Offline** — works without a connection after the first load; all data stored in `localStorage`.
- **Installable** — add to your home screen on Android or iOS and it opens like a native app.

## Install on mobile

**Android (Chrome):** tap the three-dot menu → *Add to Home screen*

**iOS (Safari):** tap the Share button → *Add to Home Screen*

## Tech

Single `index.html` — no build step, no backend.

- [React 18](https://react.dev/) via CDN + Babel standalone
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) + [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts
- Service worker for offline caching
- Web App Manifest for installability
- GitHub Actions → GitHub Pages for deployment

## Development

No build step needed. Just open `index.html` in a browser, or serve the directory:

```bash
npx serve .
# or
python -m http.server
```
