# Ledger — Expense Tracker

A single-file expense management web app. No backend, no dependencies to install.

## Deploy Options

### Option 1: Netlify (Free, fastest)
1. Go to https://netlify.com → "Add new site" → "Deploy manually"
2. Drag and drop this entire `ledger-app` folder
3. Done — live URL in seconds

### Option 2: Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` inside this folder
3. Follow the prompts

### Option 3: GitHub Pages (Free)
1. Push this folder to a GitHub repo
2. Go to Settings → Pages → Source: main branch / root
3. Live at `https://yourusername.github.io/repo-name`

### Option 4: Just open locally
Open `index.html` directly in any browser — fully functional with no server needed.

## Features
- Dashboard with charts and stats
- Transaction logging (income & expenses)
- Filter & search all transactions
- Monthly reports with charts
- AI notification parser (paste bank SMS to auto-log)
- Data persists in browser localStorage
- Mobile responsive
