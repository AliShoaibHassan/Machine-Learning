### Projects Description:

In these projects, I applied **Linear Regression** to predict housing prices and mobile phone prices using two datasets: `USA_Housing.csv` and `Mobile-Price-Prediction-cleaned_data.csv`. The goal was to analyze the relationships between different features and the target variable (Price).

For the **housing price prediction**, I performed the following steps:
1. Loaded and explored the dataset using Pandas, visualized data distributions with **Seaborn**, and observed feature correlations using heatmaps.
2. Selected key features like **income**, **house age**, and **population** as inputs and the **Price** column as the target.
3. Split the data into training and testing sets using `train_test_split` from scikit-learn.
4. Trained a **Linear Regression model**, obtained the coefficients, and visualized the predictions with scatter plots and error distributions.
5. Evaluated the model's performance using metrics like RMSE.

For the **mobile price prediction**, I followed a similar approach:
1. Cleaned and analyzed the dataset, checking for null values and resetting indices.
2. Selected features like **RAM**, **ROM**, **Mobile_Size**, and **Battery_Power** as predictors.
3. Trained another Linear Regression model and made predictions.
4. Evaluated the model's accuracy using RMSE and **R² score**.

By applying data preprocessing, visualization, and machine learning techniques, I successfully predicted the target variables and demonstrated the application of regression models in real-world datasets.
