# Chronic Kidney Disease Prediction

The Chronic Kidney Disease Dataset is a medical dataset consisting of laboratory measurements of patients. The dataset is available in the CSV format and has information on 26 variables with 400 datapoints. This dataset is used to predict the presence of chronic kidney disease in patients. In this project, we will use machine learning techniques to analyze and build a model for the Chronic Kidney Disease dataset.

## Exploratory Data Analysis
Firstly, I performed exploratory data analysis on the dataset. I visualized the distribution of numerical variables using box plots, scatter plots, and histograms. I also imputed missing numerical data using the median value of each column. Categorical variables were visualized using a bar plot and imputed missing categorical data using the mode of each column. Finally, I also used one-hot encoding to convert categorical variables to numerical variables.

## Model Training
After completing the exploratory data analysis, I split the dataset into training and testing sets using a 70:30 ratio. I used StandardScaler to scale numerical data and built a Random Forest Classifier model to predict chronic kidney disease in patients. I used GridSearchCV to tune hyperparameters for the Random Forest Classifier model with a 5-fold cross-validation. The best hyperparameters were chosen based on the F1 score, which is the harmonic mean of precision and recall. The model achieved an F1 score of 99%.

## Conclusion
The Chronic Kidney Disease dataset has valuable information for predicting chronic kidney disease in patients. I analyzed the dataset using exploratory data analysis techniques and built a Random Forest Classifier model to predict chronic kidney disease. The model achieved high performance, indicating its usefulness in predicting chronic kidney disease.
