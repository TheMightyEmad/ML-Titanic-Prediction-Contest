# Titanic Machine Learning Competition

This repository contains a simple Jupyter Notebook for the [Kaggle Titanic Machine Learning Competition](https://www.kaggle.com/c/titanic). The goal of the competition is to predict which passengers survived the Titanic shipwreck based on various features such as age, gender, class, and fare.

## Repository Contents

- `Titanic_ML_LR.ipynb`: This is the Jupyter Notebook containing the code for the machine learning model.
- `train.csv`: The training dataset provided by Kaggle which contains information about the passengers and whether they survived or not.
- `test.csv`: The test dataset provided by Kaggle which contains similar information about the passengers but without survival labels. The goal is to predict the labels using the trained model.

## How to Use

The notebook can be run by opening it in [Jupyter Notebook](https://jupyter.org/install) or [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html). It is advised to have the latest version of Python (currently [3.9](https://www.python.org/downloads/)) installed along with the necessary packages mentioned in the notebook.

The model is built using Logistic Regression and only uses a subset of the available features. The accuracy of the model may not be the best and can be improved by using more advanced machine learning techniques and feature engineering.

## References

The code in the notebook is based on the tutorial provided by [Manav Sehgal](https://www.kaggle.com/startupsci/titanic-data-science-solutions) on the Kaggle website. Other useful resources used for this notebook include:

- [Scikit-Learn documentation](https://scikit-learn.org/stable/documentation.html)
- [Pandas documentation](https://pandas.pydata.org/docs/)
- [NumPy documentation](https://numpy.org/doc/)
- [Matplotlib documentation](https://matplotlib.org/stable/contents.html)
