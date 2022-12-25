# Credit Risk Analyzer
Credit Risk Analyzer is a Python program using machine learning algorithm to solve credit risk problem in a typical peer-to-peer lending financial services. Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. Using a dataset of historical lending activity from a peer-to-peer lending services company, we will demonstrate two separate Logistic Regression Models based on the original imbalanced data and the resampled data, to predict and identify the creditworthiness of loan profiles.  We will apply resampling techniques to enhance a model’s performance for imbalanced data. We’ll predict which loans to consider at risk vs. which to consider not at risk. The at-risk loans will make up only a small portion of all the data, which is often challenging when creating Logistic Regression model to predict possible high-risk loans.

The analysis is done in the following order.

* Step 1: Split the Data into Training and Testing Sets
* Step 2: Create a Logistic Regression Model with the Original Data
* Step 3: Predict a Logistic Regression Model with Resampled Training Data
* Step 4: Prepare a Credit Risk Analysis Report

The steps above will follow a typical model-fit-predict-evaluate pattern of implementing a machine learning algorithm in Python.

---

## Technologies

This project leverages python 3.7.* with the following additional packages:
* [Jupyter Notebook](https://jupyter.org/) - The Credit Risk Analyzer is written in the Jupyter Notebook.
* [Conda](https://docs.conda.io/projects/conda/en/latest/) - Conda environment is recommended to have Pandas library and other dependencies pre-installed.

**Required Libraries:**

You may need the following key libraries to work with the program.

- [Pandas](https://pandas.pydata.org/docs/reference/index.html) - pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labeled” data both easy and intuitive.
- [imbalanced-learn](https://pypi.org/project/imbalanced-learn/) - imbalanced-learn is a python package offering a number of re-sampling techniques commonly used in datasets showing strong between-class imbalance.
- [scikit-learn](https://scikit-learn.org/stable/getting_started.html/) - Scikit-learn is an open source machine learning library that supports supervised and unsupervised learning.

---

## Usage

To use the Credit Risk Analyzer application, clone the repository in your local workspace. From the Git Bash terminal, make sure to 'activate conda' and appropriate virtual enivorment. Next, launch the JupyterLab web-based interactive development environment (IDE) interface by typing at the prompt:

```python
  > jupyter lab
```
Next, open **credit_risk_resampling.ipynb** in a Jupyter Notebook web console. See the image below for a quick hint.

![Jupyter Notebook](Images/app_usage.png)

---

**The confusion matrix and classification report of the imbalanced data model show output as:**

![Imbalanced Data Model](Images/imbalanced.png)

---

**The confusion matrix and classification report of the resampled data model show output as:**

![Resampled Data Model](Images/resampling.png)

---

## Contributors

FinTech Labs, Inc.

---

## License

None