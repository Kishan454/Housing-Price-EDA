# Housing Price Exploratory Data Analysis (EDA)

## Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on a housing dataset to identify the key factors that influence property prices. As my first Data Science project, I focused on data cleaning, univariate/bivariate analysis, and correlation mapping.

## Dataset Description
The dataset contains information on various houses, including:
- **Price:** The target variable (Target).
- **Area:** Total square footage of the house.
- **Bedrooms/Bathrooms:** Number of rooms.
- **Mainroad/Guestroom/Basement:** Categorical features (Yes/No).
- **Furnishing Status:** Furnished, Semi-Furnished, or Unfurnished.

## Key Steps Performed
1. **Data Cleaning:** Checked for null values and duplicates to ensure data integrity.
2. **Descriptive Statistics:** Analyzed the mean, median, and standard deviation of prices and area.
3. **Univariate Analysis:** Used Histograms to visualize the distribution of house prices.
4. **Bivariate Analysis:** Created Scatter plots to examine the relationship between house area and price.
5. **Categorical Analysis:** Used Box plots to see how furnishing status and air conditioning impact price.
6. **Correlation Analysis:** Generated a Heatmap to identify which variables are most strongly related to price.

## Key Insights
- **Area vs. Price:** There is a strong positive correlation; as the area increases, the price generally rises.
- **Amenities:** Houses with air conditioning and parking spots show a significantly higher median price.
- **Price Distribution:** The majority of houses are priced between [Insert your observed range, e.g., 2M to 6M], with a few high-end outliers.

## Technologies Used
- Python
- Pandas (Data Manipulation)
- Matplotlib & Seaborn (Data Visualization)
- Jupyter Notebook

## How to Run
1. Clone this repository.
2. Ensure you have `pandas`, `seaborn`, and `matplotlib` installed.
3. Open `Housing_EDA.ipynb` in Jupyter Notebook or VS Code and run all cells.
