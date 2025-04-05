# Coffee-Shop-Sales-Data-Analysis (Interactive Dashboard using MS Excel)
This project involves the development of an Excel dashboard to analyze coffee sales data. The goal is to uncover key business insights related to customer purchasing behavior, peak sales periods, and product performance. Through data visualization and trend analysis, this dashboard provides actionable insights for stakeholders.

## Learning Objective
- Profile and prepare the raw data for analysis.
- Explore the data with Excel.
- Build a dynamic dashboard to visualize patterns and trends.

## Dataset
I got this dataset from kaggle, which contains the transactional records from Maven Roasters, a fictional NYC-based coffee shop operating across 3 locations (Astoria, Hell’s Kitchen, Lower Manhattan) from January 1st to June 30th, 2023.
It encompasses comprehensive details such as transaction_id, transaction_date, transaction_time, transaction_qty, store_id, store_location, product_id, unit_price, product_category, product_type, product_detail.
- <a href="https://github.com/nikfaizdev/Data-Analysis-with-Excel-Coffee-Sales-Dashboard/blob/main/Coffee%2BShop%2BSales.zip">Source Dataset</a>

## Project Objective
1. Identity the most and least sold products.
2. Identity the primary revenue-generating items.
3. Analyze the sales trends over time.
4. Discover patterns in sales and identify peak traffic days and times.

## Process
- Verify data for any missing values and anomalies, and sort out the same.
- Made sure data is consistent and clean with respect to data type, data format and values used.
- Created pivot tables according to the questions asked.
- Merge all pivot tables into one dashboard and apply slicer to make dynamic.

## Key Findings:

![image](https://github.com/user-attachments/assets/b1426085-39fd-47ce-bf1e-a80c685b5925)

Performance by Store, Monthly, DOW, Daily and Time Session
- Hell’s Kitchen leads with $236.5K, followed by Astoria ($232.2K), and Lower Manhattan ($230.1K).
- There’s a clear upward trend from January ($81.7K) to June ($166.5K) where June is the best-performing month in terms of revenue and quantity sold.
- Revenue remains mostly consistent throughout the month with minor fluctuations. However, the trend (red dotted line) indicates a slight decrease in revenue as the month progresses.
- Base on DOW shows sales peak on Monday, Thursday, and Friday, whereas Saturday records the lowest revenue.
- The 9AM – 12PM session shows the highest sales, generating $220.1K in revenue, with 10AM marking the peak sales activity. This indicates strong mid-morning demand.

![image](https://github.com/user-attachments/assets/2b4df466-2db6-4579-91b8-bd8d1708f93a)

-  Coffee is the top contributor, accounting for 39.2% of total revenue, followed by Tea at 30.5% and Bakery at 15.3%.
-  Coffee leads with 58.4K transactions, followed by Tea with 45.4K, and Bakery with 22.8K.
-  Other categories like Drinking Chocolate and Flavours show moderate engagement, but categories such as Branded, Loose Tea, and Packaged Chocolate have very low transaction volumes (less than 2K), suggesting low demand.

## Dashboard
![image](https://github.com/user-attachments/assets/09278897-fb3b-400f-9101-d93a93aa3700)
