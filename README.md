
## Objective:
1.This project aims apply various [Python](https://www.python.org/) tools to get a visual understanding of the data and clean it to make it ready to apply machine learning opertation on it and to finally able to predict prices of houses.

2. Develop an algorithm to estimate the value of the residential homes based on fixed characteristics (those that are not considered easy to renovate).

3. Identify characteristics of homes that the company can cost-effectively change/renovate with their construction team.

Use the information to buy homes that are likely to sell for more than the initial purchase.

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

### Usage
* Clone repository and run **Datasetform.ipynb** to create dataset.
  * Preprocessing is required to convert 'text files' into  into `csv file`
  * `Datasetform.ipynb` used for extracting data from text files and  `FinalDataset.csv` is made.
  * * Run `DataAnalysis.ipynb` to visualize train and test dataset using pandas dataframe[pandas](https://pandas.pydata.org).
* Run `Feature Analysis.ipynb` to visualize relations between features and target value .
* Run `Feature Engineering.ipynb` for trying new features and feature selection and filling **NaN** values through **mean**.
  * After this data is fit with different models.
* Run `Algorithm_models.py`
  *  detail of `time` and `r2_score analysis` by  hyperparameters tuning of  regressions .
  * This will run `cross validation` across the training set on **LinearRegression**, **GradientBoostingRegessorr** and prints `r2_score`.
### Results
* With the help of `GradientBoostingRegessorr` and tuned parameters we are able to achieve r2_score of **0.995416710249**.
* `Solution.csv` is also given in repository to match results of test datase.
## Authors
This repo is maintained by Lovely Chaoudhary (mailto: lovelychoudhary1309@gmail.com)
