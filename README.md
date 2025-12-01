Stock Price Prediction (LSTM)

This project predicts stock closing prices using an LSTM model.  
All steps — data loading, preprocessing, model building, training, evaluation, and visualization — are implemented inside the notebook "stock_price_prediction.ipynb".

📂 Project Structure

.
├── Data/ # Dataset (tcs_data.csv)
├── Images/ # Saved graphs (Actual vs Predicted, etc.)
├── stock_price_prediction.ipynb # Main notebook
├── my_best_stock_lstm.keras # Saved Keras model
├── my_model.h5 # Saved H5 model
└── requirements.txt # Dependencies


 🧠 What the Notebook Does

Inside-->stock_price_prediction.ipynb:

- Loads stock data  
- Scales the "Close" price  
- Creates sequences (past 100 days → next day prediction)  
- Builds an LSTM-based neural network  
- Trains the model  
- Generates predictions  
- Plots Actual vs Predicted values  
- Saves the model ("keras" and ".h5")

This notebook contains the complete workflow.


 🚀 How to Run

1. Install the required packages:


pip install -r requirements.txt
Open the notebook:

jupyter notebook
Run all cells in stock_price_prediction.ipynb.

📊 Output
The notebook generates:

Prediction plots stored inside Images/

Saved LSTM models:

my_best_stock_lstm.keras

my_model.h5

📌 Notes
You can change the stock ticker inside the notebook.

You can modify the sequence length or LSTM layers to improve accuracy.

All training and evaluation steps happen inside the notebook.

📜 License
Free to use for learning and personal projects.


