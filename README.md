# Big-Mart-Sales

#### Project Overview: 
This project aims to predict the sales of products in various Big Mart outlets based on historical sales data. The goal is to build a predictive model that can forecast future sales and help the business understand which factors affect product sales, aiding in inventory management and strategy formulation.

#### Problem Statement: 
Big Mart, a retail company, wants to enhance its sales forecasting capabilities to manage inventory and improve revenue. The objective is to predict the sales of each product at different outlets using various product and outlet features.

#### Dataset: 
The dataset used for this project consists of sales data of 8523 products across 10 different attributes such as item weight, item visibility, item type, and outlet-related features.

#### Project Steps:
1.	Data Collection and Preprocessing:
###### o	Loaded the training and test datasets.
###### o	Identified and handled missing values using appropriate strategies such as mean imputation for numerical features and mode imputation for categorical features.
###### o	Standardized column names and encoded categorical variables using label encoding.

2.	Exploratory Data Analysis (EDA):
###### o	Analyzed the distribution of various features and their relationships with the target variable Item_Outlet_Sales.
###### o	Visualized correlations between features using a heatmap.
###### o	Used the Dtale and Klib libraries to gain deeper insights into the data through interactive visualizations.

3.	Feature Engineering:
###### o	Selected relevant features based on correlation analysis and business understanding.
###### o	Performed label encoding on categorical variables to convert them into a numerical format suitable for modeling.

4.	Data Splitting and Standardization:
###### o	Split the dataset into training and testing sets.
###### o	Applied standardization to the features to ensure that all variables contribute equally to the model performance.

5.	Model Building and Evaluation:
###### o	Built and evaluated multiple regression models, including:
###### 	Linear Regression: Achieved an R² score of approximately 0.504 with a mean absolute error (MAE) of around 880.99.
###### 	Random Forest Regressor: Performed better with an R² score of around 0.550 and an MAE of 781.78.
###### o	Assessed model performance using metrics such as R² score, mean absolute error, and root mean squared error (RMSE).

6.	Hyperparameter Tuning:
###### o	Conducted hyperparameter tuning on the Random Forest Regressor using GridSearchCV to find the best parameters for improving model performance.
###### o	The optimal parameters resulted in an R² score of approximately 0.549.

7.	Conclusion:
###### o	The Random Forest Regressor outperformed other models, providing a good balance between bias and variance.
###### o	The project demonstrates how feature engineering and model tuning can significantly impact predictive performance.


#### Technologies Used:
###### •	Python (Pandas, Numpy, Scikit-learn, Seaborn, Matplotlib)
###### •	Machine Learning algorithms: Linear Regression, Random Forest Regressor
###### •	Libraries for data cleaning and visualization: Klib, Dtale
###### •	Excel


#### Future Work:
###### •	Experiment with advanced machine learning algorithms like Gradient Boosting or XGBoost to further improve predictive performance.
###### •	Explore feature engineering techniques, such as creating new features based on domain knowledge or using interaction terms.
###### •	Extend the analysis to include more rece# Big-Mart-Sales-Prediction
