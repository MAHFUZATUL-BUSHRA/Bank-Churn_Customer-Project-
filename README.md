# Bank Churn Analysis and Customer Segmentation Project
## Overview

### This project encompasses two key areas of data analytics for a bank:

  *  Bank Churn Analysis: Understanding the factors contributing to customer churn and building predictive models to reduce churn.
  *  Customer Segmentation: Segmenting customers to identify patterns and recommend tailored products or services.

The project utilizes a dataset containing demographic, account, and behavioral information of bank customers. Through cleaning, exploration, and modeling, we aim to provide actionable insights to improve customer retention and engagement.
## Objectives
### 1. Bank Churn Analysis

 * Explore the data to identify patterns in customer churn.
 * Clean and preprocess the dataset to make it suitable for machine learning models.
 * Build and evaluate classification models to predict customer churn.
 * Provide recommendations to reduce churn and enhance customer satisfaction.

### 2. Customer Segmentation

 * Prepare and preprocess the data for clustering models.
  *  Apply clustering algorithms to segment customers based on their demographic and behavioral attributes.
  *  Analyze each segment to understand customer characteristics and preferences.
  * Recommend tailored services or products for each segment.

### Datasets

  * Customer Demographics: Includes attributes like age, gender, geography, and estimated salary.
  * Account Information: Contains account balance, tenure, number of products, credit card usage, and churn status.

### Workflow
#### Step 1: Data Preparation

  *  Merged customer demographics and account information datasets.
  *  Cleaned and processed the data:
  *  Handled missing values.
  *  Removed duplicates.
  * Standardized categorical values and formats.
  * Engineered features for model improvement.

#### Step 2: Exploratory Data Analysis (EDA)

 * Analyzed distributions, correlations, and patterns in the data.
 * Visualized key metrics like churn rate, product usage, and customer demographics.

#### Step 3: Churn Prediction

  * Built classification models to predict customer churn.
  * Evaluated models using metrics like accuracy, precision, recall, and F1-score.
    ![p](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/churn/roc.png)
    ![p](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/churn/recall%20%26%20precision.png)
  * Identified top predictors of churn using feature importance analysis.
    ![p](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/churn/churn%20Features.png)

#### Step 4: Customer Segmentation

 ### Applied clustering algorithms (e.g., K-Means, Hierarchical Clustering) to identify distinct customer groups.
  ![p](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/customer_Seg_pictures/customer_Seg1.png)
  ![p](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/customer_Seg_pictures/customer_Seg2.png)

  ### Visualized clusters and analyzed their characteristics.
  ![p](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/customer_Seg_pictures/seg3.png)
  ![p](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/customer_Seg_pictures/seg4.png)

 ### Recommended marketing and product strategies for each customer segment.
 #### Recommendations:

   * Clsuter 0: Create an Entry-level Credit Card; Also, do some research on their Demographic Information.

   * Cluster 1: They have very high Balance, but likely to leave. So, try to keep them by offering them financial seminars or advisors or, maybe suggest investment opportunities.

   * Cluster 2: They are less likely to leave. We can reward them (French and Spanish Customers) for staying. We can introduce reward programs to encourage them to invest in more products.

   * Cluster 3: They have many products in a very short time. Churn rate is also relatively high. Since, they like products we may offer them products with higher tenure.

### Technologies Used

* Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.
* Tools: Jupyter Notebook/Google Colab for analysis and visualization.

### Key Findings
#### Churn Analysis

  * High churn is observed among customers with lower account balances and inactive accounts.
  * Younger customers with higher credit scores are less likely to churn.

#### Customer Segmentation

  * Segmented customers into distinct groups based on behavior and demographics.  
  * Identified segments that prefer premium services and those that respond to discounts.

### Future Steps

* Implement proactive retention strategies for customers identified as high risk of churn.
* Develop targeted marketing campaigns for different customer segments.
* Launch loyalty programs for segments with high product usage to enhance engagement.

### Run the Project
 ![Churn Prediction Analysis](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/Bank_Churn_Customer_Project.ipynb)
 
 ![Customer Segmentation Analysis](https://github.com/MAHFUZATUL-BUSHRA/Bank-Churn_Customer-Project-/blob/main/Bank_Customer_Segmentation.ipynb) 

