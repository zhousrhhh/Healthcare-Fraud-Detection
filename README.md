# Healthcare-Fraud-Detection

Roughly one-third of the $3.3T spent on healthcare in the US is attributable to fraud, waste, and abuse. The US Medicare system is particularly susceptible fraud and abuse, since it is harder to exclude problematic providers and is managed separately and with limited coordination across the states. In recent years, machine learning and data mining techniques are being used to address this problem. When constructing a healthcare fraud detection model, it is very important to extract the right features from the data.

> Objectives: The [first report](1-Feature-Engineering-and-Exploratory-Data-Analysis-for-Healthcare-Fraud-Detection.ipynb) uses a real dataset to conduct the Exploratory Data Analysis (EDA) and Feature Engineering (FE) process for healthcare fraud/abuse detection. The main objective is to create some useful features, that can capture the hospital reimbursement patterns and detect the anomalities. With the anomalities detected, we can further investigate the specific hospital and make alerts to potential fraud/abuse.
> 1. Detect any hospital that may abuse the resources compared to the average or median of its peers with the same DRG and Zipcode.
> 2. Detect any hospital that may abuse the resources compared to the average or median of its peers with the same DRG and City.
> 3. Detect any hospital that may abuse the resources compared to the average or median of its peers with the same DRG and State.
>> The [second report](2-Healthcare-Fraud-Detection-unsupervised-learning-I.ipynb) uses a real dataset to conduct healthcare fraud/abuse detection. In this project, I will use unsupervised learning methods (PCA and KNNs) to revise the features and identify anomalous hospitals that may abuse/defraud healthcare resources.
> The [third report](3-Healthcare-Fraud-Detection-unsupervised-learning-II.ipynb) report uses a real dataset to conduct healthcare fraud/abuse detection. In this project, I will use unsupervised learning methods (iForest and Autoencoder) to revise the features and identify anomalous hospitals that may abuse/defraud healthcare resources.

> Dataset: The Medicare Inpatient Hospitals by Geography and Service dataset provides information on hospital discharges for Original Medicare Part A beneficiaries by IPPS hospitals. This dataset contains information on the number of discharges, payments, and submitted charges organized by geography and Medicare Severity Diagnosis Related Group (DRG).
