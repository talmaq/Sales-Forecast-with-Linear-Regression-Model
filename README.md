# Sales Forecast with Linear Regression Model

This project demonstrates how to use a Linear Regression model to forecast monthly sales data. The approach involves transforming time series data, generating lagged features, and using these features to predict future sales.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Project Overview

The aim of this project is to build a sales forecasting model using a Linear Regression approach. By analyzing historical sales data, we create a model that can predict future sales based on past trends and patterns.

### Key Features

- Data preprocessing and cleaning
- Time series transformation and feature engineering
- Model training and evaluation using Linear Regression
- Visualization of actual vs. predicted sales

## Dataset

- The dataset used in this project is `train.csv`, which contains historical sales data.
- **Columns:**
  - `date`: Date of the sales record.
  - `sales`: Total sales for that day.
  - `store`: Store identifier (if applicable).
  - `item`: Item identifier (if applicable).

> **Note:** Make sure your dataset is placed in the root directory of the project with the name `train.csv`.

## Installation

To run this project, you will need to have Python installed along with the following Python packages:

- Pandas
- NumPy
- Matplotlib
- scikit-learn

You can install all required packages using the following command:

\`\`\`bash
pip install -r requirements.txt
\`\`\`

> Ensure you are using a Python environment to avoid conflicts with other projects.

## Results

- The results of the Linear Regression model are plotted to show the actual vs. predicted sales.
- Performance metrics like MSE, MAE, and R² are calculated to evaluate the model's accuracy.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
