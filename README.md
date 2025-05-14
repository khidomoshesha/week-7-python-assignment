# week-7-python-assignment
# 📊 Student Habits and Performance Analysis

This project explores the relationship between student lifestyle habits (e.g., study hours, diet, sleep) and academic performance using a dataset provided in CSV format.

---

## 📁 Dataset

**Filename:** `student_habits_performance.csv`  
The dataset includes the following columns:
- `gender`
- `study_hours_per_day`
- `sleep_hours`
- `diet_quality`
- `exercise_frequency`
- `part_time_job`
- `exam_score`

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- pandas
- matplotlib
- seaborn

---

## 🎯 Objectives

### Task 1: Load and Explore the Dataset
- Load CSV using `pandas`
- Display the first few rows
- Check for missing values and data types
- Drop missing values to clean the dataset

### Task 2: Basic Data Analysis
- Descriptive statistics for numerical columns
- Group and compare:
  - Average exam score by `gender`
  - Average study hours by `part_time_job`
  - Average exam score by `diet_quality`

### Task 3: Data Visualization
Visualizations are created using `matplotlib` and `seaborn`:
1. **Line Chart:** Exam Score trend over student index
2. **Bar Chart:** Average Exam Score by Diet Quality
3. **Histogram:** Distribution of Daily Study Hours
4. **Scatter Plot:** Study Hours vs. Exam Score

All charts are labeled and styled for clarity using Seaborn themes.

---

## 🚀 How to Run

1. Clone or download the repository.
2. Ensure Python 3 and the required libraries are installed:
   ```bash
   pip install pandas matplotlib seaborn
