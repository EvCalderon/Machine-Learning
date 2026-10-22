# Machine Learning Labs

Applied machine-learning notebooks developed in Python during my Data Science training. The collection combines conceptual explanations in Spanish with executable workflows for preprocessing, model training, validation, tuning, and interpretation.

## What this repository demonstrates

- Supervised learning for regression and classification
- Reproducible train/validation/test workflows
- Pipelines, imputation, scaling, and categorical encoding
- Cross-validation, learning curves, and hyperparameter search
- Model evaluation with accuracy, precision, recall, F1, ROC-AUC, MSE, MAPE, and R²
- Strategies for imbalanced classes, including SMOTE and hybrid resampling
- Clear written interpretation alongside code and visualizations

## Notebook guide

| Notebook | Main focus |
|---|---|
| [`1erML R.ipynb`](./1erML%20R.ipynb) | End-to-end introduction to machine learning and multiple linear regression |
| [`Regularización R.ipynb`](./Regularizaci%C3%B3n%20R.ipynb) | Linear regression, Lasso, Ridge, and Elastic Net regularization |
| [`Logistica R.ipynb`](./Logistica%20R.ipynb) | Logistic-regression workflow and classification evaluation |
| [`Árbol de Decisiones.ipynb`](./%C3%81rbol%20de%20Decisiones.ipynb) | Decision trees and Random Forest comparison |
| [`Vecinos más Cercanos.ipynb`](./Vecinos%20m%C3%A1s%20Cercanos.ipynb) | KNN, neighbor selection, Grid Search, and Randomized Search |
| [`Bayes.ipynb`](./Bayes.ipynb) | Gaussian Naive Bayes and KNN comparison using ROC-AUC |
| [`Máquina de Vector Soporte R.IPYNB`](./M%C3%A1quina%20de%20Vector%20Soporte%20R.IPYNB) | Linear and nonlinear SVM decision boundaries |
| [`Clases No Balanceadas.ipynb`](./Clases%20No%20Balanceadas.ipynb) | Oversampling, undersampling, SMOTE, Tomek Links, and hybrid methods |
| [`CurvaROC R.ipynb`](./CurvaROC%20R.ipynb) | ROC curves, AUC, and classifier comparison |
| [`LearningCurves.ipynb`](./LearningCurves.ipynb) | Validation curves and learning curves for model diagnosis |
| [`RNN R.ipynb`](./RNN%20R.ipynb) | Multilayer perceptron regression and classification experiments |

> **Naming note:** these are Python notebooks. Some historical course filenames include the suffix “R”; `RNN R.ipynb` contains a multilayer perceptron rather than a recurrent neural network.

## Run locally

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

## Reproducibility notes

- `Bayes.ipynb` and `CurvaROC R.ipynb` expect a local `pima-indians-diabetes.csv` teaching dataset, which is not redistributed here.
- `1erML R.ipynb` contains references to the Google Colab sample-data directory; update those paths when running locally.
- Graphviz is optional and may be required by the decision-tree visualization in addition to the Python packages listed in `requirements.txt`.
- The notebooks are preserved as learning artifacts. Each one documents its assumptions and should be reviewed before adapting it to production data.

## Author

**Evelyn Calderón Madrigal** — Data Analyst | Data Science | Biotechnology  
[GitHub](https://github.com/EvCalderon) · [LinkedIn](https://www.linkedin.com/in/evelyn-calder%C3%B3n-madrigal/)
