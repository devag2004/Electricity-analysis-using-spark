# Electricity-analysis-using-spark
The project aims to provide insights into how various appliances contribute to electricity bills,
how consumption varies across cities and seasons, and how we can predict future consumption.
These insights can help consumers make informed decisions about their energy usage, assist
utility companies in load balancing, and support policymakers in designing effective energy
conservation initiatives.
The dataset used in this project contains information about:
• Usage hours of various appliances (fans, air conditioners, refrigerators, TVs, monitors,
and motor pumps)
• City and regional information
• Seasonal variations (month)
• Electricity tariff rates
• Monthly usage hours
• Monthly electricity bills
By applying advanced analytics to this data, the project demonstrates how big data technologies
can transform raw information into actionable knowledge in the energy sector.
Libraries and Technologies Used
The implementation relies on a robust stack of technologies and libraries:
1. Apache Spark: The core framework that enables distributed data processing and
analysis. Spark's ability to process large datasets in-memory makes it ideal for this
project.
2. PySpark: Python API for Spark that provides access to Spark's functionality while
allowing integration with Python's rich ecosystem of data science libraries.

3. Spark ML (MLlib): Spark's machine learning library used for building predictive
models (RandomForestRegressor) and clustering algorithms (KMeans).
4. Data Visualization Libraries:
o Matplotlib: For creating static visualizations like bar charts and line plots
o Seaborn: For generating statistical graphics like heatmaps
o Plotly: For interactive 3D visualizations of clustering results
5. Scientific Computing Libraries:
o NumPy: For numerical computations and array operations
o Pandas: For data manipulation and analysis
6. Google Colab Integration: The code includes components for file uploads and display
in a Google Colab environment.

Workflow
The application follows a logical workflow designed to progress from basic to advanced
analysis:
Data Acquisition and Processing
1. Data Loading: The user uploads a CSV file containing electricity consumption data.
2. Initial Processing: The system loads the data into a Spark DataFrame, which
distributes the processing across available computing resources.
3. Data Validation: Basic validation checks ensure that required columns are present.
Exploratory Data Analysis
1. Dataset Overview: The system provides basic statistics and allows the user to select
specific charts for exploration.
2. Consumption by City: Analyzes and visualizes how electricity consumption varies
across different cities, with detailed textual analysis explaining the patterns.
3. Consumption by Month: Examines seasonal variations in electricity usage,
identifying peak months and trends.
4. Appliance Usage Analysis: Investigates how different appliances contribute to overall
electricity consumption.
Advanced Analytics
1. Correlation Analysis: A heatmap visualizes the relationships between different
variables, helping identify which factors are most strongly related to electricity bills.
2. Appliance Impact Charts: Dedicated analysis of how each appliance's usage affects
the final electricity bill.
3. Predictive Modeling: Building a Random Forest regression model to predict electricity
bills based on appliance usage and other factors.
4. Consumption Pattern Discovery: K-means clustering identifies distinct consumption
patterns among households.
