# 🧠 Decision Tree Classifier on Classification Dataset

This project demonstrates how to build and evaluate a **Decision Tree Classifier** using Python and scikit-learn. The notebook includes steps from data preprocessing to model evaluation with visualization.

## 📂 Project Structure

- `code.ipynb` – Jupyter notebook containing the complete code for training, evaluating, and visualizing a decision tree classifier.

## 📌 Features

- Load and preprocess a classification dataset
- Train a `DecisionTreeClassifier`
- Evaluate using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC AUC
- Generate and visualize:
  - Confusion Matrix
  - Classification Report

## 🛠️ Requirements

Install the following Python packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Open `code.ipynb` in Jupyter Notebook or JupyterLab.
3. Run each cell step-by-step to train and evaluate the model.

## 📊 Example Output

- **Accuracy**: ~0.99  
- **Precision**: ~0.97  
- **Recall**: ~0.99  
- **F1 Score**: ~0.98  
- **ROC AUC**: ~0.99

## 📈 Confusion Matrix Example

The confusion matrix is visualized using Seaborn’s heatmap for better interpretation of true positives, false positives, etc.

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✅ Model Evaluation Results

### Classification Report:
```
               precision    recall  f1-score   support

           0       1.00      0.99      1.00      8960
           1       0.98      1.00      0.99      7040

    accuracy                           0.99     16000
   macro avg       0.99      0.99      0.99     16000
weighted avg       0.99      0.99      0.99     16000
```

### Metrics Summary:
- **Accuracy**: 0.9931
- **Precision**: 0.9777
- **Recall**: 0.9954
- **F1 Score**: 0.9865
- **ROC AUC**: 0.9938

---

## 📊 Confusion Matrix

The confusion matrix shows a very high number of correct predictions:
- **True Positives (TP)** and **True Negatives (TN)** are dominant
- Very few **False Positives (FP)** and **False Negatives (FN)**

This suggests the model is highly effective for this dataset.

