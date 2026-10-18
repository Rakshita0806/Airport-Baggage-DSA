# AeroSort: Airport Baggage Management System

A Python-first Data Structures and Algorithms project built with **Python, Flask, SQLite, HTML and CSS**. It uses no JavaScript and no React. Python handles all sorting, searching, queue operations and database logic.

## Features
- Dashboard with live totals by baggage status
- Register baggage and update/delete records
- Search records with Linear Search or Binary Search by numeric tracking ID
- Bubble Sort, Insertion Sort and Merge Sort
- Priority queue: Urgent, Priority, then Normal
- Persistent SQLite database and sample data
- Responsive layout and locally stored SVG illustrations

## Run on Windows
1. Extract this ZIP and open the `airport-baggage-python` folder in VS Code.
2. Open **Terminal → New Terminal**.
3. Create a virtual environment:

   ```powershell
   py -m venv .venv
   .\\.venv\\Scripts\\Activate.ps1
   ```

   If activation is blocked, use `.\.venv\Scripts\python.exe` instead of `python` in the commands below.
4. Install Flask:

   ```powershell
   python -m pip install -r requirements.txt
   ```
5. Start the site:

   ```powershell
   python app.py
   ```
6. Open http://127.0.0.1:5000

## DSA viva notes
- Queue: First In, First Out (FIFO).
- Priority queue: higher-priority baggage is processed first.
- Bubble Sort and Insertion Sort: O(n²) average/worst case.
- Merge Sort: O(n log n) time.
- Linear Search: O(n).
- Binary Search: O(log n), requires records sorted by ID.

This is an educational simulation, not a connection to real airline or airport systems. Use fictional passenger details.
