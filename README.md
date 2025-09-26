# Fraud Detection System

Project Description :-

This repository features a robust fraud detection solution for large-scale financial transactions leveraging advanced machine learning and data visualization. The system processes millions of records, uses outlier analysis, and builds a classification model (Random Forest) to identify and evaluate fraudulent activity in payment systems. Outlier detection, visualization, and thorough model evaluation (classified by Accuracy & F1 Score) are central to the solution.

Technology Stack

- Programming Language: Python 3.x
- Core Libraries:
  - pandas – For data handling and preprocessing
  - numpy – Mathematical and array operations
  - matplotlib, seaborn – Visualization and outlier analysis
  - scikit-learn – Machine learning: model development/evaluation (Random Forest, metrics)
- Data: Requires a dataset named fraud.csv in the project directory.

Installation

1. Clone this repository:

```
git clone https://github.com/your-username/fraud-detection-system.git
cd fraud-detection-system
```

2. Install required dependencies: It’s recommended to use a virtual environment:

```
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

If a requirements.txt is missing, install core dependencies manually:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Dataset: Place fraud.csv in the project directory. Ensure correct format/columns based on project code.

Usage

- The main code is provided as a Jupyter notebook (code.ipynb):
  1. Launch JupyterLab or Jupyter Notebook:

```
jupyter lab
```
or

```
jupyter notebook
```

  2. Open code.ipynb and run all cells to execute the workflow: data load, preprocessing, visualization (outlier detection), and classification modeling.

- Example on CLI (if notebook is converted to a script):

```
python code.py
```

Features

- Handles multi-million row datasets with cleaning and preprocessing.
- Visualizes outlier transactions using IQR and boxplots.
- Automatically imputes or handles missing values for accuracy.
- Builds and evaluates a Random Forest classification model.
- Provides detailed scores: accuracy, F1, confusion matrix, feature importance, ROC-AUC.
- Visual outputs for feature importances and fraud trends.

Results

- Achieves high precision and F1 on large, realistic datasets (Accuracy >99%, F1 >88%).

Author

- Amritanshu Kumar
