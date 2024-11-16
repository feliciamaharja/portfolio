# Project Background

Heicoders Bank, a leading financial institution in Singapore, offers a wide range of banking products, including savings accounts, loans, and credit cards. The GoCard, one of the bank's flagship credit cards, is designed to attract and retain customers through rewards and cashback benefits. In a competitive market where consumers often own multiple cards and switch based on incentives, GoCard's goal is to increase transaction volumes and customer loyalty. Key business metrics include transaction volume, spending patterns, and customer engagement across different transaction types and categories.

This project focuses on analyzing consumer spending patterns on the GoCard to identify key drivers of transaction activity. By understanding customer preferences, popular spending categories, and transaction behaviors, the objective is to **boost GoCard's transaction volumes and spendings in Q3 2020**. The analysis will provide actionable insights for the Product & Marketing teams to enhance GoCard's appeal in a highly competitive credit card market.


Insights and recommendations are provided on the following key areas:
- **Customer Spending Trends by Location:** Analysis of transaction data to identify popular spending categories, average transaction sizes, and customer preferences. 
- **Transaction Type Preferences** 
- **Expense Category Analysis**
- **Seasonal Spending Patterns**

The SQL queries used to inspect and clean the data for this analysis can be found here [link].

Targeted SQL queries regarding various business questions can be found here [link].

An interactive Tableau dashboard used to report and explore sales trends can be found here [link].



# Data Structure & Initial Checks

The main database comprises four tables with a total row count of approximately [X] records. A summary of each table is as follows:
- **Transactions:** Details each customer transaction, including date, amount, and type.
- **Customers:** Contains customer demographic information (limited in this dataset).
- **Locations:** Includes town and mall names with geolocation data (latitude, longitude).
- **Expense Categories:** Categorizes spending for each transaction (food, travel, bills, etc.).

[Entity Relationship Diagram here]



# Executive Summary

### Overview of Findings
**1. Geographic Spending Patterns:** The Seletar Mall leads in customer spending, indicating regional concentration.
**2. Shift in Payment Preferences:** A significant decline in physical card transactions in 2020 Q2, with a slight uptick in digital payments.
**3. High Expense Categories:** Instalments dominate total spending, highlighting a preference for high-value purchases through deferred payments.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
### Customer Spending Trends by Location:

* **Main insight 1.** The Seletar Mall had the highest spending, totaling S$37,114.86 in 2019 Q3.
  
* **Main insight 2.** Spending patterns in other top malls align with regional population density and shopping preferences.

[Visualization: Geographic map for regional spending]


### Transaction Type Preferences:

* **Main insight 1.** Physical card transactions consistently lead but dropped significantly in 2020 Q2.
  
* **Main insight 2.** Online and virtual wallet transactions remained steady, indicating resilience in digital payments.

[Visualization: Line chart showing transaction types over time]


### Expense Category Analysis:

* **Main insight 1.** Instalment purchases account for over S$836K in 2019 Q3, the highest among categories.
  
* **Main insight 2.** Food-related spending (S$152K) is second, reflecting its importance in daily customer expenditure.

  
[Visualization: Bar chart for expense categories]


### Seasonal Spending Patterns:

* **Main insight 1.** 2019 Q3 shows a peak in transaction volume, suggesting seasonality or promotional impacts.
  
* **Main insight 2.** Such spikes are opportunities for targeted campaigns during similar periods in 2020.

[Visualization: Line chart for quarterly trends]



# Recommendations:

Based on the insights and findings above, we would recommend the Product and Marketing teams to consider the following: 

* **Boost Promotions in High-Spending Malls:** Focus on top-performing malls to increase in-person transactions.
  
* **Enhance Digital Payment Campaigns:** Encourage adoption of virtual wallets and online payments through targeted offers.
  
* **Leverage Instalment Purchases:** Expand partnerships for big-ticket items, promoting "buy now, pay later" options.
  
* **Implement Seasonal Campaigns:** Repeat successful 2019 Q3 promotions for upcoming quarters to drive engagement.
  
* **Monitor Emerging Trends Post-Pandemic:** Assess long-term shifts in physical vs. digital payment preferences.

  

# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* **Missing Data:** Some transaction dates were imputed or excluded to maintain trend integrity.
  
* **Geographic Analysis:** Incomplete geolocation data may limit full regional insights.
  
* **Limited Demographic Data:** Lack of customer profiles restricts deeper segmentation analysis 
  
* **External Factors:** COVID-19’s impact is considered a major external driver, though broader economic indicators weren't available.


