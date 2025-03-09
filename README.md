# Stock Price Prediction Model

This project aims to predict the stock's closing price for the next 5 trading days using machine learning models trained on historical stock price data.

## Instructions to Reproduce Results

### 1. Clone the Repository
Clone the repository to your local machine:


git clone https://github.com/ransilu12345/Intellihack_Code-Nexus_4.git
cd stock-price-prediction

### 2. Install Dependencies
To install the necessary dependencies for this project, use the requirements.txt file. Run the following command:


pip install -r requirements.txt

### 3. Run the Jupyter Notebook
The main analysis and model training are done in the Intellihack_Code-Nexus_4.ipynb notebook. To run the notebook:

(1) Open the terminal (command line) in the project directory.
(2) Run the following command to start Jupyter:

jupyter notebook Intellihack_Code-Nexus_4.ipynb

This will open the notebook in your default web browser. Follow the instructions in the notebook to execute the code and generate predictions.

### 4. Review the Results
After running the notebook, the final predictions for the next 5 trading days will be generated. These predictions will be saved as a CSV file in the predictions/ folder.

To review the results:

(1) Navigate to the predictions/ folder.
(2) Open the Intellihack_Code-Nexus_4.csv file to see the predicted stock prices.

## Project Structure

data/: Folder containing raw and cleaned datasets.
       question4-stock-data.csv: Historical stock price data used for training the model.

notebooks/: Jupyter notebooks for EDA, model development, and evaluation.
       Intellihack_Code-Nexus_4.ipynb: Main notebook containing code for data analysis, feature engineering, model    training, and evaluation.

reports/: Folder containing project documentation and report.
       Documentation.pdf: Detailed explanation of the methodology, model selection, and findings.
       Report.pdf: Summary of the project, key findings, and results.

predictions/: Folder containing the final predictions in CSV format.

requirements.txt: Python dependencies required for the project.

README.md: This file (which you're reading right now).

## Limitations and Future Work

Data Limitations: The data used covers a limited time period. Using more extensive datasets could lead to better predictions and capture long-term trends.

Model Limitations: The model doesn't account for external factors such as news or market sentiment, which could influence stock prices.

Improvement Strategies: Future improvements could include:
            Experimenting with Long Short-Term Memory (LSTM) networks for better time-series forecasting.
            Adding sentiment analysis on financial news and social media as additional features.
            Using macroeconomic indicators (e.g., interest rates, GDP data) to enhance model predictions.