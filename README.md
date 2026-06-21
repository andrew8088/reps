# reps

A mobile-first spaced-repetition flashcard app — a single self-contained `index.html`
with no backend and no build step. All data (decks, cards, cloze items, review
history, scheduling) is stored locally in the browser via IndexedDB.

**Live:** https://andrew8088.github.io/reps/

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server
```

## Deploy

Hosted on GitHub Pages, served from the `main` branch root. Pushing to `main`
updates the live site automatically. Enabled once via **Settings → Pages →
Build and deployment → Source: Deploy from a branch → `main` / `/ (root)`**.
