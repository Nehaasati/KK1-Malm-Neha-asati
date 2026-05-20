 KK1 Project – Titanic & Spotify Dataset Analysis

Project Overview
This project contains exploratory data analysis (EDA), visualization, and basic machine learning experiments using two public datasets:

1.Titanic Dataset
2.Spotify Top Hits (2000–2019) Dataset

The notebook demonstrates data cleaning, preprocessing, visualization, and insights extraction using Python libraries such as Pandas, Matplotlib, and Seaborn.



 Datasets Used

1.Titanic Dataset
Source: :kaggel

Description
This dataset combines the Titanic test file with the gender submission file to provide survival information. It is useful for visualization and beginner machine learning projects.

Features Include
- Passenger information
- Survival status
- Passenger class
- Age
- Gender
- Fare
- Embarked location

 Project Tasks
- Data cleaning
- Survival analysis
- Gender and class comparisons
- Data visualization
- Basic predictive analysis



2.Spotify Top Hits Dataset (2000–2019)
Source: :kaggel

Description
This dataset contains audio statistics of the top 2000 Spotify tracks from 2000 to 2019.

 Features Include
- Artist name
- Song title
- Popularity
- Danceability
- Energy
- Loudness
- Tempo
- Genre
- Acousticness
- Instrumentalness
- Valence
- Release year

Project Tasks
- Audio feature analysis
- Trend visualization
- Popularity analysis
- Genre comparison
- Correlation analysis between musical features



Project Structure

text
project-folder/
│
├── notebook.ipynb       # Main Jupyter notebook
├── data/                # Dataset files
├── README.md            # Project documentation
Installation
 Python 3.10+.

python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt

Requirements

Install the following Python libraries before running the notebook:

pip install pandas numpy matplotlib seaborn scikit-learn
How to Run
1.Clone or download the project folder.
2.Place the datasets inside the data/ folder.
3.Open the notebook:
4.jupyter notebook notebook.ipynb
5.Run all cells sequentially.

Tools & Technologies
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Objectives
Practice data preprocessing techniques
Create meaningful visualizations
Analyze trends and patterns in datasets
Apply beginner-level machine learning concepts
