# Diamond Data Analysis

This project performs exploratory data analysis on a dataset of diamond traits to uncover insights into how different attributes impact pricing.

## Data
The diamonds dataset from Tensorflow Datasets is used, containing over 50,000 diamonds with features including:

- Carat
- Cut 
- Color
- Clarity
- Depth
- Table
- Price

The training split is loaded as a Pandas DataFrame for analysis.

## Analysis
Various visualizations and plots are generated to explore relationships in the dataset using Matplotlib, Seaborn, and Plotly, including:

- Pairplot
- Correlation Heatmap
- Box Plots
- Scatter Plots
- Count Plots

Key findings:

- Carat has the highest correlation to price
- Diamonds with ideal cuts tend to be larger in size
- There is a linear relationship between carat and price
- Color distribution skews towards yellow tints

## Next Steps

Potential next steps for analysis:

- Build machine learning models to predict diamond prices
- Add additional data visualizations as needed
- Perform statistical testing on distribution differences

## References

Diamonds dataset: https://www.tensorflow.org/datasets/catalog/diamonds
