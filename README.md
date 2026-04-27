# Finance Tracker

A mobile-first personal finance tracker — PWA, dark mode, fully offline, no backend.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Complete single-page app |
| `manifest.json` | PWA manifest for home screen install |
| `sw.js` | Service worker for offline support |

---

## Deploy to GitHub Pages

### 1. Create a GitHub repo

1. Go to [github.com](https://github.com) and sign in.
2. Click **+** → **New repository**.
3. Name it (e.g. `finance-tracker`), set to **Public**, click **Create repository**.

### 2. Push the files

```bash
cd "path/to/Finance Tracker"
git init
git add index.html manifest.json sw.js
git commit -m "Initial deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/finance-tracker.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. In your repo, go to **Settings** → **Pages** (left sidebar).
2. Under **Source**, select **Deploy from a branch**.
3. Choose **main** branch, **/ (root)** folder.
4. Click **Save**.
5. Wait ~60 seconds. Your app is live at:
   `https://YOUR_USERNAME.github.io/finance-tracker/`

---

## Add to iPhone Home Screen

1. Open Safari on your iPhone.
2. Navigate to your GitHub Pages URL above.
3. Tap the **Share** button (box with up arrow) at the bottom.
4. Scroll down and tap **Add to Home Screen**.
5. Name it **Finance Tracker** and tap **Add**.

The app will now appear on your home screen and launch full-screen like a native app. It works completely offline after the first load.

---

## Features

- **Dashboard** — weekly budget ring, income breakdown, recent expenses, investment summary, TFSA room, budget health grade, spending charts
- **Expenses** — log expenses with category, description, and date; week/month/all-time filter; swipe to delete
- **Budget** — set savings/investment allocations, per-category monthly limits, recurring bills, week start day
- **Investments** — add TFSA / Non-Registered / Crypto / Other accounts, log weekly contributions, automatic TFSA room tracking
- **Settings** — edit income, birth year, TFSA contributions; full data reset

## Data & Privacy

All data is stored in your browser's `localStorage` — nothing leaves your device. Clearing browser data or tapping **Clear All Data** in Settings will erase everything.
