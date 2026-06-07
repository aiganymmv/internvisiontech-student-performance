# Student Performance Analysis

A data science project focused on programmatic dataset generation, exploration, and visual analysis of student academic records. This project was completed as part of the **InternVision Tech** Data Science Internship (Task 1).

## 📌 Project Overview
The main goal of this project is to simulate and analyze a synthetic academic dataset containing 100 student records across various departments. It demonstrates the full data science pipeline: data generation, handling missing values, statistical analysis, and advanced data visualization.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab 

---

## 🔍 Analytical Steps & Pipeline

### 1. Data Generation
* Programmatically created a dataset with 100 unique rows.
* Features include: `Student ID`, `Student Name`, `Department` (Computer Science, Data Science, Psychology, Business Analytics), `Attendance Percentage`, `Marks Obtained`, and `Semester`.
* Modeled a correlated relationship where higher attendance statistically leads to higher marks.

### 2. Data Exploration
* Loaded data structure into a Pandas DataFrame.
* Checked for data types and memory usage via `df.info()`.
* Performed data integrity verification (`df.isnull().sum()`) ensuring zero missing values.
* Generated comprehensive summary statistics (mean, min, max, quartiles).

### 3. Data Analysis
* Calculated overall metrics (Average Marks, Highest and Lowest Marks).
* Conducted department-wise performance aggregation.
* Computed the Pearson correlation coefficient between student attendance and academic results.
* Filtered and extracted the Top 10 performing students.

### 4. Data Visualization
Built 4 production-ready analytical plots using Matplotlib and Seaborn:
* **Bar Chart:** Average marks comparison across different departments.
* **Pie Chart:** Percentage distribution of student enrollment per department.
* **Histogram:** Distribution and density (KDE) of marks obtained.
* **Line Chart:** Smoothed rolling average trend showing the direct link between Attendance and Marks.

---

## 💡 Key Insights
* The dataset maintains a balanced distribution of students across all 4 departments.
* Data Science and Computer Science departments showed strong average marks.
* **Core Finding:** The analysis mathematically and visually proved a strong positive correlation between attendance and marks. Students maintaining near-100% attendance systematically achieved the highest performance tier.
