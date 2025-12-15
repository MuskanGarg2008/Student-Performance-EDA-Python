# Student Performance EDA using Python

An end-to-end **Exploratory Data Analysis (EDA) project** using Python to analyze student academic performance and identify key factors influencing exam scores.  
This project demonstrates my ability to work with real-world data, clean and transform datasets, perform structured EDA, and extract meaningful insights using Python.

---

## 📊 Dataset Overview

- Dataset: `Expanded_data_with_more_features.csv`
- Source: Kaggle – Students Exam Score Dataset
- Link: https://www.kaggle.com/datasets/desalegngeb/students-exam-score

---

## 🔍 Project Workflow

### 1️⃣ Data Loading & Understanding
- Imported dataset using Pandas
- Performed initial exploration using:
  - `head()`
  - `info()`
  - `describe()`
  - Null value checks

### 2️⃣ Data Cleaning & Transformation
- Removed irrelevant columns 
- Fixed inconsistent categorical values
- Standardized string values for accurate grouping and analysis

### 3️⃣ Exploratory Data Analysis (EDA)

#### Gender Distribution
- Analyzed the distribution of male and female students using count plots

#### Parent Education vs Student Scores
- Used `groupby()` and aggregation to calculate average scores
- Visualized results using heatmaps
- Observed strong correlation between higher parent education and student scores

#### Parent Marital Status Impact on Student's Score
- Compared average scores across different marital statuses
- Found minimal impact on academic performance

#### Outlier Detection
- Used boxplots to identify outliers in Math, Reading, and Writing scores
- Math scores showed the highest variability and multiple zero values

#### Ethnic Group Distribution
- Analyzed demographic distribution using pie charts and count plots
- Identified the most represented ethnic groups

---

## 📊 Sample Visualizations

### Parent Education vs Student Scores
![Parent Education's impact on student's scores Heatmap](images/Relationship between Parent's education and Student's score.jpg)

### Score Distribution & Outliers
![Score Outliers](images/Outlier Detection.jpg)

---

## 📈 Key Insights

- Students with parents holding Bachelor’s or Master’s degrees score significantly higher on average
- Parent marital status has negligible impact on exam scores
- Math is the most challenging subject with the widest score spread
- Proper data cleaning is crucial before performing any analysis
- Visualization plays a key role in understanding patterns and trends

---

## 🎯 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning & Transformation
- Data Visualization
- Python Programming
- Analytical Thinking
- Insight Generation
- Git & GitHub Documentation

---

## 🛠 Tools & Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation & analysis
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization

---

## ▶️ How to Run This Project

**Step 1: Clone the Repository**
git clone https://github.com/your-username/Student-Performance-EDA-Python.git

**Step 2: Install Dependencies**
Make sure Python is installed, then run:
- pip install -r requirements.txt

**Step 3: Open Jupyter Notebook**
Launch Jupyter Notebook using:
- jupyter notebook

**Step 4: Run the Notebook**
Open StudentPerformanceAnalysis.ipynb
- Run all cells from top to bottom to view the complete analysis and visualizations

---

## 📌 Conclusion

This project highlights my **ability to analyze real-world datasets using Python**, apply structured EDA techniques, and communicate insights effectively through visualizations and documentation. It reflects my readiness for Data Analyst roles.

---

## 📄 License

This project is open-source and available under the MIT License.


