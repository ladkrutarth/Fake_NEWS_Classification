# 📰 Fake News Classification

## 📌 Overview
This project aims to classify news articles as **Real** or **Fake** using **Machine Learning** techniques. We use **TF-IDF vectorization** for text processing and apply **Logistic Regression** for classification.

## 📂 Dataset
The dataset consists of labeled news articles with text and corresponding labels:
- **Real (1)** - Verified news articles
- **Fake (0)** - Misinformation or misleading articles

## 🛠️ Installation & Setup
To run this project locally, follow these steps:

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/fake-news-classification.git
cd fake-news-classification
```

### 2️⃣ Install Dependencies
Ensure you have Python installed, then install required libraries:
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Model
```sh
python train_model.py
```

## ⚙️ Model Training
- Uses **TF-IDF Vectorization** to process text data.
- Implements **Logistic Regression** for binary classification.
- Evaluates model performance using **K-Fold Cross-Validation**.

## 📊 Results & Evaluation
The model is evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Precision, Recall, F1-score**

## 📈 Visualization
- **Confusion Matrix Heatmap**
- **K-Fold Cross-Validation Accuracy Graph**

