# GrowthLink_Internship

# 📱 SMS Spam Detection

A machine learning project that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques and a Naive Bayes classifier.

---

## 🧠 Objective

To develop a robust SMS classification model that accurately detects spam messages based on their text content.

---

## 🗃 Dataset

- **Source**: UCI Machine Learning Repository via Kaggle (`uciml/sms-spam-collection-dataset`)
- **Format**: CSV file with two columns:
  - `label`: `ham` (not spam) or `spam`
  - `message`: The SMS content

---

## 🔍 Feature Flow

graph TD;
    A[Load Dataset] --> B[Preprocessing]
    B --> C[Train-Test Split]
    C --> D[Text Vectorization (TF-IDF)]
    D --> E[Train Naive Bayes Model]
    E --> F[Evaluate Accuracy & Metrics]
    F --> G[Prediction on New Message]
    E --> H[Feature Importance Visualization]
```

---

## ⚙️ Model & Tools

- Language: **Python**
- Libraries: `pandas`, `scikit-learn`, `seaborn`, `matplotlib`
- Algorithm: **Multinomial Naive Bayes**
- Vectorizer: **TF-IDF (Term Frequency - Inverse Document Frequency)**

---

## 📊 Visualizations

### ✅ Confusion Matrix

Shows true/false positives/negatives.

![Confusion Matrix](your_confusion_matrix_image.png)

### 📈 ROC Curve

Illustrates performance trade-offs at different thresholds.

![ROC Curve](your_roc_curve_image.png)

### 🔍 Feature Importance (Top Spam Indicators)

Displays which words are most influential in predicting spam.

![Top Spam Words](your_feature_importance_graph.png)

---

## 🚀 How to Run

1. Clone this repo or open `Spam SMS Detection.ipynb` in Google Colab.
2. Run all cells step-by-step.
3. A model will be trained and tested.
4. Optionally test with a custom SMS message.
5. Outputs include accuracy, classification report, and visualizations.

---

## 🧪 Example Test

**Message**:
```
"Congratulations! You've won a $1000 Walmart gift card. Click to claim now."
```

**Model Prediction**: ✅ `Spam`

---

## 📈 Performance

- **Model Accuracy**: ~95%
- Simple yet powerful model for real-world spam filtering.

---

## 📬 Contact

For questions, ideas, or contributions, feel free to open an issue or connect with me!
