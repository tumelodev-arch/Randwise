# Randwise

A local-first monthly cash-flow planner for recording income and expenses in South African rand.

## Demo

When GitHub Pages is enabled for this repository, the app will be available at [https://tumelodev-arch.github.io/Randwise/](https://tumelodev-arch.github.io/Randwise/).
The application is also runnable locally; see below.

## Features

- Add, edit and delete income/expense entries.
- Filter by month, type, category and search terms.
- Calculate monthly income, expenses, net cash flow and savings rate.
- Compare spending by category.
- Export the visible filtered transactions to CSV.
- Persist entries in the current browser using local storage.
- Restore synthetic starter data for demonstration.

## Run locally

Open `index.html` in a modern browser. There is no build step or external runtime dependency. `styles.css` and `app.js` are loaded locally.

## Data and privacy

Records are stored in this browser only; they are not sent to a server or shared across browsers. Use synthetic or non-sensitive information. Clearing browser storage can remove locally saved records.

## Boundaries

This is a budgeting utility, not financial advice or a bank-connected product. It has no account system, cloud sync, bank integration or encryption beyond the browser's own storage facilities. Never enter bank credentials, account numbers or information you would not want saved in this browser.
