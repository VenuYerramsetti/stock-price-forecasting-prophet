# 📈 Stock Price Forecasting with Prophet

This project forecasts Apple (AAPL) stock prices using **Prophet**, a powerful open-source time series forecasting library. Historical data is fetched from Yahoo Finance via `yfinance`, and forecasts are visualized using `matplotlib`.

---

## 🔧 Technologies Used

- Python  
- yfinance  
- Prophet  
- Matplotlib  
- Pandas  

---

## 📁 Project Structure

| File Name           | Description                                                      |
|--------------------|------------------------------------------------------------------|
| `stock_forecast.py` | Python script for downloading data, training model, forecasting |
| `forecast_plot.png` | Image file showing the forecasted stock price                   |
| `requirements.txt`  | List of Python dependencies                                     |
| `README.md`         | Project overview and instructions                               |

---

## 📸 Output

The forecast plot will be saved as `forecast_plot.png`.  
It will also be displayed interactively using `matplotlib`.

---

## 💡 About Prophet

Prophet is a forecasting tool built by Meta (Facebook) for time series data. It supports modeling:

- Seasonality (yearly, weekly, daily)
- Holiday effects
- Non-linear trends
- Missing data and outliers

---

## 🌐 How GitHub Fits In

This GitHub repository serves as a central hub for this project:

* **Hosts the source code:** All the project files are stored here.
* **Tracks project history:** You can see all the changes made to the code over time.
* **Shares the project with others:** Makes it easy for collaborators and others to access and contribute.

**Important Note:** GitHub does not execute your code directly. To run this project, you'll need to **clone the repository** and execute the code locally on your machine or within a cloud notebook environment.

---

## 🚀 Optional: Run in Google Colab or Binder

For a quick and easy way to run this notebook online without any local setup, you can use one of these free platforms:

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/VenuYerramsetti/stock-price-forecasting-prophet/blob/main/stock_forecast.ipynb)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/VenuYerramsetti/stock-price-forecasting-prophet/main?filepath=stock_forecast.ipynb)



Alternatively, you can upload the notebook directly to [Google Colab](https://colab.research.google.com/) and run all cells there.

---

## ▶️ How to Run the Project Locally

```bash
# 1. Clone the Repository
git clone https://github.com/VenuYerramsetti/stock-price-forecasting-prophet
cd stock-price-forecasting-prophet

# 2. Set Up the Environment
pip install -r requirements.txt

# If needed, install manually:
pip install yfinance prophet matplotlib pandas

# If Prophet fails to install:
pip install pystan==2.19.1.1
pip install prophet

# 3. Run the Code
# Run the script:
python stock_forecast.py

# Or run the Jupyter Notebook:
jupyter notebook
# Then open `stock_forecast.ipynb` and run all cells
