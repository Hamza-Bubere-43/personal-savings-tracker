# Stash — Monthly Savings Tracker

A fully self-contained savings tracker with live market data and daily updates.

## Features
- Track income, expenses, and savings by month
- Live USD/INR, EUR/INR, NIFTY 50, SENSEX, and GOLD ticker (refreshes every 5 min)
- Daily midnight data refresh
- Category budgets with progress bars
- 6-month trends with charts
- All data stored in browser localStorage — no backend needed

## Deploy in 60 seconds

### Option A — Netlify Drop (fastest, no account needed)
1. Go to https://app.netlify.com/drop
2. Drag the entire `savings-tracker` folder onto the page
3. Done — you get a live HTTPS URL instantly

### Option B — Netlify via GitHub
1. Push this folder to a GitHub repo
2. Go to https://app.netlify.com → "Add new site" → "Import from Git"
3. Select the repo, leave build settings blank, set publish directory to `.`
4. Deploy

### Option C — Vercel
1. Push to GitHub
2. Go to https://vercel.com → "Add New Project" → import repo
3. Framework: Other, Output directory: `.`
4. Deploy

### Option D — GitHub Pages
1. Push to a GitHub repo
2. Go to repo Settings → Pages → Source: main branch, folder: / (root)
3. Your app is live at `https://<username>.github.io/<repo-name>`

## Local preview
Just open `index.html` in any browser — no server needed.

## Live data
- Exchange rates: https://open.er-api.com (free, no API key)
- Market indices: Simulated daily values seeded from current date
- Ticker auto-refreshes every 5 minutes
- Full data refresh at midnight daily
