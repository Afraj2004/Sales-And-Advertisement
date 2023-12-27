# Advertisement vs Sales Analysis

## Project Overview:

This Python project involves analyzing the impact of different advertising channels (TV, Radio, Newspaper) on sales. The dataset used for this analysis is stored in a CSV file named `advertisement.csv`. The project includes data exploration, visualization, and building a multiple regression model to understand the relationship between advertising investments and sales.

## Project Structure:

1. **Data Loading and Exploration:**
   - The project starts by loading the dataset using pandas (`pd.read_csv("/content/advertisement.csv")`) and displaying the first few rows to get a sense of the data (`df.head()`).
   - Descriptive statistics of the dataset are provided using `df.describe()`.

2. **Data Visualization:**
   - Visualizations are created to explore the relationships between each advertising channel (TV, Radio, Newspaper) and sales.
   - Scatter plots are used for visualizing the correlation between advertising expenditures and sales for TV, Radio, and Newspaper.

3. **Data Preprocessing:**
   - The target variable (`Sales`) and the feature variables are separated.
   - Standard scaling is applied to normalize the feature variables using `StandardScaler`.

4. **Multiple Regression:**
   - The project involves building a multiple regression model using the `LinearRegression` algorithm from scikit-learn.
   - The dataset is split into training and testing sets using `train_test_split`.
   - The model is trained on the training set and evaluated on the testing set.

5. **Model Evaluation:**
   - The model's performance is evaluated using the R-squared score on both the training and testing sets.
   - A scatter plot is created to visualize the predicted values against the actual values in the training set.

6. **Results and Insights:**
   - The project concludes with insights gained from the model, including the importance of advertising channels in influencing sales.
   - The weights of each feature in the multiple regression model are presented to highlight the most influential advertising channel.

## Conclusion:

The analysis provides valuable insights into the impact of advertising investments on sales, emphasizing the importance of TV advertising. The project can serve as a foundation for further explorations and optimizations in advertising strategies.

## Instructions for Running the Code:

1. Ensure you have Python and the required libraries installed (NumPy, pandas, matplotlib, scikit-learn).
2. Download the `advertisement.csv` dataset.
3. Run the provided Python script in a Jupyter notebook or any Python environment.

Feel free to contribute, provide feedback, or use this project as a template for similar analyses.

