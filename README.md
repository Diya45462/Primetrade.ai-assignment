Project Overview

This project analyzes financial market sentiment using the Fear & Greed Index, a widely used indicator that reflects investor emotions and market psychology. The goal is to extract insights from historical sentiment data and visualize how market fear and greed evolve over time.

The analysis is performed using a Jupyter Notebook in Google Colab, leveraging Python’s data science ecosystem for efficient processing and visualization.

Objectives

Load and preprocess historical Fear & Greed Index data

Analyze sentiment trends over time

Identify key patterns in market psychology

Visualize sentiment fluctuations using charts and graphs

Key Features
Data Import

Loads Excel-based financial sentiment data (fear_greed_index.xlsx)

Supports file upload directly in Google Colab

Data Analysis

Uses pandas and numpy for cleaning, transformation, and statistical insights

Explores trends, distributions, and sentiment shifts

Visualization

Generates clear and informative visualizations using matplotlib and seaborn

Tracks sentiment changes across time

Tech Stack & Libraries

The project requires the following Python libraries:

pandas – Data handling

numpy – Numerical computation

matplotlib – Data visualization

seaborn – Enhanced plotting

openpyxl – Excel file support

How to Run the Project (Google Colab)
Step 1: Open Notebook

Go to https://colab.research.google.com

Upload the ASSIGNMENT.ipynb notebook

Step 2: Install & Import Libraries

Run the initial cell to import required dependencies such as pandas, numpy, matplotlib, and seaborn.

Step 3: Upload Dataset

Run the cell containing:

from google.colab import files


Click “Choose Files”

Upload fear_greed_index.xlsx

Confirm upload (you should see a message like:
Saving fear_greed_index.xlsx to fear_greed_index.xlsx)

Step 4: Execute Analysis

Run remaining cells sequentially

View processed data, insights, and visualizations

Output

Cleaned dataset

Sentiment trend analysis

Time-series plots showing Fear vs Greed patterns

Market behavior insights
