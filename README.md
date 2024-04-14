# mental_fitness_tracker
The AI Mental Fitness Tracker is a project designed to analyze and track the prevalence of mental health disorders across different countries over time. The project utilizes two datasets: one containing information about the prevalence of various mental and substance use disorders, and the other detailing the share of these disorders as part of the overall disease burden.

The first step in the project involves merging these datasets to create a comprehensive dataset for analysis. After cleaning and preprocessing the data, various visualizations are created to better understand the trends and relationships within the data. These visualizations include histograms, heatmaps, pair plots, pie charts, and line plots.

To predict the mental fitness levels based on other variables, two machine learning models are trained: Linear Regression and Random Forest Regressor. The models are trained on a subset of the data and then evaluated on another subset to assess their performance. The evaluation metrics used include Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.

The Linear Regression model is a simple model that assumes a linear relationship between the input features and the target variable. The Random Forest Regressor, on the other hand, is an ensemble learning method that uses multiple decision trees to make predictions. Both models are compared based on their performance metrics to determine which one is more suitable for predicting mental fitness levels based on the available data.

Overall, this project aims to provide insights into the prevalence of mental health disorders and to develop a predictive model for mental fitness levels. By analyzing this data, we can gain a better understanding of mental health trends globally and potentially identify factors that contribute to better mental fitness.
