# crop-price-prediction
In this project, I analyzed a dataset containing crop prices and related agricultural metrics across various states in India. The dataset, crop_price.csv, includes features such as cultivation costs, production yield, temperature, rainfall, and annual prices for different crops. After loading and inspecting the data, I confirmed its integrity by checking for duplicates and missing values, finding none. The dataset comprises 49 entries and 9 columns, with various numerical and categorical data types.

I conducted exploratory data analysis (EDA) by visualizing the distribution of key features through histograms. This helped to understand the underlying trends and variability in cultivation costs, production yields, and prices. The visualizations revealed insights into how these factors may influence crop pricing across different states.

To model the relationship between the features and crop prices, I split the data into training and testing sets. I implemented a Linear Regression model, which achieved an impressive mean squared error (MSE) of approximately 
9.02
×
1
0
−
29
9.02×10 
−29
  and an R² score of 1.0, indicating perfect predictive accuracy on the test set. This suggests a strong linear relationship between the independent variables and the annual crop prices, although such a perfect score may also indicate potential overfitting or data leakage.
