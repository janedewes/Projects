
Title: Predicting the Purchase Intent for E-Commerce Users (Web Analytics)

Developed in Python language.

Objective: Evaluate which attributes influence a user to purchase products online and build a predictive model to make predictions about future purchases.

To answer this type of question, we must analyze the variables that define the user's navigation through the web site, as well as which variables influence the target variable.
Only by doing an exploratory analysis on the categorical variables of the dataset can we already know if the sale occurred or not, which type of visitor, which sessions end in sales, if there are more sales during the week or at the weekend, in which systems operational, more sales occur, what type of traffic the user reached our website...
Also check which areas of the website are most accessed.
Sometimes the company does not sell online, but the website is a channel to attract customers, and it is important to know where to place information to attract customers.


This project is a classification problem, we can use algorithms like RandomForest, Naive Bayes, Logistic Regression, KNN, and compare the performance between them, for this project I chose the SVM (Support Vector Machine) algorithm.

Data source: Online Shoppers Purchasing Intention Data set 
https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset
The dataset consists of resource vectors belonging to 12,330 online sessions (server logs). The dataset was formed so that each session belongs to a different user over a period of 1 year to avoid any bias towards a specific campaign, special day, user, profile or period.
The dataset consists of 10 numeric and 8 categorical attributes. The attribute 'Revenue' can be used as the class label.


Steps:

1. Download and import the necessary packages.
2. Upload the data collected at the UCI.
3. Exploratory analysis of the data. 
4. Divide data into continuous and categorical variables. 
5. Create the graphics needed to visualize the behavior of these variables. 
6. Pre-process the data (according to the SVM algorithm!).
    - Convert text type columns to numeric.
    - Balance the target variable classes (Oversampling).

7. Predictive modeling (4 models)
    - a. Base model with Linear Kernel (from this model improvements will be made).
    - b. Model with Kernel and standardized data (Scaled) (so we can check if the standardization makes any difference).
    - c. Hyperparameter Optimization with Grid Search and RBF Kernel.
    - d. Hyperparameter Optimization with Grid Search and Polynomial Kernel.




Important detail:
This type of project must be done in real time!

That is, the collection must be done in real time (pipeline) and go to feed this predictive model, this may result in some action by the company.



