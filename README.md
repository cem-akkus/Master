# Python Code for Master's Thesis - Predictive Modeling of Asset Returns

- `Data.ipynb`: This file prepares Dataset for Asset Return Prediction. It loads the dataset, visualises it, extracts subsets for simpler experimentation, identifies and normalizes relevant features, filters the datasets and saves them.
- `Fine-Tuning_SBERT_colab.ipynb`: This file trains a fine-tuned SBERT model for asset return prediction using Google Colab. It first loads the data and splits it into training, validation, and test sets. Then, it fine-tunes the SBERT model using a custom architecture and training/evaluation routine. Finally, it saves the trained model and fine-tuned embeddings to disk.
- `AssetReturnPrediction.ipynb`: This file makes 1-Day and 5-Day ahead predictions for EURO STOXX 50 using ARIMA and LSTM models. The different models and their parameters are created before final results are obtained.




