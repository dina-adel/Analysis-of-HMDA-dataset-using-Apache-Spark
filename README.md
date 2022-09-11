# Analysis of the Home Mortgage Disclosure Act (HMDA) dataset using Apache Spark
Home Mortgage Disclosure Act (HMDA) is a US federal law that enforced banks to collect and share their mortgages’ data to the public in order to ensure they are not discriminating or misusing their money. The dataset can be found [here](https://www.consumerfinance.gov/data-research/hmda/historic-data/).
In this project, using PySpark, I worked on:
- Analyzing the HMDA public dataset (collected in 2014) to investigate the fairness of the mortgages approval criteria. 
- Building different supervised machine learning models, using PySpark, such as decision trees, naive bayes, and logistic regression to predict whether a loan request will be accepted or not.
- Building a very simple recommendation system. This system will check the applicant’s provided information and assess it. It will then either recommend some modifications to his application or tell him/her to proceed.
