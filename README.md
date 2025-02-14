# Fake News Classification

## Project Overview
This project aims to classify news articles as **real** or **fake** using Natural Language Processing (NLP) and machine learning techniques. The dataset consists of labeled news articles, and we use logistic regression and other classifiers to determine their authenticity.

## 📂 Dataset
- The dataset contains a collection of news articles labeled as **"real"** (1) or **"fake"** (0).
- Preprocessing steps include:
  - Handling missing values
  - Tokenization & vectorization (TF-IDF)
  - Removing stopwords & special characters

## 🚀 Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning Models**: Logistic Regression, SVM, Random Forest
- **Natural Language Processing (NLP)**: TF-IDF Vectorization
- **Git & GitHub**: Version control

## 📜 Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/fake-news-classification.git
   cd fake-news-classification
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the model:
   ```sh
   python train_model.py
   ```

##  Model Performance
- Evaluated using **K-Fold Cross-Validation**
- Performance Metrics: Accuracy, Precision, Recall, F1-Score
- Confusion matrix visualization included

## 📊 Results
- Logistic Regression achieves an accuracy of **~91%**

## 📌 Usage
1. Upload a news article text.
2. The model predicts whether it is **Real (1) or Fake (0)**.
3. Outputs confidence scores & highlights key features influencing the prediction.




