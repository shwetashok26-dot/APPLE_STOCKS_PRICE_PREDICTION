<h1 align="center"> Apple Stock Price Prediction with SARIMA Model</h1>
<p align="center" style="font-size:16px; font-weight:600;">
Time Series Forecasting using SARIMA
</p>



<p align="left" style="font-size:15px; font-weight:500;">
<b>Author:</b> Akritichhaya
</p>

<p align="left">
  <a href="https://applestockpriceprediction-hkm5pzapkx5ss7nte92har.streamlit.app/" target="_blank">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-Streamlit-red?style=for-the-badge">
  </a>
</p>

<div class="section">
  <h2>1️⃣ Problem Statement</h2>
  Stock prices change over time due to trends, seasonality, and market behavior.
  The goal of this project is to <span class="highlight">predict future Apple Inc. stock prices</span>
  using historical data through a time series forecasting model.
</div>

<div class="section">
  <h2>2️⃣ Dataset Used</h2>
  A historical Apple stock price dataset (<b>P587 DATASET.csv</b>) was used, containing:
  <ul>
    <li>Date</li>
    <li>Open price</li>
    <li>High price</li>
    <li>Low price</li>
    <li>Close price</li>
    <li>Volume</li>
  </ul>
  This dataset represents time-based financial data, making it suitable for time series analysis.
</div>

<div class="section">
  <h2>3️⃣ Exploratory Data Analysis (EDA)</h2>
  In the Jupyter Notebook (<b>Apple_stock_prediction.ipynb</b>), the following steps were performed:
  <ul>
    <li>Loaded the dataset using Pandas</li>
    <li>Checked data shape, columns, and data types</li>
    <li>Converted the Date column into datetime format</li>
    <li>Sorted data based on time</li>
    <li>Plotted closing prices to analyze trends, seasonality, and fluctuations</li>
  </ul>
  This analysis helped in understanding historical stock behavior.
</div>

<div class="section">
  <h2>4️⃣ Why SARIMA Model</h2>
  SARIMA was chosen because:
  <ul>
    <li>Stock prices show clear trends</li>
    <li>Seasonal patterns repeat over time</li>
    <li>SARIMA captures AR, I, MA, and Seasonal components</li>
  </ul>
  This makes it highly suitable for financial time series forecasting.
</div>

<div class="section">
  <h2>5️⃣ Data Preprocessing</h2>
  Before training the model:
  <ul>
    <li>Missing values were removed</li>
    <li>Close Price was selected as the target variable</li>
    <li>Scaling was applied to improve stability and consistency</li>
  </ul>
  Saved scalers:
  <ul>
    <li>scaler_X_sarimax.pkl</li>
    <li>scaler_y.pkl</li>
  </ul>
</div>

<div class="section">
  <h2>6️⃣ Model Training</h2>
  <ul>
    <li>Data split into training and testing sets</li>
    <li>SARIMA model trained on historical data</li>
    <li>Parameters tuned to capture trend and seasonality</li>
    <li>Model evaluated using forecast plots and error analysis</li>
  </ul>
  The trained model was saved as <b>best_model.pkl</b>.
</div>

<div class="section">
  <h2>7️⃣ Model Saving & Reusability</h2>
  <ul>
    <li>Saved trained SARIMA model</li>
    <li>Saved scalers used during training</li>
  </ul>
  This makes the project efficient, reusable, and deployment-ready.
</div>

<div class="section">
  <h2>8️⃣ Streamlit Application (app.py)</h2>
  A Streamlit web application was built to deploy the model:
  <ul>
    <li>Loads trained model and scalers</li>
    <li>Displays historical stock prices</li>
    <li>Shows future stock price predictions</li>
    <li>Provides interactive visualizations</li>
  </ul>
</div>

<div class="section">
  <h2>9️⃣ Deployment</h2>
  The application was deployed on <b>Streamlit Cloud</b> using:
  <ul>
    <li>requirements.txt</li>
    <li>runtime.txt</li>
    <li>postBuild</li>
  </ul>
  <span class="link">
    Live App: https://applestockpriceprediction-hkm5pzapkx5ss7nte92har.streamlit.app/
  </span>
</div>

<div class="section">
  <h2>🔟 Repository Structure</h2>
  <ul>
    <li>Apple_stock_prediction.ipynb – EDA & model training</li>
    <li>app.py – Streamlit frontend</li>
    <li>best_model.pkl – Trained SARIMA model</li>
    <li>scaler_X_sarimax.pkl, scaler_y.pkl – Saved scalers</li>
    <li>P587 DATASET.csv – Dataset</li>
    <li>requirements.txt – Dependencies</li>
    <li>runtime.txt – Python version</li>
    <li>postBuild – Deployment setup</li>
  </ul>
</div>

<div class="section">
  <h2>1️⃣1️⃣ What You Achieved</h2>
  <ul>
    <li>End-to-end time series forecasting project</li>
    <li>Statistical modeling using SARIMA</li>
    <li>Converted notebook to real-time web app</li>
    <li>Successful cloud deployment</li>
    <li>Demonstrated Python, EDA, forecasting, and Streamlit skills</li>
  </ul>
</div>

<div class="section">
  <h2>1️⃣2️⃣ Conclusion</h2>
  This project demonstrates how historical stock data can be effectively used to
  forecast future prices using SARIMA, combined with a deployed Streamlit
  application to deliver a real-world solution.
</div>
lder>
