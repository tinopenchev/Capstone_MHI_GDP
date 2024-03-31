# Capstone_MHI_GDP

## Overview

"Capstone_MHI_GDP" leverages sophisticated data analysis and machine learning techniques to explore the impact of Mental Health Issues (MHI) on the Gross Domestic Product (GDP) across Bulgaria's regions. This project aims to inform policy-making processes, enabling the optimization of EU fund allocation for enhancing regional economic development and addressing MHI.

## Installation

To run the analyses presented in this project, ensure you have the following libraries installed in your Python environment:

- numpy
- pandas
- matplotlib
- seaborn
- scipy
- statsmodels
- sklearn
- pymc
- arviz
- tensorflow
- torch
- linearmodels

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scipy statsmodels scikit-learn pymc3 arviz tensorflow torch linearmodels
```

## Project Structure

The project is structured into several key sections, each critical for understanding the relationship between MHI and GDP:

### Panel Data Analysis
This section delves into analyzing time-series data from different regions, focusing on MHI indicators like depression and suicide rates and their correlation with GDP.

### Feature Engineering
In this critical step, input features are normalized to improve the model's performance. Two normalization techniques are highlighted:
- **Min-Max Normalization:** Scales the data to a range of [0, 1].
- **Standardization (Z-Score Normalization):** Scales features based on their mean and standard deviation, resulting in a distribution with a mean of 0 and a standard deviation of 1.

Normalization ensures that our neural network models, which utilize activation functions like sigmoid or tanh, receive data within an appropriate range.

## Usage

Follow the Jupyter notebook `Capstone - Full Pipeline.ipynb` for a step-by-step guide through the analysis. The notebook is structured to guide you from data preprocessing, through panel data analysis and feature engineering, to the final machine learning model training and evaluation.

### Running the Notebook
1. Ensure all dependencies are installed.
2. Open the notebook in Jupyter Lab or Jupyter Notebook.
3. Execute the cells in order to replicate the study findings.

## Contributing

Contributions to enhance the models, explore new datasets, or improve the analysis methodology are welcome. Please refer to the project's contribution guidelines for more details.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.
