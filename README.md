# 🏠 Tunisia Real Estate Market Intelligence
> *Strategic Analysis of 6,314 Property Listings for Investment Optimization*

## 📊 Project Overview
This project transforms raw real estate data into actionable investment intelligence. The goal is to identify high-performing geographic markets and determine which property features drive the highest ROI for developers and investors in the Tunisian market.

### 🎯 Strategic Business Questions Addressed:
1. **Regional Performance:** Which governorates generate the highest price per $m^2$?
2. **Investment Efficiency:** Are certain regions over-invested or under-supplied?
3. **Value Drivers:** What specific property features (amenities) command the highest price premiums?

## 🛠️ Technical Methodology
- **Data Cleaning:** Processed raw datasets to remove 1,800+ invalid records and standardized 200+ city name variants.
- **Feature Engineering:** - Developed a **Luxury Score** (0–54) based on a weighted sum of premium features.
  - Calculated **Price per $m^2$** and **Room Density** metrics.
  - Categorized listings into **Economy, Mid-Range, and Premium** segments using quantile-based pricing bins.
- **Investment Classification:** Built a 4-quadrant model (Strong Market, Opportunity, Over-Invested, Low Priority) to classify governorates based on volume vs. pricing efficiency.

## 📈 Key Insights
* **Top Performing Hubs:** Tunis leads the market with an average of $3,440 \text{ TND}/m^2$, representing a 31% premium over the market average.
* **The "Luxury" Lift:** Properties with a **Swimming Pool** command a **+97% price premium** (+539K TND) compared to those without.
* **Portfolio Risk:** Identified **Ben Arous** as an "Over-Invested" region—high supply volume but pricing remains 32% below the market average.

## 📂 Repository Structure
- `/data`: Raw and cleaned datasets.
- `/docs`: Data dictionary and methodology report.
- `Real_Estate_Market_Analysis.xlsx`: The final interactive dashboard.
- `Executive_Summary.pdf`: Formal presentation of findings.
