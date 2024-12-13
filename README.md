# Air Quality Forecasting

This project focuses on the analysis and forecasting of air quality using time-series data. The project is divided into two main parts: Exploratory Data Analysis (EDA) and Time-Series Forecasting.

## Project Structure

- `EDA-ON-AIR-QUALITY-TIME-SERIES-DATASET.ipynb`: This notebook contains the exploratory data analysis of the air quality dataset.
- `TIME-SERIES-FORECASTING-OF-AIR-QUALITY-3.ipynb`: This notebook focuses on the time-series forecasting of air quality.

## Dataset

The dataset used in this project is the Air Quality UCI dataset, which contains various air quality measurements collected from a monitoring station.

## Exploratory Data Analysis (EDA)

The EDA notebook includes the following steps:

1. **Data Loading and Preprocessing**:

   - Import necessary libraries.
   - Load the dataset and handle missing values.
   - Convert columns with commas to numeric values.
   - Combine `Date` and `Time` columns into a single `Datetime` column.

2. **Data Visualization**:
   - Plot distribution of key features using histograms.
   - Generate a correlation heatmap to understand relationships between variables.
   - Plot time-series trends for selected features.

## Time-Series Forecasting

The forecasting notebook includes the following steps:

1. **Data Preparation**:

   - Load and preprocess the dataset.
   - Split the data into training and testing sets.

2. **Modeling**:
   - Implement various time-series forecasting models.
   - Evaluate model performance using appropriate metrics.

## Requirements

- Python 3.11.5
- Libraries: pandas, matplotlib, seaborn, warnings, torch, wandb

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Lee4real/air-quality-forecasting.git
   ```
2. Navigate to the project directory:
   ```bash
   cd air-quality-forecasting
   ```
3. Run the notebooks to perform EDA and forecasting.

## Conclusion

This project provides a comprehensive analysis and forecasting of air quality data. The EDA helps in understanding the data, while the forecasting models provide insights into future air quality trends.
