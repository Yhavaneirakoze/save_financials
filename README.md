# save_financials
Save Financials

Save Financials is a beginner-friendly, personal-use budget tracker written in Python. Effortlessly record your transactions, categorize spending, and visualize your financial habits—all from the command line!

Features

- Add and review transactions with descriptions and categories
- Summarize your total balance and spending by category
- Simple, clean text output for easy tracking
- [Planned] Visualize expenses with charts and plots for better insights

Getting Started

Prerequisites

- Python 3.x
- `matplotlib` (for plotting, planned in future releases)

Install `matplotlib` (if you want to try plotting features):

```bash
pip install matplotlib
```

Usage

```python
from save_financials import BudgetTracker

tracker = BudgetTracker()
tracker.add_transaction(-50, "Food", "Groceries at supermarket")
tracker.add_transaction(1000, "Salary", "May paycheck")
tracker.add_transaction(-20, "Transport", "Bus pass")
tracker.show_transactions()
tracker.show_summary()
tracker.plot_spending_by_category()  # [Planned] Visuals coming soon!
```

 Example Output

```
Date       | Category   | Amount    | Description
--------------------------------------------------
2025-05-27 | Food       | $-50.00   | Groceries at supermarket
2025-05-27 | Salary     | $1000.00  | May paycheck
2025-05-27 | Transport  | $-20.00   | Bus pass

Total Balance: $930.00

Spending by Category:
  Food       : $-50.00
  Salary     : $1000.00
  Transport  : $-20.00
```

Roadmap

- [x] Add and display transactions
- [x] Summarize balance and spending by category
- [ ] Add visualizations (pie/bar charts for spending)
- [ ] Export data to CSV
- [ ] User authentication for multiple profiles

Contributing

Contributions and suggestions are welcome! If you’re a beginner, this is a great project to get started with open source. Open an issue or pull request to discuss improvements.

 License

MIT License

---

Happy budgeting!

