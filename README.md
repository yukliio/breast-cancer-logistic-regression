# breast-cancer-logistic-regression


## Overview

This project demonstrates the use of a logistic regression model to predict breast cancer. The objective is to classify whether the cancer is benign or malignant based on various input features. The implementation utilizes Python's `pandas` for data manipulation and `scikit-learn` for building and evaluating the model.

## Features

- **Data Loading and Preprocessing:** Efficiently read and preprocess the breast cancer dataset for analysis.
- **Model Training:** Train a logistic regression model to classify the cancer types.
- **Evaluation:** Assess the model’s performance using confusion matrix and cross-validation techniques.

## Dataset

The dataset used in this project is the `breast_cancer.csv` file, which includes multiple features related to breast cancer and a target variable indicating whether the cancer is benign or malignant.

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/breast-cancer-prediction.git
   cd breast-cancer-prediction
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure that the `breast_cancer.csv` file is present in the project directory.

2. Execute the script to train and evaluate the logistic regression model:
   ```bash
   python main.py
   ```

3. The script will display the predicted results, a confusion matrix, and cross-validation outcomes.

## Results

The model’s performance is evaluated using a confusion matrix, which details the true positives, false positives, true negatives, and false negatives. Additionally, cross-validation provides insights into the model's accuracy and reliability by computing average accuracy and standard deviation across multiple splits of the data. It has an accuracy of 96.70% and a SD of 1.97%

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

## Contributing

Contributions to improve this project are welcome! Feel free to fork the repository and submit a Pull Request with your enhancements.

## Acknowledgments

- The dataset used in this project is sourced from publicly available repositories, and we extend our gratitude to those who provided it for research and educational purposes.
