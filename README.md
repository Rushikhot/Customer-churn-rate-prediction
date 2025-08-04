# Customer-churn-rate-prediction

# Customer Churn Rate Prediction

This project utilizes deep learning methods (Keras with TensorFlow backend) to predict customer churn. All code runs in a Google Colab notebook for ease of use and zero local setup.

## Dataset

- **Churn_Modelling.csv**: Contains customer data including demographics, account information, and a label indicating whether the customer churned.

## Running on Google Colab

1. Open the notebook `Customer_churn_rate_prediction.ipynb` in Google Colab.
2. Upload `Churn_Modelling.csv` when prompted in the notebook, or mount your Google Drive to make the file accessible.
3. Execute the notebook cells in order for data preprocessing, model building, training, and evaluation.

## Requirements

All dependencies are installed within the notebook. Major libraries used:
- TensorFlow
- Keras
- pandas
- numpy
- matplotlib
- seaborn

_No local setup required; running the notebook on Google Colab will handle all installations._

## Project Structure

- `Churn_Modelling.csv`: Dataset
- `Customer_churn_rate_prediction.ipynb`: Colab notebook
- `README.md`: Project instructions

## Approach

- **Data Preprocessing:** Cleaning, feature engineering, and normalization.
- **Model Architecture:** Deep neural network using Keras Sequential API (typically 2-3 dense layers with activation functions like ReLU and sigmoid).
- **Training:** Compilation with suitable loss function (e.g., binary crossentropy) and optimizer (e.g., Adam), model fitting, and validation.
- **Evaluation:** Metrics such as accuracy, loss, confusion matrix, and ROC-AUC.

## Results

- The final notebook cell will output model performance and a brief analysis of which features most influence churn.

## Author

Rushikhot


Feel free to raise issues, fork, or submit pull requests to contribute.
