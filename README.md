# METROBANK-Transaction-Behaviour-Insights
<img width="730" height="399" alt="image" src="https://github.com/user-attachments/assets/41f783ab-0b94-4401-8db9-13a6b4d63b5d" />

## Project Background  
MetroBank requires a consolidated analysis of customer transaction behavior to evaluate financial flows, merchant engagement, and channel performance. The primary goal is to understand how customers distribute activity across deposits, payments, transfers, and withdrawals, while also identifying top merchants and preferred transaction channels. This project delivers a focused dashboard that highlights transaction volumes, average amounts, merchant activity, credit card usage trends, and channel value distribution, providing actionable insights into customer engagement and operational efficiency.  

## Executive Summary (Customer Transaction Insights)  
MetroBank processed **5,000 transactions** totaling **$25.1M** across **800 accounts**, with an average transaction value of **$5,013**. Transaction activity is evenly distributed across deposits (24.7%), payments (25.4%), transfers (24.4%), and withdrawals (25.5%), reflecting balanced customer usage. The top merchantsAirbnb, LocalStore, Apple, Uber, and Shell demonstrate diverse spending patterns across travel, retail, technology, transport, and fuel.  

Credit card holders account for **21% of payment transactions**, while non‑users dominate with **79%**, highlighting an opportunity to expand card adoption. Channel analysis shows **POS terminals handle the highest transaction value**, whereas online and ATM channels remain underutilized for major transactions. Overall, MetroBank demonstrates strong transaction diversity and merchant engagement, with clear opportunities to grow digital channel usage and credit card penetration.  

---

## Data Structure & Initial Checks  

### Data Overview  
The analysis was built entirely within a single Excel workbook, using a structured Excel Data Table as the source for all PivotTables and calculations. No external data models or Power Pivot were used, this ensures the dashboard demonstrates core spreadsheet competency and high‑performance analytics within a flat‑file environment.  

### Data Cleaning and Preparation  
The data cleaning process relied on native Excel tools, PivotTables, and standard formulas to derive the transaction insights.  

- **Data Quality:** Raw transactional records were audited for duplicates and missing values before being converted into a structured Excel Table. This ensured that the **$25.1M Total Amount** and **5,000 Transactions** were grounded in accurate, verified records.  
- **Field Engineering:** Helper columns were created using text and date functions to standardize transaction categories (Deposit, Payment, Transfer, Withdrawal) and extract fiscal periods for trend analysis. This enabled seamless comparison of transaction flows across customer segments.  
- **Aggregation:** PivotTables were used exclusively to aggregate transaction counts and values across dimensions such as merchant activity, channel distribution, and credit card usage.  
- **Calculated Measures (Time Intelligence):** Key ratios, such as the **21% vs. 79% split in payment transactions between credit card users and non‑users** were derived using calculated fields and formula‑based helper tables. This approach allowed dynamic comparisons without reliance on external models.  

### Technical Highlights  
- **Dynamic Visuals:** Leveraged Excel’s charting tools and conditional formatting to create a high‑contrast, visually engaging dashboard.  
- **Native Slicers:** Implemented interactive slicers for transaction type and merchant categories, enabling filtered views without manual table adjustments.  
- **Formula‑Driven Logic:** Used GETPIVOTDATA and lookup functions to link KPI cards (Total Accounts, Total Amount, Average Transaction Value) to back‑end Pivot summaries, ensuring the dashboard updates automatically as the source table grows.  
<img width="1340" height="684" alt="image" src="https://github.com/user-attachments/assets/e2a668cd-095d-4514-af2d-ebd6036e48af" /> 

## Project Background  
MetroBank requires a consolidated analysis of customer transaction behavior to evaluate financial flows, merchant engagement, and channel performance. The primary goal is to understand how customers distribute activity across deposits, payments, transfers, and withdrawals, while also identifying top merchants and preferred transaction channels. This project delivers a focused dashboard that highlights transaction volumes, average amounts, merchant activity, credit card usage trends, and channel value distribution, providing actionable insights into customer engagement and operational efficiency.  

## Executive Summary (Customer Transaction Insights)  
MetroBank processed **5,000 transactions** totaling **$25.1M** across **800 accounts**, with an average transaction value of **$5,013**. Transaction activity is evenly distributed across deposits (24.7%), payments (25.4%), transfers (24.4%), and withdrawals (25.5%), reflecting balanced customer usage. The top merchants Airbnb, LocalStore, Apple, Uber, and Shell demonstrate diverse spending patterns across travel, retail, technology, transport, and fuel.  

Credit card holders account for **21% of payment transactions**, while non‑users dominate with **79%**, highlighting an opportunity to expand card adoption. Channel analysis shows **POS terminals handle the highest transaction value**, whereas online and ATM channels remain underutilized for major transactions. Overall, MetroBank demonstrates strong transaction diversity and merchant engagement, with clear opportunities to grow digital channel usage and credit card penetration.  

---

## Key Insights and Analysis  

### Transaction Distribution  
Customer activity is balanced across deposits, payments, transfers, and withdrawals, suggesting that MetroBank is used for a wide range of financial needs rather than being skewed toward one transaction type.  

### Merchant Engagement  
Top merchants include Airbnb, LocalStore, Apple, Uber, and Shell, reflecting diverse spending patterns across travel, retail, technology, transport, and fuel. This highlights strong merchant partnerships and opportunities to deepen engagement with high‑volume sectors.  

### Credit Card Usage  
Credit card holders contribute 21% of payment transactions, while non‑users dominate with 79%. This imbalance signals untapped potential for credit card adoption campaigns and incentives to shift more payment activity toward cardholders.  

### Channel Performance  
POS terminals handle the largest transaction values, while online and ATM channels remain underutilized. This suggests customers prefer merchant‑linked or in‑person transactions for higher amounts, but digital channels could be strengthened to capture more value.  

---
### Data Overview  
The analysis was built entirely within a single Excel workbook, using a structured Excel Data Table as the source for all PivotTables and calculations. No external data models or Power Pivot were used—this ensures the dashboard demonstrates core spreadsheet competency and high‑performance analytics within a flat‑file environment.  
## Recommendations & Next Steps  

### 1. Expand Credit Card Adoption  
- **Opportunity:** Credit card holders account for only 21% of payment transactions.  
- **Action:** Launch targeted campaigns (e.g., rewards, cashback, merchant discounts) to encourage adoption and shift more payment activity toward cardholders.  
- **Impact:** Increased card usage strengthens customer loyalty and generates higher fee-based revenue.  

### 2. Strengthen Digital Channels  
- **Opportunity:** Online and ATM channels remain underutilized compared to POS.  
- **Action:** Invest in digital banking features, mobile app enhancements, and online transaction incentives.  
- **Impact:** Improved digital engagement reduces reliance on physical channels and enhances convenience for customers.  

### 3. Deepen Merchant Partnerships  
- **Opportunity:** Top merchants (Airbnb, Apple, Uber, Shell, LocalStore) dominate transaction volumes.  
- **Action:** Negotiate co-branded offers, loyalty programs, or exclusive deals with high-volume merchants.  
- **Impact:** Strengthens MetroBank’s ecosystem and drives recurring customer engagement.  

### 4. Diversify Transaction Mix  
- **Opportunity:** Transaction distribution is balanced, but growth opportunities exist in transfers and payments.  
- **Action:** Promote peer-to-peer transfer services and bill payment solutions to capture more everyday financial activity.  
- **Impact:** Positions MetroBank as the go-to platform for daily financial needs.  

### 5. Enhance Customer Segmentation Analytics  
- **Opportunity:** Current dashboard highlights aggregate flows but lacks demographic segmentation.  
- **Action:** Integrate customer demographics (age, region, tenure) into transaction analysis.  
- **Impact:** Enables tailored marketing strategies and targeted product offerings.  

### 6. Continuous Data Quality & Automation  
- **Opportunity:** Dashboard relies on manual Excel processes.  
- **Action:** Transition to Power BI or similar platforms for automated refresh, advanced analytics, and scalability.  
- **Impact:** Improves efficiency, reduces manual errors, and supports real-time decision-making.  
