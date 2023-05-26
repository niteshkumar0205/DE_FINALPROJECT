FIFA 2018 Dataset Preprocessing and Analysis

This repository contains the FIFA 2018 dataset, which consists of statistics and playing attributes of all players in the full version of FIFA 18, a popular football simulation video game developed by Electronic Arts (EA Sports). The dataset has been preprocessed, cleaned, and analyzed using Python. The clean data has then been imported into a PostgreSQL database and visualized using Power BI.

Dataset

The original dataset, named collection.csv, contains comprehensive information on various attributes and statistics of FIFA 18 players. It includes details such as player names, nationality, age, overall rating, skill ratings, preferred positions, and more. The dataset is in CSV (comma-separated values) format and serves as the starting point for the preprocessing and analysis tasks.

Preprocessing and Cleaning

The dataset underwent a preprocessing and cleaning phase to ensure the data was consistent, accurate, and ready for analysis. Various steps were taken to handle missing values, remove irrelevant columns, handle duplicates, and address any inconsistencies in the data. The preprocessing tasks were performed using Python and popular data manipulation libraries such as Pandas and NumPy.

Analysis

Once the dataset was cleaned and prepared, several analysis tasks were performed using Python. The cleaned data, named complete.csv, was used as the input for these analyses. Python libraries such as Pandas, Matplotlib, and Seaborn were employed to gain insights into the dataset. Exploratory data analysis (EDA) techniques were applied to identify trends, correlations, and interesting patterns within the FIFA 2018 player data.

PostgreSQL Database

The cleaned dataset, complete.csv, was imported into a PostgreSQL database for efficient storage and querying. PostgreSQL is a powerful open-source relational database management system that provides robust data management capabilities. By storing the data in a PostgreSQL database, it becomes easier to perform complex queries and retrieve specific subsets of data.

Power BI Visualization

To visualize the data and create interactive dashboards, Power BI was utilized. Power BI is a business analytics service provided by Microsoft that enables users to visualize and share insights from various data sources. By connecting to the PostgreSQL database, the FIFA 2018 player data can be transformed into visually appealing and informative dashboards, providing a deeper understanding of the dataset.

Repository Contents

collection.csv: The original dataset containing FIFA 2018 player information.

complete.csv: The cleaned dataset ready for analysis and import to PostgreSQL.

DE_FINAL_PROJECT.ipynb: Jupyter Notebook containing the Python code for preprocessing and cleaning the dataset.

README.md: The file you are currently reading, providing an overview of the repository.

Usage

Run the DE_FINAL_PROJECT.ipynb notebook to preprocess and clean the dataset.

Import the cleaned dataset, complete.csv, into a PostgreSQL database using the database.sql script.

Connect Power BI to the PostgreSQL database and create visualizations based on your analysis requirements.
