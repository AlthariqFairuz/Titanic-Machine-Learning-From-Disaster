## Titanic: Machine Learning from Disaster
This project presents an in-depth analysis of the Titanic dataset, exploring the factors that influenced passenger survival aboard the RMS Titanic. Through careful data analysis and machine learning techniques, this notebook aims to understand the social, economic, and demographic factors that played a role in determining survival rates during this historic maritime disaster.

## 📋 Overview
The dataset comes from the Kaggle competition [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/overview).

## 🛠️ Requirements
The project requires the following main dependencies:
- Python 3.x
- Numpy
- Matplotlib and Seaborn (for visualization)
- scikit-learn (for evaluation metrics)
- Jupyter Notebook (for interactive development)

## 🚀 Getting Started

1. Clone the repository:
  ```bash
    git clone https://github.com/AlthariqFairuz/Titanic-Machine-Learning-From-Disaster.git
    cd Titanic-Machine-Learning-From-Disaster
  ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook from local or google colab

## 🤖 Model Architecture
There are some models that being used in this notebook:
1. Gaussian Naive Bayes 
2. Logistic Regression
3. CART
4. KNN
5. Random Forest
6. SVC
7. XGBoost

This notebook also uses Grid Search for hyperparameter tuning for some models in order to find the best parameters. The best model in this notebook is the Hard Voting Classifier with ```accuracy 0.7918``` on the test dataset.
