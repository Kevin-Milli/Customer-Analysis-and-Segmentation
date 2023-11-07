# Customer Analysis and Segmentation

## Introduction
In this GitHub repository, I'm embarking on a data research project using the Kaggle dataset titled "Customer Personality Analysis." The main objective is to delve into customer behavior analysis and segmentation, which holds immense potential for businesses in understanding and catering to their diverse customer base more effectively.

## Context
Customer Personality Analysis essentially entails a comprehensive study of a company's ideal customers. By examining various attributes, behaviors, and concerns of different customer types, this analysis empowers businesses to customize their products and services to better align with customer preferences. A key outcome of this endeavor is the ability to identify specific customer segments, which, in turn, can help companies target their marketing efforts more efficiently. This, in contrast to broadly marketing products to all customers, enables businesses to pinpoint the most likely customers to buy their offerings.

## Data Description
Before diving into the nitty-gritty of the project, it's crucial to understand the dataset we're working with. The data is categorized into three primary sections:

### People
- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in the customer's household
- Teenhome: Number of teenagers in the customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since the customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise
### Products
- MntWines: Amount spent on wine in the last 2 years
- MntFruits: Amount spent on fruits in the last 2 years
- MntMeatProducts: Amount spent on meat in the last 2 years
- MntFishProducts: Amount spent on fish in the last 2 years
- MntSweetProducts: Amount spent on sweets in the last 2 years
- MntGoldProds: Amount spent on gold in the last 2 years
### Promotion
- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise
### Place
- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalogue
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to the company’s website in the last month

## Project Structure
To keep things organized and ensure a systematic approach to our analysis, the project is structured into several key sections:

1. Objectives and Goal: Introduction to the project's purpose and goals.
2. Setup: Environment setup and dependencies.
3. Data Description: Detailed explanation of the dataset.
4. Feature Engineering: Creating new features if necessary.
5. Tools and Functions: Description of tools and functions used in the analysis.
6. Exploratory Data Analysis: An initial exploration of the dataset.
7. RFM Analysis: Analysis of Recency, Frequency, and Monetary (RFM) metrics.
8. Data Preprocessing: Data cleaning and preparation.
9. Model Evaluation: Evaluating different clustering models.
10. Cluster Analysis: Segmentation of customers.
11. K-Means: Application of K-Means clustering.
12. DBSCAN: Utilizing DBSCAN for clustering.
13. Visual Comparison: Visual representation and comparison of customer clusters.
14. Conclusions: Final remarks and insights.


Feel free to explore the code and analysis within this repository to gain a deeper understanding of customer behavior and segmentation based on the provided data. If you have any questions or need further assistance, please don't hesitate to reach out.
