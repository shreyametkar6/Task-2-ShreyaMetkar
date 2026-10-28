# Task 2: Expense Tracker (Python)

## Description
A command-line expense tracker written in Python. The user types expense amounts one by one, and the program adds them up and shows the running total. When the user types `quit`, it prints the final total.

Built as **Task 2** of my Python Programming Internship at **DecodeLabs** (Batch 2026).

## Features
- Enter any number of expenses (including decimals like 49.50)
- Running total shown after every entry
- Invalid input (like `ten`, `0` or negative numbers) is rejected without crashing
- Type `quit` to stop and see the final total

## How to Run
1. Install Python and Jupyter Notebook.
2. Download this repository (green **Code** button, then **Download ZIP**) and extract it.
3. Open a terminal in the extracted folder and start Jupyter:

```
jupyter notebook
```

4. Open `expense_tracker.ipynb`.
5. Click the code cell and press **Shift + Enter** to run it.
6. Type each expense amount and press Enter. Type `quit` to finish.

## Example
```
Enter expense amount (or 'quit'): 100
Added $100.00 | Running total: $100.00

Enter expense amount (or 'quit'): 50
Added $50.00 | Running total: $150.00

Enter expense amount (or 'quit'): ten
Invalid data. Please enter a positive number like 100 or 49.50.

Enter expense amount (or 'quit'): quit

===========================
Expenses entered : 2
FINAL TOTAL      : $150.00
===========================
```

## Concepts Used
- Accumulator pattern (`total += new_expense`)
- `while True` loop with a `quit` kill switch
- Type conversion with `float()`
- Defensive coding with `try / except ValueError`
- Functions (logic separated from display)

## Author
Shreya Metkar - [GitHub](https://github.com/shreyametkar6)
