# Revenue Improvement with Pricing Strategies of Applying Discounts Based Strategies

## Repository Outline
1. *e-commerce_dataset_update.csv* - Original dataset from [kaggle](https://www.kaggle.com/datasets/steve1215rogg/e-commerce-dataset/data).
2. *P0M1_Luthfi_Nadyan.ipynb* - Notebook file containing all analysis and visualization for the project

## Problem Background
As a Data Analyst in the Pricing Strategies Department of a top E-Commerce company, you are tasked with increasing product revenue by 10% over the next quarter. This must be achieved without sacrificing profitability from current discount strategies. To meet this objective, the focus will be on identifying top-performing product categories, evaluating the effectiveness of discounts (discounted vs. non-discounted pricing), and understanding the impact of payment methods on revenue. The ultimate goal is to optimize discount efficiency while preserving or increasing revenue.

## Project Output
The result of this project is to create a dashboard containing visualization of the dataset analysis that answer to the problem arises in this project.

## Data
| # | Column Name | Description |
| --- | --- | --- |
| 1 | User_ID | Consist of unique user id |
| 2 | Product_ID | Product id is consists all unique product id in the form of Ids |
| 3 | Category | Category is a group of product categories for any particular product ids |
| 4 | Price | Price is showing the prices of the unique product ids |
| 5 | Discounts | Discount is showing which product ids have a discounts or not-discounted |
| 6 | Final_Price | Final Price is given values of prices after discounted |
| 7 | Payment_Method | Payment method is which payment method used in the transaction by the user |
| 8 | Purchase_Date | Purchase date is the date of these product ids been purchased by user ids |

Data Info:
 - There are 3660 columns and 8 rows

## Method
This project using t-test and ANOVA two-way test for inferential calculation, and using build in pandas for analyzing visualization and etc.
 
## Stacks
This project using Python libraries such as,

- pandas -> using packages for dataframe manipulation and analysis. 
- numpy -> used for mathematical and array function
- matplotlib -> Base of visualization library for seaborn
- seaborn -> Used for creating charts, stats plots, and other statistics visualization
- from scipy import stats -> for all statistics build in Pandas
- from scipy.stats import t -> In this analysis use for T-test statistics
- import matplotlib.lines as lines -> one of the build in matplotlib for creating background lines
- import statsmodels.stats.api as sms -> in this analysis use for ANOVA two way test
- from statsmodels.formula.api import ols -> in this analysis use for ANOVA two way test

## Tableu Dashboard Link
[P0M1_Luthfi_Nadyan_Dashboard](https://public.tableau.com/app/profile/luthfi.nadyan.putra/viz/Dashboard_17478305213680/VisualizationDashboard?publish=yes) 

**Referensi tambahan:**
- [Netflix Data Visualization](https://www.kaggle.com/code/joshuaswords/netflix-data-visualization/notebook)
- [Data Visualization on Sales Data](https://www.kaggle.com/code/darpan25bajaj/data-visualization-on-sales-data)
- [Two way ANOVA and interactions](https://www.kaggle.com/code/brekhnaa/two-way-anova-and-interactions)
- [Two-way ANOVA with Python](https://www.kaggle.com/code/alexmaszanski/two-way-anova-with-python)
- [Data Visualization using Matplotlib 📊](https://www.kaggle.com/code/sanikamal/data-visualization-using-matplotlib)
