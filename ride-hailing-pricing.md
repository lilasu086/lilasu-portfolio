# 🚗 Ride-Hailing Demand & Pricing Insights (Uber & Lyft)

## 📌 Business Problem
Ride-hailing platforms like Uber and Lyft use dynamic pricing to balance supply and demand, incentivize drivers, and maximize revenue. However, understanding the **key factors that influence prices and demand**—such as time of day, location, trip characteristics, and external conditions—is critical for operational strategy, pricing optimization, and customer experience improvement.

## 🎯 Objective
Analyze ride-hailing trip data to explore how demand and pricing vary across different factors (e.g., hours, locations, service type) and extract insights that can help pricing strategy, driver allocation planning, and revenue optimization.

---

## 📍 Data & Analytical Approach

### 📊 Data Overview
- Cleaned rideshare dataset with features such as:
  - Trip timestamps (hour, day, month)
  - Ride source and destination
  - Cab type (Uber/Lyft variants)
  - Price information
  - Weather and temporal attributes  
(*Dataset was preprocessed to remove missing price values and irrelevant columns for improved analysis quality.*) :contentReference[oaicite:0]{index=0}

### 🛠 Analytical Steps

1. **Data Preprocessing**
   - Removed rows with missing price values (~<8% of dataset)
   - Dropped non-informative features to reduce noise  
   - Ensured complete data for demand/pricing analysis :contentReference[oaicite:1]{index=1}

2. **Exploratory Data Analysis (EDA)**
   - Examined price distributions by ride type and time windows  
   - Visualized demand patterns across hours and days of the week  

3. **Demand vs Pricing Analysis**
   - Compared price variations by service type (Uber vs Lyft)
   - Analyzed how demand segments (locations, peak times) affect pricing
---

## 📈 Key Insights

- **Time of Day Effects:** Prices and demand show strong patterns across different hours and commute periods, reflecting predictable peaks in morning and evening usage.  
- **Service Differentiation:** Uber and Lyft demonstrate distinct pricing patterns; price variability often maps to service category and dynamic pricing engines. :contentReference[oaicite:2]{index=2}  
- **Operational Implications:** Pricing differences across regions and hours hint at supply–demand imbalances that could be addressed with targeted driver incentives during less popular times or zones.

---

## 💡 Business Recommendations

- ✨ **Dynamic Driver Allocation:** Align driver incentives with predicted high-demand windows to ensure coverage and reduce wait times.  
- 💰 **Pricing Strategy Optimization:** Identify peak pricing segments and calibrate surge/discount strategies for competitive balance.  
- 📊 **Localized Strategy:** Use segmented pricing/demand insights to tailor service offerings and promotions by city zones.

---

## 🧰 Tools & Techniques
- Python (Pandas, NumPy)
- Exploratory Data Analysis (EDA)
- Price & Demand pattern visualization

---
🔗 **Full Notebook & Code:**  
[Ride Hailing Demand & Pricing Insights (Uber & Lyft)](https://github.com/lilasu086/Ride-Hailing-Demand-Pricing-Insights-Uber-Lyft-)
