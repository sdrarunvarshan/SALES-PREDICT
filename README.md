# Time Series Forecasting for Warehouse Sales

## Project Overview
This project performs time series forecasting on warehouse sales data using Python. It employs the Holt-Winters Exponential Smoothing model to predict future sales based on historical data. The analysis is performed using monthly sales data grouped by warehouse and visualized for better insights.

## Contributors
- **Primary Developer:**  [sdrarunvarshan](https://github.com/sdrarunvarshan)

- **Collaborator:** [Parimala-15](https://github.com/Parimala-15)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-Learn
- Google Colab

## Project Structure
- **Data Upload:** Users upload an Excel dataset containing warehouse sales.
- **Data Transformation:** Data is reshaped for time series analysis.
- **Exploratory Data Analysis (EDA):** Basic statistics, missing values, and sales visualizations are generated.
- **Time Series Forecasting:** Holt-Winters Exponential Smoothing is applied to predict future sales.
- **Forecast Evaluation:** Model performance is evaluated using Mean Absolute Percentage Error (MAPE).
- **Results Export:** Forecasted results are exported to an Excel file and made available for download.

## Installation & Setup
1. Open Google Colab.
2. Run the following commands to install necessary libraries if not already available:
   ```python
   !pip install pandas numpy matplotlib statsmodels openpyxl
   ```
3. Copy and run the provided code in a Colab notebook.
4. Upload your dataset when prompted.

## Dataset Requirements
The dataset should be in Excel format with the following columns:
- `Warehouse id`
- `Region`
- `SKU id`
- Monthly sales columns in `MMM-YY` format (e.g., `Jan-21`, `Feb-21`, etc.)

## Usage Instructions
1. Run the notebook.
2. Upload the dataset file when prompted.
3. Review the EDA output and visualizations.
4. View the forecast results printed in the notebook.
5. Download the `Forecast_Results.xlsx` file when it becomes available.

## Model Insights
The model uses Holt-Winters Exponential Smoothing with additive seasonality and a seasonal period of 12 months. MAPE is calculated to evaluate the model's accuracy.

## Sample Output
The resulting forecast file will contain the following columns:
- `Warehouse id`
- `Region`
- `SKU id`
- `Jun-21` (Forecasted sales for June 2021)

## Acknowledgments
Special thanks to [Parimala-15](https://github.com/Parimala-15) for contributing to this project.

## License
This project is licensed under the MIT License.

