# Time Series Forecasting — Household Electricity Consumption

Analysis and forecasting of individual household electricity consumption patterns using 4 years of minute-level data from a French household.

## Project Overview
Using real electricity consumption data to identify daily, weekly, and seasonal patterns, then building a Prophet forecasting model to predict future consumption.

## Dataset
UCI Individual Household Electric Power Consumption Dataset — 2,075,259 minute-level measurements from December 2006 to November 2010.

Download the dataset here:
https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

Place the downloaded `household_power_consumption.txt` file in the project root directory.

## Key Findings
- Clear daily cycle: morning peak (7am), midday dip, evening peak (8-9pm)
- Weekend consumption significantly higher than weekdays during daytime hours
- Strong seasonal pattern: winter peaks, summer dips
- December 2007 anomaly: unusually high consumption
- Unmetered devices account for 51.2% of total consumption

## Project Structure
- `01_time_series_analysis.ipynb` — Data loading, cleaning, and exploratory analysis

## Tech Stack
- Python 3.11
- Pandas
- Prophet
- Plotly
- FastAPI (coming)
- React (coming)

## Setup
1. Clone this repository
2. Create a virtual environment: `python -m venv venv`
3. Activate it: `source venv/bin/activate`
4. Install dependencies: `pip install pandas matplotlib jupyter prophet plotly scipy`
5. Download the dataset (see above)
6. Open `01_time_series_analysis.ipynb`