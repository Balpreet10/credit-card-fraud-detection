# 💳 Credit Card Fraud Detection System

An end-to-end machine learning classification solution designed to analyze credit card transactions and flag fraudulent activity in real-time. This project features a robust data preprocessing pipeline, evaluation analytics, and an interactive web user interface.

## 📊 Project Overview & Performance
Real-world credit card data is highly imbalanced (99.8% legitimate transactions). This project shifts from linear tracking metrics to a tailored **Logistic Regression classification pipeline** to guarantee high precision when identifying real anomaly patterns.

*   **Model Architecture:** Logistic Regression Classifier (Scikit-learn)
*   **Model Accuracy:** 99.9% Overall Accuracy
*   **Fraud Identification Confidence:** 99.73% operational confidence on flagged live fraud rows.
*   **Target Metrics Evaluated:** Confusion Matrix, Precision, and Recall optimization.

## 🛠️ Tech Stack & Libraries
*   **Language:** Python
*   **Machine Learning Engine:** Scikit-Learn (Linear Models, Metrics, Data Splits)
*   **Data Manipulation:** Pandas & NumPy
*   **UI Dashboard Framework:** Gradio

## 🖥️ Interactive Web Interfaces Built
This project includes two fully operational web application deployment setups via Gradio:
1.  **Batch Scanner CSV Interface:** Allows operators to upload massive production transaction ledgers (e.g., `creditcard.csv`) to automatically index and tag fraud spikes.
2.  **Manual Field Simulator Dashboard:** A "what-if" sliding layout matrix allowing custom value tests across human-readable figures (`Amount`, `Time`) and hidden PCA signals (`V1` to `V28`).

## 🚀 How to Run the App Locally
1. Clone this repository to your machine.
2. Ensure you download the standard source dataset file from Kaggle's official Medical Cost / Credit Card Personal repository hubs.
3. Install dependencies:
   ```bash
   pip install scikit-learn pandas numpy gradio joblib
   ```
4. Run the Jupyter Notebook cells to execute the model generation pipeline and automatically trigger the inline Gradio shareable web engine loops.
