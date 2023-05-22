
## Project: Hospital Mortality Prediction

### Motivation:

The predictors of in-hospital mortality for intensive care units (ICU)-admitted heart failure (HF) patients remain poorly characterized. This project aims to develop and validate a prediction model for all-cause in-hospital mortality among ICU-admitted HF patients using machine learning techniques.

### Objective:

The main objective of this project is to predict the mortality rate, i.e., whether a person will live or die, based on various parameters observed. By analyzing different attributes in the provided dataset, we will build a machine learning model that can accurately predict the outcome.

### Project Timeline:

Data Analysis
Data Preprocessing
Model Building and Prediction using ML models
Evaluation and Performance Analysis

## Project Structure
The project directory is structured as follows:
.
 * [data](./Data)
   * [raw_data](./Data/Raw_data)
   * [processed_data](./data/processed_data)
 * [notebooks](./Notebooks)
   * [Data_Analysis.ipynb](./Notebooks/Data Analysis.ipynb) 
   * [Feature_Engineering.ipynb](./Notebooks/Data Preprocessing.ipynb)
   * [model_training.ipynb](./Notebooks/Model Development.ipynb)
 * [Reports](./Reports)
   * [report.md](./Reports/Report.md)
   * [visualizations](./Reports/Visualization)
 * [README.md](./README.md)

- The `data/` directory contains the raw data and processed data subdirectories, where you can store the respective data files.
- The `notebooks/` directory contains Jupyter notebooks for data analysis, feature engineering, and model training.
- The `reports/` directory contains the `report.md` file, which provides a detailed report on the project, and the `visualizations/` subdirectory, where you can save any generated visualizations.
- The `README.md` file is the current file you are reading, which provides an overview of the project and its structure.

## Usage

To run the project, follow these steps:

1. Ensure you have the necessary dependencies installed. You can find the required libraries in the Jupyter notebooks under the `notebooks/` directory.
2. Place the raw data files in the `data/raw_data/` directory.
3. Run the Jupyter notebooks in the following order:
   - `Data_Analysis.ipynb` for data analysis and exploration.
   - `Feature_Engineering.ipynb` for feature engineering and preprocessing.
   - `model_training.ipynb` for training and evaluating the machine learning models.
4. The generated visualizations will be saved in the `reports/visualizations/` directory.
5. The final project report will be available in the `reports/report.md` file.

Feel free to explore the project files, modify the code, and adapt it to your specific needs.
