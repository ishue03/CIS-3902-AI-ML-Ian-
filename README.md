# CIS 3902 – AI and Machine Learning
 
Name: Ian Shue, Student <br>
Major: Mathematical Finance  <br>
Semester: Spring 2026 <br>
 
This repository contains coursework and projects for CIS 3902.
 
## Linear Regression Example
This notebook demonstrates how to build, evaluate, and visualize a linear regression model using housing data.
<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/Linear_Regression_Example_with_the_Housing_Data.ipynb">
  Linear Regression Example
 </a>
</p>

## Bias and Variance Example with LR
This notebook demonstrates how model complexity affects bias, variance, and overfitting using a simple agricultural dataset relating fertilizer rate to crop yield. 
<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/bias_variance_overfitting_fertilizer_crop_yield_starter.ipynb">
  Bias and Variance Example with LR
 </a>
</p>

## Reading Files in Colab with Jupyter
This notebook demonstrates multiple ways to load datasets into a Jupyter Notebook using Pandas, depending on where the data is stored. These methods are commonly used in data mining and data analysis workflows.
<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/Reading_Files_in_Colab_with_Jupyter_Notebook.ipynb">
 Reading Files in Colab with Jupyter
 </a>
</p>

## Regularization
This notebook demonstrates how regularization affects linear regression models using a synthetic dataset with meaningful features, correlated copy features, and random noise. By comparing Linear Regression**, Ridge (L2), and Lasso (L1), the notebook shows how each method handles irrelevant and correlated features.

<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/regularization.ipynb">
 Regularization
 </a>
</p>




## Data Wrangling with the Titanic Dataset 
This notebook walks through a complete data cleaning pipeline using the Titanic dataset. It covers exploring the data, handling missing values, removing unnecessary features, encoding categorical variables, detecting outliers, and scaling numerical features. The goal is to prepare messy real-world data for machine learning while demonstrating why thoughtful preprocessing decisions matter.

<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/Data_Cleaning_Exercise.ipynb">
  Data Wrangling with the Titanic Dataset
 </a>
</p>

## Data Cleaning Exercise
This notebook applies a complete data cleaning pipeline to the Heart Failure Prediction dataset. It covers exploring the dataset structure, identifying hidden data quality issues (such as unrealistic zero values), handling missing data through median imputation, encoding categorical medical variables, detecting outliers using the IQR method, and scaling numerical features for modeling. The goal is to prepare clinical healthcare data for machine learning while emphasizing careful inspection and thoughtful preprocessing decisions.

<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/Data_Cleaning_Exercise_2.ipynb">
 Data Cleaning Exercise
 </a>
</p>


## Random Forest Crime Assignment
This notebook builds a complete machine learning pipeline using a recent real-world Chicago crime dataset to predict whether an arrest was made following a reported crime. It covers exploring the dataset structure, cleaning and selecting relevant variables, handling missing geographic data, visualizing spatial crime patterns with an interactive map, engineering categorical features through dummy encoding, and training a Random Forest classification model. The notebook evaluates performance using accuracy, a confusion matrix, classification metrics, and cross-validation, and interprets feature importance to understand which factors most influence arrest outcomes. The goal is to demonstrate end-to-end classification modeling while critically examining how geographic patterns and crime types shape arrest predictions and discussing the ethical implications of predictive policing models.

<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/random_forest_crime_assignment_(1).ipynb">
 Random Forest Crime Assignment
 </a>
</p>



## Autoviz
This notebook demonstrates automated exploratory data analysis using AutoViz on Seaborn’s built-in Penguins dataset. AutoViz generated statistical visualizations including scatterplots, heatmaps, and distribution plots to analyze relationships between bill length, flipper length, and body mass. The analysis revealed strong positive correlations between flipper length and body mass, species-based differences in measurements, and mild negative correlations involving bill depth. The project emphasizes visual data exploration prior to modeling.

<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/Autoviz_(3).ipynb">
 Autoviz
 </a>
</p>

## Mushroom Reduced Student Exercise
This notebook builds and interprets a Decision Tree classifier using selected features from the UCI Mushroom dataset to predict whether a mushroom is edible or poisonous. After one‑hot encoding categorical variables, the model is evaluated using accuracy and a confusion matrix, and the resulting tree is visualized to extract clear IF–THEN decision rules. The project emphasizes model interpretability, highlights odor as a key predictive feature, and explores how tree depth affects performance and complexity.

<p>
 <a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/Mushroom_Reduced_Student.ipynb">
 Mushroom Reduced Student Exercise
 </a>
</p>


# Capstone Project

## Optimizing Financial Portfolios: A Mathematical Approach Using Covariance Matrices and Linear Algebra

This capstone project applies **Modern Portfolio Theory (Markowitz, 1952)** to construct and compare minimum variance portfolios across multiple tiers of U.S. banking institutions. Using historical market data retrieved via `yfinance`, the study estimates monthly returns, volatility, and covariance matrices to compute optimal portfolio allocations through matrix inversion and constrained optimization techniques.

The project evaluates three distinct bank categories:

- Successful large-cap banks (JPM, BOA, WFC)  
- Mid-tier regional banks (FITB, CMA, TFC)  
- Small regional banks (WAL, ZION, FHN)  

For each group, the analysis:
- Computes mean returns and standard deviations  
- Constructs covariance matrices  
- Solves for the Minimum Variance Portfolio (MVP) using linear algebra  
- Calculates Sharpe ratios for risk-adjusted performance  
- Compares results across bank classifications  

The project bridges **linear algebra, statistics, and finance**, demonstrating how covariance structures and optimization theory directly inform real-world portfolio construction. It also evaluates diversification effects within and across banking tiers while discussing economic interpretation and model limitations.

<p>
 <a href="LINK_TO_NOTEBOOK_OR_PDF_HERE">
  View Capstone Project
 </a>
</p>

<p>
<a href="https://githubtocolab.com/ishue03/CIS-3902-AI-ML-Ian-/blob/main/cohens_kappa_ml_notebook%20(1).ipynb">
View Capstone Project
 </a>
</p>

