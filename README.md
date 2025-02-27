# Consumer Complaint Classification 

## 🔹 Project Overview  
This project classifies **consumer complaints** into different categories using **Natural Language Processing (NLP) and Machine Learning**.  
We trained a **Logistic Regression model** on the **Consumer Complaint Dataset** to predict the category of a complaint.

---

## 🔹 Dataset Used  
- **Source:** [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database)  
- **Columns Used:**  
  - `Consumer complaint narrative` → **(Complaint Text - Input)**  
  - `Product` → **(Category - Target Label)**  

The dataset was **cleaned, preprocessed, and vectorized** using **TF-IDF** before training the model.

---

## 🔹 Steps Followed in This Project  
**Step 1: Load the Dataset**  
**Step 2: Text Preprocessing** (Lowercasing, Stopword Removal, Lemmatization)  
**Step 3: Convert Text into Numerical Form** (TF-IDF Vectorization)  
**Step 4: Train a Logistic Regression Model**  
**Step 5: Evaluate Model Performance** (Accuracy ~96.67%)  
**Step 6: Make Predictions on New Complaints**  

---

## 🔹 Model Performance  
| Metric       | Score  |
|-------------|--------|
| **Accuracy** | 96.67% |
| **Precision** | 90% (avg) |
| **Recall** | 82% (avg) |
| **F1-score** | 85% (avg) |

The model performs **exceptionally well** for **Debt Collection (Class 1) and Mortgage (Class 3)**.  
⚠️ **Consumer Loan (Class 2)** had slightly lower recall (50%), but the overall model is highly accurate.

---

## 🔹 How to Run This Project  
### ** Install Dependencies**  
Run this in your terminal:
```bash
pip install pandas numpy nltk scikit-learn
