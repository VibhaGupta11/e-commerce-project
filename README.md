# E-Commerce Data Analysis and Clustering
This project involves analyzing and clustering e-commerce purchase data to uncover patterns in customer behavior, product categories, and brands. The cleaned data is used for exploratory analysis, visualization, and clustering using K-Means, Hierarchical Clustering, and Association Rule Mining.

## Table of Contents
* [Overview](#overview)
* [Dataset Description](#dataset-description)
* [Technologies Used](#technologies-used)
* [How It Works](#how-it-works)
* [Results](#results)
* [Association Rule Mining](#association-rule-mining)
* [Status](#status)
* [Contact](#contact)

## Overview
This project focuses on analyzing and clustering e-commerce transaction data to:
-	Identify trends in product categories and brands.
-	Determine the most expensive and cheapest products across categories.
-	Cluster products based on purchase behavior and product attributes.
-   Discover relationships between product categories, brands, and purchase behaviors using association rule mining.

## Dataset Description
The dataset includes information about:
-	Product attributes: product_id, category_code, brand, price.
-	Transaction details: event_time, user_id, category_id.
-	The data was cleaned to remove duplicates, missing values, and anomalies such as entries with impossible timestamps.

## Technologies Used
-	Python Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, scipy, mlxtend.
-	Clustering Algorithms: K-Means, Hierarchical Clustering.
-   Association Rule Mining: Apriori Algorithm.
-	Visualization: Seaborn and Matplotlib for creating interactive and static plots.

## How it Works
###  **1. Data Cleaning:**
-	Fixed column swapping issues in the dataset.
-	Removed duplicate and invalid rows (e.g., data from 1970).
-	Ensured numerical consistency in the price column.

###  **2. Exploratory Data Analysis:**
-	Visualized trends in price and purchase activity over time.
-	Identified top categories and brands based on the number of purchases.

###  **3. Clustering:**
-	Applied K-Means and Hierarchical Clustering to group products.
-	Analyzed clusters to identify distinct product characteristics.

###  **3. Association Rule Mining:**
-   Used the Apriori algorithm to discover significant patterns in transaction data.
-   Evaluated rules based on support, confidence, and lift metrics.
-   Generated actionable insights about product combinations frequently purchased together.

## Results
  **Key Insights:**
-	Top 10 categories and brands by number of purchases.
-	Identification of most expensive and cheapest products.
-	Clusters summarizing product pricing and popular categories/brands.

  **Cluster Analysis:**
-	Insights into the product segmentation and customer preferences.

## Association Rule Mining
Association Rule Mining was performed using the Apriori algorithm to identify relationships between frequently purchased products. Key findings include:

###  **Key Rules:**
**1. Samsung Headphones & Smartphones:**
-  **Rule:** Samsung headphone buyers often purchase Samsung smartphones.
-  **Confidence:** 20.87%, Lift: 1.45

**2. Dogland Pillows & Apple Smartphones:**
-  **Rule:** Customers buying Dogland pillows frequently purchase Apple smartphones.
-  **Confidence:** 55.60%, Lift: 14.07

**3. Samsung & Awax Smartphones:**
-  **Rule:** Samsung smartphone buyers often purchase Awax smartphones.
-  **Confidence:** 2.65%, Lift: 3.59

**4. TVs & Smartphones:**
-  **Rule:** Customers purchasing Megogo or Okko TVs commonly buy Awax smartphones.
-  **Confidence:** 82.60%, Lift: ~110

### **Insights:**
-   Cross-marketing opportunities exist between home decor and electronics (e.g., pillows and smartphones).
-   TVs and smartphones show strong co-purchase trends, suggesting bundled promotions.
-   High lift values for TVs and Awax smartphones indicate niche customer preferences.

## Status
This project is complete, and further analysis or feature additions can be built on top of the existing framework.

## Contact
Feel free to reach out for collaboration, feedback, or questions.  
**Created by:** Vibha Gupta  

Connect with me:  
* **Email:** [vgupta14@horizon.csueastbay.edu]
* **GitHub:** [https://github.com/VibhaGupta11] 
* **LinkedIn:** [https://www.linkedin.com/in/vibha-gupta-42307699/]
