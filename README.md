# PaperScope

*A research paper metadata analysis project built using the arXiv Metadata Dataset.*

---

## Overview

PaperScope is a data analysis project that explores research paper metadata from the arXiv Metadata Dataset using Python and the data science ecosystem.

The project focuses on exploratory data analysis (EDA), feature engineering, feature analysis, and data visualization to better understand publication patterns, research categories, author information, and paper metadata.

This project was built to strengthen practical skills in Python, Pandas, NumPy, Matplotlib, Git, and exploratory data analysis while creating a real-world portfolio project.

---

## Dataset

- **Source:** Kaggle – arXiv Metadata Dataset (https://www.kaggle.com/datasets/Cornell-University/arxiv)
- **Format:** JSON
- **Sample Size:** 10,000 research papers

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## Project Features

### Exploratory Data Analysis

- Loaded and explored the arXiv metadata dataset
- Inspected dataset structure and data types
- Analyzed research categories
- Identified the most common research categories
- Analyzed author information
- Investigated publication and update dates
- Analyzed missing values and missing value percentages
- Explored paper version history
- Analyzed title and abstract text
- Identified the most common words in titles and abstracts

### Feature Engineering

Created additional features for further analysis:

- Abstract length
- Title length
- Number of authors
- Publication year
- Number of paper versions

### Feature Analysis

- Analyzed distributions of engineered features
- Investigated relationships between features
- Performed correlation analysis
- Explored potential predictive relationships

### Data Visualizations

- Missing value distribution
- Top research categories
- Top authors
- Publication year distribution
- Paper version distribution
- Abstract length distribution
- Number of authors distribution
- Abstract length vs. paper versions
- Number of authors vs. paper versions

---

## Key Findings

- Most papers in the sample have only one published version.
- Paper version counts are highly right-skewed, with only a few papers having many revisions.
- Most abstracts are between approximately 500 and 1000 characters in length.
- Abstract length shows almost no linear relationship with the number of paper versions.
- Number of authors also shows very little linear relationship with paper versions.
- Since all sampled papers were published in 2007, publication year contains no variance and therefore cannot be used for correlation analysis within this sample.

---

## Project Summary

This project explored a sample of **10,000 research papers** from the arXiv Metadata Dataset through exploratory data analysis, feature engineering, and visualization.

The analysis identified publication patterns, research category distributions, author statistics, text characteristics, and relationships between engineered features.

While investigating feature relationships, the analysis showed that the engineered features had little linear relationship with the selected target (`num_versions`). This demonstrated the importance of exploratory data analysis in understanding a dataset before applying machine learning techniques.

Overall, the project provided practical experience with real-world data analysis workflows, including data exploration, cleaning, feature engineering, visualization, interpretation, and documenting analytical findings.

---

## Learning Outcomes

Through this project I gained practical experience with:

- Python
- Pandas
- NumPy
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Correlation Analysis
- Data Visualization
- Git & GitHub