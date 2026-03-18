# Gold Recovery Optimization: Machine Learning for Industrial Processes

## Project Overview
This project focuses on optimizing the gold extraction process from ore. Using a data-driven approach, I built a machine learning model to predict the gold recovery concentrate at different stages: rougher and final.

## Dataset Access
Due to file size limitations on GitHub, the datasets are hosted externally. You can download the required CSV files for training and testing here:
* [**Download Project Datasets**]((https://drive.google.com/drive/folders/1QaHdj42U3QMOCPxfF60-zmOP--22Y0Gu?usp=drive_link))

*Note: Place the files in a folder named `data/` within the project root for the notebook to run correctly.*

## Key Objectives
* **Data Validation:** Verify recovery calculations using Mean Absolute Error (MAE).
* **Process Analysis:** Study metal concentrations (Au, Ag, Pb) changes through purification stages.
* **Modeling:** Train and evaluate models (Linear Regression, Random Forest) using Cross-Validation.
* **Custom Metric:** Implementation of Final sMAPE to weight stage-specific errors.

## Technical Skills
* **Python:** Pandas, NumPy, Scikit-learn.
* **Visualization:** Matplotlib, Seaborn.
* **Metrics:** sMAPE, MAE, Cross-validation.

## Results
The Final Random Forest model achieved the best performance, outperforming the baseline (DummyRegressor), proving its effectiveness in predicting industrial output.
