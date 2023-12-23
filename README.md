# Exploratory-Data-Analysis-on-California-Housing-EDA-
Python code analyzes California housing data: checks missing values, duplicates, computes stats, and visualizes. It shows house value distribution on maps, correlation matrix, temporal analysis, detects outliers, and creates a new feature. Uses Pandas, NumPy, Scikit-Learn, and Seaborn for data handling, analysis, and visualization.
This code is a comprehensive data analysis and visualization workflow for the California housing dataset. It covers several key steps in the data science pipeline:

Data Loading and Inspection:

Imports necessary libraries such as NumPy, Pandas, and tools from Scikit-Learn.
Loads the California housing dataset and creates a Pandas DataFrame.
Inspects the data using methods like df.shape, df.head(), df.tail(), and checks for missing values and duplicates.
Data Exploration and Visualization:

Computes and prints descriptive statistics using df.describe().
Visualizes the geographical distribution of median house values using a scatterplot with longitude and latitude.
Creates histograms to display the distribution of median house values.
Generates a heatmap to visualize the correlation matrix among different features.
Temporal Analysis:

Simulates a temporal feature ('YearBuilt') by generating random years between 1950 and 2020.
Converts the 'YearBuilt' data into a datetime format and extracts year and month information.
Visualizes the distribution of the 'YearBuilt' feature using a histogram.
Outlier Detection and Feature Engineering:

Detects outliers in the 'AveRooms' feature using a boxplot.
Creates a new feature 'RoomsPerHousehold' by dividing 'AveRooms' by 'AveBedrms'.
Summary Statistics:

Prints summary statistics for the updated DataFrame after feature engineering.
Throughout the code, visualizations are created using Matplotlib and Seaborn, enhancing the understanding of the dataset's various aspects. This script serves as a useful starting point for analyzing the California housing dataset, performing basic data cleaning, exploration, and visualization, while also demonstrating key data manipulation techniques.




