# Property Price Prediction with Analytics & Recommendations

In this comprehensive capstone project, the primary focus was on leveraging data science techniques to provide insights, predictions, and recommendations in the real estate domain. The project unfolds through various stages, covering data gathering, cleaning, exploratory analysis, modeling, recommendation systems, and the deployment of a user-friendly application.

## Data Cleaning:

To prepare the dataset for analysis, a meticulous data cleaning process was undertaken, handling missing values and ensuring consistency.

## Feature Engineering:

The dataset underwent feature engineering to enhance its richness and informativeness. New features were introduced to provide a more detailed representation of the properties.

## Exploratory Data Analysis (EDA):

Univariate and multivariate analyses were conducted to uncover patterns and relationships within the data. 

## Outlier Detection, Missing Value Imputation:

Outliers were identified and removed to ensure the robustness of subsequent analyses. Missing values, particularly in critical columns like area and bedroom, were addressed using appropriate imputation techniques.

## Feature Selection:

Multiple feature selection techniques were employed to identify the most impactful variables for modeling. These included correlation analysis, random forest and gradient boosting feature importance.

## Model Selection:

In the Model Selection and Productionalization phase, an exhaustive comparison of various regression models was conducted to determine the most effective model for predicting property prices. The process involved implementing a detailed price prediction pipeline that incorporated encoding methods, ensuring the robustness and accuracy of the chosen model. 

The regression models considered in the comparison included:

1. **Linear Regression**

2. **Support Vector Regression (SVR)**

3. **Random Forest Regressor**

4. **Multi-layer Perceptron (MLP)**

5. **LASSO Regression**

6. **Ridge Regression**

7. **Gradient Boosting Regressor**

8. **Decision Tree Regressor**

The comparison involved assessing the performance of each model on relevant evaluation metrics, considering factors such as accuracy, precision, and recall. After careful evaluation, the most suitable regression model was selected based on its overall performance and ability to generalize to new data.

The chosen regression model was then integrated into a comprehensive price prediction pipeline, which included preprocessing steps, encoding methods, and handling of various features to ensure optimal performance. 

## Building the Analytics Module:

An analytics module was developed to visually represent key insights about the real estate data. Geographical maps, scatter plots, pie charts, and box plots were employed to offer users a comprehensive understanding of the market.

## Building the Recommender System:

A content based recommender system was built using k-nearest neighbours calculated using cosine similarity, which returned top-k features
