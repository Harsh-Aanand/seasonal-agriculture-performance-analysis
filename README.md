Major Project: Seasonal Agriculture Performance Analysis
# Seasonal Agriculture Performance Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ct-wL5MLYoSIp9-hDWJWZwEzKmQ5o5Oe?usp=sharing)

## Project Overview
This project investigates the impact of seasonal variations on agricultural performance across diverse farming conditions, agro-climatic zones, and resource allocations[cite: 1]. Using a comprehensive dataset of 4,000 farm observations, the study conducts exploratory, descriptive, and multivariate data analyses to identify critical trends in crop yields, input efficiency, resource utilization, and farm profitability across the Kharif, Rabi, and Zaid seasons[cite: 1].

---

## Problem Statement
Agricultural productivity and economic feasibility fluctuate substantially across seasons due to changing rainfall, temperatures, input availability, and market dynamics[cite: 1]. However, raw farm-level records do not inherently clarify how or why performance differs across periods[cite: 1]. This project resolves that gap by cleaning, analyzing, and synthesizing agricultural performance data to produce actionable, evidence-based recommendations for seasonal agricultural planning[cite: 1].

---

## Key Analytical Insights
1. **Seasonal Profitability Collapse:** Kharif generates an average net profit of ₹1,78,915 and Rabi yields ₹87,689, whereas Zaid incurs an average net loss of -₹24,805 with over 50% of farms operating at a deficit.
2. **Irrigation Technology Resilience:** Drip irrigation maintains profitability across all seasons (averaging ₹21,292 even during arid Zaid conditions), whereas flood irrigation leads to substantial financial deficits (-₹69,787).
3. **Severe Crop Disparities:** Commercial crops (Sugarcane and Chilli) demonstrate high profitability across all seasons, whereas staple cereals (Rice, Wheat, and Maize) operate at net losses when input costs are fully accounted for.
4. **Water Efficiency Deterioration:** Water productivity declines by 25.1% from Kharif (5.89 t/1,000 m³) to Zaid (4.41 t/1,000 m³) due to elevated temperatures (31.0°C) and evaporative losses.
5. **Monsoon Disease Surges:** Pathogen and pest risk peaks significantly during the humid Kharif season (54.5%) compared to Rabi (40.5%) and Zaid (38.2%).
6. **Inelastic Chemical Use:** Pesticide application volumes remain static (~5.08–5.17 L/ha) across seasons despite disease pressures dropping by nearly 30% in dry months, indicating calendar-based rather than conditional spraying.
7. **Economic Drivers:** Net profit correlates strongly with revenue ($r = 0.89$) and yield ($r = 0.49$), but exhibits almost zero correlation with rainfall ($r = 0.11$), proving that modern irrigation and crop selection matter far more than raw precipitation.
8. **Flood Irrigation Waste:** Flood irrigation consumes the largest water volumes (mean 8,026 m³) but yields the lowest efficiency (3.44 t/1,000 m³).

---

## Project Structure & Deliverables
The accompanying Jupyter/Colab notebook fulfills all academic rubric requirements[cite: 1]:
- **Data Preprocessing & Cleaning:** Resolution of missing values across rainfall, soil moisture, and crop yield via seasonal median imputation and production-area recalculations[cite: 1].
- **Exploratory Data Analysis (EDA):** Univariate distribution profiles, IQR-based statistical outlier detections, bivariate pairwise analyses, and correlation heatmaps[cite: 1].
- **Structured Seasonal Benchmarking:** Comparative four-pillar evaluations across climate, inputs, productivity, and profit margins[cite: 1].
- **Student-Designed Inquiries:** Three custom analytical evaluations exploring irrigation–season interactions, crop-specific profitability heatmaps, and pest risk versus water efficiency[cite: 1].

---

## Technology Stack
- **Language:** Python 3
- **Environment:** Google Colab / Jupyter Notebook[cite: 1]
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Statistical Analytics:** Pearson Correlation, Interquartile Range (IQR) Outlier Bounding, Descriptive Statistics

---

## Policy & Practical Recommendations
1. **Mandate Micro-Irrigation Transition:** Prioritize capital subsidies for drip and precision sprinkler systems to replace flood irrigation, particularly during summer (Zaid) cultivation.
2. **Crop Realignment for Dry Seasons:** Discourage water-intensive cereal cultivation during Zaid, shifting regional acreage toward drought-tolerant pulses or high-value horticulture.
3. **Pest Surveillance & Dynamic Input Spraying:** Replace fixed-calendar chemical spraying schedules with disease-risk threshold spraying, curbing operating costs and chemical runoff.

---

## Future Scope
- Developing supervised machine learning models (Random Forest, XGBoost) to predict farm yield and profit margins pre-sowing.
- Building an interactive decision-support tool (Streamlit/Dash) for real-time crop suitability and ROI simulations.
- Integrating real-time IoT soil-moisture sensor data and satellite weather forecasting feeds.
