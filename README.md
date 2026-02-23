# Mutual Funds Insight Platform (Frontend Prototype)

A role-based **Mutual Fund Investment Perception** web prototype built for full-stack project submission (current scope: frontend + UI/UX only).

This platform helps users understand mutual funds, compare them, assess risk, and simulate investment decisions with interactive dashboards inspired by Groww/Zerodha-style UX.

---

## Project Scope (Current)

- Frontend-only prototype
- No backend/API/database integration yet
- All operations are UI-simulated using mock data
- Role-based flows for:
  - Investor
  - Admin
  - Financial Advisor
  - Data Analyst

---

## Tech Stack

- **Node.js**
- **React.js**
- **Vite**
- **React Router DOM**
- **Tailwind CSS**
- PostCSS + Autoprefixer

---

## Roles and Features

## 1) Investor

### Modules
- Fund Discovery (search + filtering + categorization)
- Risk Profiling Quiz
- Fund Comparison Dashboard
- Portfolio Analytics
- Goal-Based Investing
- SIP Management
- Alerts & Notifications
- Tax Estimation
- Behavioral Analytics
- Education Feed

### Investor Capabilities
- Filter funds by:
  - Risk
  - Return
  - Fund house
  - Expense ratio
  - Rating
  - Fund type
- Compare funds side-by-side:
  - 1Y/3Y/5Y returns
  - Expense ratio
  - Risk level
  - AUM
  - Fund manager
  - Exit load
- Risk profiling quiz input:
  - Age
  - Income
  - Investment duration
  - Risk tolerance
  - Financial goals
- Classification output:
  - Conservative
  - Moderate
  - Aggressive
- Personalized fund recommendation from profile
- Portfolio analytics:
  - Total invested
  - Current value
  - Profit/Loss %
  - XIRR (approximate)
  - Asset allocation pie chart
  - Sector allocation breakdown
- Goal planning:
  - Education / House Purchase / Retirement / Vacation
  - Required SIP
  - Expected corpus
  - Time to goal
- SIP operations:
  - Start
  - Pause
  - Step-up SIP
  - Auto debit simulation
  - Reminder simulation
  - SIP calculator
- Tax simulation:
  - Capital gains tax
  - LTCG/STCG
  - ELSS 80C savings
- Behavioral nudges:
  - Panic selling tendency
  - Overtrading tendency
  - SIP consistency
- Education interactions:
  - Like
  - Comment
  - Ask advisor questions

---

## 2) Admin

### Admin Control Panel
- Approve advisors
- Add/update fund data (UI simulation)
- View platform-level statistics
- Handle user complaints
- Remove fraudulent accounts

---

## 3) Financial Advisor

### Advisor Dashboard
- View client snapshot
- Suggest funds
- Send personalized recommendations
- Track client risk profile
- Generate investment report (UI simulation)

### Advisor Education Hub
- Post:
  - Articles
  - Videos
  - Market analysis
  - Risk guides

---

## 4) Data Analyst

### Analyst Lab (Advanced Features Prototype)
- Monte Carlo simulation (visual prototype)
- Market sentiment indicator
- NAV integration simulation
- Portfolio rebalancing engine toggle
- Advanced analytics-style cards

---

## Special Features Implemented

- Rule-based **AI-powered insights** (example outputs):
  - “This fund is underperforming compared to category average.”
  - “Your portfolio is over 80% equity. Consider diversifying.”
  - “You are overexposed to banking sector.”
- Risk & volatility metrics with beginner tooltip explanations:
  - Standard Deviation
  - Beta
  - Sharpe Ratio
  - Alpha
- Mutual fund type explainers:
  - Equity
  - Debt
  - Hybrid
  - Index
  - ELSS (Tax Saving)
- Interactive charts:
  - Bar comparison charts
  - Line trend charts
  - Pie allocation charts

---

## Current Limitations

- No real authentication backend
- No real transaction execution
- No real-time NAV APIs
- No database persistence (state resets on refresh)
- PDF/report generation is UI-simulated

---

## Run Locally

```bash
npm install
npm run dev
