# Personal Budget Tracker & Tax Workbook

A self-built personal finance tool I use to track income, expenses, budgets, tax obligations, and investment allocation across multiple accounts.

## Live Demo

**[View Live](https://alessandro114.github.io/personal-budget-tracker/)**

## What It Does

- **Budget Monitoring** — monthly income vs expenses with category breakdown and budget-vs-actual progress bars
- **Transaction Ledger** — chronological spending log with categorization and running balance
- **Tax Workbook** — tax estimation for flat-rate regime (Italian "forfettario"), advance payment calendar, deductible expense tracking with regime-specific notes
- **Investment Tracker** — asset allocation across equity ETFs, government bonds, crypto ETPs, and cash; capital gains tax tracker (realized/unrealized) with correct tax rates per instrument type

## Why I Built It

Commercial tools (YNAB, Mint, etc.) don't handle:
- **Tax regime-specific calculations** — flat-rate coefficient-based taxation, advance payment "hump" effect in year 1, INPS social contribution interplay
- **Mixed currency tracking** — EUR income + USD subscriptions + CHF/GBP exposure
- **Business + personal in one view** — infrastructure costs (VPS, domains, SaaS) alongside personal expenses, with deductibility flags

So I built my own. It runs as a single static page with no backend, no login, no third-party data sharing.

## Tech

- Vanilla HTML/CSS/JS — zero frameworks, zero build step
- [Chart.js](https://www.chartjs.org/) for visualizations (bar, doughnut, line)
- Fully responsive, dark mode
- GitHub Pages deployment

## Privacy

Some values are redacted. This is a real, actively-used tool — not a demo with fake data.

## License

MIT
