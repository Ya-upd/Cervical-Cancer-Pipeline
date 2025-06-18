# Cervical Cancer Screening Prediction Pipeline

## Description

This project implements an end-to-end machine learning pipeline to predict the results of various cervical cancer screening tests (Hinselmann, Schiller, Citology, Biopsy). The pipeline includes:

- Data loading and preprocessing (imputation, outlier removal, normalization)
- Dimensionality reduction via Principal Component Analysis (PCA)
- Class imbalance handling using SMOTE
- Model training and evaluation using SVM and K-Nearest Neighbors (KNN)
- Performance reporting (accuracy, precision, recall) and confusion matrix visualization

## Project Structure

```
├── data/
│   └── kag_risk_factors_cervical_cancer.csv  # Raw dataset
├── notebooks/
│   └── cervical_cancer_pipeline.ipynb       # Jupyter notebook with full pipeline
└── README.md                                # Project overview and instructions
```

## Requirements

- Python 3.7 or higher
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
   ```bash
   ```

git clone [https://github.com/](https://github.com/)/.git cd&#x20;

````
2. Install dependencies:
   ```bash
pip install -r requirements.txt
````

3. Launch the Jupyter notebook:
   ```bash
   ```

jupyter notebook notebooks/cervical\_cancer\_pipeline.ipynb

```
4. Run all cells to reproduce data preprocessing, training, and evaluation.

## Results
- **Best validation accuracy**: 78.7% on Citology test set using KNN
- Precision and recall metrics for all four screening outcomes are reported in the notebook.
- Confusion matrices are visualized to show true/false positive and negative counts.

## Contributing
Contributions and improvements are welcome. Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact
Yash Upadhyay — yash.upadhyay@example.com

Project repository: https://github.com/<your-username>/<repo-name>

```
