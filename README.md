# Marcus Lite

Goldman Sachs Hackathon submission. Empowering the Everyday Investor.

## What this is

A single self-contained `index.html` file. Open it in any browser and it works. No build step, no npm, no dependencies to install. React loads from a CDN.

## How to deploy to your existing GitHub repo

1. Open your repo on github.com.
2. Click "Add file" then "Upload files". Drag in `index.html`. (Or replace the existing one if you already uploaded a previous version.)
3. Commit the change.
4. Go to Settings, then Pages in the left sidebar.
5. Under "Source", pick branch `main` and folder `/ (root)`. Click Save.
6. Wait about a minute. The page will appear at `https://YOUR_USERNAME.github.io/REPO_NAME/`.

If Pages was already enabled, the new file will go live in about 30 seconds after commit. No rebuild needed since there's no build step.

## How to test locally

Just double-click `index.html`. It opens in your default browser.

For a proper local server (recommended for the live demo):

```bash
cd marcus-lite
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Demo profiles

Three profiles are built in. Switch between them on the welcome screen or from the dropdown on the dashboard:

- **Maya**: moderate risk, steady income
- **Arjun**: aggressive, high income
- **Sofia**: conservative, beginner investor

Each profile has its own debts, goals, recommendations, allocation, and transparency data.

## Features

- 6-section onboarding (who you are, income, debts, goals, current money, risk feeling)
- Unified dashboard with portfolio value and gain/loss
- Three status cards (health score, risk match, this week's action)
- Translate This (paste any news or worry, get plain English meaning)
- What If (free text scenario planning)
- Holdings list with sparklines
- Asset Allocation section with current vs target visualization
- Risk Match Check with one-tap fix
- Goals tracker
- Smart Money Moves engine (3-step combo plan that's market-aware)
- Debts shown by priority
- History panel
- Floating "Why these recommendations?" button that opens a transparency panel showing every input the system uses
- Trust footer
