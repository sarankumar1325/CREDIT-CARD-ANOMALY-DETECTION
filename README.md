# Credit Card Fraud Anomaly Detection

This project demonstrates multiple unsupervised anomaly detection methods to identify fraudulent transactions in credit card data. By exploring different approaches, we aim to improve the detection of outliers that indicate potential fraud. Methods implemented include Z-Score, Mahalanobis Distance, Local Outlier Factor, Isolation Forest, and One-Class SVM.

## Project Structure

- **data/**: Contains the credit card dataset (e.g., `creditcard.csv`).
- **notebooks/**: Jupyter notebooks for exploratory data analysis and anomaly detection.
- **scripts/**: Python scripts for data loading, model evaluation, and visualization.

## Dataset

The dataset used is a [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle. It consists of anonymized features and a target column indicating fraudulent transactions.

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/Credit-Card-Fraud-Anomaly-Detection.git
cd Credit-Card-Fraud-Anomaly-Detection
pip install -r requirements.txt
