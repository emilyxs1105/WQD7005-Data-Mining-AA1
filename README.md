# WQD7005-Data-Mining-AA1
This repository is created for WQD7005 Data Mining alternative assessment Semester 1 2023/2024. The study is related to Customer Behavior Analysis using Python, Talend Data Preparation Desktop Free version, Talend Open Studio for Data Integration and SAS Enterprise Miner.

## Case Study Objectives:
1. conduct comprehensive analysis of customer behavior and
2. utilize decision tree model and ensemble model for churn prediction.

This objective aimed at gaining actionable insights into the diversity of customer behaviors, facilitating targeted marketing strategies, and improving personalized customer experiences. Also, the case study objective sought to enhance retention strategies and optimize loyalty programs for improved customer satisfaction and loyalty.

## Role of used Software:
1. Python: used to generate a sample dataset that align with the specified requirements for this case study from the original dataset.
2. Talend Data Preparation Desktop Free version:
   - utilized for data preprocessing,
   - modify incorrect datatype of the columns,
   - group similar class under categorical variables, and
   - data transformation.
4. Talend Open Studio for Data Integration: remove duplicates values in the dataset.
5. SAS Enterprise Miner:
   - impute missing value,
   - create training and validation set,
   - apply decision tree analysis to the dataset,
   - apply ensemble method model (bagging, boosting) to the dataset, and
   - build predictive model.

## Dataset
The dataset utilized in this case study comprises 1021 records, encompassing 12 attributes related to customer transactions sourced from the Amazon website. The original dataset, available on Kaggle (https://www.kaggle.com/datasets/earthfromtop/amazon-sales-fy202021/data), initially contains a total of 35 columns. For the purpose of this study, a subset of 1021 records were selected, focusing on specific columns including 'cust_id,' 'age,' 'Gender,' 'State,' 'total,' 'category,' 'order_date,' 'payment_method,' and 'full_name.' To align with the specified dataset structure, modifications and aggregations were applied to the obtained dataset.

## Code and Script
- DataMiningAA.zip: SAS Enterprise Miner Project file
- Generate Customer Behavior Dataset.ipynb: Python code to generate dataset
- TalendOpenStudioProj.zip: Talend Open Studio Integration Project file
- customer_v3.csv: dataset csv file
