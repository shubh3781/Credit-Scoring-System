# Credit Scoring System

This repository contains a project for developing a Credit Scoring System using logistic regression and the Weight of Evidence (WoE) concept. The project is implemented in a Jupyter Notebook and uses the German Credit Data from the UCI Machine Learning Repository.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The objective of this project is to develop a credit scoring system to assess the creditworthiness of loan applicants. The system uses logistic regression and the Weight of Evidence (WoE) concept to provide a credit score, improve approval rates, and reduce false positives.

## Dataset

The dataset used in this project is the German Credit Data from the UCI Machine Learning Repository. It contains information on individuals' creditworthiness, including features such as age, income, loan amount, loan purpose, and credit history.

- [German Credit Data](https://archive.ics.uci.edu/ml/machine-learning-databases/statlog/german/german.data)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/credit-scoring-system.git
    cd credit-scoring-system
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Navigate to `credit_scoring_system.ipynb` and open it.

3. Follow the steps in the notebook to load the data, preprocess it, train the logistic regression model, and evaluate its performance.

## Project Structure

- `credit_scoring_system.ipynb`: Jupyter Notebook containing the implementation of the credit scoring system.
- `README.md`: Project documentation.

## Results

The results of the project include the following:
- Classification report with precision, recall, F1-score, and support.
- ROC-AUC score and ROC curve plot.
- Insights into the most important features affecting creditworthiness.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
