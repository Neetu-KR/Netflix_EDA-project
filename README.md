# Netflix_EDA-project
This project performs Exploratory Data analysis ( EDA ) on the Netflix movies and TV shows data set using python. it uses Pandas, Matplotlib, and Seaborn to clean data and clean data and create visualizations like scatter plots, heatmaps, bar charts, box plots, and histograms to analyze trends and patterns.

1. Netflix Movies & TV Shows – Exploratory Data Analysis (EDA)

•	Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset. The goal is to analyze patterns, trends, and relationships within the dataset using visualization techniques.

EDA helps in understanding the structure of the data and extracting meaningful insights before applying any machine learning models.


2. Dataset Description

The dataset used in this project is the Netflix Movies and TV Shows Dataset, which contains detailed information about content available on Netflix.

•	Features in Dataset:

- Title – Name of the movie or TV show
- Type – Movie or TV Show
- Director – Director of the content
- Cast – Actors involved
- Country – Country of origin
- Release Year – Year of release
- Rating – Age rating (e.g., PG, TV-MA)
- Duration – Length of the content
- Genre (Listed In) – Category/genre


3. Objectives

- To explore and understand the dataset
- To perform data cleaning and preprocessing
- To visualize relationships between different features
- To identify patterns in Netflix content


•	Technologies Used

- Python – Programming language
- Pandas – Data manipulation and analysis
- Matplotlib – Basic plotting library
- Seaborn – Advanced visualization library


4. Steps Performed

a. Data Loading

- Imported dataset into Google Colab using Pandas
- Displayed first few rows using "head()"

b. Data Understanding

- Checked structure using "info()"
- Generated statistical summary using "describe()"

c. Data Cleaning

- Converted release year into numeric format
- Extracted numerical values from duration column
- Handled missing values where necessary

d. Data Visualization

The following visualizations were created:

•	Scatter Plot

- Shows relationship between release year and content distribution
- Helps understand how content has increased over time

•	Heatmap

- Displays correlation between numerical features
- Helps identify relationships between variables

•	Bar Chart

- Compares number of Movies vs TV Shows
- Shows which type is more dominant

•	Box Plot

- Shows distribution of duration
- Helps detect outliers and spread of data

•	Histogram

- Shows distribution of release years
- Helps understand trends over time


5. Key Insights

- Netflix contains more Movies compared to TV Shows
- Content production has increased significantly in recent years
- Duration varies widely depending on content type
- Most content falls within recent decades


•	Conclusion

This project demonstrates how Exploratory Data Analysis (EDA) can be used to extract meaningful insights from raw data. Visualization techniques make it easier to understand patterns and trends in the dataset.


6. Output

All graphs are generated using Matplotlib and Seaborn in Google Colab.


7. Project Structure

- "netflix_eda.ipynb" → Google Colab Notebook
- "/content/netflix_titles.csv" → Dataset file
- "README.md" → Project documentation


8. Future Scope

- Apply Machine Learning models for prediction
- Perform deeper analysis on genres and ratings
- Build a recommendation system


9. Author:

   Neetu KR


 10.Acknowledgement

    Dataset sourced from Kaggle.
