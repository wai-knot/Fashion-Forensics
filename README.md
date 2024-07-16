<div id="top"></div>

# 📌Fashion_Forensics

*Introduction:*

Dicoding Collection (DiCo) is an online fashion company that recognizes the value of data-driven decision making. They meticulously store all their sales history, product information, and customer details in a centralized database. This project aims to leverage this data to analyze DiCo's sales performance, identify top-selling and underperforming products, and gain valuable insights into their customer demographics. By understanding their customer base better, DiCo can develop more effective marketing campaigns.

*Data Analysis Process:*

This project will follow a structured data analysis approach consisting of the following key steps:

1. Business Questions:

2. *Data Wrangling:* 
    - In this initial phase, we will clean and prepare the data from the four tables (customers, orders, products, and sales) within the database. This might involve tasks like removing inconsistencies, fixing missing values, and formatting data for optimal analysis. 

3. *Exploratory Data Analysis (EDA):* 
    - Once the data is wrangled, we will perform an initial exploration to uncover patterns and trends. This might include calculating summary statistics, identifying relationships between variables, and visualizing the data to gain a deeper understanding. 

4. *Data Visualization:* 
    - To effectively communicate our findings, we will create visual representations of the data. This could involve charts, graphs, or other infographics that clearly showcase trends and patterns identified during the EDA stage. 

5. *Draw Conclusion:* 
    - After analyzing the prepared data and visualizations, we will draw conclusions about DiCo's sales performance, customer demographics, and product popularity. This will involve interpreting the findings and formulating actionable insights that can inform business decisions.

*Project Deliverables:*

- A comprehensive report outlining the analysis process, key findings, and actionable insights.
- Data visualizations that effectively communicate the project's conclusions.


# 🎯Business Questions

Business questions that will be answered through this data analysis include:
1. How has the company's sales and revenue performance been in the last few months?
2. What products sell the most and least?
3. What are the customer demographics of the company?
4. When was the last time a customer made a transaction?
5. How often has a customer made purchases in the last few months?
6. How much money did customers spend in the last few months?

# :dart:Results
## 📊Streamlit Dashboard

Link Streamlit Dashboard: [Dicoding Collection Dashboard](https://nurkholiq-online-fashion-data-analysis.streamlit.app/)

<p align="center">
  <img alt="Dicoding Collection Dashboard" title="Dicoding Collection Dashboard" src="https://github.com/nurkholiqaganihafid/Online_Fashion_Data_Analysis/assets/89395541/b2953718-3ac9-4f39-af8b-63f2df9ee8e4" width="750">
</p>

## 📈My Analysis Results
### Merging all Data
Total Data from the Merge Results
<p align="center">
  <img alt="Data Frame" title="Data Frame" src="https://github.com/nurkholiqaganihafid/Online_Fashion_Data_Analysis/assets/89395541/391487aa-1cc9-4fea-b621-cd3170f920c1" width="400">
</p>

### Data Visualization
#### 1st Question

How has the company's sales and revenue performance been in the last few months?

- Sales Performance in Recent Months
<p align="center">
  <img alt="Number of Orders per Month (2021)" title="Number of Orders per Month (2021)" src="https://github.com/nurkholiqaganihafid/fashion_forensics/assets/89395541/d00a4f03-93e5-4960-9ab4-c6f8b9a61dd4" width="750">
</p>

- Company Revenue in Recent Months
<p align="center">
  <img alt="Total Revenue per Month (2021)" title="Total Revenue per Month (2021)" src="https://github.com/nurkholiqaganihafid/Online_Fashion_Data_Analysis/assets/89395541/4942e487-4fd4-4ab7-b0da-1333a2691fe2" width="750">
</p>

#### 2nd Question

What products sell the most and least?
- Best and Worst Performing Product by Number of Sales
<p align="center">
  <img alt="Best and Worst Performing Product by Number of Sales" title="Best and Worst Performing Product by Number of Sales" src="https://github.com/nurkholiqaganihafid/Online_Fashion_Data_Analysis/assets/89395541/29d85840-d9cb-4995-a212-c33a2798782c" width="750">
</p>

#### 3rd Question

What are the customer demographics of the company?

- By gender
<p align="center">
  <img alt="Number of Customer by Gender" title="Number of Customer by Gender" src="https://github.com/nurkholiqaganihafid/Online_Fashion_Data_Analysis/assets/89395541/0f6fc017-b540-4d27-800a-4412881a460a" width="750">
</p>

- By age
<p align="center">
  <img alt="Number of Customer by Age" title="Number of Customer by Age" src="https://github.com/nurkholiqaganihafid/Online_Fashion_Data_Analysis/assets/89395541/1c40164a-bd85-4959-b57a-7aaedd82c0d8" width="750">
</p>

- By state
<p align="center">
  <img alt="Number of Customer by States" title="Number of Customer by States" src="https://github.com/nurkholiqaganihafid/Online_Fashion_Data_Analysis/assets/89395541/80a3ead7-8f25-4fbe-8b75-5e10cf3f21fc" width="750">
</p>

#### RFM Analysis

To figure out which customers are the most important, we can use something called RFM analysis. This method looks at three things about each customer:

Recency: How long ago did they buy something from us?

Frequency: How often do they buy from us?

Monetary Value: How much money do they spend when they shop with us?

By looking at these three things, we can see which customers are buying from us recently, often, and spending the most money.

<p align="center">
  <img alt="Best Customer Based on RFM Parameters (customer_id)" title="Best Customer Based on RFM Parameters (customer_id)" src="https://github.com/nurkholiqaganihafid/Online_Fashion_Data_Analysis/assets/89395541/48617f92-7044-4eeb-9586-a27c86deb55b" width="750">
</p>

# 📚Conclusions and Recommendations
- Conclusions
  We looked at how the company did over the past few months. Here's what we found:

- Sales Up and Down: March was our busiest month with lots of orders, but things slowed down in February, April, May, and October. This meant less money coming in.

- Denim is Popular: Denim clothes were our best sellers, but not many people bought Mandarin collar styles.

- Most Customers are Adults: We don't know much about our customers' genders, but most are adults and live in South Australia.

- Customers Buy Often: People are buying things from us pretty regularly, sometimes even on the same day. One person spent a lot of money, about $7,632.

- Recommendations
  Based on what we found, here's what we can do to improve:

- Boost Slow Months: We need to figure out why sales dropped in some months and find ways to sell more then. Maybe there's something our competitors are doing, or we need a better marketing plan.

- Focus on What Sells: Since denim is popular, we could try selling more denim styles. We should also think about why people aren't buying Mandarin collar clothes.

- Find More Customers: We need to reach out to new customers and find ways to get them to buy from us.

- Keep Customers Happy: We should make sure our customers are happy with their purchases by giving good service and selling quality products. This will help them keep coming back.

<p align="right"><a href="#top">Back to top</a></p>
