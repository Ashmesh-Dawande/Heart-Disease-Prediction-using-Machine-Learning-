# Heart-Disease-Prediction-using-Machine-Learning-
Heart disease is a leading cause of death worldwide. Predicting the likelihood of a person having heart disease can aid in early detection and timely intervention. In this project, we will use machine learning techniques to develop a predictive model for heart disease.
We use the kaggle dataset which contains the following attributes-
1. Age; 2. Sex/Gender (1 for male and 0 for female) ;  3. Chest pain, 4 levels (Value 0: typical angina, Value 1: atypical angina, Value 2: non-anginal pain, Value 3: asymptomatic); 4. Resting Blood Pressure; 5. serum cholesterol (mg/dl); 6.  fasting blood sugar (1 if fbs >120 , 0 otherwise); 7. resting electrocardiographic (ecg) results (values 0, 1, 2); 8. Maximum heart rate achieved; 9. exercise-induced angina (1 for yes, 0 for no); 10.  ST depression induced by exercise relative to rest; 11. the slope of the peak exercise ST segment; 12. number of major vessels (0–3) colored by flourosopy; 12. A blood disorder called thalassemia (0 = normal; 1 = fixed defect; 2 = reversible defect)

## Project Steps
1.) Data Exploration: Load and explore the dataset to gain insights into the available features, their distributions, and potential relationships with the target variable (presence or absence of heart disease).

2.EDA : We will build several plots graphs to find relationship in the dataset. Like how many people in the dataset have heart disease.Like wise the age wise distribution also gender wise distribution and many more.

3. Data Preprocessing: First we check for null values if we found any we will drop it or use different methods to remove the null values.Then we will remove the Outliners by calculating the zscore of the numerical features of the dataset. And we will remove the data which zscore is greater than out threshold zscore. Then we will do feature scaling using a Scaler in this we will be using MinMaxScaler for our numerical data. And finally we will do train_test_split.

4.  Model Building : Now we will use many Machine Learning algorithms such as Linear Regression , Logisitic Regression , K- Nearest Neighbours with different K values , Decision Tree Classifier , Random Forest , SVM and Navie Bayes and perform Cross Validation. After that we got the mean training accuracy for 10 folds cross validation and we compared the accuracy of different models.
And then we fit the model with and we predict the x_test values and finally we find the accuracy score , log_loss, recall score , percision .







