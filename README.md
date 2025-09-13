# Tata_Motors_Stock_Details-1995-2025-
<div style="display: flex; align-items: center; background: linear-gradient(135deg, #002D62, #00537E); color: white; padding: 25px; border-radius: 8px; box-shadow: 0 4px 12px 0 rgba(0,0,0,0.3);">
    <div style="flex: 1;">
        <h1 style="margin: 0; font-family: 'Georgia', serif; font-size: 28px; font-weight: bold; letter-spacing: 1px;">
            TATA Motors Stock Analysis & Forecasting
        </h1>
        <h2 style="margin: 10px 0 0; font-family: 'Helvetica', sans-serif; font-weight: 300; font-size: 20px; opacity: 0.9;">
            A Time-Series & Deep Learning Project (1995-2025)
        </h2>
    </div>
</div>

<br>

> This repository contains an end-to-end data science project focused on the time-series analysis and prediction of TATA Motors' stock prices. It leverages historical data to perform in-depth exploratory data analysis (EDA) and builds a sophisticated **LSTM neural network** to forecast future stock values.

---

<div style="background-color: #003366; color: white; font-family: 'Helvetica', sans-serif; display: inline-block; padding: 10px 20px; border-radius: 7px; box-shadow: 0 3px 6px rgba(0,0,0,0.25);">
    <h2>📖 Overview & Features</h2>
</div>

* **Comprehensive EDA**: Visualizations of price trends, trading volume, and moving averages.
* **Data Preprocessing**: Scaling and sequencing of data for a time-series deep learning model.
* **Predictive Modeling**: Implementation of an **LSTM network** for forecasting.
* **Model Evaluation**: Assessment using the **Root Mean Squared Error (RMSE)** metric.
* **Clear Visualizations**: Informative plots generated using `Matplotlib` and `Seaborn`.

---

<div style="background-color: #003366; color: white; font-family: 'Helvetica', sans-serif; display: inline-block; padding: 10px 20px; border-radius: 7px; box-shadow: 0 3px 6px rgba(0,0,0,0.25);">
    <h2>🛠️ Technologies Used</h2>
</div>

| Category      | Technology                                                                                                                                      |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Core** | `Python 3.x`, `Jupyter Notebook`                                                                                                                |
| **Data Stack**| `Pandas`, `NumPy`, `Scikit-learn`                                                                                                               |
| **Deep Learning** | `TensorFlow`, `Keras`                                                                                                                           |
| **Visualization** | `Matplotlib`, `Seaborn`                                                                                                                         |

---

<div style="background-color: #003366; color: white; font-family: 'Helvetica', sans-serif; display: inline-block; padding: 10px 20px; border-radius: 7px; box-shadow: 0 3px 6px rgba(0,0,0,0.25);">
    <h2>🚀 How to Run</h2>
</div>

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/tata-motors-stock-analysis.git](https://github.com/your-username/tata-motors-stock-analysis.git)
    cd tata-motors-stock-analysis
    ```
2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Launch Jupyter Notebook and run the `.ipynb` file.**

---

<div style="background-color: #003366; color: white; font-family: 'Helvetica', sans-serif; display: inline-block; padding: 10px 20px; border-radius: 7px; box-shadow: 0 3px 6px rgba(0,0,0,0.25);">
    <h2>📊 Results</h2>
</div>

The LSTM model successfully captured the primary trends in the stock data, achieving a **low Root Mean Squared Error** on the test dataset. This demonstrates the effectiveness of using deep learning for financial time-series forecasting.
