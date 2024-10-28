# Data Science Job Market Analysis


## Overview

This project aims to analyze the job market for Data Science roles using exploratory data analysis (EDA) techniques. By examining a dataset containing job listings for various Data Science positions, we seek to gain insights into factors such as salary trends, required qualifications, skills in demand, and more.

## Dataset
[Data Source](https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset)

The dataset used for this analysis contains job listings for Data Science roles from diverse locations and companies. It includes information such as job title, experience required, qualifications, salary range, job description, responsibilities, and required skills.

## Analysis Steps

1. **Data Cleaning and Preprocessing**: We started by cleaning and preprocessing the dataset, which involved filtering relevant data, handling duplicates, handling missing values, and transforming certain features such as qualifications and experience.

2. **Extracting Skills**: Using natural language processing (NLP) techniques with the spaCy library, we extracted skills from job descriptions to understand the most sought-after skills in the Data Science job market.

3. **Visualization and Analysis**:
   - Visualized the frequency of skills found in job descriptions using bar plots and word clouds.
   - Analyzed salary trends by role and qualifications using bar plots and scatter plots.
   - Examined the distribution of salaries using histograms.
   - Explored the proportion of skills found in the dataset using a pie chart.

4. **Word Clouds**: Generated word clouds to visually represent the most frequently mentioned skills for the overall dataset, as well as specific roles such as Machine Learning Engineer and Data Engineer.

## Repository Structure

- **Notebooks**: Contains Jupyter Notebooks detailing the data analysis process.
- **Data**: Stores the dataset used for analysis.
- **Images**: Contains images used in the README and notebooks.
- **Requirements.txt**: Lists the required Python packages for reproducing the analysis.

## Plots

### Frequency of Skills Found in Job Descriptions
<img src="images/sfjd.png" width="500" height="400">

### Minimum Salary by Role and Qualifications
<img src="images/minbr.png" width="500" height="400">

### Maximum Salary by Role and Qualifications
<img src="images/maxbr.png" width="500" height="400">

### Distribution of Salaries
<img src="images/saldis.png" width="500" height="400">

### Minimum Experience vs Minimum Salary
<img src="images/mems.png" width="500" height="400">

### Proportion of Skills Found
<img src="images/proportion.png" width="500" height="400">

### Word Cloud of Skills Found 
<img src="images/word.png" width="500" height="400">

### Word Cloud of Skills Found for Machine Learning Engineer role
<img src="images/ml.png" width="500" height="400">

### Word Cloud of Skills Found for Data Engineer role
<img src="images/DataEngineerRole.png" width="500" height="400">



