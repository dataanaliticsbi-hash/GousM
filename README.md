# MalBankAI Credit Lending Dashboard

**Tableau Public Link:** [View Dashboard](https://public.tableau.com/views/MalBankAI/CreditLending?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**Dashboard Owner:** Gous Mahammad  
**Last Updated:** 01-09-2026 12:00:00 AM
**Status:** Active — Real-time & Historical Data

---

## Quick Navigation

**New to this dashboard?** Start with [Overview](#overview) → [How to Access](#how-to-access)  
**Want to use it daily?** Jump to [Dashboard Pages Overview](#dashboard-pages-overview) → [Page 2: Executive Dashboard](#page-2-executive-dashboard)  
**Need metric definitions?** Go to [Page 5: KPI Dictionary](#page-5-kpi-dictionary)  
**Metric doesn't match your report?** See [Page 4: Metric Conflict Resolution](#page-4-metric-conflict-resolution)  
**Having issues?** Jump to [Troubleshooting](#troubleshooting)

---

## Table of Contents

1. [Overview](#overview)
2. [Key Audience & Use Cases](#key-audience--use-cases)
3. [Dashboard Pages Overview](#dashboard-pages-overview)
   - [Page 1: Self-Service Landing Page](#page-1-self-service-landing-page)
   - [Page 2: Executive Dashboard](#page-2-executive-dashboard)
   - [Page 3: Credit & Lending Domain Dashboard](#page-3-credit--lending-domain-dashboard)
   - [Page 4: Metric Conflict Resolution](#page-4-metric-conflict-resolution)
   - [Page 5: KPI Dictionary](#page-5-kpi-dictionary)
   - [Navigating Between Pages](#navigating-between-pages)
4. [Metric Definitions (Certified)](#metric-definitions-certified)
5. [How to Access](#how-to-access)
6. [Common Use Cases & How-To](#common-use-cases--how-to)
7. [Data Refresh Cadence](#data-refresh-cadence)
8. [Troubleshooting](#troubleshooting)
9. [Metric Conflicts & Resolutions](#metric-conflicts--resolutions)
10. [Data Dictionary & Governance](#data-dictionary--governance)
11. [Contact & Support](#contact--support)
12. [Related Documentation](#related-documentation)

---

## Overview

The **Credit Lending Dashboard** is an executive-grade analytics tool that monitors the credit origination, approval funnel, portfolio quality, and risk metrics for the MalBankAI lending platform. This dashboard serves Credit, Finance, and Product teams with a single source of truth for credit performance.

### Key Audience
- **Chief Credit Officer** — Portfolio health, default rates, risk concentration
- **Finance Team** — Revenue attribution, loss reserves, GAAP reporting
- **Product Team** — Approval rates, customer cohort performance
- **Risk & Compliance** — Regulatory metrics, early warning indicators

---

## Dashboard Pages Overview

The dashboard contains **5 comprehensive pages**, each serving a distinct stakeholder need. Navigate between them using the tab bar at the top.

---

## Page 1: Self-Service Landing Page

**Purpose:** Central hub for access, dataset discovery, and SLA communication  
**Audience:** All users (first-time & returning)  
**Time to Review:** 5 minutes

### What's On This Page

**Quick Stats Cards**
- Executive Dashboard: 8 KPIs
- Domain Dashboards: Credit Funnel
- Metric Conflicts: 3 Resolved
- Catalog: 15 Metrics

### Available Datasets

**Credit & Lending**
- Loan approval funnel
- Portfolio risk metrics
- Default rates by cohort

**Finance & Product**
- Revenue recognition
- Active customer metrics
- Product adoption

### How to Request Access

1. Email `bi-team@company.com` with your domain name
2. Include your use case (analysis, monitoring, reporting)
3. We'll provision access in your preferred tool within 2 business days
4. Consult the KPI Dictionary for certified metric definitions

### Support & SLAs

| Service | SLA |
|---------|-----|
| Dashboard access | 2 hours |
| Data refresh | Hourly for real-time, daily for historical |
| Support hours | 8 AM–6 PM PT, weekdays |
| Escalation (Critical) | 30 min response |

**Contact:** `bi-team@company.com`  
**Slack:** `#bi-support`

### Why This Page Matters
- **Reduces support tickets:** Self-service access & SLA info
- **Centralizes communication:** One place for all dataset info
- **Sets expectations:** Clear SLAs prevent frustration
- **Drives adoption:** Clear pathways to onboard new users

---

## Page 2: Executive Dashboard

**Purpose:** High-level view of business performance across Credit, Finance, and Product  
**Audience:** C-suite, Board members, Senior managers  
**Refresh Rate:** Real-time (approval/application data), Hourly (balances), Daily (delinquency)  
**Time to Review:** 10 minutes

### Key Performance Indicators (8 Total)

#### Revenue & Growth (Row 1)
| KPI | Current | MoM Change | Target | Status |
|-----|---------|-----------|--------|--------|
| Total Revenue | $2.47M | +18% | $2.5M+ | ✓ On Track |
| Active Customers | 45,230 | +23% | 40,000+ | ✓ Exceeding |
| Credit Originations | $18.5M | +31% YoY | $17M+ | ✓ Exceeding |
| Approval Rate | 73.2% | -2.1% | 75%+ | ⚠ Slightly Below |

#### Portfolio Health (Row 2)
| KPI | Current | QoQ Change | Target | Status |
|-----|---------|-----------|--------|--------|
| Payment Volume | $142M | +42% YoY | $130M+ | ✓ Exceeding |
| Default Rate (30+ DPD) | 2.1% | -0.3% | <2.0% | ✓ Good |
| Assets Under Management (Savings) | $67.3M | +54% YoY | $60M+ | ✓ Exceeding |
| Net Promoter Score | 61 | +7 points | 50+ | ✓ Strong |

### Charts & Visualizations

**Chart 1: Revenue by Domain (Last 6 Months)**
- Line chart showing Credit, Payments, and Savings revenue trends
- Credit: $450k → $850k (steady growth, +89%)
- Payments: $780k → $1.52M (sharp acceleration, +95%)
- Savings: $120k → $680k (exponential growth, +467%)
- **Insight:** Payments & Savings are becoming major revenue drivers

**Chart 2: Customer Growth Trend**
- Bar chart showing monthly active customer count
- Growth pattern: 18.5k → 45.2k over 6 months (+145%)
- Acceleration visible starting Month 4
- **Insight:** Product adoption accelerating; may indicate successful marketing or product-market fit

### How to Use This Page

**Daily Use (5 min):**
1. Scan the 8 KPI cards for any red flags
2. If approval rate < 70% or default rate > 3%, drill into domain dashboards
3. Note MoM/QoQ changes for executive standup

**Weekly Reporting (10 min):**
1. Export KPI cards as PDF (Download button, bottom)
2. Compare to prior week (set date filter to previous week)
3. Highlight 2–3 key insights for board deck

**Quarterly Board Reporting (20 min):**
1. Set date range to quarter (e.g., "Q2 2024: Apr 1 – Jun 30")
2. Download CSV of all metrics
3. Cross-reference with KPI Dictionary for definitions
4. Include context: "Revenue +18% MoM driven by Payments product launch"

### Metric Definitions

All metrics on this page are **CERTIFIED** and defined in the KPI Dictionary:
- **Total Revenue:** GAAP revenue (owner: CFO)
- **Active Customers:** Transaction activity in current month (owner: BI Lead)
- **Credit Originations:** Total funded loans (owner: CCO)
- **Approval Rate:** Completed decisions only (owner: CCO)
- **Payment Volume:** Gross value of settled transactions (owner: VP Payments)
- **Default Rate:** % of active loans 30+ DPD (owner: CCO)
- **AUM:** Total savings balances (owner: Head Savings)
- **NPS:** Promoters - Detractors (owner: VP Product)

### Common Questions

**Q: Why is my approval rate (68%) different from the dashboard (73%)?**  
A: Dashboard uses certified definition (completed decisions only, excludes abandoned applications). See "Metric Conflicts" page.

**Q: Can I export this page?**  
A: Yes. Click Download → CSV. Limit: 10,000 rows.

**Q: Why does revenue sometimes jump or drop?**  
A: Dashboard uses GAAP revenue (accrual basis), which includes timing of invoice recognition. Finance reconciles daily.

---

## Page 3: Credit & Lending Domain Dashboard

**Purpose:** Deep dive into credit product performance, approval funnel, portfolio quality, and risk  
**Audience:** Chief Credit Officer, Underwriting team, Risk & Compliance, Finance  
**Refresh Rate:** Real-time (applications), Hourly (balances), Daily (delinquency & risk)  
**Time to Review:** 15 minutes

### Key Metrics (4 Cards)

| Metric | Value | Benchmark | Status |
|--------|-------|-----------|--------|
| Total Originations | $18.5M | $17.5M | ✓ +5.7% vs target |
| Active Loans | 12,847 | 12,500 | ✓ Good |
| 30+ Days Past Due (DPD) | 3.8% | <3.5% | ⚠ Above threshold |
| Average Loan Size | $1,439 | $1,400 | ✓ Consistent |

### Chart 1: Approval Funnel (30-Day Window)

Shows the loan application lifecycle from initial submission through funding.

```
Applications: 18,500 (100%)
    ↓ 73.2% approved
Approved: 13,542 (73.2%)
    ↓ 94.8% funded
Funded: 12,847 (69.4% of applications)
```

**Interpretation:**
- **Applications:** Volume of new requests
- **Approval Rate:** 73.2% = applications approved (target: 70–75%)
- **Funding Rate:** 94.8% = approved loans that successfully fund (target: >95%)
  - Drop-off < 95% indicates: account verification issues, customer cancellations, or funding delays
- **Overall Conversion:** 69.4% of applications → funded (key business metric)

**Filters Available:**
- Loan Purpose (auto, home, debt consolidation, other)
- Risk Tier (low, moderate, high, very high)
- Date Range (daily, weekly, monthly)

**Actions:**
- If approval rate < 70%: Review underwriting policy changes
- If funding rate < 94%: Investigate funding delays with treasury team
- If purpose-specific approval rates vary >10%: Audit underwriting consistency

---

### Chart 2: Portfolio Risk Distribution

Histogram showing credit risk scores across the active loan book.

| Risk Tier | Count | % of Portfolio | Typical | Variance |
|-----------|-------|---------------|---------|---------| 
| Low (0–300) | 4,200 | 32.7% | 30–35% | ✓ Good |
| Moderate (300–600) | 5,100 | 39.6% | 35–40% | ✓ Good |
| High (600–750) | 2,300 | 17.9% | 15–20% | ✓ Good |
| Very High (750+) | 1,247 | 9.7% | 5–10% | ⚠ Slightly High |

**Interpretation:**
- **Very High >12%:** Risk model may be drifting; schedule retraining
- **Low <25%:** May indicate overly aggressive lending
- **Healthy distribution:** 30-40-18-9 (Low-Moderate-High-VeryHigh)

**Risk Score Model:**
- Version: v2.1 (updated Q2 2024)
- Inputs: Credit score, income, loan-to-value, payment history
- Refresh: Daily, real-time scoring for new applications

---

### Chart 3: Default Rates by Origination Cohort

Tracks cumulative default probability as loans age, segmented by origination month.

**Cohort Performance:**
- **Jan 2024:** 0.8% at 6 months (lowest risk)
- **Feb 2024:** 1.2% at 5 months
- **Mar 2024:** 1.8% at 4 months
- **Apr 2024:** 2.2% at 3 months
- **May 2024:** 2.4% at 2 months
- **Jun 2024:** 2.1% at 1 month (most recent)

**Typical Pattern:**
- Month 0–1: Very low default (pre-seasoning)
- Month 1–3: Rapid rise (early payment issues surface)
- Month 3–6: Plateau (stable delinquency)

**What to Watch:**
- If new cohort default rate > 0.5% above historical: Investigate underwriting quality
- If mature cohort curves up unexpectedly: May indicate economic stress in borrower base
- Compare Feb vs Mar: Mar showing higher early defaults (potential underwriting drift)

**Actions:**
- If cohort variance > 0.5%: Audit applications & triggers
- If mature cohorts trending up: Escalate to CFO for reserve adjustments

---

### Summary Statistics Panel

**Delinquency Breakdown**
- Current (0 DPD): 12,287 loans (95.6%)
- 1–29 DPD: 460 loans (3.6%)
- 30–59 DPD: 73 loans (0.6%)
- 60+ DPD: 27 loans (0.2%)

**Funding Status**
- Actively Funded: 12,847 loans
- Pre-Funding (Approved): 695 loans
- Closed/Payoff: 1,242 loans (historical)

### How to Use This Page

**Weekly Risk Review (10 min):**
1. Check **30+ DPD Rate** card
2. If >3.5%, click funnel chart to isolate by loan purpose
3. Check **Risk Score Distribution** for concentration
4. If Very High >12%, flag for model retraining

**Monthly Cohort Analysis (20 min):**
1. Filter to origination cohort (e.g., "Mar 2024")
2. Review cohort default curve
3. Compare to prior month (switch filter, take screenshot)
4. Check if variance within ±0.5% of historical average
5. Escalate if variance > 0.5% to CCO

**Board Reporting (15 min):**
1. Set date range to quarter end
2. Download funnel & risk data as CSV
3. Build dashboard: approval rate, default rate, risk distribution
4. Add context: "Approval rates stable at 73.2%, portfolio risk well-distributed"

### Key Insights (Last 30 Days)

- ✓ Approval rate stable at 73.2% (within target 70–75%)
- ⚠ 30+ DPD elevated to 3.8% (above 3.5% benchmark) → escalated to Collections
- ✓ Credit originations tracking +31% YoY, exceeding revenue target
- ⚠ Very high risk loans 9.7% (slightly above 5–10% expected range) → monitoring

---

## Page 4: Metric Conflict Resolution

**Purpose:** Transparency on metric disagreements and certified definitions  
**Audience:** Finance, Product, Credit, BI team  
**Refresh Rate:** As-needed (metrics are stable; dashboard updates when definitions change)  
**Time to Review:** 10 minutes

### Background

Three critical metrics had conflicting definitions across Finance, Product, and Credit teams. This page shows each conflict, the competing definitions, and the certified resolution.

---

### Conflict 1: Active Customers

**The Problem:**
- Finance counted customers generating revenue = 41,200
- Product counted app logins in 90 days = 52,840
- 28% difference; executives couldn't trust the number

**Competing Definitions:**

❌ **Finance Definition:** Customers with revenue in current month  
- Result: 41,200
- Issue: Misses engaged non-paying users; too narrow

❌ **Product Definition:** Customers with app login in last 90 days  
- Result: 52,840
- Issue: Counts inactive users; too broad for revenue reports

✓ **Certified Definition (BI):** Customers with transaction activity (send/receive/view) in current month  
- Result: 45,230
- Source: `transactions.processed_at`
- Owner: BI Lead
- Advantage: Balances engagement + currency; acceptable to both teams

**Resolution Agreement:**
- All executive reporting uses **45,230** (certified)
- Product reports "engaged users (90-day)" separately for product analytics
- Finance reports "revenue-generating customers" separately for internal tracking
- BI dashboard auto-flags >2% discrepancy and sends Slack alert

**Monthly Reconciliation:** Auto-report showing three definitions side-by-side, signed off by BI Lead

---

### Conflict 2: Total Revenue

**The Problem:**
- Finance reported GAAP revenue (accrual basis) = $2.67M
- Payments team reported cash received only = $2.41M
- CFO needed one number for board reporting

**Competing Definitions:**

❌ **Finance (GAAP Accrual):** Revenue recognized per GL policy  
- Result: $2.67M
- Issue: Includes accruals not yet collected; overstates cash position

❌ **Payments Team (Cash Only):** Cash actually received in settlements  
- Result: $2.41M
- Issue: Undercounts accrued but legitimate revenue; doesn't match GAAP

✓ **Certified Definition (CFO):** GAAP revenue + recognized accruals (GL source of truth)  
- Result: $2.47M
- Source: `revenue.transactions` + `accruals`
- Owner: CFO
- Advantage: GAAP-compliant; reflects both cash & accruals; external audit approves

**Resolution Agreement:**
- All executive reporting & board decks use **$2.47M** (GAAP + accruals)
- Payments team reports "cash collected" dashboard separately
- Finance & Payments reconcile daily; any >$50k variance escalated to CFO
- Quarterly external audit confirms GAAP compliance

**GL Reconciliation:** Daily automated check; Slack alert if discrepancy >1%

---

### Conflict 3: Credit Approval Rate

**The Problem:**
- Credit team reported 68.4% (excludes abandoned applications)
- Finance reported 63.7% (includes abandoned applications)
- Board was confused which rate to use for performance management

**Competing Definitions:**

❌ **Credit Team:** Approved / (Approved + Declined), excludes abandoned  
- Result: 68.4%
- Issue: Only reflects completed decisions; abandoned apps are legitimate failures

❌ **Finance:** Approved / Total Applications, includes abandoned  
- Result: 63.7%
- Issue: Conflates underwriting quality (approved %) with app abandonment (user behavior)

✓ **Certified Definition (CCO):** Approved / (Approved + Declined + Referred) — completed decisions only  
- Result: 73.2%
- Source: `credit.applications WHERE status IN ('approved', 'declined', 'referred')`
- Owner: Chief Credit Officer
- Advantage: Focuses on underwriting quality, not user behavior; cleaner KPI

**Resolution Agreement:**
- Credit performance = **73.2%** (CCO metric; used for incentives & targets)
- Conversion rate (approved / total) = **63.7%** (Finance metric; for board context)
- "Completion rate" (non-abandoned / total) = **~88%** (Product metric; for funnel analysis)
- All three metrics visible in dashboard; clearly labeled to avoid confusion
- Credit team & Finance reconcile daily; >2% variance escalated to CFO

**Policy Documentation:** Updated in KPI Dictionary; all new analysts trained on distinction

---

### Why This Page Matters

✓ **Transparency:** Teams can see exactly how conflicts were resolved  
✓ **Trust:** One source of truth; eliminates "my metric is right" debates  
✓ **Compliance:** External auditors & regulators see documented reconciliation  
✓ **Efficiency:** New team members learn the definitions once, never argue again  

### How to Use This Page

**If someone cites a different number:**
1. Ask: "Which definition are you using?" (points them to this page)
2. They'll see the certified definition is actually **X**
3. Both of you now aligned, no need to re-reconcile

**For audit & compliance:**
1. Show this page to external auditors
2. Demonstrates deliberate metric governance & documented resolution
3. Satisfies audit trail requirements

**For quarterly calibration:**
1. Review this page with domain owners
2. Confirm definitions still make sense
3. Update if business context changed (e.g., new product, new accounting rule)

---

## Page 5: KPI Dictionary

**Purpose:** Comprehensive metric reference for all 15+ metrics  
**Audience:** Data analysts, finance, BI team (anyone citing a metric)  
**Refresh Rate:** Static (updates quarterly when metrics are recertified)  
**Time to Review:** 20 minutes to skim, 60 minutes to fully understand

### Table Overview

All 15 metrics displayed in interactive table with the following columns:

| Column | Example | Purpose |
|--------|---------|---------|
| **Metric Name** | Approval Rate | What it's called in reporting |
| **Domain** | Credit | Which team owns it (Credit, Finance, Product, Payments, Marketing, Savings) |
| **Business Definition** | Approved / (Approved + Declined + Referred) | Plain-English definition |
| **Formula** | `COUNT(approved) / COUNT(approved + declined + referred)` | SQL/calculation logic |
| **Data Source** | `credit.applications` | Underlying table |
| **Refresh Cadence** | Real-time | How often data updates |
| **Status** | ✓ CERTIFIED | Whether metric is approved for executive reporting |

### All 15 Metrics

**CERTIFIED METRICS (Ready for executive reporting):**

1. **Total Revenue** — Finance — GAAP accrual basis → $2.47M
2. **Active Customers** — Product/Finance — Transaction activity in current month → 45,230
3. **Credit Originations** — Credit — Total funded loans → $18.5M
4. **Approval Rate** — Credit — Completed decisions only → 73.2%
5. **Payment Volume** — Payments — Gross settled transactions → $142M
6. **Default Rate (30+ DPD)** — Credit — % active loans 30+ days late → 2.1%
7. **AUM (Savings)** — Savings — Assets under management → $67.3M
8. **Net Promoter Score** — Product — Promoters minus Detractors → 61
9. **Approval-to-Funding Ratio** — Credit — Approved loans that fund → 94.8%
10. **Loan-to-Value Ratio** — Credit — Average LTV for originations → 72.5%
11. **Charge-Off Rate** — Credit — % originations written off → 2.1%
12. **Average Loan Size** — Credit — Mean loan amount → $1,439
13. **Risk Score Distribution** — Credit — Histogram by risk tier → (30/40/18/10%)
14. **Customer Retention Rate** — Product — 30-day cohort retention → 82%
15. **Transaction Decline Rate** — Payments — % payment attempts failed → 1.2%

**EXPLORATORY METRICS (Not yet certified; in development):**

- **Customer Acquisition Cost** — Marketing — $85 per new customer (attribution model TBD)
- **Churn Rate** — Product — Monthly customer loss rate (definition in flux)
- **Portfolio Loan-to-Deposit Ratio** — Finance — Lending vs. savings balance (new metric)

### How to Use This Page

**Scenario 1: "I want to cite a metric in a report"**
1. Search table for metric name (e.g., "approval rate")
2. Confirm business definition matches your intent
3. Check certification status (must be ✓ CERTIFIED for executive reporting)
4. Copy formula if building a query
5. Note refresh frequency (is data fresh enough for your use case?)

**Scenario 2: "Finance uses a different number than the dashboard"**
1. Search table for metric name
2. Compare Finance's formula to certified formula
3. Click "Conflicts" link to see documented reconciliation
4. Share certified definition with Finance

**Scenario 3: "I'm building a new dashboard"**
1. Find relevant metrics in table
2. Copy data sources & formulas
3. Filter for CERTIFIED metrics only (avoid exploratory)
4. Contact data engineer with your list to implement

**Scenario 4: "I need to export all metric definitions for audit"**
1. Click Download (bottom) → CSV
2. File includes all 15 metrics + formulas + owners
3. Send to external auditor as metric governance documentation

### Metric Status Legend

| Badge | Meaning | Use It? |
|-------|---------|---------|
| ✓ **CERTIFIED** | Approved by domain owner; audited; safe for executive reports | Yes, always use |
| ⚠ **EXPLORATORY** | In development; definition may change; not yet audited | No, use for analysis only |

### Key Takeaways

**For Analysts:**
- Before citing any metric, check this table
- Only report CERTIFIED metrics to executives
- Use EXPLORATORY metrics for internal analysis only

**For Finance:**
- All financial metrics (Revenue, CAC, Retention) are jointly certified with CFO
- Monthly reconciliation reviews ensure continued accuracy
- Quarterly external audit validates GAAP compliance

**For Credit:**
- All credit metrics (Approval Rate, Default Rate, LTV) certified by Chief Credit Officer
- Risk metrics used for regulatory filings (OCC, FDIC)
- Monthly validation against loan-level data

**For Data Teams:**
- Use formulas as templates for your own queries
- Data sources point to canonical tables (no manual spreadsheets)
- Alert `#bi-support` if you find discrepancies

---

## Navigating Between Pages

**Quick Links (Tab Bar):**
- **Landing** → Access info, datasets, SLAs
- **Executive** → 8 KPI cards + 2 trend charts (5-10 min check-in)
- **Credit** → Approval funnel, portfolio risk, cohort analysis (15 min deep dive)
- **Conflicts** → Metric reconciliations & certified definitions (troubleshooting)
- **Dictionary** → All 15 metrics + formulas (reference guide)

**Suggested User Journeys:**

**First-Time User (20 min):**
1. Start on Landing page (understand SLAs & access)
2. Review Executive page (see 8 key metrics)
3. Skim Conflicts page (understand metric definitions)
4. Bookmark Dictionary for later reference

**Daily Executive (5 min):**
1. Go to Executive page
2. Scan 8 KPI cards for red flags
3. If issue detected, drill into Credit page

**Weekly Credit Review (15 min):**
1. Start on Credit page
2. Check approval rate & funnel
3. Review risk distribution
4. Scan cohort analysis for anomalies

**Monthly Finance Review (20 min):**
1. Go to Executive page
2. Download KPI CSV (for board deck)
3. Check Conflicts page for metric reconciliation
4. Compare to prior month (date filter)

**Troubleshooting (10 min):**
1. Go to Conflicts page if metrics don't match
2. Check Dictionary if formula questions
3. Review Landing page for SLAs & escalation
4. Email `bi-team@company.com` if still unsure

---

## Metric Definitions (Certified)

### Active Customers (Finance, Product, Credit)
**Definition:** Customers with transaction activity in current month  
**Formula:** `COUNT(DISTINCT user_id WHERE transaction_date >= CURRENT_MONTH_START)`  
**Source:** `transactions.processed_at`  
**Owner:** BI Lead  
**Refresh:** Daily  
**Status:** CERTIFIED  

### Credit Originations
**Definition:** Total funded loan amount in period  
**Formula:** `SUM(loan_amount) WHERE status = 'funded'`  
**Source:** `loans.originations`  
**Owner:** Chief Credit Officer  
**Refresh:** Daily  
**Status:** CERTIFIED  

### Approval Rate
**Definition:** Approved / (Approved + Declined + Referred) — completed decisions only  
**Formula:** `approved_count / (approved_count + declined_count + referred_count)`  
**Source:** `credit.applications`  
**Owner:** Chief Credit Officer  
**Refresh:** Real-time  
**Status:** CERTIFIED  

### Default Rate (30+ DPD)
**Definition:** % of active loans with 30+ days past due  
**Formula:** `dpd_30plus_count / active_loans`  
**Source:** `credit.arrears`  
**Owner:** Chief Credit Officer  
**Refresh:** Daily  
**Status:** CERTIFIED  

### Charge-Off Rate (180+ DPD)
**Definition:** % of originated loans written off as loss  
**Formula:** `chargeoff_count / total_originations`  
**Source:** `credit.chargeoffs`  
**Owner:** Chief Credit Officer  
**Refresh:** Monthly  
**Status:** CERTIFIED  

---

## How to Access

1. **Public View (Read-Only)**  
   No authentication required. [Open dashboard](https://public.tableau.com/views/MalBankAI/CreditLending?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

2. **Interactive Filters & Drill-Down**
   - **Date Range:** Select custom start/end dates
   - **Loan Purpose:** Filter by use case (auto, home, consolidation, other)
   - **Risk Tier:** Isolate specific risk bands
   - **Cohort:** Drill into origination vintage

3. **Export Data**  
   - Click **Download** (bottom toolbar) → Choose CSV or PDF
   - Limit: 10,000 rows per export
   - For larger datasets, contact BI team

4. **Tableau Server Access (Internal Only)**  
   Request access via `bi-team@company.com` with your domain  
   SLA: 2 business days

---

## Common Use Cases & How-To

### Use Case 1: Monitor Weekly Delinquency
1. Open dashboard → Set date filter to "Last 7 Days"
2. Check **30+ DPD Rate** card
3. If >3.5%, click into risk distribution to identify high-risk cohorts
4. Route to collections team

### Use Case 2: Benchmark Approval Rates by Product
1. Navigate to **Approval Funnel by Loan Purpose**
2. Compare approval rates across loan types
3. Investigate outliers (>10% variance from peer)
4. Escalate to underwriting for policy review

### Use Case 3: Perform Cohort Analysis
1. Select origination cohort from date range (e.g., "Jan 2024")
2. Flip to **Default Rates by Cohort** sheet
3. Check 6-month performance vs. historical average
4. If trend is positive (lower default), retraining improved model
5. If negative (higher default), trigger underwriting audit

### Use Case 4: Export for Board Reporting
1. Set date range to quarter end (e.g., "Q2 2024")
2. Click **Download** → CSV
3. Paste into board deck; cross-reference with KPI Dictionary for definitions
4. Highlight exceptions (approval rate, default rate) with context

---

## Data Refresh Cadence

| Component | Frequency | Last Refresh | Next Refresh |
|-----------|-----------|--------------|--------------|
| Applications & Approvals | Real-time | [Auto] | [Continuous] |
| Funded Loans & Balances | Hourly | [Timestamp] | +1 hour |
| Delinquency & Arrears | Daily @ 6 AM PT | [Date] | +24 hours |
| Risk Scores | Daily @ 6 AM PT | [Date] | +24 hours |
| Default Cohort Analysis | Monthly @ Month-end | [Date] | [Next month-end] |

---

## Troubleshooting

### Dashboard Won't Load
- Clear browser cache: `Ctrl+Shift+Delete` (Windows) / `Cmd+Shift+Delete` (Mac)
- Use Chrome or Firefox (not Safari — known issues)
- Check Tableau Public status: https://trust.tableau.com

### Numbers Don't Match Reports
- Confirm metric definition in **KPI Dictionary** (linked in main README)
- Check date range filters (common source of discrepancy)
- Verify timezone (all timestamps are PT)
- Email `bi-team@company.com` with screenshot

### Can't Export Data
- Maximum export: 10,000 rows
- For larger requests, contact BI team with your query
- SLA: 2 business days

---

## Metric Conflicts & Resolutions

Three critical metrics had conflicting definitions across Finance, Product, and Credit:

### 1. **Active Customers**
- **Finance:** Revenue-generating in current month → 41,200
- **Product:** App login in 90 days → 52,840  
- **Certified Definition:** Transaction activity in current month → **45,230** (Owner: BI Lead)

### 2. **Total Revenue**
- **Finance (GAAP):** Accrual basis → $2.67M
- **Payments:** Cash received only → $2.41M  
- **Certified Definition:** GAAP + recognized accruals → **$2.47M** (Owner: CFO)

### 3. **Approval Rate**
- **Credit:** Approved / (Approved + Declined), excludes abandoned → 68.4%
- **Finance:** Approved / Total, includes abandoned → 63.7%  
- **Certified Definition:** Completed decisions only → **73.2%** (Owner: Chief Credit Officer)

**Resolution:** Finance, Product, and Credit teams reconcile daily. Certified definitions are source of truth for all executive reporting.

---

## Data Dictionary & Governance

For comprehensive definitions of all 15+ enterprise metrics, see the **[KPI Dictionary](./KPI_DICTIONARY.md)** in this repo.

Each metric includes:
- Business definition
- Formula & calculation logic
- Data source & table lineage
- Refresh frequency & SLA
- Certified vs. exploratory status
- Domain owner contact

---

## Dependencies & Tech Stack

| Component | Version | Purpose |
|-----------|---------|---------|
| Tableau Public | Latest | Dashboard hosting & visualization |
| PostgreSQL | 13+ | Source data warehouse |
| Python (dbt) | 3.9+ | Data transformation & lineage |
| Airflow | 2.0+ | ETL orchestration & scheduling |
| Slack | Integration | Alert notifications (>3% DPD, model drift) |

---

## Contact & Support

| Role | Name | Email | Slack |
|------|------|-------|-------|
| Chief Credit Officer | [Name] | [Email] | @[Slack Handle] |
| BI Lead | [Name] | bi-team@company.com | @bi-team |
| Data Engineer | [Name] | [Email] | @[Slack Handle] |

**Request Access:** Email `bi-team@company.com` with your domain and use case  
**Report Bug:** Open an issue in this repo or Slack `#bi-support`  
**Response SLA:** 2 hours for critical (e.g., data discrepancy), 24 hours for standard requests

---

## Key Insights (Last 30 Days)

- ✓ Approval rate stable at 73.2% (within target band 70–75%)
- ⚠ 30+ DPD elevated to 3.8% (above 3.5% benchmark) → escalated to collections
- ✓ Credit originations tracking +31% YoY, exceeding revenue target
- ⚠ Very high risk loans increased 0.8% — model retraining scheduled for Q3

---

## Changelog

| Date | Change | Owner |
|------|--------|-------|
| [Latest] | Added cohort analysis by risk tier | BI Lead |
| [Date] | Updated approval rates to real-time refresh | Data Eng |
| [Date] | Added default curve by origination vintage | Credit Ops |
| [Date] | Launched public Tableau link | BI Lead |

---

## FAQ

**Q: Why is my approval rate different from what I see locally?**  
A: Dashboard uses certified definition (completed decisions only). Your system may include abandoned applications. See "Metric Conflicts" section above.

**Q: Can I download historical data?**  
A: Yes, up to 10,000 rows per export. For bulk historical exports, email `bi-team@company.com` with date range.

**Q: How often is this dashboard updated?**  
A: Real-time for approvals/applications; hourly for balances; daily for delinquency. See "Data Refresh Cadence" table above.

**Q: Who owns the data in this dashboard?**  
A: Chief Credit Officer owns all credit metrics. Finance owns revenue. BI Lead owns data pipeline & definitions.

**Q: Is there a private/authenticated version?**  
A: Yes. Tableau Server users can access `CreditLending_Internal` with row-level security. Request access via BI team.

---

## License

This dashboard is proprietary to MalBankAI. Access is restricted to authorized employees and contractors.

---

## Related Documentation

- **[KPI Dictionary](./KPI_DICTIONARY.md)** — Comprehensive metric definitions
- **[BI Platform Runbook](./BI_RUNBOOK.md)** — How to request data, access SLAs
- **[Data Lineage](./DATA_LINEAGE.md)** — Table/column-level traceability
- **[Tableau Public Profile](https://public.tableau.com/app/profile/gous.mahammad)** — All MalBankAI dashboards

---

## Version

**Version:** 1.0  
**Status:** Production  


