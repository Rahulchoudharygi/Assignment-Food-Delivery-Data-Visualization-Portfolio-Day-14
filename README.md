# Food Delivery Business Performance — Data Visualization Portfolio (Day 14)

This repository contains an exploratory data visualization portfolio built with **Python**, **Matplotlib**, and **Seaborn** using the `Day14_Food_Delivery_Visualization_Dataset.csv`.

---

##  Key Visualizations & Interpretations

### 1. Monthly Revenue & Order Volume Trends (Dual-Axis Line Plot)
* **Insight:** Peak demand occurs in June and December (>₹2.3M monthly gross), while February marks the annual low (~₹1.1M), showing strong seasonal surges around mid-year holidays and year-end festivities.

### 2. Cuisine Performance & Ticket Size (Bar Chart)
* **Insight:** High Average Order Value (AOV) cuisines like **Healthy** (AOV ~₹502) and **Biryani** (AOV ~₹459) generate the highest revenue per batch (~₹73k and ~₹67k), outperforming volume-heavy but low-ticket categories like **Fast Food** (AOV ~₹317).

### 3. Channel Distribution & Rating Quality (Count & Bar Charts)
* **Insight:** The native **Mobile App** handles the largest share of orders and achieves higher customer satisfaction (4.51 / 5.0) compared to third-party **Partner Platforms** (4.38 / 5.0).

### 4. Weather Impact on Delivery Delays & Ratings (Scatter Plot)
* **Insight:** Deliveries during **Rainy** weather average ~38.8 minutes (vs. ~30.0 minutes in clear weather). Order fulfillment exceeding 35 minutes directly depresses customer ratings below 4.3.

### 5. Multi-City Delivery Distributions (Box Plot & Violin Plot)
* **Insight:** Turnaround times remain consistent across cities (~32 min median), while discount allocations remain uniform across weather types, indicating marketing promotions are fixed rather than weather-adaptive.

### 6. Operational Metric Correlation Heatmap
* **Insight:** `Avg_Delivery_Minutes` has a strong inverse correlation ($r = -0.88$) with `Customer_Rating`. Higher ratings directly drive loyalty, sharing a strong positive correlation ($r = 0.82$) with `Repeat_Customer_Percent`.

---

##  Executive Summary & Core Findings

1. **Delivery Speed Governs Retention:** Delivery latency is the single biggest factor hurting customer satisfaction ($r = -0.88$). Faster deliveries directly drive customer retention ($r = 0.82$).
2. **Rainy Weather Friction:** Inclement weather adds ~8.8 minutes to fulfillment, driving customer rating drops.
3. **App Channel Superiority:** First-party app ordering delivers higher margins and customer satisfaction over aggregated partner channels.

---

##  Repository Contents
* `Day14_Food_Delivery_Visualization.ipynb` — Executed Colab notebook with charts and interpretations.
* `Day14_Food_Delivery_Visualization_Dataset.csv` — Dataset file.
