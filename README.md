# Blinkit Sales Performance & Outlet Optimization Analytics

## 📌 Project Overview
This business intelligence project delivers a comprehensive, end-to-end data analytics solution inspired by the **Blinkit** (Quick-Commerce) retail ecosystem. Operating in a high-velocity delivery market requires highly optimized inventory management and swift outlet execution. 

This Power BI dashboard processes raw transactional logs, fulfillment distribution channels, and localized outlet configurations to surface actionable insights. The project uncovers critical patterns in consumer buying behaviors, maps multi-tier outlet performance, evaluates service quality scores, and identifies opportunities to maximize gross merchandising value (GMV).

---

## 🛠️ Tech Stack & Technical Competencies
* **BI Platform:** Power BI Desktop & Power BI Service
* **Data Transformation (ETL):** Power Query (Advanced column parsing, data type alignment, handling structural missingness)
* **Data Modeling:** Optimized Star Schema layout establishing direct relationships between Fact Ledger and Dimension tables
* **Analytical Expressions:** Advanced Data Analysis Expressions (DAX) for dynamic matrix evaluations, time intelligence, and operational tracking

---

## 📊 Core Performance Metrics & Features
* **Top-Line Sales & Revenue Metrics:** Consolidated analysis tracking Total Revenue, Average Ticket Size (AOV), Total Order Volume, and Average Customer Satisfaction Ratings.
* **Granular Product Segmentation:** Evaluates item sales velocity across distinct fast-moving categories (Snacks, Frozen Foods, Dairy, Produce) and breaks them down further by low-fat vs. regular dietary variations.
* **Outlet Infrastructure Optimization:** Compares localized dark stores across multiple facets—establishment maturity tier, physical size classifications (Small, Medium, High), and geographical operational zones.
* **Interactive Filtering Matrix:** Dynamic cross-filtering options using customized slicers for dynamic region, category, and temporal scoping.

---

## 🗄️ Architectural Data Schema & DAX Metrics
The semantic data structure leverages an optimized architecture built for low-latency visual rendering and responsive cross-filtering.

### Key DAX Calculated Measures Implemented:
* **Total Sales Volume:**
  $$Total\_Sales = SUM(Fact\_Sales[Sales\_Amount])$$
* **Average Order Value (AOV):**
  $$Average\_Order\_Value = DIVIDE([Total\_Sales], COUNT(Fact\_Sales[Order\_ID]))$$
* **Item Rating Distribution:**
  $$Average\_Rating = AVERAGE(Fact\_Sales[Customer\_Rating])$$

---

## 🌐 Live Dashboard Preview
Experience the fully interactive, multi-page quick-commerce analytics workspace directly inside your browser below:

<div align="center">
  <iframe 
    title="Blinkit Quick-Commerce Sales Analytics Ledger" 
    width="100%" 
    height="600" 
    src="https://app.powerbi.com/view?r=eyJrIjoiYmNkM2ZjMGMtN2MyMy00YzZlLTg5NzktNTViNzA1ODJjMTQ4IiwidCI6ImE4ZjNjYzcyLTZiYTAtNDJlNy1hNjU1LTI3NTA2ZDBiOGI5NCJ9&pageName=ReportSection" 
    frameborder="0" 
    allowFullScreen="true">
  </iframe>
</div>

---

## 📈 Strategic Business Recommendations Derived
1. **Inventory Alignment:** Accelerate stock allocation for high-velocity item categories within Tier 3 operational setups during documented peak purchasing windows.
2. **Size Optimization:** Replicate the structural shelf blueprints of top-performing Medium-sized quick-commerce outlets across underperforming High-capacity nodes to minimize overhead inefficiencies.
3. **Rating Correlation:** Tie delivery performance workflows and dark store logistics structures closer to low-rating categories to protect high-value customer retention.
