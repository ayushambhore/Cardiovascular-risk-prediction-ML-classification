This project focused on the prediction of Coronary Heart Disease (CHD) risk based on a dataset containing demographic, behavioral, and medical history features of patients. The dataset included information on gender, age, smoking status, blood pressure medication, previous stroke history, hypertension, diabetes prevalence, and various medical measurements.

The initial exploratory data analysis revealed interesting insights, such as a slightly higher number of females in the dataset and more non-smokers than smokers. Age was found to be a significant risk factor for CHD, and certain medical measurements like cholesterol levels, blood pressure, BMI, heart rate, and glucose levels showed distinct patterns.

To preprocess the data, missing values were handled by dropping rows with missing values, and outliers were treated using the Interquartile Range (IQR) method for continuous variables. Categorical variables were encoded, and feature manipulation and selection were performed to enhance the model's performance.

The dataset was then split into training and testing sets, and to handle the class imbalance issue, the Synthetic Minority Over-sampling Technique (SMOTE) was applied.

Eight different machine learning models, including Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and XGBoost, were trained and evaluated on the dataset.

The evaluation results demonstrated promising performance for all models, with high accuracy, precision, recall, F1 score, and ROC AUC values on both training and test datasets.

The Logistic Regression model displayed stable performance with no signs of overfitting, making it a reliable choice for the task.

The Decision Tree model exhibited perfect accuracy on the training dataset but slightly worse performance on the test dataset, indicating some overfitting.

The Random Forest model demonstrated robust performance on both datasets but also showed signs of overfitting.

The KNN model achieved perfect accuracy on the training dataset, but its performance on the test dataset was still promising, making it a viable option.

The SVM model demonstrated stable and consistent performance on both datasets, showcasing good generalization capabilities.

The XGBoost model emerged as the best-performing model with high accuracy, precision, recall, F1 score, and ROC AUC values on both datasets. It exhibited strong generalization capabilities and minimal overfitting, making it the most reliable and efficient model for this classification task.

In summary, this project successfully developed and evaluated machine learning models to predict the risk of Coronary Heart Disease. The XGBoost model proved to be the most robust and reliable model, offering accurate and precise predictions. The insights gained from this project could be valuable for medical practitioners and policymakers to identify individuals at higher risk of CHD and implement preventive measures accordingly. However, further research and analysis with a larger dataset could enhance the model's performance and provide more comprehensive insights into CHD risk factors.
