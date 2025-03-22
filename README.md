# Aurora Bank Dashboard

## Purpose
The Aurora Bank Dashboard is an engaging business intelligence tool that enables users to analyze and visualize crucial financial metrics, customer trends, and operational performance for Aurora Bank. It delivers actionable insights to stakeholders and facilitates data-driven decision-making.

## Data Model

![Data Model](https://github.com/omkardhumma/Aurora-Bank-Dashboard/blob/master/Auror_Bank_DataModel.png)

The above image represents the data model used in the analysis, including the following tables:
- **Fact Transactions Table**: Contains detailed records of all financial transactions.
- **Dimension Users Table**: Stores user information such as name, ID, and demographics.
- **Dimension Cards Table**: Holds card-related data including card types and issuance details.
- **Dimension MCC Codes Table**: Provides information on Merchant Category Codes (MCC) for classifying transactions.
- **Dimension Calendar Table**: Includes date and time data to facilitate time-based analysis.


## Dashboard Pages and Key Insights

### Demographics Page

#### Summary
The **Demographics Page** overviews the bank's customer base by analyzing their income, debt, and credit risk. It includes key financial indicators and visualizations to help understand user demographics, financial behavior, and risk levels. This page helps stakeholders make data-driven decisions about customer segmentation, credit assessment, and risk mitigation.

#### Key Performance Indicators (KPIs)
- **Average Age**
- **Per Capita Income**
- **Total Clients**
- **Average Yearly Income**

#### Visualizations

- 📊 **Pie Chart**: Displays the distribution of clients by income group.
- 🔵 **Pie Chart**: Shows the distribution of clients by credit score group.
- 📈 **Clustered Column Chart**: Represents demographics based on age group, credit score, and yearly income.
- 📉 **Column Chart**: Defines total clients by **DTI (Debt-to-Income) Category**.
- 🏦 **Column Chart**: Illustrates total clients by **Overall Loan Risk Score Category**.


![Demographics Page]()

### Card Details Page

#### Summary
The **Card Details Page** provides insights into the bank's issued credit and debit cards. It analyzes card distribution, usage patterns, and limits to help stakeholders understand customer behavior and financial trends. This page is crucial for monitoring card issuance trends, credit utilization, and brand preferences.

#### Key Performance Indicators (KPIs)
- **Visa Card** - Transaction Amount, Issued Cards, and Transaction Count (viewed in reference labels).
- **Mastercard Card** - Transaction Amount, Issued Cards, and Transaction Count (viewed in reference labels).
- **Discover Card** - Transaction Amount, Issued Cards, and Transaction Count (viewed in reference labels).
- **Amex Card** - Transaction Amount, Issued Cards, and Transaction Count (viewed in reference labels).

#### Visualizations
- 📊 **Column Chart**: Displays client card distribution by card brand.
- 🏦 **Column Chart**: Highlights top clients with the most transaction amounts and credit limits.
- 📈 **Column Chart**: Represents total card limit by card brand.
- 🍩 **Pie Chart**: Shows failed transaction distribution by card brand.


![Card Details Page]()

### Transaction Information Page

#### Summary
The **Transaction Information Page** provides an in-depth analysis of banking transactions, focusing on volume, value, and potential errors. This page helps stakeholders track transaction trends, identify common issues, and optimize financial operations.

#### Key Performance Indicators (KPIs)
- **Transaction By Chip Used**
- **Total Transaction Volume**
- **Total Transaction Amount**
- **Transaction Status**

#### Visualizations

- 📊 **Matrix**: Displays the monthly time distribution of transactions.
- 📈 **Column Chart**: Shows the total transaction amount and total transaction count by Merchant Category Code (MCC).
- 🗺️ **Bar Chart 1**: Displays the total number of transactions by merchant state.
- 📊 **Bar Chart 2**: Shows the total transaction count by merchant state.


![TransactionInfo Page]()

### Financial Health Page

#### Summary
The **Financial Health Page** offers a comprehensive overview of client financial standing, focusing on debt levels, risk scores, and income group distribution. This page assists stakeholders in assessing financial risks, identifying high-risk client segments, and making informed decisions.

#### Key Performance Indicators (KPIs)
- **Total Clients**
- **Total Debt**
- **Average Loan Risk Score**
- **Debt to Income Ratio (DTI)**

#### Visualizations

- 🥧 **Pie Chart 1**: Displays the distribution of clients by income group.
- 🥧 **Pie Chart 2**: Represents the distribution of clients by credit score group.
- 📊 **Column Chart**: Shows the total accumulated debt by age group.
- 📉 **Small Column Chart 1**: Displays the total accumulated debt by DTI category.
- 📉 **Small Column Chart 2**: Represents the total accumulated debt by debt risk score.

![Financial Health Page]()


## Conclusion  
The **Aurora Bank Dashboard** provides valuable insights into user demographics, card distribution, and transaction trends, helping stakeholders make data-driven decisions. By leveraging interactive visualizations and key financial metrics, this dashboard enhances operational efficiency and financial oversight. 

## Feedback & Support  
If you have any questions, suggestions, or feedback, feel free to reach out:  
📩 **Email:** omkardwork1202@gmail.com
💼 **LinkedIn:** www.linkedin.com/in/omkardhumma

Thank you for exploring the **Aurora Bank Dashboard**! ⭐ Don't forget to star this repository if you found it helpful!

