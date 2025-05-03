# Brent Supermarket Analysis

[Introduction](#Introduction)

[Story of Data](#StoryofData)

[Data Splitting and Preprocessing](#DataSplittingandPreprocessing)

[Pre-Analysis](#Pre-Analysis)

[In-Analysis](#In-Analysis)

[Post-Analysis and Insights](#Post-AnalysisandInsights)

[Data Visualizations & Charts](#DatavVisualization&Chart) 

[Recommendations and Observations](#Recommendationandobservation)

[Conclusion](#Conclusion)

[Reference](#Reference)

# Introduction
This report analyzes Brent Supermarket’s 2019 sales performance using transactional data from its four regional branches. The supermarket offers a wide range of food and household items, with orders placed online, by phone, or in person and delivered through a shipping company.The findings provide insights into sales performance, business growth, and opportunities for improvement.

## Objective
The objective of this project is to evaluate sales performance, understand customer purchasing patterns, and assess the efficiency of each salesperson in the firm’s various regions so that it can prepare for the coming year.

 ### Problem being Addressed
The organization is concerned about generating more revenue, as well as increasing retention and referral among its customers. To solve the problem of the organization, the analysis is designed to uncover key insights about revenue drivers:

i) High-performing salesperson

ii) Top products,

iii) Best contributing customer,

iv) Top contributing city

v) Regional sales performance.

#### Key Datasets and Methodologies
The analysis in this report is based on sales transaction data from a grocery store for the year 2019. The methodologies applied include data cleaning, descriptive statistics, pivot table analysis, trend analysis, and comparative analysis, all conducted using Microsoft Excel.

# Story of Data
## Data Source
The sales transaction data used for this analysis was sourced from Kaggle, a reputable online platform for data science and machine learning datasets. It provides reliable and well-structured data, making it suitable for conducting meaningful business and performance analysis.

### Data Collection Process
Data was collected from company sales logs, including orders, customer details, ship city, salesperson, region, product name, category, quantity, revenue and shipping costs.

#### Data Structure
i) Rows: Each row represents a sales transaction.

ii) Columns: Variables include Order ID, Order Date, Customer ID, Customer Name, Ship Date and Address, Salesperson, Region, Product Name, Category Quantity, Revenue, and Shipping Fee.

##### Important Features and Their Significance
i) Revenue: Key metric for financial performance.

ii) Product Category: Helps identify top-selling product segments.

iii) Salesperson Performance: Determines top performers.

iv) Regional Sales: Helps optimize market targeting.

###### Data Limitations or Biases
Missing values in Discount, Profit, Payment Type, and Product Name columns could affect data on the top performing product.

# Data Splitting and Preprocessing
## Data Cleaning
Before analyzing the sales transactional data, I conducted a data quality check to ensure accuracy and reliability. This involved identifying missing values, duplicate entries, and inconsistencies using Microsoft Excel’s built-in functions.

i) Handling Missing Values

For missing values, I used Excel built in function which is located under the Home Tab (Find &Select ribbon). This function helped me quickly discover the cells with missing values under the following column: payment type, product name, category, unit price, quanity and revenue. Instead of deleting the entire rows with missing data ,since other cells in the same row contained useful information, I applied a filter during comparative analysis using Pivot Tables. This ensured that blank spaces did not distort the final results or visualizations. By addressing these issues systematically, I improved data integrity, leading to more accurate insights during the analysis.

ii) Duplicate Values

When I used the Excel Built In function under Data to remove duplicates, there were no records of duplicates found. In summary, the data was clean from duplicate errors.

iii) Data Transformations

Prior to the analysis, categorical data standardization was performed to ensure consistency in text-based data, reducing variations caused by typographical errors, inconsistent formatting, and multiple representations of the same value. This standardization was applied to product names and categories to ensure uniformity, as well as to payment types, country and region names, and customer names

### Data Splitting
In this analysis, data splitting was performed to distinguish between dependent and independent variables. The sales column (revenue) was identified as the dependent variable, as it represents the target outcome. Independent variables, such as order date, customer name, city, salesperson, region and product category were separated to analyse their impact on sales performance. This division allowed for a structured approach to understanding relationships within the dataset and conducting meaningful comparative analysis.

#### Industry Context
This dataset represents a grocery store sales transaction with insights towards improving sales performance and generating more revenue.

##### Stakeholders
In this project, the stakeholders were the Chief Executives comprising of :

i)Sales Team: Understand performance metrics.

ii) Marketing Department: Identify customer trends.

iii) Human Resource Department: Examine Salesperson Performance

iv) Senior Management: Strategic decision-making

###### Value to the Industry
For this industry, value is measured through revenue growth, which comes from expanding their customer base and boosting sales. By understanding purchasing patterns and regional trends, one can identify key opportunities to maximize profitability and sustain long-term growth.

# Pre-Analysis
## Identify Key Trends

An initial review of the dataset suggests potential trends in sales performance across different months, regions, and product categories. Key areas of interest include identifying the :

i) Best-performing sales month

ii) Top regions by revenue

iii)Top Cities by revenue

iv) High-performing salesperson

v) Top performing customers

vi) Best performing product category

vii) Most Category of Transaction performed.

viii) Top Ship Cities by revenue

### Potential Correlations

Based on the potential trends identified, the following potential correlations may exist in the data:

i. Sales Month vs. Revenue Generated — There may be a seasonal pattern where certain months consistently generate higher revenue due to promotions, holidays, or demand cycles.

ii. Region vs. Revenue — Some regions might contribute more revenue due to higher customer density, economic factors, or local market preferences.

iii. Salesperson Performance vs. Revenue — A correlation may exist between the top-performing salespeople and the total revenue they generate, influenced by their experience, customer network, or sales strategies.

iv. Customer Category vs. Revenue — High-value customers or frequent buyers might be responsible for a significant portion of the revenue.

v. Product Category vs. Revenue — Certain product categories might drive more revenue, possibly due to popularity, seasonal demand, or pricing strategies.

vi. City vs. Revenue — Larger or more urbanized cities might show higher revenue generation due to greater purchasing power and customer base.

vii. Transaction Category vs. Sales Volume — Higher-priced product categories might have fewer transactions but contribute significantly to revenue, while Lower-priced products might have higher transaction volumes due to affordability and frequent purchases.

#### Initial Insights

i) Other salespersons can learn from the best performing salesperson measures of improving sales to generate more income in the coming year.

ii) We can also finetune the least performing regions and implement a similar practice as the best performing regions and ensure the measure are kept in place.

iii) Implement targeted marketing campaigns to increase demand for low-performing products.

iv) Offer discount and reward program for top customers to promote patronage and drive sales growth.

v) Improve the efficiency and accessibility of the most frequently used payment methods to enhance customer experience.

vi) Maintain adequate stock levels for high-demand products to prevent shortages.

# IN- ANALYSIS
## Observations

i) Sales Performance by Rep

Nancy Freehafer was the best performing salesperson with a grossing revenue of $104,242.34 while Jan Kotas was the least performing salesperson with a revenue of $16,350.50.

ii) Sales Trend Report

The firm exhibited a fluctuating trend with its peak sales recorded in June ($55,601.61), Octoboer ($53,033.59), and December ($66,642.78), and its lowest sales were recorded in February ($19,955.50)

iii) Top 10 Customer

Company D was the best-performing customer, contributing a gross revenue of $67,189.50.

iv) Sales Performance by Region

The North branch had the best sales when compared with other regions, generating 32% ($144,660.34) of the total revenue while the West branch had the least sales with a revenue of $91,251.98 which is 21% of the total revenue.

v) Sales by Product Category

Beverages was the most sought product in the store contributing $110,557. 11 followed by Sauces, Jams Preserve, Dairy Product and Dried Fruits and Nuts.

vi) Transaction by Amount

Products below $1000 had 218 transactions recorded and those in the range of 7000–8000 had one transaction recorded.

# POST ANALYSIS
## Key Findings

i) Salesperson Performance

Nancy Freehafer is the top-performing salesperson, generating the highest revenue of $104,242.34, supported by a consistent sales trend and strong customer relationships.
Anne Larson follows closely with $93,848.33 in revenue, excelling as the sole salesperson in her region, with two of her customers ranking among the top ten.
Andrew Cencini ranks third with $67,180 in revenue from a single high-value customer, Company D, which is also the best-performing customer overall. His sales contributed to New York emerging as the top city for revenue.
In contrast, Jan Kotas is the least-performing salesperson, with $16,350.50 in revenue and inconsistent sales, indicating a need for improvement in customer engagement and sales strategy.
ii) Top 10 Customers

Company D was the top-performing customer, generating $67,180.50 in revenue, with peak sales recorded in June ($11,595). Most of their transactions (15) were under $1,000, and they primarily purchased products such as jams, preserves, dried fruits and nuts, pasta, grains, and baked goods & mixes. Company D is managed by Andrew Cencini from the Eastern Region.

iii) Sales Trend

A seasonal sales pattern was observed across all salespeople. February ($19,955.50) and April ($20,771.79) recorded the lowest sales figures, even for the top-performing salespeople.

iv) Sales by Region

The Northern Region, represented by Nancy Freehafer and Michael Naipper, was the best-performing region, generating 33% ($141,660.34) of total revenue. The Western Region, with Mariya Sergienko, Robert Zare, and Jan Kotas, was the least-performing region, generating 21% ($91,251.98) of total revenue.

v) Top Cities by Revenue

New York was the highest revenue-generating city, contributing $67,180.50. This revenue came from Company D, whose peak purchase occurred in June ($11,595.50), while the lowest was in April ($738.40). Given their strong contribution, establishing a sub-branch in New York could reduce shipping costs and attract more customers.

vi) Top Products by Revenue

Beverages generated the highest revenue of $110,577.11, showing a seasonal sales trend with peaks in June, April, October, and December. The top five cities in beverage sales were Seattle ($30,491.99), Memphis, Boise, Las Vegas, and Milwaukee. Nancy Freehafer was the top salesperson in this category, generating $47,695.99, followed by Anne Larsen and Mariya Sergienko.

vii) Transactions by Amount

Transactions below $1,000 had the highest count, contributing 24% of total revenue, with peak sales in December.
Chicago led this category with $20,010.01, followed by Milwaukee, Portland, Miami, and Los Angeles.
Nancy Freehafer processed the highest number of transactions in this category, followed by Anne, Laura, and Mariya.
Transactions between $4,000 and $8,000 had the lowest count, suggesting the need to introduce an installment payment plan for purchases in this range to increase transaction volume.

### Comparison with Initial Findings

The analysis confirmed several initial expectations, such as the Northern Region’s strong performance and Beverages being the highest revenue-generating product. However, the seasonal dip in February and April was more pronounced than expected, affecting even top-performing salespeople. Additionally, New York’s dominance in revenue generation was a surprising insight, indicating a strong customer base in that location. The underperformance of Jan Kotas compared to his regional counterparts further highlighted disparities in sales effectiveness, suggesting an opportunity for focused training interventions.

# DATA VISUALISATION AND CHARTS

# Link to the Excel documents and Dashboard:

Sales Trend Report
The peak sales were recorded in December ($66,642.78) indicating a seasonal sales. The lowest sales were recorded in the month of February ($19,955.50). Overall the sales trend portrays a fluctuating trend.


7.2 Top 10 Customer
Company D was the best-performing customer, contributing the highest revenue amounting to $67,180.50 to the supermarket.


7.3 Salesperson Performance
Nancy Freehafer was the best performing salesperson generating the highest revenue ($104,242.34) while Jan Kotas was the least performing salesperson generating $16,350.50.


7.4 Sales by Product Category
Beverages was the best performing product generating the highest revenue amounting to $110,577.11 to the supermarket .


# RECOMMENDATIONS
Based on the findings from the Brent Supermarket Performance Dashboard, the following recommendations are proposed:

🔑 Top Strategic Recommendations (Priority Actions)
Promote Top Salesperson: Promote Nancy Freehafer to Regional Supervisor to leverage her outstanding performance ($104,242.34) in training others.
Open New Branch in New York: Due to its top revenue ($67,180.50), create a branch and delivery outlet there.

Transfer Andrew to Manage NY Branch: With his strong performance and familiarity with New York, Andrew should manage the new outlet.

Recruit Two More Salespersons: One to support Andrew in New York, another to support Laura in the Eastern Region.

🤝 Performance Improvement & Collaboration
Transfer Jan Kotas for Mentorship: Move Jan (lowest performer: $16,350.50) to Southern Region to learn under Anne Larsen.

Reward Top 3 Salespersons: Recognize Anne Larsen and Andrew Cencini for their strong contributions.

Foster Inter-Regional Collaboration: Encourage peer learning — e.g., Nancy mentoring Michael, Andrew guiding Laura.

📈 Sales Growth Strategies
Launch Targeted Marketing in Low Months: Focus campaigns in February, April, and July to counter seasonal drops.

Implement Loyalty Program: Include discounts, coupons, or raffles to retain and attract customers.

Introduce Installment Payment Plans: Make high-price products more accessible to increase demand.

🔍 Monitoring & Product Strategy
Quarterly Monitoring & Evaluation: Track sales, customer preferences, and performance to respond to trends quickly.

Ensure Availability of Top Products: Maintain stock for top sellers, discount slow movers, and match stock to regional preferences.

# CONCLUSION
One of the most important lessons I learned from this analysis is that business decisions should not be based on guesswork or the patterns of other firms, but rather on data-driven insights specific to the company. The pre-analysis phase played a crucial role in guiding the investigation, ensuring a structured and efficient approach to uncovering trends, patterns, and key performance indicators.

From the analysis, the following key insights were identified:

Sales Performance Disparities: While some salespeople, such as Nancy Freehafer and Anne Larson, showed outstanding sales performance, others, like Jan Kotas, struggled significantly, highlighting the need for targeted sales training.

Seasonal Sales Trends: There were noticeable dips in sales during February and April, affecting even the best-performing salespeople, suggesting the need for seasonal marketing strategies.

Regional and City Performance: The Northern Region and New York City emerged as top revenue generators, revealing potential expansion opportunities in these high-performing areas.

Product and Transaction Trends: Beverages were the highest revenue-generating product, while small-value transactions (below $1,000) dominated the sales volume. Meanwhile, mid-range transactions between $4,000 and $8,000 were limited, suggesting that installment payment plans could increase revenue.

Customer Insights: Company D was the highest revenue-contributing customer, reinforcing the importance of customer relationship management in business success.

Overall, the findings emphasized the importance of using data analytics to make informed business decisions, ensuring that strategies are tailored to actual performance trends rather than assumptions.
