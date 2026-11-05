# Network Protocol Classification

## Project Overview

This machine learning project uses network packet information to predict the packet's protocol, such as TCP, UDP, or DNS.

## Dataset

The dataset is from Kaggle:

- **Dataset:** Internet Traffic Data Set
- **Kaggle ID:** `asfandyar250/network`
- **Link:** https://www.kaggle.com/datasets/asfandyar250/network

Download the dataset from Kaggle and upload its CSV file to Google Colab before running the notebook.

## Project Steps

1. Load and inspect the dataset.
2. Clean missing values.
3. Remove duplicate rows.
4. Create graphs to explore the data.
5. Prepare the packet features and protocol labels.
6. Split the data into training and testing sets.
7. Train four classification models:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
8. Compare model accuracy.
9. Review a confusion matrix and classification report.
10. Use the selected model to predict the protocol of a new packet.

## Tools and Libraries

- Python
- Google Colab
- pandas
- matplotlib
- seaborn
- scikit-learn

## How to Run

1. Download the dataset from the Kaggle link above.
2. Open the project notebook in Google Colab.
3. Upload the dataset CSV file when prompted.
4. Run the notebook cells from top to bottom.

## Files

- `Network_Protocol_Classification_10_Steps.ipynb` — project notebook
- `README.md` — project information

## Notes

The notebook expects the dataset to contain a protocol target column and packet feature columns. If the downloaded CSV uses different column names, update the column names in the notebook to match the file.
