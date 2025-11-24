📊 Customer Shopping Behavior Analysis

This project analyzes 3,900 customer shopping records to uncover insights about demographics, spending patterns, product preferences, and subscription engagement. The goal is to support data-driven business decisions and improve customer retention, marketing strategies, and revenue performance.
(Reference: Project Report 

Customer-Shopping-Behavior-Anal…

)

📁 Dataset Summary

The dataset contains 18 columns covering:

👤 Customer Demographics

Age, Gender, Location, Subscription Status

🛒 Purchase Details

Item, Category, Amount, Season, Size, Color

💳 Shopping Behavior

Discount, Promo Code, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

There were 37 missing values in Review_Rating, handled using median imputation.
(Source: Page 2 of report 

Customer-Shopping-Behavior-Anal…

)

🧹 Data Preparation & Cleaning

Steps performed (Page 3):

Loaded data using pandas

Checked summary statistics

Imputed missing Review_Rating using median

Dropped redundant columns like promo_code_used
(Page 4 of report)

🛠️ Feature Engineering

Based on insights in the report (Page 4):

Age Group Binning: Categorized customers into Young Adult, Middle-aged, and Senior.

Purchase Frequency Feature: Derived from historical purchases.

PostgreSQL Integration: Cleaned dataset uploaded for SQL-based analysis.

📈 Key Insights & Visualizations
1️⃣ Revenue by Gender

(Page 5)

Male customers generate significantly more revenue than females.

Opportunity: Targeted campaigns to increase female customer purchases.

2️⃣ Top Products by Rating

(Page 6)

Rank	Product	Rating
1	Gloves	3.86
2	Sandals	3.84
3	Boots	3.82
4	Hat	3.80
5	Skirt	3.78
3️⃣ Shipping Preference Insights

Express Shipping customers spend slightly more ($60.48) than Standard ($58.46).

4️⃣ Subscription Analysis

(Page 7)

Subscribers = 1,053, Non-Subscribers = 2,847

Subscribers spend slightly less on average but contribute significantly to total revenue.

5️⃣ Discount Dependency

Top discount-driven items include:

Hat (50%), Sneakers (49.6%), Coat (49%), Sweater (48%), Pants (47%)

6️⃣ Customer Segmentation

(Page 8)

Segment	Count
New	83
Returning	701
Loyal	3,116

Most customers fall into Loyal group → strong retention.

7️⃣ Revenue by Age Group

(Page 9)

Young Adults contribute the highest revenue, followed by Middle-aged adults.

🧠 Business Recommendations

(Page 10)

✔ Boost Subscriptions

Promote exclusive subscriber benefits.

✔ Customer Loyalty Programs

Reward repeat buyers to strengthen retention.

✔ Targeted Marketing

Focus on:

High revenue age groups

Express-shipping users

✔ Product Positioning

Highlight:

Best-rated products

Best-selling items

🧰 Tech Stack

Python: Pandas, NumPy, Matplotlib/Seaborn

SQL: PostgreSQL for storage and analysis

Presentation: Insights summarized using dashboards & storytelling visuals


📌 Conclusion

This analysis provides clear insights into customer behaviors, profitable segments, purchasing preferences, and operational opportunities. The results help guide marketing strategy, product positioning, and customer retention efforts.
