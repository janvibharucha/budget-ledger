# Budget Ledger

A personal budgeting app in a single self-contained HTML file. It runs as a
Claude Artifact with persistent, per-user storage that syncs across your
devices when you're signed in — and it's designed to be added to an iPhone
home screen and used like a native app.

## Pages

### Spending Log
A month-by-month ledger of what you spend.
- Log a purchase: date, amount, a tap-to-pick category (Groceries, Eating Out,
  Rent/Bills, Activity, Other), and an optional note.
- Step between months; each month is its own view.
- Filter the table by category.
- Automatic month total plus a per-category breakdown with bars and percentages.

### Big Picture
Dated cash-flow snapshots for the larger picture.
- Record a paycheck plus that period's savings, brokerage, 401(k), Roth IRA,
  and credit-card bill.
- Roll everything up on a **weekly, bi-weekly, monthly, or annual** basis.
- See net cash flow (paycheck minus everything out), a history-by-period table,
  and the raw entries.

### Insights
A dashboard that turns logged data into advice.
- Headline KPIs: total spent, average per month, savings rate, net cash flow.
- Monthly spending trend chart.
- Auto-generated insights: savings rate vs. the 20% target, spending vs.
  take-home, month-end pace, needs-vs-wants split, food spending breakdown,
  biggest category, and month-over-month change.
- Behavior deep-dive: transaction count, average transaction, biggest purchase,
  and spending by day of week.
- An adjustable range (last 3 / 6 / 12 months / all time).

## Design
Soft pink/rose palette with full light and dark themes. Mobile-first layout:
16px inputs (so iOS Safari doesn't zoom on focus), 44px+ tap targets, and
safe-area handling for notches and home indicators.

## Files
- `budget.html` — the entire app (markup, styles, and logic in one file).

## Using it on iPhone
Open the artifact link in Safari, then **Share → Add to Home Screen**. Sign in
with the same account on your phone and computer to see the same data in both.
