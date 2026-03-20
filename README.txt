# Diabetes Data Analysis

This project is part of the coursework **SDSC2001 Introduction to Data Science** at City University of Hong Kong. It performs exploratory data analysis (EDA) and builds a simple classification model to predict diabetes risk based on health indicators.

## Table of Contents
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Key Steps](#key-steps)
- [Results](#results)
- [How to Run](#how-to-run)
- [Author](#author)

## Dataset
The dataset used in this project is a publicly available diabetes dataset (e.g., from Kaggle or UCI). It contains features such as glucose level, blood pressure, BMI, age, and the target variable indicating diabetes outcome.

*Note: If you use a specific dataset, replace this description with the actual source and attributes.*

## Technologies Used
- Python 3.x
- Pandas – data manipulation
- NumPy – numerical operations
- Matplotlib & Seaborn – data visualization
- Scikit-learn – machine learning model (Logistic Regression)

## Project Structure
SDSC2001_Project_Diabetes/

- diabetes_analysis.ipynb # Jupyter Notebook with full analysis
- data/ # Folder containing the dataset (if included)
- README.md # This file
-  requirements.txt # Python dependencies (optional)

## Key Steps
1. **Data Loading & Cleaning**  
   - Load the dataset and handle missing values.
   - Check data types and basic statistics.

2. **Exploratory Data Analysis**  
   - Visualize distributions of features.
   - Analyze correlations with the target variable.
   - Identify patterns across different patient groups.

3. **Feature Engineering & Modeling**  
   - Prepare features and target.
   - Split data into training and testing sets.
   - Train a Logistic Regression classifier.
   - Evaluate model performance (accuracy, precision, recall, confusion matrix).

4. **Results Interpretation**  
   - Discuss important features and model limitations.

## Results
   - The model achieved an accuracy of around 90% on the test set.
   - Key features (e.g., glucose, BMI) showed strong correlation with diabetes outcome.
   - The analysis provides a baseline for further improvements using more complex algorithms.

*Note: Replace XX with your actual accuracy.*

## How to Run
1. Clone this repository:
   git clone https://github.com/DavidCui23333/SDSC2001_Project_Diabetes.git
2. Open the Jupyter Notebook:
Project.ipynb
3. Run all cells sequentially.

## Author
   - David, Cui Tsz Wai
This project was completed as part of the SDSC2001 course at City University of Hong Kong.