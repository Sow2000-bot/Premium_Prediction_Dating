# Premium_Prediction_Dating

### Introduction

In the rapidly evolving realm of online dating, understanding the factors influencing user behavior and preferences is crucial for enhancing matchmaking algorithms and improving user experiences. This study focuses on predicting whether an individual will purchase a VIP subscription on an online dating platform based on demographic and behavioral data. The dataset used for this analysis includes variables such as gender, income, children, age, attractiveness, and the number of matches. We employ machine learning techniques, specifically Logistic Regression, Random Forest, and Gradient Boosting classifiers, to build predictive models. The performance of these models is evaluated and compared to determine their effectiveness in predicting VIP subscription purchases.

### Abstract

This study utilizes machine learning techniques to predict the likelihood of users purchasing a VIP subscription on an online dating platform. The dataset, sourced from Kaggle, encompasses demographic and behavioral attributes, including gender, income, parental status, age, attractiveness, and the number of matches. We preprocess the data by scaling the features and apply three different classifiers: Logistic Regression, Random Forest, and Gradient Boosting. The models are trained and tested on this dataset, and their accuracy is evaluated. Logistic Regression achieved an accuracy of 76.33%, while Random Forest and Gradient Boosting attained 71.67% and 72.33% accuracy, respectively. These findings provide insights into the predictive power of various classifiers for understanding online dating behaviors.

### Results

1. **Data Preprocessing:**
   - The dataset contains no missing values and all columns are of integer type.
   - Features are scaled using StandardScaler to improve model performance.

2. **Logistic Regression:**
   - Accuracy: 76.33%
   - Model was trained and tested on scaled data.
   - Prediction for a new data point [Gender: 0, Income: 2000, Children: 1, Age: 29, Attractiveness: 8, Matches: 10]: 0 (Not Purchased VIP).

3. **Random Forest Classifier:**
   - Accuracy: 71.67%
   - Model was trained and tested on scaled data.
   - Prediction for a new data point [Gender: 0, Income: 2000, Children: 1, Age: 29, Attractiveness: 8, Matches: 10]: 0 (Not Purchased VIP).

4. **Gradient Boosting Classifier:**
   - Accuracy: 72.33%
   - Model was trained and tested on scaled data.
   - Prediction for a new data point [Gender: 0, Income: 2000, Children: 1, Age: 29, Attractiveness: 8, Matches: 10]: 0 (Not Purchased VIP).

5. **Model Comparisons:**
   - Logistic Regression outperformed the other models in terms of accuracy.
   - All models consistently predicted that the example individual would not purchase a VIP subscription based on the provided features.

This analysis demonstrates the application of machine learning models to predict user behavior in online dating, with Logistic Regression showing the highest accuracy. The insights from these models can help online dating platforms tailor their services and marketing strategies to better meet user needs and preferences.
