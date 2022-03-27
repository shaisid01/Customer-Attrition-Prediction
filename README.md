# Customer-Attrition-Prediction

Capstone Project
Data Science Career Track, Springboard
Thanks to mentor Julian Jenkins III
<br />Build a predictive analysis on the credit card dataset to understand whether the customer churn or not, and identify the reasons for them to leave.

<br />I have used a credit card datset.Credit cards are a good source of income for banks because of different kinds of fees charged by the banks like annual fees,balance transfer fees, and cash advance fees, late payment fees, foreign transaction fees, and others. Some fees are charged to every user irrespective of usage, while others are charged under specified circumstances.
#### Objectives:
<br />●Explore the dataset and visualize the same
<br />●Build a model to predict the customer is going to churn or not
<br />●Optimize the 3 models with appropriate techniques
<br />●Generate a set of insights and recommendations that may help the bank
#### Data Source
From google data search
https://www.kaggle.com/c/1056lab-credit-card-customer-churn-prediction/data
#### Data Wrangling
There are 10127 rows and 23 columns. Here are the steps performed to clean and oraganize
the data.
<br />● Checked for missing values
<br />● Checked for Null
<br />● Checked for missing values
<br />● Checked for unique values
<br />● Weird values or filled, for example “unknown”
<br />● Corrected weirdly formatted values(income category)
<br />● From the initial look on data, found below information.
#### <b>My target variable is :Attrition_Flag: if the account is closed then "Attrited Customer" else "Existing Customer"</b>
#### Feature Scaling and Distribution:
4 different types scaling is applied -
<br />1. z-score scaling : Approximately normally distributed
<br />2. Divided by Median: related by magnitude or right skewed
<br />3. Log scaling:related by magnitude
<br />4. Square root : for counts
<br />![image](https://user-images.githubusercontent.com/87315447/160265343-4e7becfa-7992-40d7-89f3-d5b52837e66f.png)

