NOMA (Non-Orthogonal Multiple Duplex)

📖 Description

This project predicts uplink and downlink SINR using machine-learning models and visualizes various network interference metrics.
It is designed for exploring NOMA communication behavior and analyzing how interference changes under different network conditions.

🎯 Project Goal

The main goal of this project is to:

Predict uplink and downlink interference levels

Visualize interference behavior

Help identify optimal user power allocation

Provide an ML-based approach to understanding crosslink, uplink, and downlink interference relationships

This project assists in analyzing network efficiency and improving power distribution strategies.

🛠 Technologies Used

Google Colab

Python 3

NumPy

Pandas

Scikit-Learn

Matplotlib

Seaborn

Custom Network Calculations (SINR, BER, noise modeling)

✨ Key Features

✔ Data preprocessing & cleaning
✔ SINR computation (linear & dB)
✔ BER calculation for uplink/downlink
✔ Noise modeling
✔ Machine Learning model training
✔ ML evaluation metrics (MSE, R², learning curves, etc.)
✔ Graphs & visualizations
✔ Export of predictions as CSV/Excel

📦 Dataset Information

The dataset includes numerical features such as:

avg_uplink

avg_downlink

avg_crosslink

avg_userpower

avg_transmitpower

user IDs, base station IDs, etc.

📌 The dataset must be downloaded separately (not included inside the repository).

🚀 How to Run

Open the project notebook in Google Colab

Ensure GPU runtime is enabled

Upload your dataset

Run notebook cells step-by-step in order

The notebook will:

preprocess data

calculate SINR/BER

train models

generate predictions

output visual graphs and Excel files

📊 Outputs

This project generates:

📈 Learning curves

📉 Interference visualizations

📘 Excel and CSV export files

🔍 ML evaluation metrics such as:

MSE

RMSE

R² Score

📡 Predicted uplink & downlink SINR values

🔮 Future Work

The next phase of the project will focus on:

Optimizing power allocation to reduce interference

Testing reinforcement learning for dynamic network adaptation

Real-time interference prediction
