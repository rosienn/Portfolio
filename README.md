# Rosie's Portfolio

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
