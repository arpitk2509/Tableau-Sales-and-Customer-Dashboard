# Commercial Sales & Customer Value Optimization Tracker

## 📌 Project Overview & Intent
This project was built to solve a classic corporate visibility problem: high-level executive revenue targets often lose visibility into individual client account health. To fix this, I developed a two-tiered Tableau analytics suite that connects macro sales performance directly with granular customer profitability metrics. 

By tracking Year-over-Year (YoY) shifts and isolating margin leakage, this workbook gives sales leaders the exact insights they need to protect top-tier accounts and stop bleeding cash on low-margin products.

---

## 📈 Deep-Dive Breakdown

### 1. Macro Sales & Margin Performance
*This layer isolates overall revenue health, seasonal pacing, and product line viability.*

* **Core Operational Tracking:** Monitors **Sales ($733K)**, **Profits ($93K)**, and **Volume (12K units)** alongside live YoY performance baselines.
* **Automated Run-Chart Anomalies:** Built automated indicators into the monthly trend lines to instantly flag seasonal peaks (Blue) and valleys (Orange). This cuts down time-to-insight for stakeholders tracking revenue consistency.
* **The "Volume vs. Value" Trap:** Used a dual-axis visual matrix to spot category-level profit leakage. A key finding here shows that while *Tables* generate massive top-line sales velocity, they operate at a severe net loss. Conversely, *Copiers* represent a smaller but highly lucrative margin anchor.
* **Weekly Performance Baselines:** Integrated control charts tracking weekly variance against baseline averages ($1,340 for sales, $142 for profit) to dynamically isolate weeks that underperformed or surged past expectations.

### 2. Client Demographics & Account Ledger
*This layer shifts focus to transactional frequency, customer value distribution, and high-risk client tiers.*

* **Portfolio Health Metrics:** Keeps pulse on active account distribution, highlighting an average customer spend baseline of **$1,058** across **1,687 discrete orders**.
* **Order Frequency Skew:** Designed a frequency distribution to track order volume across the customer base. The data reveals a heavy right-skew, meaning the vast majority of the portfolio relies on 1 to 3 transactional touches—highlighting a critical focus area for customer retention and lifetime value expansion.
* **The High-Value Ledger:** Built a dynamic, real-time leaderboard isolating the business's most critical assets. This highlights elite-tier accounts like *Raymond Buch* ($6.7k profit) and *Hunter Lopez* ($5k profit) so accounts teams can prioritize relationship management and mitigate churn risks where the stakes are highest.

---

## 🛠️ Key Technical Challenges Addressed

* **Dynamic Cohort Logic:** Authored the underlying calculated fields to compute exact Current Year (CY) vs. Prior Year (PY) metrics on the fly, eliminating the need for hardcoded dates and keeping the data model completely automated.
* **Dual-Axis Synchronization:** Resolved a critical layout challenge where independent conditional thresholds (the peak/valley dots) mismatched with standard sales curves. Handled this by standardizing and forcing cross-axis data type parity.
* **Clean UI/UX Design:** Prioritized user experience by stripping away default gridline clutter, implementing a strict 3-color corporate palette, and organizing cross-filters into a functional hidden container layout to maximize screen real estate.

---

## 🔗 Live Interactive Link
The interactive, fully functional version of this workbook is hosted live on Tableau Public. You can test the global parameters, filter by product categories, and explore the dynamic tooltips here:

👉 **[Launch Interactive Tableau Dashboard](https://public.tableau.com/app/profile/arpit.kumar8685/viz/SalesandCustomerDashboard_17815163510030/CustomerDashboard)**
