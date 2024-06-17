# PRODIGY_ML_01
This repository contains a Linear Regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms. Developed during my internship at Prodigy, this project demonstrates the application of regression techniques in machine learning.
Certainly! Here's an updated guide for your README file, removing the duplicate text and ensuring clarity.

---
Welcome to the PRODIGY_ML_01 project! This project is focused on implementing a linear regression model to predict house prices based on their square footage, number of bedrooms, and number of bathrooms.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

PRODIGY_ML_01 is a machine learning project aimed at predicting house prices using a linear regression model. The model takes into account the square footage, number of bedrooms, and number of bathrooms of a house to make its predictions.

## Features

- **Data Preprocessing:** Handling missing values and feature selection.
- **Model Training:** Training a linear regression model.
- **Model Evaluation:** Evaluating the model using Mean Squared Error (MSE) and R-squared metrics.
- **Visualization:** Visualizing the actual vs. predicted house prices.

## Installation

To get started with this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/astromanu007/PRODIGY_ML_01.git
    cd PRODIGY_ML_01
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
   Note: Open the CMD Where the file is stored only.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare your dataset:
    - Ensure your dataset (`house_data.csv`) is in the project directory with columns: `SquareFootage`, `Bedrooms`, `Bathrooms`, and `Price`.

2. Run the project:
    ```bash
    python main.py
    ```

3. The script will output the Mean Squared Error, R-squared value, and display a plot of actual vs. predicted prices.

## Project Structure

```
PRODIGY_ML_01/
│
├── data/
│   └── house_data.csv     # Example dataset
│
├── src/
│   ├── preprocess.py      # Data preprocessing functions
│   ├── train.py           # Model training functions
│   ├── evaluate.py        # Model evaluation functions
│   └── visualize.py       # Visualization functions
│
├── main.py                # Main script to run the project
├── requirements.txt       # Required Python packages
└── README.md              # Project documentation
```

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to submit a pull request. Please make sure to follow the project's code of conduct.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions, feel free to contact me:

**Manish Avishkar Dhaatrak**  
GitHub: [astromanu007](https://github.com/astromanu007)
