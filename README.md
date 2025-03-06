# Credit Card Default Prediction

## Overview
This project predicts the probability of a credit card holder defaulting based on their behavioral scores. The system leverages **machine learning** and **deep learning** techniques to analyze historical data and classify users as potential defaulters or non-defaulters.

## Features
- **Data Preprocessing:** Handling missing values, feature selection, and normalization.
- **Credit Default Prediction:** Uses both **Logistic Regression** and a **Neural Network (TensorFlow)** for classification.
- **Feature Selection:** Applied **VarianceThreshold, SelectKBest, and RFECV** for optimal feature extraction.
- **Performance Evaluation:** Assesses models using **Accuracy, Classification Report, Confusion Matrix, and ROC-AUC Score**.
- **Visualization:** Uses **Matplotlib** and **Seaborn** for data insights and performance analysis.

## Technologies Used
- **Programming Language:** Python
- **Libraries & Frameworks:**
  - **Data Processing:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn
  - **Machine Learning:** Scikit-learn (Logistic Regression, Feature Selection)
  - **Deep Learning:** TensorFlow, Keras (Neural Network for classification)
  - **Evaluation Metrics:** Accuracy, ROC-AUC, Confusion Matrix

## Installation & Usage
### Prerequisites
Ensure you have Python installed along with the required libraries:
```sh
pip install numpy pandas scikit-learn tensorflow keras matplotlib seaborn
```

### Running the Project
1. Clone the repository:
   ```sh
   git clone <repo-link>
   cd credit-card-default
   ```
2. Run the prediction script:
   ```sh
   python main.py
   ```
3. View the evaluation metrics and predictions.

## Future Enhancements
- Improve model accuracy with advanced deep learning architectures.
- Implement Explainable AI (XAI) techniques for better model interpretability.
- Deploy the model as a web-based application.

## License
This project is licensed under the MIT License.
