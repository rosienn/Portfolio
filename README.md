 ## **Rosie N. Osi - Data Analyst Portfolio**
 ---

## **About**
Hi, I'm Rosie! I'm a seasoned data analyst with over 5 years of experience in data cleaning, analysis, and visualization. With a strong foundation in delivering user-centered, fit-for-purpose solutions, I specialize in uncovering actionable insights and communicating them effectively to diverse stakeholders.

This repository showcases my skills and projects in data analytics and machine learning, including customer segmentation and data visualization. It’s a space where I track my growth and share my work with the data community.

---

## **Table of Contents**
* [About](#about)
* [Portfolio Projects](#portfolio-projects)
   - Python
     - [Shopper Segmentation and Clustering for Targeted Marketing](#Shopper-Segmentation-and-Clustering-for-Targeted-Marketing)
   - [SQL](#sql)
   - [Excel/Google Sheets](#excelgoogle-sheets)
   - [Power BI/Tableau](#power-bitableau)
* [Education](#education)
* [Certificates](#certificates)
* [Contact Information](#contact-information)

---

## **Portfolio Projects**
This section lists my data analytics and machine learning projects, with brief descriptions of the technology stack and methods used.

### **Shopper Segmentation and Clustering for Targeted Marketing** 
**Code:** [Shopper Segmentation and Clustering for Targeted Marketing.ipynb](https://github.com/rosienn/Portfolio/blob/main/Shopper%20Segmentation%20and%20Clustering%20for%20Targeted%20Marketing.ipynb)   

**Goal:** Segment customers based on their behaviors and demographics to optimize marketing strategies.  

**Description:** This project involved clustering customers using K-Means to identify patterns based on income, age, and spending score.

**Skills:** Data preprocessing, clustering, visualization, Exploratory Data Analysis(EDA).

**Technology:** Python, scikit-learn, matplotlib, pandas, seaborn.  

**Results:** Identified distinct customer groups, leading to actionable marketing strategies

**Key Findings:** powerpoint link 

---

### **SQL**
#### Sales Data Cleaning and Analysis  
**Code:** [Sales_Data_Cleaning.sql](#)  
**Description:** Cleaned and analyzed sales transaction data to uncover trends and optimize reporting.  
**Skills:** Joins, aggregate functions, data cleaning, querying.  
**Technology:** SQL Server.  
**Results:** Improved data quality and provided key insights into product performance.  

---

## **Education**
- **Bachelor of Science in [Your Major]**, [Your University], [Year of Graduation]  
- Relevant coursework: [List key subjects if applicable]  

---

## **Certificates**
- Google Data Analytics Professional Certificate (Completion Date)  
- Python for Data Science (Completion Date)  
- [Other relevant certificates you have earned]  

---

## **Contact Information**
- **LinkedIn:** [Your LinkedIn Profile](#)  
- **Email:** [Your Email Address](#)  











# Rosie Osi - Data Analyst Portfolio

This portfolio houses projects that I am passionate about 

## Project 1 Shopping Customer Segmentation & Clustering
### Overview
This project applies unsupervised machine learning through clustering to identify target customers for a marketing campaign. By analyzing demographic and behaviorial factors distinct customer groups are identified and tailored strategies are recommended based on their behaviors.

### Project Motivation
In today's competitive business landscape, understanding customer behavior is essential for creating impactful marketing campaigns. This project segments customers based on income, age, and spending score to uncover actionable insights. By identifying distinct customer groups, businesses can implement targeted strategies that resonate with each segment, improving satisfaction, engagement and conversion rates.

### Dataset 
The dataset used in this project is sourced from [AbsentData](https://absentdata.com/data-analysis/where-to-find-data/) It includes key features such as:

* Income: The annual income of the customer
* Age: The age of the customer
* Gender: Whether the Ccustomer is male or female
* Spending Score: A score based on the customer's purchasing behavior

Data preprocessing steps included checking for missing values, standardizing numerical features, and normalizing where necessary for clustering

### Methodology 

1. Data Preprocessing:
* Performed quick Exploratory Data Analysis (EDA) to understand data distribution and identify anomalies
* Encoded categorical variable "Gender" into a numeric variable (1 or 0) to ensure compatibility with machine learning algorithms
* Normalized data for effective clustering
  
2. Clustering Algorithm:
* Applied K-Means clustering to segment customers based on income, age, gender, and spending score
* Determined the optimal number of clusters using the elbow method
  
3. Evaluation:
* Visualized cluster distributions and analyzed patterns within each group to identify actionable insights
* Used summary statistics on each cluster to understand their key characteristics

### Key Findings

<img src="https://github.com/user-attachments/assets/917ceed5-f225-4bb5-b41b-ef5a17ec35ac" align="left" width="400" alt="Clustering Visualization">

As can be seen, customers were segmented into **5 distinct groups**, each characterized by unique behaviors and demographic profiles:  

- **Cluster 0**: The target group with high income and spending score 
  * 53% of shoppers in this cluster are women. A marketing campaign focused on popular items within this cluster, tailored to women's preferences, would be beneficial
- **Cluster 4**: Low income but high spending score—this presents an intriguing opportunity for targeted marketing. Marketing strategies focusing on value-driven offers and loyalty programs could attract customers in this group.  

These insights provide a foundation for implementing tailored marketing strategies that cater to each group’s specific needs, enhancing customer engagement and increasing conversions.


