# Time Series Analysis and Forecasting - AI19642

This repository contains a series of experiments focused on Time Series Analysis and Forecasting as part of the course **AI19642**. The experiments aim to cover various aspects of time series data handling, visualization, and forecasting techniques. Each experiment is structured with a Jupyter notebook, datasets, and a Word document describing the steps and methodologies used.

## Table of Contents

### [Experiment 1: Time Series Data Cleaning, Loading, and Pre-processing](https://github.com/Abiney-Yadav/Time-Series-and-Forecasting/tree/main/exp1)
### [Experiment 2: Visualizing Time Series Data](https://github.com/Abiney-Yadav/Time-Series-and-Forecasting/tree/main/exp2)
3. [Experiment 3: Linear Regression Model for Forecasting](#experiment-3)
4. [Experiment 4: Estimating & Eliminating Trend (Aggregation, Smoothing)](#experiment-4)
5. [Experiment 5: Checking Stationarity of Time Series Data](#experiment-5)
6. [Experiment 6: Moving Average Smoothing for Forecasting](#experiment-6)
7. [Experiment 7: Decomposing Time Series Data (Trend and Seasonality)](#experiment-7)
8. [Experiment 8: ARIMA Model for Time Series Forecasting](#experiment-8)
9. [Experiment 9: Neural Network-based Forecasting Model](#experiment-9)
10. [Experiment 10: Vector Auto Regression (VAR) Model for Multivariate Forecasting](#experiment-10)

## Folder Structure

Each experiment is stored in a separate folder, named as `exp1`, `exp2`, ..., `exp10`. Inside each folder, you will find the following files:

- **exp.ipynb**: The Jupyter Notebook containing the code for the respective experiment.
- **dataset**: The dataset file used for the experiment (usually in CSV, Excel, or other formats).
- **word document**: A Word document detailing the steps, methodology, and results of the experiment.

## List of Experiments

### Experiment 1: Time Series Data Cleaning, Loading, and Pre-processing
- This experiment involves cleaning, loading, and pre-processing time series data.
- Focuses on handling missing values, handling outliers, and standardizing the data format for analysis.

### Experiment 2: Visualizing Time Series Data
- In this experiment, various visualization techniques such as line plots, box plots, and histograms are used to visualize time series data.

### Experiment 3: Checking Stationarity of Time Series Data
- This experiment involves testing for the stationarity of time series data using techniques like the Augmented Dickey-Fuller test.

### Experiment 4: Estimating & Eliminating Trend (Aggregation, Smoothing)
- Techniques for eliminating trends such as aggregation and smoothing are implemented to make the data stationary and more suitable for forecasting.

### Experiment 5: Linear Regression Model for Forecasting
- This experiment implements a linear regression model to forecast future values based on historical time series data.

### Experiment 6: Moving Average Smoothing for Forecasting
- This experiment applies moving average smoothing techniques to prepare the data and create time series forecasts.

### Experiment 7: Decomposing Time Series Data (Trend and Seasonality)
- In this experiment, time series data is decomposed into its trend, seasonal, and residual components to better understand the underlying patterns.

### Experiment 8: ARIMA Model for Time Series Forecasting
- The ARIMA (Auto-Regressive Integrated Moving Average) model is applied to forecast future time series values based on historical data.

### Experiment 9: Neural Network-based Forecasting Model
- This experiment focuses on implementing a neural network model for time series forecasting, utilizing deep learning techniques.

### Experiment 10: Vector Auto Regression (VAR) Model for Multivariate Forecasting
- In this experiment, the Vector Auto Regression (VAR) model is implemented for forecasting multivariate time series data.

## Requirements

The following packages are required to run the Jupyter Notebooks:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scikit-learn
- tensorflow (for neural networks)
- pmdarima (for ARIMA models)

To install the necessary libraries, you can use the following command:

```bash
pip install pandas numpy matplotlib seaborn statsmodels scikit-learn tensorflow pmdarima
```
## Additional Notes
- The datasets provided in each folder are meant to be used for the respective experiment.
- Ensure that the dataset is correctly loaded into the Jupyter Notebook before running the code.
- The Word documents provide detailed explanations of the methodology, data analysis, and results for each experiment.
- If you encounter any issues, feel free to raise an issue in the repository.
