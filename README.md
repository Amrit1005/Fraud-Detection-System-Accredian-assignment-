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

Clone this repository:

```sh
git clone https://github.com/your-username/fraud-detection-system.git
cd fraud-detection-system
```

Install required dependencies using a virtual environment:

```sh
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

If `requirements.txt` is missing, install core dependencies manually:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

Place the dataset `fraud.csv` in the project directory.

Usage

The main code is provided as a Jupyter notebook (`fraud_detect.ipynb`).

To run the notebook:

```sh
jupyter lab
```
or

```sh
jupyter notebook
```

Then open `fraud_detect.ipynb` and run all cells to execute the full workflow: loading data, preprocessing, visualizing outliers, and classification modeling.

If running the notebook as a script after conversion:

```sh
jupyter nbconvert --to script fraud_detect.ipynb
python fraud_detect.py
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
  ## Amritanshu Kumar ##
