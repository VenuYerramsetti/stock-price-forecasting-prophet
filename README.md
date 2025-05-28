# 📈 Stock Price Forecasting with Prophet

This project forecasts Apple (AAPL) stock prices using **Prophet**, a powerful open-source time series forecasting library. Historical data is fetched from Yahoo Finance via `yfinance`, and forecasts are visualized using `matplotlib`.

---

## 🔧 Technologies Used

- Python  
- [yfinance](https://pypi.org/project/yfinance/)  
- [Prophet](https://pypi.org/project/prophet/)  
- [Matplotlib](https://matplotlib.org/)  
- [Pandas](https://pandas.pydata.org/)

---

## 📁 Project Structure

| File Name             | Description                                                              |
|----------------------|--------------------------------------------------------------------------|
| `stock_forecast.py`  | Python script for downloading data, training model, and forecasting      |
| `forecast_plot.png`  | Image file showing the forecasted stock price                            |
| `requirements.txt`   | List of Python dependencies                                               |
| `README.md`          | Project overview and instructions                                        |

---

## ▶️ How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/VenuYerramsetti/stock-price-forecasting-prophet
cd stock-price-forecasting-prophet

### **2. Set Up the Environment**
Install the required Python packages:

```bash

pip install -r requirements.txt
Or install manually:

bash

pip install yfinance prophet matplotlib pandas
If Prophet fails to install directly, try:

bash

pip install pystan==2.19.1.1
pip install prophet

3. Run the Code
To run the script:

bash

python stock_forecast.py
To run the Jupyter Notebook:

bash

jupyter notebook
Then open stock_forecast.ipynb and run all cells.

📸 Output
The forecast plot will be saved as forecast_plot.png.

It will also be displayed using matplotlib.

💡 About Prophet
Prophet is a forecasting tool built by Meta (Facebook) for time series data. It handles seasonality, trends, holidays, and works well with messy data.

🌐 How GitHub Fits In
GitHub does not run code directly. It is used to:

Host your code

Track changes

Allow others to clone and run the project locally

👉 To Run This Project from GitHub
Clone the repository:

bash

git clone https://github.com/VenuYerramsetti/stock-price-forecasting-prophet
cd stock-price-forecasting-prophet
Install dependencies:

bash

pip install -r requirements.txt
Run the script or notebook as shown above.

🚀 Optional: Run in Google Colab or Binder
Run this project in the cloud without any setup:



Or upload the notebook to Google Colab and run it there.
