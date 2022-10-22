# Online-Payments-Fraud-Detection-Blossom-Bank
In 2018, fraud cost the world economy £3.2 trillion, according to Infosecurity Magazine. Fraud losses for some companies might amount to more than 10% of their overall expenses. Such significant losses encourage businesses to look for fresh ways to avoid, catch, and get rid of fraud. The most effective technology tool to combat financial fraud yet is machine learning. Payment fraud is any type of false or illegal transaction completed by a cybercriminal. The perpetrator deprives the victim of funds, personal property, interest or sensitive information via the Internet.

## Payment fraud is characterized in three ways:

-Fraudulent or unauthorized transactions

-Lost or stolen merchandise

-False requests for a refund, return or bounced cheques.

Ecommerce businesses rely on electronic transactions to charge customers for products and services. The increased volume of electronic transactions has also resulted in an increase in fraudulent activities.

Our case study, Blossom Bank also known as BB PLC is a multinational financial services group, that offers retail and investment banking, pension management, asset management and payments services, headquartered in London, UK. Blossom Bank wants to build a Machine Learning model to predict online payment fraud. At the end of this project, we should be able to:

 -Effectively detect and identify anomalies in the transactions that would normaly be undetected using traditional methods
 
 -Improve it's cyber sercurity policies.
 
 -Solidify the trust in the platform and amongst their customers by preventing fraudulent transactions.
 
 ## Methodology
 1. Problem Statement:
 Blossom Bank wants to build a Machine Learning model to predict online payment fraud. Fraud is a major issue in the banking system, in other to mitigate the fraud, we would select and predict the fraud using a machine learning model
 2. importing of libraries for data manipulation and visualization:
 Libraries like Pandas, Numpy for imported data manipulation while Matplotlib and Seaborn were imported for visualization.
 3. Data set for loaded using pd.read_csv("") from the local computer
 4. Identifying the first five columns and the last five columns of the data set using data.head() and data.tail()
 5. Exploraatory Data Analysis
 
 - Inspection of Data set: 
 
 i. identification of columns
 
 ii. Identifiying if there are unique vslues
 
 iii. checked if there are missing values and visualizing it using the heatmap
 
 iv. identified the shape of the entire data set
 
 v. Checked the info of the columns and data types
 
 vi. checked the statistical analysis of the data
 
 vii. outlier detection
 
 ## Relationship, insights and Visualizations
 -Univariate Analysis techniques was done and visualisation after creating a function that properly labels fraud_trans.
 
-Bivariate Analysis was done by comparing two categorical variables and its visualization.

-Multivariate Analysis was done with transaction types in relation to transaction amount and fraud status.

## Peforming Feature Engineering by encoding categorical variables. 
This implies that converting useful columns that are categorical into numerical columns so they can be featured or implemented in the machine learning model. The target feature was dropped, which fraud_trans

## Model preparation and deployment. 
Interpreting the results of the modelling, determining which of the models best fit the data and also realistic in post production and finally recommending business strategies to help the bank avoid losing money to fraud.

## Feature Engineering.
I observed that some columns would not be processed during the deployment of the models becuse that were categorical hence my decision to convert them to numerical values (encoding). I encoded the type column by creating 5 dummy columns being that there were 5 unique values in the type column. Created a new X train with only 4 features to see how they are able to fit properly on a new data set.

## Evaluating with Cross Validation.
In cross validation, the model splits the training data into multiple blocks. Using 1 block as test set for each training iteration, it trains the other blocks and validates against the test data.

This gives you an idea of how the model will perform when it sees new data in the real world that it hasn't seen before.

## Model Deployment
I deployed supervised machine learning models (classification and regression) Linear Regression, Random Forest and Decision Tree. Of the 3 models, Random Forest was the most accurate at detecting fraudulent transactions. Also, the confusion matrix also showed it had the best results post production.

Conclusion
Based on the insights and recommendations in the Stakeholders Report, if implemented, the bank will effectively detect and identify anomalies in the transactions that would normaly be undetected using traditional methods and also improve it's banking practices.
