# 🎓 Student Performance(Score) Prediction System

A Machine Learning-based student performance prediction system that predicts a student's **Total Score** and **Grade** using academic and behavioral factors such as attendance, study hours, assignment performance, and project scores.

The system also provides **data visualization** to analyze how different factors affect student performance.

---

## ✨ Features

✅ Predict Student Total Score  
✅ Predict Student Grade (A, B, C, D, F)  
✅ Linear Regression for Score Prediction  
✅ Logistic Regression for Grade Prediction  
✅ Data Standardization using StandardScaler  
✅ Model Efficiency Check (R² Score)  
✅ Visual Relationship Analysis with Graphs  
✅ Interactive User Input System

---

## 🧠 Machine Learning Models Used

### 1. Linear Regression
Used to predict:

```txt
Total Score
```

based on student academic performance.

### 2. Logistic Regression
Used to predict:

```txt
Grade
```

Possible outputs:

```txt
A, B, C, D, F
```

---

## 📊 Features Used for Prediction

The model uses the following student attributes:

- Attendance %
- Midterm Score
- Assignment Average
- Project Score
- Study Hours Per Week

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**

---

## 📂 Project Structure

```txt
Student-Performance-Prediction/
│── students_performance_dataset.csv
│── main.py
│── README.md
│── requirements.txt
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/student-performance-predictor.git
cd student-performance-predictor
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## ▶️ Run the Program

```bash
python main.py
```

---

## 🎮 User Inputs

The user enters:

```txt
Attendance %
Midterm Score
Assignment Marks
Project Score
Study Hours Per Week
```

Example:

```txt
Enter your Attendance: 90
Enter your Midterm Score: 85
Enter your Assignment Marks: 88
Enter your Project Score: 92
Enter your Study Hours Per Week: 15
```

---

## 📈 Output Example

```txt
YOUR PREDICTED SCORE IS: 87.53
YOUR PREDICTED GRADE IS: A
```

---

## 📉 Model Efficiency Check

The program can evaluate model quality using:

```txt
R² Score
```

Performance categories:

| R² Score | Model Quality |
|-----------|---------------|
| < 0 | Worse Model |
| 0 – 0.25 | Useless Model |
| 0.26 – 0.50 | Average Model |
| 0.51 – 0.80 | Good Model |
| 0.81 – 1.00 | Perfect Model |

---

## 📊 Data Visualization

The system can visualize relationships between:

### 1. Attendance VS Total Score

Shows how attendance affects student performance.

### 2. Study Hours VS Total Score

Shows the impact of study time on marks.

### 3. Assignment Marks VS Total Score

Shows how assignment performance influences total score.

Graphs include:

✅ Density Visualization (Hexbin Plot)  
✅ Trend Line (Linear Fit)  
✅ Relationship Analysis

---

## 🚀 Future Improvements

- GUI Interface
- Better Model Accuracy
- More Student Features
- Deep Learning Integration
- Live Prediction Dashboard
- Export Results as PDF

---

## 📚 Concepts Used

- Supervised Learning
- Linear Regression
- Logistic Regression
- Feature Scaling
- Label Encoding
- Data Visualization
- Model Evaluation

---

## 👨‍💻 Author

**Namit Singh**  
Machine Learning & Python Enthusiast
