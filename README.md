# Predicting Crop Export Values: An MLP Regression Model

## Description

This project uses a Multilayer Perceptron (MLP) regression model to forecast the export value of crops for various geographical regions. The analysis is based on multiple economic, agricultural, and environmental indicators compiled from the [FAO Statistics](https://www.fao.org/faostat/en/#home) dataset. The workflow involves preprocessing individual datasets, merging them on common variables like country and year, and analysing them with the MLP regressor.

## Installation

To set up this project, install the following dependencies:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

You can install the required packages using pip:

```bash
pip install numpy matplotlib pandas scikit-learn seaborn jupyter
```

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Al-Saqib/MLP-Model-for-Agricultural-Output.git
```

2. Navigate to the project directory:

```bash
cd MLP-Model-for-Agricultural-Output
```

3. Open the Jupyter notebooks for step-by-step execution:
   - data_preprocessing.ipynb: Preprocess individual datasets.
   - data_merge.ipynb: Merge datasets based on common variables (e.g., country, year).
   - data_analysis.ipynb: Train and evaluate the MLP regression model
  
## Dataset
The dataset used for this project is not included in the repository. Users can download the necessary data directly from the FAO Statistics website. Ensure that data files are formatted correctly and contain consistent variables (e.g., year, country) before running the notebooks.

## Project Workflow
1. **Data Preprocessing**:
- Handle missing values using imputation.
- Standardise features with scaling.
- Perform feature engineering for effective analysis.

2. **Data Merging**:
- Integrate individual datasets on common keys like country and year.

3. Analysis:
- Train the MLP model using optimised hyperparameters.
- Evaluate performance using metrics such as MAE, RMSE, and R².

## Features
### Model Setup
- Architecture: Multilayer Perceptron (MLP) with optimised hidden layers.
- Activation Function: ReLU for non-linear transformations.
- Regularisation: L2 penalty to reduce overfitting.
- Optimiser: Adam for efficient gradient-based optimisation.

### Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
R² (Coefficient of Determination)

## Results
The MLP model demonstrates high accuracy, achieving an R² score of 0.97 on the validation set.

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Commit changes with clear messages.
4. Push to your fork and submit a pull request.


## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For questions or collaborations, reach out via email: saqib.majumder01@gmail.com
