# Randwise

A local-first cash-flow planner for recording income and expenses, reviewing monthly totals and category breakdowns, and exporting filtered transactions as CSV.

**Live demo:** https://tumelodev-arch.github.io/Randwise/

## What it does

- Create, edit and delete income/expense entries.
- Filter by month, type, category and search term.
- Review income, expenses, net cash flow, savings rate and spending by category.
- Export filtered transactions to CSV.
- Persist records in the current browser using local storage.

## Run locally

Open `index.html` in a modern browser. The application uses local HTML, CSS and JavaScript and has no build step or external runtime dependency.

## Data and privacy

Records stay in the current browser until exported or cleared. They are not sent to a server or shared across browsers. This is a budgeting utility, not financial advice or a bank-connected product. It has no account system, backend, cloud sync or bank integration. Do not enter bank credentials or other sensitive information.

## Tests

The repository includes Playwright end-to-end tests. Install dependencies and Chromium before running them.

```bash
npm install
npx playwright install chromium
npm run test:e2e
```

## Interface design

The interface uses the shared Engineering Field Notes design language, adapted for this app's main task. Primary controls have labelled actions, the mobile layout keeps actions reachable, and keyboard focus is visible. The app uses its own accent colour to make it recognisable beside the portfolio.

## Limitations

This is a browser-based practice application. A successful static deployment does not establish that it has a backend, authentication, shared state or production monitoring.
