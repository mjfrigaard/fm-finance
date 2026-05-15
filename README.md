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
├── _quarto.yml          # book config
├── _common.R            # shared knitr/options + co_box helper
├── custom.scss          # theme overrides
├── references.bib       # bibliography
├── index.qmd            # welcome / preface
├── intro.qmd            # introduction (the four levers)
├── foundations.qmd      # part 1 cover + chapters
├── savings.qmd          # part 2 cover + chapters
├── investing.qmd        # part 3 cover + chapters
├── taxes_insurance.qmd  # part 4 cover + chapters
├── planning.qmd         # part 5 cover + chapters
└── resources.qmd        # appendix
```

## Author

Martin Frigaard
