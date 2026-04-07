# AeroFit Treadmill Customer Profiling - Exploratory Data Analysis

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on AeroFit's customer database to identify market segments and develop customer profiles for different treadmill product lines. The goal is to provide actionable insights for better targeting and recommendation strategies.

## 📊 Key Business Insights
Based on the analysis of customer demographics and purchasing behavior, the following key insights were identified:

### 1. Product Segmentation & Profiles
* **KP281 (Entry Level):** The most popular model, accounting for **44.4%** of total sales. It appeals to a broad demographic with a balanced gender ratio and moderate income levels.
* **KP481 (Mid-Level):** Holds **33.3%** of the market share. It is preferred by intermediate runners with moderate fitness levels.
* **KP781 (Premium):** The "Elite" model (**22.2%** share). It is predominantly purchased by high-income males ($75k+) with a self-rated fitness level of 5.

### 2. Significant Correlations
* **Income & Product:** There is a high correlation between annual income and the purchase of the KP781 model.
* **Fitness & Usage:** Customers purchasing the KP781 plan to use the treadmill significantly more often (avg. 5-6 times/week) compared to entry-level buyers.

---

## 🖼️ Visualizations

### Customer Distribution by Product
![Product Distribution](images/product_distribution.png)
*Insight: The KP281 is the volume leader, while the KP781 represents the high-margin niche.*

### Income vs. Product Purchase
![Income Boxplot](images/income_analysis.png)
*Insight: Clear income separation is visible for the KP781 model, indicating a distinct target audience.*

### Correlation Heatmap
![Heatmap](images/heatmap.png)
*Insight: Features like 'Miles' and 'Usage' show a very strong positive correlation with 'Fitness' levels.*

---

## 💡 Recommendations
* **Targeted Marketing:** Position the **KP281** as an entry-level, versatile product for a broad demographic.
* **Premium Focus:** Target high-fitness individuals and males for the **KP781** through premium positioning.
* **Gender-Specific Strategies:** Increase KP781’s appeal among female customers by offering tailored fitness programs.
* **Bundle Offers:** Leverage the fact that **59.44%** of users are partnered by creating household or couple-based discount packages.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## 📂 Repository Structure
```text
├── images/               # Visualization exports (PNG/JPG)
├── notebooks/            # Ayesha_EDA_Portfolio_Project.ipynb
├── reports/              # EDA Portfolio Project.pdf
├── README.md             # Project Documentation
└── requirements.txt      # Project Dependencies
