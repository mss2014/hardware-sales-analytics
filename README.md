# hardware-sales-analytics
Interactive Power BI report and executive presentation analyzing enterprise hardware performance. It transforms raw transactional records into actionable commercial insights—highlighting brand market share, price tier distributions, and regional logistics velocity with a clean, card-based canvas design.

# Device Sales Performance & Logistics Intelligence Dashboard

## 📋 Project Overview
This project delivers an interactive, end-to-end Business Intelligence solution designed for corporate stakeholders to monitor enterprise sales performance, portfolio diversification, and supply chain logistics. 

Using **Power BI** for data modeling and interactive visualization, and **PowerPoint** for an executive summary, this project transforms raw transactional data from `mobile_sales_data.csv` into actionable strategic insights.

---

## 📊 Deliverables Included
1. **Interactive Power BI Dashboard (`.pbix`)** – A interactive analytical report featuring high-level KPIs, time-series trends, and granular regional/brand breakdowns.
2. **Executive Summary Presentation (`.pptx`)** – A 6-slide deck summarizing the core business insights, supply chain bottlenecks, and strategic growth recommendations for leadership.

---

## 📈 Core Key Performance Indicators (KPIs)
The dashboard tracks 6 critical operational and financial metrics extracted directly from the dataset:
* **Total Revenue:** `$28.28B` – Overall gross sales across the device catalog.
* **Total Units Sold:** `275.69K` – Inventory volume cleared from stock.
* **Average Order Value (AOV):** `$565.58K` – Average revenue generated per processed transaction line item.
* **Total Orders:** `50.00K` – Total volume of invoices/sales tickets processed.
* **Avg Delivery Time:** `30.6 Days` – Average days elapsed from product inward logging to final dispatch.
* **Max Fulfillment Delay:** `60 Days` – Peak logistics bottleneck duration recorded in the supply chain.

---

## 🗂️ Power BI Dashboard Architecture

### **Visual Theme & Styling**
* **Canvas Background:** Minimalist Light Gray (`#F3F4F6`), creating a clean, modern "card-like" separation for standard white chart backgrounds.
* **Navigation:** A vertical left-hand navigation pane using Power BI buttons and bookmarks to seamlessly switch between report views.

### 
* **Top Ribbon:** Three financial KPI summary cards (Total Revenue, Total Units, Average Order Value, Total Orders, Avg Delivery Days, Max Delivery Delay).
* **Global Filters (Slicers):** Dynamic timeline slider (`Inward Date`), category dropdown (`Product`), and region checklists.
* **Time-Series Analysis (Line Chart):** Monthly sales revenue trends mapping performance over time.
* **Portfolio Diversification (Donut Chart):** Hardware split displaying revenue share between Laptops (`$14.19B / 50.17%`) and Mobile Phones (`$14.09B / 49.83%`).
* **Brand Competitive Landscape (Stacked Column Chart):** Top 10 Brands sorted descending by sales volume, displaying the inner product mix (Laptop vs. Mobile) for each OEM using a **Top N Filter**.
* **Geographic Distribution (Clustered Column Chart):** Performance ranked across territories (West, South, North, Central, East).

---

## 💡 Key Strategic Insights for Stakeholders
1. **Perfect Portfolio Balance:** Revenue is split almost exactly 50/50 between Laptops and Mobile Phones, indicating balanced market demand and zero over-reliance on a single hardware category.
2. **Geographic Stability:** Sales are remarkably uniform across the country. The leading territory (**West** at `$5.86B`) and trailing territory (**East** at `$5.59B`) vary by less than 5%.
3. **Logistics Consistency:** Supply chain turnaround time remains steady at a median of ~30.6 days regardless of geography or item price, proving that premium inventory moves at the same velocity as budget devices.

---

## 🚀 Setup & Usage Instructions
1. Download `mobile_sales_data.csv` and the `.pbix` file into the same directory.
2. Open the `.pbix` file in **Power BI Desktop**.
3. If prompted to refresh data sources, navigate to **Home > Transform Data > Data source settings** and update the file path to point to your local copy of `mobile_sales_data.csv`.
4. Click **Refresh** to populate the visuals.

---

This project is licensed under the MIT License.
