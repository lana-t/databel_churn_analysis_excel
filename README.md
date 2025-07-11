# Databel Telecom Churn Analysis (Excel Case Study)

This project investigates the drivers of customer churn for a fictitious telecom company, **Databel**, using Excel-based analysis and executive reporting. It walks through data cleaning, transformation, and churn segmentation to provide actionable business recommendations.

> For full insights and recommendations, see the [PowerPoint Presentation](./Databel-churn-presentation.pdf) with speaker notes.
<br/>

## The Business Case
- **Company**: Databel (ficticious telecom provider)
- **Dataset**: Provided by DataCamp
- **Tools Used**: Microsoft Excel, Pivot Tables, PowerPoint

### Business Question

**Why are customers leaving Databel and what strategies can help reduce churn and improve retention?**

This case study simulates a real-world scenario to uncover churn drivers using customer and aggregated data. The goal is to provide Databel's executive team with clear, actionable insights into customer behaviour and identify areas for improvement.

<br/>

## Data Cleaning & Preparation
The data came in two tables: Customer Table and Aggregate Table.  

### **Key Cleaning Steps:**
- Removed duplicates and verified data types
- Dropped unnecessary columns
- Filtered the **Customer Table** to retain:
  - Customer ID
  - Churn
  - Churn Category
  - Churn Reason
- Filtered the **Aggregate Table** to retain relevant dimensions like:
  - Age, State, Contract Type
  - Unlimited Data Plan
  - Account Length
  - Churn metrics (Total & Churned Customers)
  - Data usage and churn descriptors
 
### **Transformations:**
- Demographics Column: Created with nested IFs to classify customers as Under 30, 30-65, or Senior (65+)
- Data Usage Category: Grouped usage into:
  - Less than 5GB
  - Between 5 and 10GB
  - 10GB or more

<br/>

## Data Analysis
### **Customer Table Insights**

- Counted total churned customers
- Calculated overall churn rate
- Calculated customer distribution across churn categories
- Drilled down into the top churn category, Competitor, to explore detailed churn reasons
 
### **Aggregate Table Insights**
- Created a Churn Rate calculated field:
Churn Rate = Churned Customers / Total Customers
- Analysed churn by:
  - Demographic groups: Under 30, 30–65, 65+
  - Age ranges: Binned into 10-year intervals
  - Unlimited Data Plan: Compared churn between plan holders and non-holders
  - Data usage: Segmented into <5GB, 5–10GB, and 10GB+ groups
  - Account length: Grouped by year
  - Contract type
  - Geography: Identified top 10 states with the highest churn rates

<br/>

## Key Insights

- **Top churn category**: **45.5%** of churn was due to competitors.
- **Unlimited data plans** are causing dissatisfaction among low-data users. Churn was **twice as high** among customers with unlimited data plans compared to those without.
- **Early churn** is common. **49%** of new customers leave within the first year
- **Contract type** strongly correlates with retention. Churn rates of **Month-to-Month** contracts where an astonishing **74.1%** compared to the **3.2% churn rate** of **two year contracts**. 

<br/>

## Recommended Strategies

- Offer more competitive contracts. Introduce price matching and offer a wider range of products to help retain customers who are tempted by rival offers.
- Introduce a limited data plan. Provide a cost-effective alternative for low-data users creating flexibility and reducing unnecessary churn from customers who don’t need unlimited data.
- Strengthen retention strategies. Focus on early-stage engagement through better onboarding and incentivise long-term commitment with attractive contract benefits.

<br/>

## PowerPoint Presentation

The presentation outlines the analysis and recommendations in a format suitable for stakeholders. Speaker notes provide narrative context for each slide.

<br/>

## Contact

Lana Trimmer<br/>
[LinkedIn](https://www.linkedin.com/in/lana-trimmer/) • [Portfolio](#) • [Email](lana.trimmer32@gmail.com)
