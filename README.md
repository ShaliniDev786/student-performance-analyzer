# 📊 Student Performance Analyzer

This beginner-friendly AI/ML project predicts whether a student will **Pass or Fail** using features like **Study Hours** and **Attendance**, based on the UCI Student Performance dataset.

---

## 📁 Dataset Used

- `student-mat.csv` from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- We selected important features:
  - `studytime` → Study Hours
  - `absences` → used to calculate Attendance
  - `G3` → Final Exam Marks

---

## 🛠️ Tools & Libraries

- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Logistic Regression)

---

## 📈 Features Created

| Feature      | Description                          |
|--------------|--------------------------------------|
| StudyHours   | Weekly study time (1–4)              |
| Attendance   | Calculated as `100 - absences`       |
| Marks        | Final exam marks (0–20)              |
| Result       | 1 = Pass (Marks ≥ 10), 0 = Fail      |

---

## 🔍 ML Task

- **Problem Type**: Binary Classification
- **Model Used**: Logistic Regression
- **Target**: `Result` (Pass/Fail)

---

## 📊 Results

- Achieved **~80% accuracy** using:
  - Study Hours
  - Attendance
- Visualizations:
  - Pairplot
  - Heatmap
- Evaluation:
  - Accuracy Score
  - Confusion Matrix

---

## ▶️ How to Run

1. Open `student-performance-analyzer.ipynb` in **Google Colab**
2. Upload the dataset file: `student-mat.csv`
3. Run all cells to clean data, visualize, train the model & test predictions

---

## 🙋‍♀️ Created by

**Shalini Singh**  
A passionate learner starting her journey in AI/ML and Data Science 🚀  
