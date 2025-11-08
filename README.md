#🛍️ Customer Shopping Behavior Analysis
Unlocking insights from 3,900 retail transactions — understanding spending patterns, product preferences & revenue drivers.
📌 Project Summary

This project analyzes real customer shopping behavior data to extract insights that help drive smarter business decisions.

I handled the entire analytics pipeline → from data cleaning → to SQL queries → to visual analytics in Power BI.


🧠 Business Goal

Identify which customer segments, products, and shopping characteristics drive the most revenue — and recommend actions companies can take to increase profitability.


🗂 Project Deliverables
File Type	Description
Jupyter Notebooks	Data loading, EDA, preprocessing, feature engineering
SQL File	10+ advanced business analysis SQL queries (PostgreSQL)
Power BI Dashboard	Visual overview of insights & business recommendations
Problem Statement PDF	Objective, business context & analytical scope


🔧 Tech Stack & Tools Used

Python → Pandas, NumPy, Matplotlib, Seaborn

PostgreSQL / SQL

Power BI

Jupyter Notebook


📊 Dataset Snapshot

3,900 transactions

18 features (demographics + purchase behavior)

Includes → category, pricing, discount usage, shipping type, subscription status, reviews etc.


🧪 What I Did (Key Steps)

Imputed 37 missing review ratings using category-wise median

Created new features (age_group, purchase_frequency_days)

Standardized column naming for clean documentation

Loaded final DataFrame into PostgreSQL for SQL business analysis

Ran multiple business-focused SQL queries (revenue, pricing, discount behavior, segmentation)


🔍 Key Insights
Focus Area	Finding
Revenue	Male customers generate 2.1x more revenue
Discount Behavior	Discount users still spend above average → discount ≠ low spend
Shipping Type	Express users spend 3.5% more on average
Subscriber Potential	~80% of high-frequency buyers are not subscribed → huge conversion opportunity


💡 Business Recommendations

Introduce subscriber-only rewards → convert heavy buyers into members

Push top-rated products in marketing (high ROI items)

Optimize discount strategy (don’t over-discount strong sellers)

Target young adults + express shipping users for premium pricing
