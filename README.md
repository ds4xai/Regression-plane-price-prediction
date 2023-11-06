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
pip install pandas numpy matplotlib scipy scikit-learn
```


## License

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)


## Contributions

Contributions to this project are welcome! If you have any ideas for improvement, if you have identified errors or issues, or if you want to make changes, feel free to contribute.

### How to contribute

1. **Fork the project**: Start by forking this repository to your own GitHub account.

2. **Clone**: Clone the project from your GitHub account to your local machine.

   ```bash
   git clone git clone https://github.com/NirSheva/Regression-plane-price-prediction.git
   ```

3. Create a Branch: Create a branch to work on your modification.
4. 
    ```bash
        git checkout -b my-modification
    ```
5. Make Changes: Make your modifications, improvements, or corrections.

6. Commit: Commit your changes.
   
   ```bash
    git commit -m "Addef feature X" 
   ```

7. Push: Push your changes to your GitHub account.

    ```bash
        git push origin my-modification
    ```
8. Pull Request: Create a Pull Request from your GitHub account. Make sure to provide a clear description of your changes and the reasons why they should be integrated.

9. Discussion: Engage in the discussion regarding the Pull Request to talk about your changes and potentially enhance them.

## Notes and Suggestions

If you have any comments, suggestions, or questions, feel free to share them by opening a new issue. We appreciate community feedback and are open to continuous improvement of this project.

Thank you for your participation and your interest in this project!


## Contacts

For any questions or comments, please feel free to contact me at the following email address: sekoudabo884@gmail.com or by visiting my GitHub profile.
