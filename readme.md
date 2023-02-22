# A/B Testing for E-Commerce Website
This project is aimed to analyze the results of an A/B test run by an e-commerce website. The goal is to determine whether the company should implement a new webpage, keep the old webpage, or run the experiment longer.

# Background
The e-commerce website wants to increase the number of users who convert, meaning the number of users who decide to purchase the company's products. The company has developed a new webpage and wants to test if it will lead to more conversions than the old webpage.

To test this, the company ran an A/B test, where they randomly divided users into two groups: Group A, which was shown the old webpage, and Group B, which was shown the new webpage. The company then recorded whether each user in each group made a purchase or not.

# Objectives
The objectives of this project are as follows:

Perform a hypothesis test to determine whether the new webpage leads to more conversions than the old webpage.
Calculate the p-value and use it to make a decision about whether to implement the new webpage, keep the old webpage, or run the experiment longer.
Provide recommendations to the company based on the results of the A/B test.
Dataset
The dataset for this project contains two columns:

group: either "control" for Group A or "treatment" for Group B.
converted: either 1 if the user made a purchase or 0 if they did not.
# Requirements
This project was developed using Python 3.8.5 and the following packages:

numpy
pandas
matplotlib
scipy.stats
You can install these packages by running the following command:

Copy code
pip install numpy pandas matplotlib scipy.stats
Getting Started
To get started with this project, you can clone the repository and open the AB_test.ipynb notebook in Jupyter Notebook or JupyterLab.

# The notebook contains the following sections:

1- Introduction: Provides an overview of the project.
2- Data Wrangling: Loads the dataset and performs data cleaning.
3- Data Exploration: Explores the dataset and visualizes the results.
4- Hypothesis Testing: Performs a hypothesis test and calculates the p-value.
5- Results: Provides recommendations to the company based on the results of the A/B test.
# Conclusion
The A/B test performed in this project helps the company determine whether to implement the new webpage, keep the old webpage, or run the experiment longer. By analyzing the results of the A/B test and calculating the p-value, the company can make an informed decision and improve their website's conversion rate.