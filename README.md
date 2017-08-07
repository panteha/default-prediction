# Credit Default Prediction

This [notebook](Default_prediction.ipynb) investigates predicting credit card defaults using
this [dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients).

## Dependencies

* [Python 3](https://www.python.org/download/releases/3.0/)
* [Jupyter notebook](http://jupyter.org/)
* [Pandas](https://pandas.pydata.org/)
* [scikit-learn](http://scikit-learn.org/)
* [plotnine](https://github.com/has2k1/plotnine)
* [xlrd](https://github.com/python-excel/xlrd)

## How to run

* Clone the repository
```bash
$ git clone git@github.com:panteha/default-prediction.git
$ cd default-prediction
```
* Set up a virtual environment
```bash
$ pip3 install virtualenv
$ virtualenv env
$ . env/bin/activate
```
* Install dependencies
```bash
$ pip3 install jupyter
$ pip3 install pandas
$ pip3 install matplotlib
$ pip3 install sklearn
$ pip3 install scipy
$ pip3 install plotnine
$ pip3 install xlrd
```
* Download the dataset
```bash
$ mkdir data
$ curl -o ./data/defaults.xls 'https://archive.ics.uci.edu/ml/machine-learning-databases/00350/default%20of%20credit%20card%20clients.xls'
```
* Run Jupyer notebook
```bash
$ jupyter notebook
```
