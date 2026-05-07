# Executive Sales Dashboard

An interactive browser-based sales analytics dashboard covering classic vehicle orders across 2003–2005 — no installation, no account, no server required.

**[Live Dashboard →](https://brian-pollard.github.io/Executive-Sales-Dashboard/sales-dashboard.html)**

---

## What It Does

Select a year (or view all) to explore $10M in sales across 307 orders, 19 countries, and 4 global territories. All charts and KPIs update instantly from the year filter.

- **KPI Row:** Total revenue, order count, units sold, and average order value — with year-over-year % change when a single year is selected
- **8 interactive charts:** Revenue trend, territory mix, deal size mix, product line performance, top countries, order status, quarterly view, and year-over-year comparison
- **Sortable customer table:** Top 10 customers with revenue bar, order count, and average order value — click any column header to re-sort

---

## Data Coverage

| Period | Orders | Revenue |
|--------|--------|---------|
| 2003 | 104 | $3.52M |
| 2004 | 144 | $4.72M |
| 2005 (partial, through May) | 59 | $1.79M |
| **Total** | **307** | **$10.03M** |

**Territories:** North America, EMEA, APAC, Japan

**Product lines:** Classic Cars, Vintage Cars, Motorcycles, Trucks and Buses, Planes, Ships, Trains

---

## Key Findings

- Classic Cars drive 39% of total revenue ($3.9M), more than double the next category
- EMEA is the largest territory at 49.6% of revenue; NA is second at 38.4%
- Q4 spikes consistently — November is the highest month in both 2003 and 2004
- Euro Shopping Channel is the top customer at $912K across 26 orders (3 full years)
- 2005 revenue pace is on track to exceed 2004 annualized, based on partial-year data

---

## Implementation

Single self-contained HTML file — no build step, no external JS dependencies beyond Chart.js (CDN), no server required. Open `docs/sales-dashboard.html` directly in any browser.

All data is pre-aggregated and embedded directly in the HTML. The source CSV is not required to run the dashboard.
