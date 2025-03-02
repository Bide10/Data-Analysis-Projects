# Google Stock Price Prediction Using RNN
### 📌 Project Overview
This project leverages a Recurrent Neural Network (RNN) to predict Google stock price trends for January 2017. The dataset is sourced from Kaggle, and the model is trained using historical stock prices. The project includes data cleaning, preprocessing, model training, and visualization of predicted vs. actual trends.

### 🔍 Problem Statement
Stock price movements are influenced by various factors, making them difficult to predict. Traditional statistical models often fail to capture sequential dependencies in financial data. To address this, a deep learning-based approach using RNN is implemented, which is well-suited for time-series forecasting.

### 🚀 Proposed Solution
 - Data Collection: Acquired Google stock price data from Kaggle.
 - Preprocessing: Handled missing values, normalized data, and created sequences for model input.
 - Model Architecture: Built an RNN model with LSTM layers to capture sequential patterns.
 - Training & Prediction: Trained the model on past stock prices and predicted trends for January 2017.
 - Evaluation & Visualization: Plotted the predicted vs. actual stock price trends to assess model performance.

### 💡 Business Impact
Helps traders and investors gain insights into stock trends using deep learning.
Demonstrates the effectiveness of RNNs in financial time-series forecasting.
Lays the groundwork for more advanced AI-driven trading strategies.

### 🔮 Further Scope
#### To improve forecasting accuracy, the following enhancements can be explored:

 - Using More Advanced Models: Implementing Bidirectional LSTMs, GRUs, or Transformer-based models to capture complex dependencies.
 - Incorporating More Features: Adding external factors such as market sentiment, economic indicators, trading volume, and news analytics.
 - Hyperparameter Tuning: Optimizing the number of layers, neurons, dropout rate, and learning rate for better generalization.
 - Longer Training Data: Expanding the dataset to include more historical stock prices for improved trend recognition.
 - Hybrid Models: Combining RNNs with traditional statistical methods (ARIMA, GARCH) or CNN-RNN architectures for enhanced performance.

### 📊 Results
The model successfully captures the general stock price trend, showing the potential of RNNs in financial forecasting.
