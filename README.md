# Employee Attrition Analysis

## Overview
This project explores employee attrition patterns and builds a baseline machine-learning model using Python. It is intended for learning and portfolio demonstration.

## Dataset
Use the IBM HR Analytics Employee Attrition & Performance dataset:
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

Download `WA_Fn-UseC_-HR-Employee-Attrition.csv` and place it in the project root next to the notebook. The dataset is a public educational sample and is not live HR data.

## Questions
- What is the overall attrition rate?
- How does attrition vary by department?
- How is attrition associated with overtime and job satisfaction?
- How can a baseline classifier be evaluated beyond accuracy?

## Tools
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- Jupyter Notebook

## How to run
1. Install Python 3.10+ and Jupyter, or open the notebook in Google Colab.
2. Download the CSV dataset from the link above.
3. Place the CSV beside `Employee_Attrition_Analysis.ipynb`.
4. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

5. Open the notebook and run all cells in order.

## Project workflow
1. Load and inspect data.
2. Check missing values, duplicates, and class balance.
3. Perform exploratory data analysis.
4. Visualize attrition by overtime, department, satisfaction, and income.
5. Train a logistic regression baseline with a stratified train/test split.
6. Evaluate using accuracy, attrition-class recall, ROC-AUC, classification report, and confusion matrix.

## Results
Run the notebook and record the metrics and findings produced by your own run here. Do not invent or copy model results without verifying them.

## Limitations and responsible use
This is an educational analysis of a fictional/synthetic sample. Associations do not prove causes. The model may be inaccurate or biased and must not be used to make hiring, firing, promotion, or employee-monitoring decisions about real people.
