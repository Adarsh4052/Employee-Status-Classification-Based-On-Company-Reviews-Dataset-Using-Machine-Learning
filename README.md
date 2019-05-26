# Employee-Status-Classification-Based-On-Company-Reviews-Dataset-Using-Machine-Learning

This project specifically focuses on the opinions of the employees about the company and how the reviews given by them can be categorized in the form of employment status such as a current employee or former employee. In this project, I have used Machine learning algorithms to find out if the employees are former or current employees of a company depending on the feedback they gave.

Project consists the following steps:

A. Data Preprocessing 
- Class Imbalance
- Data Cleaning
- Treatment of missing values
- Feature Engineering
- Text Preprocessing with NLP
- Conversion of Categorical features into Numerical features
- Normalization

Project was mainly divided into 3 parts after data preprocessing:
- Experiement 1: Predictive Modeling with Numeric Data only
- Experiement 2: Predictive Modeling with Text Data only
- Experiement 3: Predictive Modeling with Numeric and Text Data


B. K-fold Cross-Validation

Machine Learning Models used:-

1. Rule-based model - Dummy Classifier
2. Linear Classifier - Logistic Regression, Linear SVC
3. Tree-based Model - Decision Tree Classifier
4. Distance-based model - K Neighbors Classifier
5. Probabilistic model -	Multinomial Naïve Bayes
6. Ensemble - 	ADABoost , Bagging Classifier, Random Forest Classifier, Voting Classifier

C. Model Evaluation - (Accuracy, Precision, Recall, F1-Score, AUC)

D. Statistical Testing

E. Fine Tuning the Model for Performance

Dataset:

employee_reviews.csv: This is our original dataset downloaded from

https://www.kaggle.com/petersunga/google-amazon-facebook-employee-reviews/home

Description of the Dataset features: 
This dataset contains employee reviews for various companies. A description of each feature is defined in the following:
1) Index: Provides the index for different rows
2) Company: Name of the company
3) Location: Provides the city names and states with countries as optional. Ex: Phoenix, AZ or Toronto, ON(Canada)
4) Date Posted: Date posted for the review in the following format DD MM YYYY
5) Job-Title: Job title of the reviewer along with their employment status at the time when the review was posted. The employment status could be either ’current- employee’ or ’former-employee’
6) Summary: A short summary of the employee review
7) Pros: Pros of the company and the job position
8) Cons: Cons of the company and the job position
9) Advice to management: Review on the management of the company
10) Overall Rating: An ordinal data scaling from 1-5 with 1 being the lowest rating and 5 being the highest rating
11) Work/Life Balance Rating: 1-5 scale rating
12) Culture and Values Rating: 1-5 scale rating
13) Career Opportunities Rating: 1-5 scale rating
14) Comp & Benefits Rating: 1-5 scale rating
15) Senior Management Rating: 1-5 scale rating
16) Helpful Review Count: Gives the count value on how many people found the reviews to be helpful
17) Link to Review: Direct link to the page that contains the review. However, it is likely that some links will be outdated
NOTE: ’none’ is placed in all cells where no data value is found.

The Jupyter Notebook is very descriptive, so it should be easy to understant the project.
