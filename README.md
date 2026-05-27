fm-finance
==========

A Personal Finance Field Manual -- a working reference for the day-to-day
decisions that shape your financial life: budgeting, savings, borrowing,
investing, taxes, insurance, and planning.

Built with [Quarto](https://quarto.org/). Code examples use both **R** (with
the tidyverse) and **Python** (with pandas / NumPy).

## Contents

### Introduction

- The four core levers: income, spending, savings, investing
- Time horizon

### Part 1 -- Foundations

- Income
- Budgeting
- Tracking Spending
- Emergency Fund
- Managing Debt

### Part 2 -- Savings

- Savings Strategies
- High-Yield Savings Accounts
- Automating Savings

### Part 3 -- Investing

- Investing Basics
- Retirement Accounts
- Index Funds
- Asset Allocation

### Part 4 -- Taxes & Insurance

- Taxes
- Insurance

### Part 5 -- Planning

- Financial Goals
- Major Purchases
- Estate Planning

### Appendices

- Resources

## Building the book

Render the full book:

```bash
quarto render
```

Live preview with auto-reload:

```bash
quarto preview
```

Render a single chapter:

```bash
quarto render budgeting.qmd
```

## Requirements

- [Quarto](https://quarto.org/) 1.4 or newer
- **R** with `knitr`, `rmarkdown`, and the tidyverse packages used in
  `_common.R`
- **Python** 3 with `pandas` and `numpy` (only required for chapters with
  Python chunks)

## Project layout

```
fm-finance/
├── asset_allocation.qmd
├── automating_savings.qmd
├── budgeting.qmd
├── custom.scss
├── emergency_fund.qmd
├── estate_planning.qmd
├── financial_goals.qmd
├── fm-finance.Rproj
├── foundations.qmd
├── high_yield_accounts.qmd
├── income.qmd
├── index_funds.qmd
├── index.qmd
├── insurance.qmd
├── investing_basics.qmd
├── investing.qmd
├── major_purchases.qmd
├── managing_debt.qmd
├── planning.qmd
├── README.md
├── references.bib
├── renv/
├── resources.qmd
├── retirement_accounts.qmd
├── savings.qmd
├── savings_strategies.qmd
├── taxes_insurance.qmd
├── taxes.qmd
└── tracking_spending.qmd

12 directories, 60 files
```

## Author

Martin Frigaard
