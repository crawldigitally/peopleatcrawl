# People at Crawl — HR Management Platform

A complete, single-file HR platform for **Crawl Digitally**. Everything runs in the browser — no server, no build step, no dependencies to install. Data is stored locally in the browser (`localStorage`).

> ⚠️ This is a self-contained prototype. Authentication and data live in the browser only — for production, move auth and storage to a real backend (e.g. Supabase/Postgres).

## 🚀 Run it

**Option A — just open it**
Download `index.html` and double-click to open in any modern browser.

**Option B — GitHub Pages (free hosting)**
1. Create a new GitHub repository and upload `index.html` (and this `README.md`).
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick branch **main** and folder **/ (root)**, then **Save**.
5. After a minute your app is live at `https://<your-username>.github.io/<repo-name>/`.

## 🔐 Login

Sign in with a work email + password. All demo accounts use the password **`crawl123`**.

| Role | Email | Password |
|------|-------|----------|
| Super Admin | `akshay@crawldigitally.com` | `crawl123` |
| HR Manager | `priya@crawldigitally.com` | `crawl123` |
| Manager | `rahul@crawldigitally.com` | `crawl123` |
| Employee | `abhay@crawldigitally.com` | `crawl123` |

There's also a **Quick demo login** dropdown on the sign-in screen, and a **Reset demo data** link to reload fresh sample data.

## ✨ Modules

- **Dashboard** — role-based overview with charts
- **Employees** — directory, 360° profiles, access roles, org chart
- **Document Vault** — per-employee docs with upload/links
- **Asset Register** — company devices assigned to staff
- **Leave** — requests, approvals, balances, team calendar, leave types
- **Time & Attendance** — clock in/out with pause/resume, timesheets, roster, attendance log
- **Payroll** — salary structures, payslips (auto + manual), statutory deductions (EPF/ESI/PT/LWF/TDS), configurable rules engine (late/leave penalties, custom rules), increment eligibility, bank disbursement
- **Reimbursements** — apply → approve → clear
- **Tax & Investments** — declaration & proof approval
- **Sales Incentives** — commission calculator per sales policy + payout history
- **Recruitment (ATS)** — candidate shortlisting, pipeline, CV/portfolio, interviews
- **Onboarding / Probation / Offboarding**
- **Performance** — goals, reviews, feedback
- **KPI Scorecards** — position-wise templates (custom builder), self vs. manager scoring, grade bands
- **Learning**, **Engagement**, **Compliance**, **People Analytics**
- **Settings** — departments, KPI positions, document types, leave types

## 🛠 Tech

Plain HTML + CSS + JavaScript in one file. Charts via Chart.js (CDN). No frameworks.

---
© Crawl Digitally · 303, Sanrachna Avenue, Indore
