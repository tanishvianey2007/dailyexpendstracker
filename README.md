# Daily Expenses Tracker (Python + Tkinter + SQLite)

## Overview
Daily Expenses Tracker is a personal finance management desktop application built in Python using Tkinter for the user interface and SQLite for the database.

The application helps users:
- Track income and expenses
- Manage spending categories
- View monthly summaries
- Analyze spending using pie charts
- Set savings goals
- Monitor budget limits

---

## Features

### Core Features
- User Signup and Login
- Add Income
- Add Expenses
- Categories:
  - Food
  - Travel
  - Shopping
  - Bills
  - Health
  - Other

- View all transaction records
- Delete records
- Search transactions
- Monthly financial summary

---

## Extra Features
- Spending Pie Chart Visualization
- Budget Limit Alert
- Savings Goal Tracker
- Dashboard Overview
- SQLite Database Storage

---

## Tech Stack
- Python
- Tkinter
- SQLite
- Pandas
- Matplotlib

---

## Database Schema

### Users Table
| Field | Type |
|------|------|
| id | Integer (Primary Key) |
| name | Text |
| email | Text |
| password | Text |

---

### Transactions Table
| Field | Type |
|------|------|
| id | Integer (Primary Key) |
| user_id | Integer |
| type | Income/Expense |
| category | Text |
| amount | Real |
| date | Text |
| note | Text |

---

## Installation

### Install Dependencies
```bash
pip install matplotlib pandas
```

---

## Run the Project
Run in Jupyter Notebook or Python:

```python
python expense_tracker.py
```

or run the notebook cells in Jupyter.

---

## Default Login
Use demo login:

```text
Email: admin@gmail.com
Password: 1234
```

---

## Project Structure
```text
Daily-Expenses-Tracker/
│
├── expense_tracker.py
├── expenses_tracker.db
├── README.md
└── screenshots/
```

---

## Application Modules
- Authentication
- Dashboard
- Transaction Manager
- Search System
- Budget Alert
- Savings Goal Module
- Charts and Analytics

---

## Sample Workflow
1. Create account / Login  
2. Add income  
3. Add expenses  
4. View records  
5. Search or delete transactions  
6. Analyze spending chart  
7. Set savings goals  
8. Monitor budget alerts

---

## Future Enhancements
- Edit Transaction Feature
- PDF Bill Export
- Dark Mode
- Expense Reports
- CSV/Excel Export
- Recurring Expense Tracking
- Password Encryption
- Mobile App Version

---

## Screenshots (Optional)
Add screenshots here:

- Login Page
- Dashboard
- Add Expense Form
- Pie Chart Analytics

---

## Author
Created as a Python mini project for Expense Management.
