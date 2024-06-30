**Project Title:** Credit Card Customer Spend and Repayment Behavior Analysis

**Goal:**
Analyze customer spend and repayment behavior using data-driven decision-making tools to support the CEO of PSPD Bank in evaluating areas of bankruptcy, fraud, collections, and customer service enhancement.

**Business Problem:**
PSPD Bank, operating in over 50 countries, aims to leverage data analytics to gain insights into customer behavior, improve marketing campaigns, personalize offerings, detect fraud, and reduce chargebacks. The CEO, Mr. Jim Watson, seeks detailed analysis and insights to make informed decisions.

**Data Available:**
The project utilized three main datasets:
1. **Customer Acquisition:** Contains details of customers at the time of card issuance.
2. **Spend (Transaction Data):** Records credit card spending for each customer.
3. **Repayment:** Tracks credit card payments made by customers.

**Key Responsibilities:**
1. **Data Cleaning and Preprocessing:**
   - Replaced ages less than 18 with the mean age.
   - Adjusted spend amounts exceeding the limit to 50% of the customer's limit.
   - Capped repayment amounts exceeding the limit to the limit value.

2. **Data Summarization:**
   - Counted the number of distinct customers.
   - Identified the number of distinct product categories.
   - Calculated the average monthly spend and repayment by customers.
   - Computed monthly bank profit based on a 2.9% interest rate on positive profits (Monthly Profit = Monthly repayment - Monthly spend).
   - Identified the top 5 product types.
   - Determined the city with the highest spend.
   - Analyzed which age group spends the most money.
   - Listed the top 10 customers based on repayment amounts.

3. **City-wise and Yearly Spend Analysis:**
   - Calculated annual city-wise spend on each product and created graphical representations.

4. **Visualization:**
   - Created monthly comparison graphs of total spends city-wise.
   - Compared yearly spend on air tickets.
   - Compared monthly spend for each product to identify seasonal trends.

5. **Custom Python Function:**
   - Developed a user-defined function to find the top 10 customers for each city based on repayment amounts, filtered by product type (Gold/Silver/Platinum) and time period (yearly or monthly).

**Technologies Used:**
- **Python:** For data cleaning, preprocessing, analysis, and creating the custom function.
- **Pandas and NumPy:** For data manipulation and statistical analysis.
- **Matplotlib and Seaborn:** For data visualization and creating graphs.
- **Excel:** For initial data exploration and basic analysis.

**Key Insights:**
- **Customer Behavior:** Provided a detailed understanding of customer spend and repayment patterns.
- **Marketing Strategies:** Helped in developing targeted marketing campaigns based on customer behavior.
- **Fraud Detection:** Enabled early detection of suspicious activities to prevent fraud.
- **Profit Maximization:** Identified profitable customers and transactions to maximize bank profits.
- **Customer Segmentation:** Offered personalized service and promotions to different customer segments.

**Final Deliverables:**
- **Detailed Analysis Report:** Summarizing key findings and insights from the data.
- **Graphs and Visualizations:** Providing visual insights into spending trends and patterns.
- **Custom Python Function:** Enabling dynamic analysis based on user inputs.

**Key Achievements:**
- Successfully cleaned and preprocessed large datasets to ensure data quality.
- Delivered actionable insights that helped PSPD Bank enhance its decision-making process.
- Demonstrated strong analytical skills in Python, data visualization, and business intelligence.
