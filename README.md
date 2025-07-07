# 🛍️ Product Review Sentiment Analyzer

This project is a beginner-friendly sentiment analysis model that classifies product reviews as **positive** or **negative** using machine learning (Logistic Regression).

## 📌 Objective
To analyze product reviews and automatically determine whether the review sentiment is positive or negative based on its rating and text content.

---

## 🧠 How It Works

### 🔹 Step 1: Import Libraries
Standard Python libraries are used:
- `pandas` for data handling
- `sklearn` for ML modeling and evaluation

### 🔹 Step 2: Load Data
A `.csv` file containing product reviews and ratings is read using `pandas`.

### 🔹 Step 3: Label Creation
A new label column is created:
- Reviews with rating > 3 are labeled **positive**
- Others are labeled **negative**

### 🔹 Step 4: Text Vectorization
TF-IDF Vectorizer (`TfidfVectorizer`) converts text into numerical vectors.

### 🔹 Step 5: Model Training
A Logistic Regression model is trained using the training dataset.

### 🔹 Step 6: Model Evaluation
The model is evaluated using accuracy, precision, recall, and F1-score.

---

## 🧪 Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Programming language |
| pandas | Data manipulation |
| scikit-learn (sklearn) | ML model, vectorizer, evaluation |
| Google Colab | Environment to run the notebook |

---

## 📁 Files

| File | Description |
|------|-------------|
| `ProductReviewSentimentAnalyzer.ipynb` | Jupyter notebook containing the full code |
| `product_reviews_sample.csv` | Dataset of product reviews and ratings (input file) |

---

## 📊 Sample Output

The output includes:
- Sentiment predictions (positive or negative)
- Model evaluation metrics (accuracy, etc.)

---

## 🚀 Future Improvements
- Use deep learning (LSTM) for improved text understanding
- Add web interface for real-time review analysis
- Use real product reviews scraped from websites

---

## 🧑‍💻 Author
**Baiju Kingston Singh**  
_Entry-level AI enthusiast building hands-on ML projects to gain real-world experience._

---

## 📬 Contact
Want to collaborate or have feedback?  
📧 [YourEmail@example.com] (Add if needed)  
📘 GitHub: [https://github.com/BaijuKingstonSingh-OB](https://github.com/BaijuKingstonSingh-OB)

---
