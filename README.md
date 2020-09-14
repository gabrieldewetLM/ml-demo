# Machine Learning Demo with Python

## Resources & requirements
### 1. Python - [Anaconda distribution](https://www.anaconda.com/products/individual), which includes:
- Useful libraries, for example:
    - Data analysis - [pandas](https://pandas.pydata.org)
    - Statsitical modelling - [statsmodels](https://www.statsmodels.org/stable/index.html) 
    - Machine learning - [scikit-learn](https://scikit-learn.org/stable)
    - Plotting - [seaborn](https://seaborn.pydata.org/index.html) 
- Development environments:
    - [IPython and Jupyter Notebook](https://ipython.org/) (also supports R)
    - [Spyder IDE](https://www.spyder-ide.org/) (Rstudio for python)

### 2. Other development environments
- Jupyter Lab (used for part 1 of demo)
    - Install [intsructions](https://jupyter.org/install.html)
- Visual Studio Code (used in part 2)
    - Install [here](https://code.visualstudio.com/)
        
### 3. Other python packages
- [Keras](https://keras.io/) & [Tensorflow](https://www.tensorflow.org/) - deep learning
- [lifelines](https://lifelines.readthedocs.io/en/latest/) & [scikit-survival](https://scikit-survival.readthedocs.io/en/latest/) - survival analysis
- [XGBoost](https://xgboost.readthedocs.io/en/latest/) & [LightGBM](https://lightgbm.readthedocs.io/en/latest/) - gradient boosting libraries 

### 4. Datasets
- Regression example (Part 1)
    - Advertising dataset from *An Introduction to Statistical Learning, with applications in R* - G. James, D. Witten,  T. Hastie and R. Tibshirani 
    - 300 observations with 3 input variables (TV, radio, newspaper) & single response variable (sales)
    - Download [here](http://faculty.marshall.usc.edu/gareth-james/ISL/data.html)
- Classification example (Part 2)
    - Fashion MNIST, from *Fashion-MNIST: a Novel Image Dataset for Benchmarking Machine Learning Algorithms* - Han Xiao, Kashif Rasul, Roland Vollgraf [arXiv:1708.07747](https://arxiv.org/abs/1708.07747)
    - Collection of 70 000, 28x28 images where each image belongs to one of 10 different classes.
    - [Source](https://github.com/zalandoresearch/fashion-mnist)
    
---

## Agenda
### Part 1: Regression in scikit-learn
1. Loading & exploring data
2. Model fitting 
    1. Entire data set
    2. Train vs Test split
3. Other models for regression
4. Evaluating & comparing models
    1. Metrics
    2. Cross validation

### Part 2: Classification with CNN
1. Image data introduction (Fashion MNIST)
2. Data analysis & preprocessing
3. Defining the network structure
4. Model fitting:
    1. Without regularization
    2. With regularization
5. Model evaluation on test set (classification report)