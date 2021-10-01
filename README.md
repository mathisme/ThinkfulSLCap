# Supervised Learning Capstone: Predict loan repayment
My repository for Thinkful's Data Science Flex program's capstone 2 on supervised learning

With this capstone project we were to go out and find a dataset of interest, explore the data, and model an outcome of interest.

For this project I chose the Loan Data dataset on Kaggle, https://www.kaggle.com/itssuru/loan-data

My interest in this dataset was the opportunity to tackle imbalanced data.  We did not go into detail on how to handle imbalanced data in the bootcamp so I needed to research this on my own.

# Included in the repository 
* Capstone.ipynb -- the main notebook
* Capstone2.pptx -- the PowerPoint presentation
* Notebooks folder -- scratch work

# Steps included
* An exploratory data analysis of the data
* Tackling imbalance using Imbalanced-learn's RandomUnderSampler and RandomOverSampler as well as moving the classification threshold
* Training the data using random forests, logistic regression, and k nearest neighbors and utilizing pipelines in Scikit-learn to avoid data leakage
* Evaluating the models on a test set using F1 score, precision and recall.  Accuracy was not used as it is not effective for imbalanced data.
* Choosing the best model and making suggestions to improve the model

# Discoveries/Reflections
* I felt the dataset did not include enough information to create a good model for predicting loan repayment.  However the performance may have been better if I used SMOTE.  I plan to add SMOTE to the notebook in the future.
* I had attempted GridSearchCV for hyperparameter tuning however left it out of my final noteboook as it did not improve results.  Some sample use of GridSearchCV can be found in various notebooks in the notebooks folder.  

# Tools used
* Numpy
* Pandas
* Seaborn
* Matplotlib
* Scikit-Learn pipelines
* Scikit-learn KNeighborsClassifier, RandomForestClassifier, LogisticRegression
* Imbalanced-Learn

# Tasks for the future
* Utilize Imbalanced-Learn SMOTE oversampling.  In my project I utilized random undersampling and random oversampling but at the suggestion of the grader of my presentation I should use SMOTE.
* Restructure the PowerPoint.  My PowerPoint presentation did not have a proper structure according to the data scientist from Thinkful I was presenting to.  He was very generous to give an outline of a proper structure.  In the future I would like to restructure my PowerPoint.
* Utilize other supervised learning algorithms.  I started notebooks to use XGBoost, SVM, and decision trees but did not complete them.
* Add AUC to metrics used to evaluate models.
