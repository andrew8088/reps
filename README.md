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

Pushing to `main` triggers `.github/workflows/pages.yml`, which publishes the site
to GitHub Pages.
