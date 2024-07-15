# BMS_TRICODE
This project provides a web-based dashboard for forecasting sales trends using ARIMA model. It allows users to input a product name and view historical sales data, forecasted sales, and key performance indicators (KPIs).

**Features**
Input product name to view sales data
Display historical sales chart
Forecast sales for the next 12 months using ARIMA
Display key performance indicators (KPIs)
Visualize sales distribution with a pie chart
**Requirements**
Python 3.x
Dash
Dash Bootstrap Components
Pandas
Statsmodels
Plotly
**Install packages:**
pip install dash dash-bootstrap-components pandas matplotlib statsmodels plotly
Upload your CSV file (e.g., shopping_trends.csv) with the required columns.

**Usage**
Run the script:
python app.py
Enter a product name to view the sales forecast and other visualizations.

**File Structure**
app.py: Main script to run the Dash app.
shopping_trends.csv: Example CSV file with sales data.
**CSV File Format**
The CSV file should contain the following columns:
Item Purchased
Purchase Amount (USD)
