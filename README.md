Amazon Forest Fire Analysis
This project explores and visualizes the forest fire data in Brazil's Amazon rainforest from 1998 to 2017. The dataset used comes from Kaggle, and the analysis was performed using pandas, matplotlib, and googletrans Python libraries in Jupyter Notebook. The goal of the project is to preprocess and analyze the data, learn from it, and produce meaningful visualizations of forest fires over time.

Table of Contents:
  - Introduction
  - About the Dataset
  - Project Workflow
  - Conclusion

Introduction:
    This project serves as a learning exercise where I used the dataset of forest fires in the Amazon region of Brazil to:
    - Preprocess the data by correcting formatting errors, cleaning missing data, and fixing incorrect encoding.
    - Visualize trends in forest fires by year and by month.
    - Utilize machine translation to convert the dataset's month column from Portuguese to English.

About the Dataset: The dataset contains information on forest fires in Brazil's Amazon region, specifically:
- year: The year when the fire was reported.
- state: The Brazilian state where the fire occurred.
- month: The month when the fire occurred (in Portuguese).
- number: The number of forest fires reported.
- date: The specific date the fire was reported.
- One key observation is that some numbers in the number column contain decimals (e.g., 2.588), which represent thousands (e.g., 2588 fires). We handle this formatting issue during data loading.

Source: Kaggle - Amazon Forest Fires Dataset

Project Workflow:

Initial Setup and Fixing Encoding Issues:
I faced issues with file encoding when reading the CSV. A quick fix involved converting the file to UTF-8 encoding and re-saving it.

Preprocessing:
Cleaned the data by handling missing values and fixing the formatting of the number column.

Exploration:
Visualized data by years and months to understand fire trends.

Translation:
Used the googletrans library to translate month names from Portuguese to English.

Visualization:
Created visual plots of forest fire trends using matplotlib.

Conclusion:

This project demonstrates the essential process of cleaning and preprocessing data, especially handling formatting errors, encoding issues, and translation. After fixing the dataset, I visualized the forest fire patterns over the years and months.
This analysis highlights the importance of data preprocessing as an integral part of any data science project and emphasizes learning by working on real-world datasets.

