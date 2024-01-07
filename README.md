# WQD7005-DataMining

# Title: Customer Behavior Analysis in E-Commerce

# Objective:
This case study is designed to assess the application of decision tree and ensemble methods in analyzing customer transaction data from an e-commerce website. Students are expected to demonstrate their understanding of these methods and their ability to derive meaningful business insights through data analysis.

•	Practical Application: Demonstrate the practical use of decision tree and ensemble methods in analyzing customer data.
•	Business Insights: Show how data analysis can translate into actionable business strategies.

# Overview:
Students will work with a dataset comprising customer attributes and their purchase history over the last year. The primary goal is to understand customer behavior and identify patterns that can lead to increased sales and customer retention.

# Prepare Dataset
In the first step of this report, two approaches were taken to address the dataset requirements for AA1:

-Seeking an Existing Dataset: The initial strategy involved searching for existing datasets that align with the specified structure and attributes. This search was conducted through various online repositories such as the UCI Machine Learning Repository, Kaggle, and databases from government or educational institutions, which are known for their wide range of publicly available datasets.

-Creating a Custom Dataset: Recognizing the possibility that an existing dataset might not fully meet the specific needs of this assessment; the decision was also made to create a bespoke dataset. This involved gathering data from multiple sources, ensuring that it closely mirrors the criteria set out for AA1.

It's essential to guarantee that the dataset accurately reflects genuine customer behaviors in e-commerce, as this is vital for conducting significant analyses and applying them effectively in real-world contexts. The primary objective should be to encompass a broad spectrum of customer engagements and transactions that are commonplace in e-commerce environments. Incorporating this variety in the dataset enhances the relevance of the analysis, enabling it to resemble actual scenarios more closely, even in cases where the dataset is not extensive. Therefore, a dataset from Kaggle was initially selected as a foundation. To enhance its relevance and comprehensiveness, additional attributes were incorporated. Furthermore, the use of data generators was considered to facilitate the creation of a dataset that not only meets the assessment's requirements but also provides a controlled environment for testing various analytical methods. A key consideration in this process was ensuring that the generated data is realistically representative of e-commerce customer behavior. This is crucial to ensure that the analysis derived from this dataset is meaningful and applicable to real-world scenarios.

# Dataset Structure:

- Customer_ID:	A unique identifier assigned to each customer. It's categorical but without an intrinsic order.
- Age:	The age of the customer. It's a quantitative measurement with a true zero point.
- Gender:	The gender of the customer, assuming two gender categories are represented (e.g., Male, Female).
- City:	The city where the customer resides. It's categorical without an intrinsic order.
- Membership_Type:	Type of membership indicating a rank or order (e.g., Bronze < Silver < Gold).
- PreferredLoginDevice:	The device type preferred by the customer for login, which is a categorical variable.
- Average_Rating:	The average rating can be seen as an interval data type since it has an arbitrary zero point.
- Last_Purchase_Date:	Dates are typically interval data as they do not have a true zero point and can be measured in intervals.
- Last_Purchase:	The number of days since the last purchase, which is a count and has a true zero point.
- Satisfaction: Level	Represents an ordered classification of satisfaction, but the intervals between levels are not necessarily equal.
- Product_Category:	The category of the product is a categorical variable without any order.
- Total_Purchase_Amount:	The total amount spent is a quantitative measurement that can be measured from a true zero point.
- Churn:	An indicator variable where '1' mean churned and '0' means not churned.


# Tools:
SAS e-Miner: Used for building decision tree models. It will enable students to visually explore data, select appropriate modeling techniques, and validate models.

Talend Data Integration: Utilized for integrating and transforming data from various sources into a unified format suitable for analysis.

Talend Data Prep: Employed for cleaning and preparing the dataset. It simplifies handling missing values, outlier detection, and normalization of data.

# Project Tasks:
Data Preparation: Use Talend Data Prep to clean and normalize the data.
Data Integration: Employ Talend Data Integration to consolidate data sources.
Model Building: Utilize SAS e-Miner to create decision tree and ensemble models.
Analysis: Interpret the models to understand customer behavior and identify key factors influencing purchase decisions.
Business Insights: Derive insights that can inform strategies for increasing sales and improving customer retention.
