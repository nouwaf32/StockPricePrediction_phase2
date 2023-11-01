# STOCK PRICE PREDICTION using CNN-LSTM
### This project focuses on predicting stock prices using a combination of Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) layers. It includes the implementation of technical indicators and evaluates the model's performance.

## Dependencies
### Ensure you have the following dependencies installed:
### Python 3.6+
### Libraries:
### pandas
### numpy
### matplotlib
### scikit-learn
### tensorflow
## You can install the required libraries using the following command:
pip install pandas numpy matplotlib scikit-learn tensorflow

## Running the Code
### Clone the repository or download the code files.
### Navigate to the directory containing the code files.
### Open a Python environment (e.g., Jupyter Notebook, Python IDE).
### Run the provided code in your Python environment. The main script is stock_price_prediction.py.
python stock_price_prediction.py
### This will execute the entire code, including data preprocessing, model training, evaluation, and visualization.
### Once the code finishes running, you will see the evaluation metrics and a visualization of the predicted vs. actual stock prices.

## Customizing the Project
### Data Input:
### Replace the file path in data = pd.read_csv('/content/MSFT.csv') with the path to your own dataset.
### Model Architecture:
### Modify the CNN-LSTM model architecture by adjusting the layers in model_cnn_lstm.
### Hyperparameters:
### Adjust hyperparameters such as sequence_length, batch_size, and epochs according to your preference.

## Additional Notes
### Ensure that the provided dataset (in CSV format) contains at least the 'Date' and 'Close' columns.
### The code assumes that you have a GPU available for accelerated training. If not, you can adjust the batch size and consider reducing the complexity of the model.
### Feel free to explore different technical indicators or add more features to enhance the model's predictive power.
