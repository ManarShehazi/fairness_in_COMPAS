# Fairness in Classification on the COMPAS Dataset

## Overview

This project involves analyzing fairness in classification using the **COMPAS** dataset, which includes information about criminal defendants in Broward County, Florida, screened for recidivism risk. The COMPAS risk assessment tool has been shown to exhibit bias against certain demographic groups, and this project explores those biases, builds classifiers to predict recidivism, and attempts to create a fairer model. The project was completed in April 2024 as part of the **Foundations of Data Science** course.

## Project Goals

1. **Bias Analysis**: Analyze the COMPAS dataset to identify biases, especially those related to race and gender.
2. **Standard Classifiers**: Train multiple classifiers to predict recidivism and evaluate their fairness relative to COMPAS.
3. **Fair Classifier**: Implement a classifier that incorporates a fairness notion and compare its performance and fairness to standard classifiers.

## Dataset

The **COMPAS dataset** includes demographic information, criminal history, and recidivism risk scores for defendants. Key fields include:
- **Demographic Information**: Gender, race, etc.
- **Criminal History**: Prior offenses, case details.
- **COMPAS Scores**: Risk rating (1-10) and categorization into low, medium, or high risk.
- **Recidivism Outcome**: Whether the defendant re-offended within two years.

Link to dataset: [compas-scores-two-years.csv on GitHub](https://github.com/propublica/compas-analysis).

## Features

- **Dataset Exploration**: Conduct a descriptive analysis of the dataset, covering feature distributions, label distributions, and demographic breakdowns.
- **Bias Detection**: Calculate performance metrics for the COMPAS classifier across different demographic groups (e.g., racial and gender differences).
- **Standard Classification Models**:
  - Train and evaluate multiple classifiers (e.g., logistic regression, decision trees, SVM) to predict recidivism.
  - Compare classifier performance to COMPAS and analyze their fairness.
  - Define and evaluate fairness metrics for each classifier.
- **Fair Classifier Implementation**:
  - Explore methods to create fair classifiers, such as excluding race from features or applying fairness constraints.
  - Implement a fair classifier and compare its performance and fairness to other models.

## Technologies Used

- **Programming Language**: Python
- **Jupyter Notebook**: For code, analyses, and visualizations
- **Libraries**: 
  - **pandas** and **numpy** for data manipulation
  - **scikit-learn** for machine learning models
  - **matplotlib** and **seaborn** for visualizations


## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/fairness_in_COMPAS.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd fairness_in_COMPAS
    ```

3. **Install Dependencies**:
    Install the required Python packages.
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook fairness_with_COMPAS_notebook.ipynb
    ```

## Usage

The notebook guides you through each stage of the analysis:
1. **Dataset Exploration**: Load the data, examine feature distributions, identify missing values, and assess demographic breakdowns.
2. **Bias Detection**: Evaluate COMPAS classifier's performance across different demographic groups and compute fairness metrics.
3. **Training Classifiers**: Train standard classifiers on the recidivism prediction task and evaluate their performance and fairness.
4. **Fair Classifier Implementation**: Experiment with fairness-enhancing methods, build a fair classifier, and analyze its results.

## References

1. **Fairness and Machine Learning** by Barocas, Hardt, and Narayanan. Available at [fairmlbook.org](http://www.fairmlbook.org).
2. **Fair prediction with disparate impact** by Chouldechova. Available on [arxiv.org](https://arxiv.org/abs/1703.00056).
3. **Equality of opportunity in supervised learning** by Hardt, Price, and Srebro. Available on [arxiv.org](https://arxiv.org/abs/1610.02413).
4. **Learning classification without disparate mistreatment** by Zafar et al. Available on [arxiv.org](https://arxiv.org/abs/1610.08452).
5. **Learning fair representations** by Zemel et al. Available at [proceedings.mlr.press](http://proceedings.mlr.press/v28/zemel13.html).

## Team Members

- **Andrei Ilin**
- **Anna Krysta**
- **Manar Shehazi**

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- **University of Grenoble Alpes** for providing resources and guidance.
- **ProPublica** for making the COMPAS dataset publicly available.


