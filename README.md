# Binary Classifiers performance metrics comparison

Predictive maintenance (PdM) is designed to assist companies to determine the time for repair
or changing the manufacturing parts right before being out of order. The main approach of
PdM is to reduce the future down-time costs of the device due to unexpected failures. In order
to achieve the approach with a good prediction having accurate information on the right time
is necessary. This information will be collected by different sensors installed on the equipment
helping PdM to improve performance in real-time. Accurate prediction with the collected then
cleaned data required a proper model which will be able to calculate the risk (probability) of
failure for a machine in each series of time. Selecting a proper model requires practice due to
having different specification and complexity of each algorithm.



Data preparation
 
-Wrangling data

Exploratory data analysis (EDA)

Algorithms comparison


# Data prepration:

Transforming the raw data to an exposable and more accessible set of data through analyzing for improving the quality is called data preparation. For data preparation knowing the data types is important. 

## Data wrangling:

The following table is a head of the collected raw data for 100 engines of planes which needs cleaning to be ready to use in the modeling processes (Garca, Luengo, & Herrera, 2014). As the table shows the training data with:

•	28 columns (with 20631 rows from the shape)

•	Missing data (there is no missing data in the data set)

•	No name columns

•	Extra space columns

# Exploratory data analysis (EDA):

Exploratory data analysis (EDA) applies mostly visual techniques analyzing the data to determine how the data should carry out. (Nisbet, Miner, & Yale, 2017) The purpose of EDA approaches is to:

•	dataset insight maximization

•	explore the underlying structures

•	important variables extraction

•	outliers and anomalies detection

•	optimal factors detection
 
 
 # Algorithms comparison

 Predictive maintenance objective is trying to predict the equipment failure in advanced then the system from this predictions schedules maintenance. Having a failure occurrence notice in advance can reduce maintenance frequency, decrease the time spent for repairing and the costs for maintenance. This case study explained the steps to draw a PdM model over feature engineering, label creation, training and evaluation via comparing different binary algorithms such as logistics regression, random forest and support vector machine with the typical performance metrics. These metrics are accuracy, precision, recall, f1 score and Receiver operating curves (ROC).  The best performance for binary models for predictive maintenance in this case study are random forest, logistic regression and last SVM with kernel respectively. For a larger amount of data logistics regression performs faster than SVM because logistics regression is simpler than SVM algorithm. The calculation of profit is not mentioned in this case study due to the expert related subject but in a brief will it will be calculated with a cost benefit matrix according to the true positives, true negative, false positive and false negative. By having a true positive (true negative) prediction the company will benefit of not having downtime costs and on the other side every false positive (false negative) will have cost.



