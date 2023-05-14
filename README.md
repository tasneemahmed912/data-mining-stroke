# stroke
Stroke Prediction with Machine Learning
Description
This project focuses on predicting the likelihood of an individual having a stroke using a machine learning model. The project uses a dataset collected from a survey with variables such as age, gender, smoking status, hypertension, heart disease, etc.

Data
The dataset contained missing values and was unclean. I processed the data and handled the missing values and unclean data. I also noticed an imbalance problem in the smoking column due to parent applying for their children's application, which I addressed during data preprocessing.

Imbalance
I handled the imbalance problem in the smoking column by undersampling the majority class and oversampling the minority class.

Machine Learning Model
I used a logistic regression model to predict the likelihood of an individual having a stroke. I also performed feature engineering to select the best features for the model.

Performance Metrics
I used both accuracy and F1 score as the performance metrics to evaluate the model's performance. The model achieved an accuracy of 96% and an F1 score of 0.80.

Dependencies
This project requires Python 3.0 or later and the following libraries: pandas, numpy, scikit-learn, matplotlib, and seaborn.
