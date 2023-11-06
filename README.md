# Regression Plane Price Prediction


![Airbus plane](ASSETS/banner.jpg)

## Description

The aim of this project is to solve a specific problem: predicting airfare prices between different cities in India using data science techniques. To achieve this goal, I adopted a classical approach to solving data science problems, which I divided into two essential steps.

### Step 1 : Data Preprocessing

> The Jupyter notebook for this task is named `preporcessing.ipynb`, and it is located in the `/PREPROCESSING/` directory.

In this first phase, I carried out data preprocessing by applying various techniques: :

- [Outlier Detection]: Identifying and managing outliers to improve data quality.
- [Correlation Analysis]: Analyzing the relationships between variables to gain a better understanding of the data.
- [Feature Engineering]: Creating new features to enrich the available information.
- [Duplicate Detection]: Identifying and removing duplicates to ensure data integrity.
- [Data Exploration]: In-depth data analysis to extract relevant information.
- [Variable Encoding]: Transforming categorical variables into numeric format.

These steps helped build a clean and well-prepared dataframe, which I subsequently exported to the "data_for_modeling" folder in the "/Data/" directory.

### Step 2 : Modeling

> > The Jupyter notebook for this task is named `modeling.ipynb`, and it is located in the `/MODELING/` directory.


The second step of the project involved implementing advanced modeling techniques to solve the problem. I used the following methods:

- [Data Splitting]: Separating the data into training, testing, and validation sets.
- [Grid Search]: Systematically searching for the best hyperparameters for models.
- [Cross Validation]: Evaluating model performance using cross-validation.
- [Time Complexity]: Analyzing the time complexity of learning algorithms to optimize model selection.
  
All these steps enabled the selection of the most suitable model for my data and provided an effective solution to the initial problem.

## Installation

Ensure you have a Jupyter notebook with a configured Python environment. Install the following libraries using the following commands:

```bash
pip install pandas numpy matplotlib scikit-learn
```


## License

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Contacts

For any questions or comments, please feel free to contact me at the following email address: sekoudabo884@gmail.com or by visiting my GitHub profile.
