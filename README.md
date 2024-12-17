# DS-Assignment
Netflix Data Analysis with PySpark

This project performs exploratory data analysis (EDA) on the Netflix dataset using Apache PySpark. The dataset contains information about movies and TV shows available on Netflix.

Project Overview

The project consists of several steps including data loading, cleaning, and analysis. Each analysis step targets specific insights like top directors, average release years, content durations, diverse genres by country, longest titles, and content rating distributions.

Files in the Project

netflix_titles.csv: The dataset used for analysis.

EDA Notebook: Jupyter Notebook file containing the entire code split into individual cells for better readability.

README.md: This file.

Environment Setup

Prerequisites

Apache Spark

Python 3.x

Jupyter Notebook

Installation

Install Apache Spark and set it up locally.

Install the following Python libraries if not already installed:

pip install pyspark
jupyterlab

Running the Project

Clone this repository.

Open the project directory.

Launch Jupyter Notebook:

jupyter notebook

Open the EDA notebook and run the cells sequentially.

Project Structure

/netflix-data-analysis
│-- netflix_titles.csv    # Dataset
│-- EDA_Notebook.ipynb   # Jupyter Notebook with analysis
│-- README.md            # Project documentation

Analysis Performed

Dataset Overview:

Schema and total records.

Most Prolific Directors:

Directors with the highest number of titles.

Average Release Year by Content Type:

Average release year of content by type.

Content Duration Analysis:

Average, maximum, and minimum content duration.

Countries with Diverse Genres:

Top countries with the most diverse genres.

Longest Titles in Terms of Word Count:

Titles with the longest word counts.

Content Rating Distribution:

Distribution of titles based on ratings.

Conclusion

This project demonstrates the use of PySpark for large-scale data analysis. It highlights various ways to extract meaningful insights from a streaming content dataset.

License

This project is for educational purposes only.

Acknowledgments

Netflix for providing the public dataset.

Apache Spark for its powerful data processing capabilities.

