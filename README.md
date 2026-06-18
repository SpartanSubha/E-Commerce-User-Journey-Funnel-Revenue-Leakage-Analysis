# 🛒 E-Commerce User Journey Funnel & Revenue Leakage Analysis
### *From Clicks to Conversions — Finding Where the Money Goes*

> **"Only 1 in 10 visitors actually bought something. This project finds out why — and what it's costing the business."**

---

## 📌 The Business Problem

Every e-commerce business faces the same brutal reality: **most visitors never buy.**

This project digs into the full customer journey — Browse → Add to Cart → Checkout → Purchase — to answer four questions that actually matter to leadership:

| Question | Answer |
|---|---|
| 🔍 Where are customers dropping off? | Cart → Checkout is the biggest leak |
| 💸 How much revenue is being lost? | ₹2.48M in unrealized potential |
| 📱 Which segments underperform? | Mobile users & Organic traffic |
| 🚀 What should the business do next? | Prioritized, effort-mapped recommendations |

---

## 📊 Project At a Glance

| Metric | Value |
|---|---|
| Users Analyzed | 10,000 |
| Overall Conversion Rate | **10.04%** |
| Revenue Generated | **₹277K** |
| Revenue Leakage (Total) | **₹2.48M** |
| Biggest Leakage Stage | **Cart → Checkout (~₹964K)** |
| Worst-Converting Device | **Mobile (9.47%)** |
| Worst-Converting Channel | **Organic (9.45%)** |

---

## 🔗 Project Links

| Resource | Link |
|---|---|
| 📊 Live Dashboard | [View on Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiNzBlZWUwMTMtMDkwMS00ZTZlLWFmNGMtMjk3YTViYjlkNzM0IiwidCI6IjQyZjRkOWVkLTBiYmItNGU5NS1hYmRjLTM5OGM1M2QzNjkxZCJ9) |
| 📁 Download .pbix | [Download File](https://github.com/SpartanSubha/E-Commerce-User-Journey-Funnel-Revenue-Leakage-Analysis/blob/main/E-Commerce%20User%20Journey%20Funnel%20%26%20Leakage%20Analysis.pbix) |
| 📂 Dataset from **kaggle** | [View Dataset](https://github.com/SpartanSubha/E-Commerce-User-Journey-Funnel-Revenue-Leakage-Analysis/blob/main/Funnel_Analysis_Data.csv) |

---

## 🗂️ Dashboard Structure

The Power BI report is structured across **4 purposeful pages**, each answering a distinct business question.

---

### Page 1 — Executive Overview
> *"What's the health of our funnel?"*

Built for leadership. No noise, just signal.

- Overall conversion rate & revenue KPIs
- Stage-by-stage funnel drop-off visualization
- Revenue leakage quantified at each stage
- **Headline finding:** Cart → Checkout alone accounts for ~₹964K in lost revenue

---

### Page 2 — Funnel Leakage Diagnostics
> *"Who's dropping off, and where?"*

Root cause analysis across every dimension.

- **Device breakdown** → Mobile converts at only 9.47%
- **Channel breakdown** → Organic traffic converts at only 9.45%
- **Regional analysis** → South region leads in revenue leakage
- **Product category funnel** → Category-level conversion gaps exposed

---

### Page 3 — Revenue Opportunity Simulator
> *"What's the upside if we fix this?"*

A dynamic what-if simulator for business planning.

- Scenario range: **1% to 20% conversion improvement**
- Outputs: Projected Revenue, Additional Revenue, Additional Purchases
- Executive scenario summary auto-generated via DAX narrative
- Built with **Power BI What-If Parameters**

---

### Page 4 — Strategic Recommendations
> *"What should we actually do about it?"*

Insights converted into prioritized action.

| Priority | Recommendation |
|---|---|
| 🔴 High | Checkout Flow Optimization |
| 🟡 Medium | Mobile UX Improvement |
| 🟡 Medium | Organic Channel Optimization |

Prioritization mapped using an **Impact vs. Effort Matrix**.

---

## 🧮 DAX Measures — What Was Built

<details>
<summary><b>Click to expand full DAX measure list</b></summary>

**Funnel Metrics**
- Browse Users, Add to Cart Users, Checkout Users, Purchasers

**Conversion Metrics**
- Browse → Cart Conversion %
- Cart → Checkout Conversion %
- Checkout → Purchase Conversion %
- Overall Funnel Conversion %

**Leakage Metrics**
- Browse / Cart / Checkout Drop-off %
- Browse / Cart / Checkout Revenue Leakage
- Total Revenue Leakage

**Revenue Metrics**
- Total Revenue
- AOV (Average Order Value)
- Revenue Per Visitor

**Diagnostic Measures**
- Worst Performing Device
- Worst Performing Channel
- Highest Leakage Stage
- Executive Narrative (Dynamic text)

**Simulation Measures**
- Selected Improvement %
- Projected Revenue
- Additional Revenue
- Additional Purchases
- Scenario Summary

</details>

---

## 🔬 Analytical Methodology

```
Descriptive   →  What is currently happening in the funnel?
Diagnostic    →  Why are users dropping off at each stage?
What-If       →  What revenue could be recovered with X% improvement?
Prescriptive  →  What actions should the business take, and in what order?
```

---

## 🏗️ Technical Stack

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-6DB33F?style=for-the-badge)

- **Tool:** Microsoft Power BI
- **Calculation Engine:** DAX (Data Analysis Expressions)
- **Techniques:** Funnel Analysis, Revenue Leakage Modeling, What-If Parameter Analysis, KPI Design, Executive Storytelling

---

## 📐 Assumptions & Limitations

**Assumptions Made:**
- Users progress through funnel stages sequentially
- Revenue leakage = Lost users × AOV
- Recovered cart users are assumed to convert directly into purchases
- Improvement % applied uniformly across all segments

**Known Limitations:**
- No page-level behavior data (scroll depth, time on page)
- No session duration or bounce rate data
- No marketing spend data to compute ROI
- No qualitative abandonment reason data (exit surveys, heatmaps)

> *These limitations represent natural next steps for a more complete analysis — layering in GA4 event data or Hotjar session recordings would significantly deepen diagnostic power.*

---

## 💡 Key Takeaways

- **The funnel isn't broken everywhere — it's broken in one critical place:** Cart to Checkout. Fixing this single stage could recover nearly ₹1M in revenue.
- **Mobile isn't a traffic problem, it's a UX problem.** Users arrive but don't convert — a responsive checkout redesign is likely the highest-leverage mobile fix.
- **Organic traffic underperforms not because of intent, but because of experience.** Landing page relevance and speed are the most probable culprits.
- **A 5% improvement in overall conversion would generate significant additional revenue** — the simulator quantifies exactly how much, making the business case undeniable.

---

## 👤 About the Author

**Subhabrata Sahoo**
Business Analyst | Power BI | SQL | Python

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/subhabrata99)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SpartanSubha)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kitusahoo@gmail.com)

---

*If this project gave you ideas or you'd like to discuss the methodology, feel free to connect on LinkedIn.*
