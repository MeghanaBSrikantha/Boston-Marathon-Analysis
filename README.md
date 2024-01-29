# Boston-Marathon-Analysis

Overview
This data science project analyzes the Boston Marathon results to gain insights into the performance of runners based on various factors such as age, gender, pace, and split times. The project includes machine learning models for predicting age groups and genders, statistical tests for comparing different groups, and visualizations to showcase key trends in the dataset.

Dataset
The dataset used in this project consists of Boston Marathon results from multiple years. It includes information such as runner demographics, split times, and official race times.

Requirements
To run the code in this project, you'll need the following:

 - Python 3.x
 - Required Python libraries (specified in requirements.txt)
 - Jupyter Notebook (optional, for running and modifying the analysis notebooks)

Project Structure
The project is organized into several sections:

1. Age Prediction Model:

 - Utilizes a Decision Tree Classifier to predict the age group of runners based on their split times.
 - Evaluates model performance using accuracy, precision, recall, and F1-score.
 - Predicts the age group for a new runner.

2. T-tests and Visualizations:

 - Conducts t-tests to compare the means of different groups (e.g., age groups, genders) for various features (e.g., official time, pace).
 - Visualizes distributions of features based on different groups using histograms.

3.  Cohen's d Effect Size Calculation:

 - Calculates Cohen's d effect size for significant t-tests.
 - Helps interpret the practical significance of observed differences between groups.

4. Pairplot for Exploratory Data Analysis (EDA):

 - Creates a pairplot to visually explore relationships between age, gender, official time, and pace.
 - Provides a quick overview of the dataset's key features and their interactions.

Analysis Steps
The project involves the following major steps:

1. Data Preprocessing: Cleaning and organizing the dataset.
2. Feature Engineering: Creating new features and modifying existing ones.
3. Exploratory Data Analysis: Visualizing and understanding the distribution of key variables.
4. Machine Learning Models: Building models to predict age groups and genders.
5. Statistical Tests: Conducting t-tests to compare different groups.
6. Visualizations: Creating plots and visualizations to communicate insights.

Results
The project provides insights into the relationships between different variables in the Boston Marathon dataset. Key findings include:

- Patterns in official time and pace for different age groups.
- Performance comparisons between male and female runners.
- Predictive models for age groups and gender.
