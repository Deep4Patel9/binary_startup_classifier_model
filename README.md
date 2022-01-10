# binary_startup_classifier_model

Predict success with up to a 73 percent accuracy in funding applicants.

---

## Technologies

This project uses python 3.7 along with jupyter lab 3.0.14 with the following packages:


* [pandas](https://github.com/pandas-dev/pandas) - For data manipulation and analysis

* [sklearn](https://scikit-learn.org/stable/) - To split, scale, model, and analyse datasets

* [tensorflow](https://www.tensorflow.org/) - library used to develop and train ML models

* [keras](https://keras.io/) - Creating deep learning models (included in tensorflow library)

---

## Installation Guide

Before running the application first install the following dependencies:

```python
$ pip install pandas
$ pip install -U scikit-learn
$ pip install --upgrade tensorflow
```

---

## Usage

This model is used to predict whether or not a a funding applicant will be successful by using historical data of other funding applicants and whether or not they were successful after being funded. It used a 2 and 3 hidden layer nueral network to sort out successful applicants the current accuracy rating is ~73 percent. Optimization methods tested were increasing nodes(no visible increase was seen after adding and removing nodes from a 2 and 3-layer network), epochs(up to 100 from 50 with only a 1 percent increase), and increasing layers (up to 3). However there were minimal improvements seen from the model. 

---

## Contributors

Deep Patel -- Deep4Patel9@gmail.com

---

## License

MIT License
