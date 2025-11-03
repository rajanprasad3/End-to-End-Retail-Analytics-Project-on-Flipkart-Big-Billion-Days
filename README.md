End-to-End Retail Analytics Project on Flipkart Big Billion Days Data

This project performs a 360° end-to-end analytics workflow on 1,500+ Flipkart Big Billion Days transactions, turning raw retail data into actionable business insights using Python, pandas, seaborn, and matplotlib.

🧩 Project Overview

The goal of this project was to analyze sales trends, understand customer behavior, identify performance drivers, and build a predictive model to estimate potential revenue impact during major sales events.

🔹 1. Data Ingestion

Loaded the raw CSV file using pandas.

Ensured data quality: 0 missing values and 0 duplicates.

🔹 2. Feature Engineering

Created KPIs: Discount_Amount, Profit, and Profit_Margin_%.

Generated datetime features and hourly bins to capture seasonality.

🔹 3. Exploratory Data Analysis (EDA)

Performed detailed visualization and statistical analysis using Seaborn and Matplotlib:

Yearly trend: 2023 revenue ≈ 2× vs 2020.

Category performance: Electronics > Home > Fashion.

Seasonality: Festive periods consistently outperform.

Hourly trends: Sales peaks at 11 AM and 9 PM.

Payment mode distribution: UPI (35%), COD (28%).

Return flag impact: 7% profit margin erosion.

Validation: Correlation matrix and joint-KDE plots to verify relationships.

🔹 4. Predictive Modeling

Implemented a Random Forest Regressor using key variables: MRP, Discount_%, Quantity, and Hour.

Achieved R² = 0.93, demonstrating strong predictive performance.

🔹 5. Deliverables

Clean, analysis-ready dataset.

11 publication-quality Seaborn visualizations.

Auto-generated Markdown report summarizing insights for stakeholders.

🛠️ Tech Stack

Python

pandas, numpy

matplotlib, seaborn

📈 Key Takeaway

This project demonstrates how data analytics and visualization can uncover actionable insights from retail transaction data — driving smarter decision-making during high-volume sales events.
