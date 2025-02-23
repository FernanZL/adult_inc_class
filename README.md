# EDA and Classification Prediction on Adult Income Dataset

This proyect does a brief EDA and trains some classification models over Kaggle's Adult Census Income [dataset](https://www.kaggle.com/datasets/uciml/adult-census-income). You can download the data from there.
The target consists on predicting if an adult's income is less or equal than 50k, or more than 50k. The caveat is the amount of each class is imbalanced.

## Included Files

- 'adult_inc_class.ipynb': notebook containing the analysis and models.

## Requirements

To run the project, Python 3.9 and the following libraries are required:  
- pandas  
- numpy  
- matplotlib  
- scikit-learn  
- seaborn  
- jupyter  
- lightgbm  
- optuna  
- category_encoders

To install the dependencies, you can use the following command:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn lightgbm optuna category_encoders jupyter
```

## Download the Dataset
Before running the project, download the dataset from Kaggle, using the link provided above.

## How to run

1. Clone the repository
If you don't have Git installed, first [install](https://git-scm.com/) it, then run this command in your terminal to clone the repository:

```bash
git clone https://github.com/FernanZL/selled_vehicl_arg.git
```

2. Install the dependencies
Once you have cloned the repository, install the necessary libraries using the following command:
```bash
pip install numpy pandas matplotlib scikit-learn seaborn lightgbm optuna category_encoders jupyter
```

3. Open the notebook
To open the notebook in Jupyter, run the following command in the terminal:

```bash
jupyter notebook selled_vehicl_arg.ipynb
```

Within the Jupyter notebook, you can run the code cells one by one by pressing Shift + Enter to perform the analysis and get the results.
