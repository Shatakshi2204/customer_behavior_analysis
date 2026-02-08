🛍️ Customer Shopping Behavior Analysis

End-to-End Data Analytics Project

📌 Project Overview

This project showcases a complete end-to-end data analytics workflow, closely aligned with real-world company practices. The primary objective is to analyze customer shopping behavior for a retail business and derive actionable insights to improve sales performance, customer satisfaction, and customer loyalty. The project covers the full analytics lifecycle—from raw data exploration to business insights, visualization, and portfolio deployment.

<img width="1216" height="727" alt="Screenshot 2026-02-08 113345" src="https://github.com/user-attachments/assets/7d9ecda1-2d28-405b-8a36-f8323a109da2" />
<img width="1210" height="730" alt="Screenshot 2026-02-08 113451" src="https://github.com/user-attachments/assets/88cabc7b-0117-4e34-ae9b-6da48851f1b4" />
<img width="1217" height="737" alt="Screenshot 2026-02-08 113532" src="https://github.com/user-attachments/assets/d5673844-430c-47a4-b7b1-2ec14d74067a" />


🎯 Business Problem

Understanding customer behavior is critical for data-driven decision-making. This project addresses key business questions such as:

What factors influence customer spending and repeat purchases?

Do discounts increase average purchase value?

Are subscribed customers more valuable than non-subscribers?

Which products and categories perform best?

🗂️ Dataset Overview

The dataset represents customer shopping behavior, with each row corresponding to a customer’s latest purchase. It includes demographic details (age, gender), transaction data (item, category, purchase amount, shipping type), engagement indicators (review rating, subscription status, discounts), and historical context (previous purchases, purchase frequency). A key real-world limitation is the absence of complete transaction history.

🧹 Data Cleaning & EDA (Python)

Using Python (Pandas), the data is inspected, cleaned, and prepared for analysis. Missing values in review_rating are handled using category-wise median imputation to avoid bias. Column names are standardized to snake_case, redundant fields are removed, and new features such as age groups and purchase frequency in days are engineered to enhance analysis.

🧠 Business Analysis (SQL – PostgreSQL)

The cleaned data is migrated to PostgreSQL for in-depth business analysis. SQL queries explore revenue by gender, discount effectiveness, subscriber vs. non-subscriber spending, top-rated and most-purchased products, customer segmentation, and age-wise revenue trends. Advanced techniques like window functions are used for ranking and segmentation.

📊 Data Visualization (Power BI)

Insights are visualized using Power BI, connected directly to the database. Interactive dashboards display key KPIs such as customer count, average purchase amount, review ratings, and subscription distribution.

🚀 Project Delivery

The project concludes with a professional report, a client-ready presentation, and deployment on GitHub and LinkedIn, making it a strong portfolio-ready analytics project.
