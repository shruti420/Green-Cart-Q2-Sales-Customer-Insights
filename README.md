📊 Green Cart Q2 Sales & Customer Insights

📌 Project Overview

This project analyzes Q2 sales, product, and customer datasets for Green Cart Ltd., a UK-based eco-friendly e-commerce company.

The goal was to uncover revenue trends, customer behavior patterns, delivery issues, and generate actionable business insights.

🛠 Tools Used

* Python (Pandas, NumPy)

* Matplotlib & Seaborn

* Jupyter Notebook

* Data Cleaning & Feature Engineering

📂 Dataset Files

* sales_data.csv

* product_info.csv

* customer_info.csv

🧹 Data Cleaning

Key steps performed:

* Standardized inconsistent text casing (delivery_status, loyalty_tier)

* Converted date columns using pd.to_datetime()

* Removed duplicates (order_id)

* Handled missing values (filled / dropped where appropriate)

* Converted numeric columns using pd.to_numeric() with validation

⚙️ Feature Engineering

Created new fields:

* revenue = quantity * unit_price * (1 - discount)

* order_week

* price_band (Low / Medium / High)

* days_to_order

* email_domain

* is_late

📈 Key Insights

* Revenue peaked in Weeks 22–24.

* Personal Care & Kitchen drove strongest sales.

* Gold tier customers generated highest revenue.

* North region showed highest delivery delays.

* 10–25% discounts increased order volume.

💡 Business Recommendations

* Promote high-performing categories in South region.

* Improve logistics in North region.

* Target Gold & Silver loyalty tiers with campaigns.

📊 Visualizations Included

* Weekly revenue trend line chart

* Category revenue bar chart

* Discount vs quantity boxplot

* Correlation heatmap

* Loyalty tier countplot

* Delivery status by price band

📎 Files Included

📓 Jupyter Notebook (week2-ShrutiDudharkar.ipynb)

📄 Final Report PDF
