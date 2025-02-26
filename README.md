# Risk Detection in the Construction Industry
This project focuses on detecting and analyzing the risk of workplace accidents in the construction industry. The goal is to identify patterns and correlations that could help predict and prevent accidents. The project involves data enrichment, cleaning, multivariate analysis, clustering, and correlation analysis with accident risk.

Project Overview
The project is divided into several key steps:
-Data Enrichment and Cleaning:
-Handling missing data and encoding categorical variables.
-Transforming date fields into meaningful features (e.g., calculating age from birth date, converting contract start dates to years of experience).
-Removing irrelevant columns and preparing the data for analysis.

Univariate Analysis:
-Analyzing individual features to understand their distribution and impact on accident risk.
-Visualizing data distributions and identifying potential outliers or anomalies.

Multivariate Analysis:
-Exploring correlations between different features and accident frequency.
-Using scatter plots and regression lines to visualize relationships between variables.

Clustering:
-Applying clustering algorithms (K-Means and DBSCAN) to group employees based on their accident frequency, absence rates, and other relevant features.
-Using Principal Component Analysis (PCA) to reduce dimensionality and improve clustering results.
-Visualizing clusters in 2D and 3D to identify patterns and trends.

Correlation Analysis:
-Analyzing the correlation between accident frequency and other variables such as message frequency, absence rates, and weather conditions.
-Using Sweetviz for automated exploratory data analysis (EDA) to generate detailed reports on feature correlations.

Time Series Analysis:
-Creating time-based vectors for accidents and weather conditions to analyze trends over time.
-Grouping data into bi-weekly periods to track accident frequency and weather patterns.

Key Findings:
* Data Enrichment: The dataset was enriched by transforming date fields into meaningful features, such as calculating years of experience from contract start dates and age from birth dates. Missing data was handled by either filling in missing values or dropping irrelevant columns.
* Clustering: Employees were grouped into clusters based on their accident frequency, absence rates, and other features. The clustering results were visualized using PCA and 3D plots, revealing distinct groups with varying levels of risk.
* Correlation Analysis: The analysis revealed strong correlations between accident frequency and variables such as absence rates, message frequency, and weather conditions. These insights can help in identifying high-risk employees and implementing preventive measures.
* Time Series Analysis: By analyzing accident and weather data over time, the project identified trends and patterns that could be used to predict future accidents.

Technologies Used:
-Python: The primary programming language used for data analysis and visualization.
-Pandas: For data manipulation and cleaning.
-NumPy: For numerical computations.
-Scikit-learn: For clustering and PCA.
-Matplotlib and Seaborn: For data visualization.
-Sweetviz: For automated exploratory data analysis (EDA).
