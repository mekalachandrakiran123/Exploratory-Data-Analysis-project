# Exploratory-Data-Analysis-project

 Exploratory Data Analysis of the Used Car Resale Market
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the used car resale market using real-world data scraped from an online used-car marketplace. The goal is to understand pricing patterns, demand trends, and key factors that influence used car prices, helping both buyers and sellers make informed decisions.

🎯 Problem Statement

The used car market is highly dynamic and varies significantly across brands, models, fuel types, transmission types, age, and kilometers driven.
Buyers often struggle to identify fair prices, while sellers face challenges in pricing vehicles competitively due to limited market transparency. Although platforms host large volumes of listings, the data is not readily available in an analytical format to derive actionable insights.

✅ Objectives

The main objectives of this project are:

Collect used car data such as price, brand, model, manufacture year, fuel type, transmission, and kilometers driven

Analyze how used car prices vary across brands and models

Identify high-demand brands and models in the used car market

Understand the impact of kilometers driven, fuel type, transmission, and car age on resale prices

Provide data-driven insights to help:

Buyers find value-for-money cars

Sellers price their vehicles competitively

📊 Dataset Overview

Total Records: 400

Total Columns: 8

Key Features:

Brand

Model

Manufacture Year

Kilometers Driven

Fuel Type

Transmission Type

Price

Data Quality:

No missing values

All columns contain non-null entries

🛠️ Data Extraction Process

Identified relevant data fields such as brand, model, price, fuel type, kilometers driven, and manufacture year.

Used Python libraries like Requests and Selenium to scrape data from web pages.

Parsed raw HTML elements into a structured tabular format using pandas.

Stored the cleaned data in CSV format for analysis and visualization.

📈 Exploratory Data Analysis
🔹 Univariate Analysis

Brand-wise Distribution:
Maruti dominates the used car listings, indicating high resale activity. Brands like Toyota and Nissan show limited availability.

Fuel Type Distribution:
Petrol cars account for nearly 85% of the listings, reflecting changing market preferences and emission regulations.

Price Distribution:
Prices are positively skewed, with most cars priced between ₹2–4 lakhs. A few premium cars create high-price outliers, making the median a more reliable metric.

🔹 Bivariate Analysis

Kilometers Driven vs Price:
Clear negative correlation showing depreciation with increased usage.

Price Outliers:
Boxplots reveal right-skewed distributions with premium cars priced around ₹12–13 lakhs.

Brand vs Price:
Premium brands like Toyota and Mahindra command higher resale prices, while Maruti and Renault dominate the lower price range.

🔹 Multivariate Analysis

Correlation Insights:

Manufacture year shows a strong positive correlation with price

Kilometers driven shows a moderate negative correlation
👉 Car age plays a more significant role in pricing than usage alone.

📐 Hypothesis Testing

Hypothesis:

H₀: Kilometers driven has no impact on car price

H₁: Kilometers driven significantly impacts car price

Test Used: Pearson Correlation Test

Decision Rule:

If p < 0.05 → Reject H₀

Result:
There is a statistically significant negative relationship between kilometers driven and resale price, confirming depreciation as a key pricing factor.

💡 Applications

For Buyers:

Compare prices across brands and models

Identify cars offering better value for money

For Sellers:

Set competitive and realistic prices based on market trends

For Platforms:

Improve price benchmarking

Optimize inventory planning

Enable targeted marketing strategies

🏁 Conclusion

This project demonstrates how web scraping combined with data analysis can generate valuable insights in the used car industry.
The analysis shows that resale prices are strongly influenced by car age, kilometers driven, fuel type, and transmission. Newer cars and automatic transmission vehicles generally command higher resale values. Overall, the project highlights the power of data-driven decision-making in real-world business scenarios.

👤 Author

Mekala Chandra Kiran
🎓 B.Tech – Computer Science and Engineering
📍 Hyderabad, India

🔗 LinkedIn: https://www.linkedin.com/in/mekala-chandra-kiran-6a2136389/

💻 GitHub: https://github.com/mekalachandrakiran123
