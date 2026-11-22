# Iris Flower Classification with Random Forest

A machine learning Jupyter notebook that classifies Iris flower species using a `RandomForestClassifier` from `scikit-learn`.

## Overview
- **Task:** Multi-class classification of Iris species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`).
- **Features (`X`):** `sepallength`, `sepalwidth`, `petallength`, `petalwidth` (in cm).
- **Target (`y`):** `class`.
- **Model:** `sklearn.ensemble.RandomForestClassifier`.

## Project Structure
```text
├── classification.ipynb   # Jupyter notebook with data loading, training, and predictions
├── iris-train.xlsx        # Training dataset
├── iris-test.xlsx         # Evaluation/test dataset
└── README.md              # Project documentation
```

## Setup & Installation
1. Clone the repository:
   ```bash
  https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git](https://github.com/jayprakashbiswa49-pixel/ML-Algorithm-On-IRIS_Dataset
   cd ML-Algorithm-On-IRIS_Dataset
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas scikit-learn openpyxl jupyter
   ```
   *(Note: `openpyxl` is required by `pandas.read_excel()` for `.xlsx` files.)*

## Usage
1. Launch Jupyter Notebook or open the `.ipynb` file in VS Code.
2. Run the cells sequentially to load the Excel data, train the `RandomForestClassifier`, and generate species predictions.

## Notes & Next Steps
- Add a proper train/test split (or train explicitly on `iris-train.xlsx` and evaluate on `iris-test.xlsx`) and log metrics such as accuracy and a classification report.
- Clean or standardize target labels if raw spreadsheets contain typos (such as `Iris-sesa`).
