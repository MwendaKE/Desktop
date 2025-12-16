# 💰 GoldenMoney — Personal Finance & Budget Manager

## 📋 Project Overview

**GoldenMoney** is a desktop personal finance manager built with **C++ and Qt**.  
It helps users manage income, expenses, debts, budgets, and savings — all in one simple and elegant desktop interface.

The app focuses on clarity, ease of use, and insightful financial visualization.

---

## 🎯 Core Purpose

To help users achieve financial control and awareness through organized records, visual summaries, and smart budgeting tools.

---

## 🎨 Design & Interface

### Theme & Feel

- Modern, clean, and distraction-free UI
- Soft gold and gray tones for a premium feel
- Rounded buttons, flat icons, and well-spaced layouts

### Color Scheme

- **Primary Color:** `#FFD54F` — Golden Yellow (highlights and buttons)
- **Accent Colors:**
  - `#4CAF50` — Green (income and positive balances)
  - `#F44336` — Red (debts and negative balances)
  - `#2196F3` — Blue (savings and neutral data)
  - `#9E9E9E` — Gray (secondary text and borders)

### Typography

- **Headings:** Segoe UI Semibold
- **Body Text:** Segoe UI or Roboto Regular

---

## 🚀 Key Features

### 1. Dashboard & Financial Overview

- Real-time financial summary cards
- Financial health score with progress visualization
- Monthly comparisons and trends
- Recent transactions sidebar
- Upcoming bills alerts

### 2. Income & Expense Management

- Add and edit income records
- Track expenses across categories:
  - Food & Dining
  - Transport
  - Housing
  - Utilities
  - Healthcare
  - Education
  - Entertainment
  - Shopping
- Smart amount formatting (K, M for large numbers)
- Monthly filtering and analysis

### 3. Debt Management

- Track loans, repayments, and due dates
- Status tracking: Pending, Partial, or Cleared
- Debt progress visualization
- Upcoming payment alerts
- Visual progress charts

### 4. Budget Planning

- Create monthly budgets per category
- Real-time overspending alerts
- Budget vs actual comparison
- Progress tracking
- Smart notifications

### 5. Savings Goals

- Create and manage savings targets
- Track progress toward goals
- Visual completion indicators
- Savings progress charts

### 6. Financial Insights

- Automated spending alerts
- Budget usage notifications
- Large expense detection
- Income trend analysis
- Financial health scoring
- Personalized money tips

### 7. Reporting & Export

- Generate detailed monthly reports
- Export to PDF format
- Printable financial summaries
- Customizable report templates

---

## 💾 Technical Features

### Platform

- Built with **C++ and Qt Widgets**
- **SQLite** database stored locally
- Data stored in relational tables

### Database Schema

- `incomes (id, amount, source, date, note)`
- `expenses (id, amount, category, date, note)`
- `debts (id, creditor, amount, due_date, status)`
- `budgets (id, category, limit_amount, period)`
- `savings (id, goal_name, target_amount, saved_amount, deadline)`

---

## 🧩 Tech Stack

- **Language:** C++
- **Framework:** Qt5 (Widgets, Charts, SQL, PrintSupport)
- **Database:** SQLite
- **Build Tool:** qmake
- **UI Design:** Qt Designer
- **Icons:** PNG assets

---

## 🖥️ Desktop Experience

### User Experience

- Intuitive navigation layout
- Dialog-based input forms
- Auto-saved records
- Toolbars for quick actions
- Responsive desktop design

### Analytics & Visualization

- Built-in Qt Charts
- Interactive pie and donut charts
- Monthly trend visualization
- Exportable PDF reports

---

## 🎯 Target Audience

- Students learning money management
- Freelancers tracking income and expenses
- Employees budgeting monthly spending
- Small business owners managing personal finance

---

## 🌟 Unique Value Propositions

1. Offline & Private — All data stored locally
2. Simple & Fast — Smooth performance on any computer
3. Visual & Insightful — Instant graphs and summaries
4. Cross-Platform — Windows, Linux, and macOS
5. Smart Alerts — Proactive financial notifications
6. Clean Design — Modern, minimalist interface

---

## 💬 Tagline

> **Master your money — the Golden way.**

---

## 🚀 Getting Started

1. Clone the repository  
2. Install Qt5 development packages  
3. Run `qmake GoldenMoney.pro`  
4. Run `make`  
5. Execute the compiled binary  

---

## 📄 License

This project is for educational and personal use.