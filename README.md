📊 Flipkart Customer Service Satisfaction (CSAT) Prediction
📌 Project Overview

Customer satisfaction is a critical factor in the highly competitive e-commerce industry. This project focuses on analyzing customer support interactions and predicting Customer Satisfaction (CSAT) using Machine Learning techniques. The objective is to identify key drivers influencing CSAT and provide actionable insights to improve customer service performance.

🎯 Business Problem

Flipkart receives a large volume of customer support interactions across multiple channels. Understanding which factors impact customer satisfaction can help:

Improve service quality

Optimize agent performance

Reduce resolution time

Increase customer retention and loyalty

This project aims to build a classification model that predicts CSAT scores based on customer interaction and agent-related features.

📂 Dataset Description

The dataset contains customer support interaction details, including:

Channel name (support channel)

Issue category and sub-category

Customer remarks

Order details and timestamps

Product category and item price

Agent details (name, tenure bucket, shift)

Handling time

CSAT Score (target variable)

🧠 Approach & Methodology

Exploratory Data Analysis (EDA)

Understanding customer behavior

Analyzing channel effectiveness

Studying agent performance and handling time

Identifying patterns affecting CSAT

Data Cleaning & Preprocessing

Handling missing values and outliers

Encoding categorical variables

Feature scaling where required

Addressing class imbalance

Feature Engineering

Time-based features

Agent tenure and shift-related attributes

Interaction-level derived metrics

Model Building

Implemented multiple ML classification algorithms

Train-test split for model evaluation

Compared performance using relevant metrics

Model Evaluation

Accuracy and classification metrics

Model comparison and selection

Interpretation of results

Insights & Conclusions

Identified key factors impacting CSAT

Derived actionable recommendations for improving customer support experience

🛠 Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn

Environment: Jupyter Notebook

📈 Key Learnings

Importance of feature engineering in customer analytics problems

Handling real-world issues such as missing values and class imbalance

Translating ML outputs into business-relevant insights

End-to-end ML workflow from problem understanding to conclusion

📎 Project Structure                        
├── data/                         
│   └── customer_support_data.csv                
├── notebooks/                  
│   └── Flipkart_CSAT_Analysis.ipynb                    
├── README.md                   

🚀 Future Enhancements

Experiment with advanced models (XGBoost, LightGBM)

Apply NLP techniques on customer remarks

Model deployment using Streamlit or Flask

Integration with cloud platforms (Azure / AWS)

👤 Author

Rajabhishek Aditya
📧 Email: rajabhishekaditya@gmail.com

🔗 LinkedIn: https://linkedin.com/in/rajabhishek-aditya

💻 GitHub: https://github.com/rajabhishek-tech
