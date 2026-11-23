# ✈️ Indian Domestic Airlines Analytics — Interactive Power BI Dashboard

### 📌 Project Overview & Business Problem
Aviation data across domestic carriers is often fragmented across separate operational, financial, and route logs—making it difficult for decision-makers to evaluate how fleet efficiency impacts profitability and customer satisfaction. This end-to-end **Power BI Business Intelligence solution** unifies flight operations, passenger demand, revenue, and geographic route performance across six major Indian domestic airlines (**IndiGo, Air India, Air India Express, Akasa Air, SpiceJet, and Alliance Air**) into an interactive, executive-level 4-page dashboard.

---

### 🏗️ Data Modeling & Technical Architecture
* **Star Schema Data Model:** Built around a central transactional fact table (`Fact_Flights`, 1,000+ records) connected via single-directional `1:*` relationships to four normalized dimension tables: `Dim_Airlines`, `Dim_Aircraft`, `Dim_Routes`, and `Dim_Airports`.
* **Advanced DAX Measures:** Engineered dynamic KPIs using iterator and relationship functions (`AVERAGEX`, `RELATED`, `CALCULATE`) so aircraft-level metrics—such as seat capacity, fuel burn per kilometer, and CO₂ emissions per passenger—recalculate accurately based on the active fleet mix of each selected carrier.
* **Offline Base64 Visual Rendering:** Transformed and optimized custom aircraft graphics into Base64-encoded strings inside **Power Query (M)**, enabling instant, offline aircraft switching without external web URL dependencies.
* **Intuitive UX & Navigation:** Designed a cohesive burnt-orange and warm peach visual theme featuring custom button navigation (`Home` $\rightarrow$ `Fleet & KPIs` $\rightarrow$ `Performance & Profit` $\rightarrow$ `Routes & Geo Map`), dynamic pill slicers, and tailored cross-filtering interactions.

---

### 📊 Key Business Insights Uncovered
* **Market & Profit Dominance:** **IndiGo** leads domestic aviation with **141K passengers** and generates **55.67% (₹229M)** of total estimated profit, followed by **Air India** at **34.78% (₹143M)**.
* **Customer Experience Leader:** **Akasa Air** achieves the highest average customer satisfaction rating (**4.1 / 5.0**), outperforming legacy carriers **IndiGo (4.0)** and **Air India (4.0)**.
* **Seasonality & Corridor Demand:** Passenger traffic peaks in **May (21.8K)** and **October (23.8K)** during holiday and festive travel seasons, with **North (72.2K)** and **South (72.1K)** regions—led by the **HYD–DEL** corridor—driving the highest regional volume.

---

### 🛠️ Tools & Skills Demonstrated
`Microsoft Power BI` • `DAX` • `Power Query (M)` • `Star Schema Data Modeling` • `ETL & Data Cleaning` • `Interactive Storytelling`
