# 📊 Student Performance Analysis

## 📌 Overview
This project analyzes student performance based on demographic, social, and academic factors.  
Using data-driven insights, we explore **how gender, parental education, lunch type, and test preparation impact scores** in **Math, Reading, and Writing**.  
The goal is to identify factors influencing academic success and provide recommendations for improving educational outcomes.

---

## 📂 Dataset
We use the **Student Performance Dataset**, which contains the following attributes:

| Column                  | Description                                           |
|-----------------------|-----------------------------------------------------|
| `gender`             | Student gender (male / female)                       |
| `race/ethnicity`     | Student group (A, B, C, D, E)                        |
| `parental level of education` | Highest education level of parents          |
| `lunch`              | Type of lunch (standard / free-reduced)              |
| `test preparation course` | Completed or not completed                     |
| `math score`         | Math exam score (0–100)                              |
| `reading score`      | Reading exam score (0–100)                           |
| `writing score`      | Writing exam score (0–100)                           |

---

## 🧠 Project Workflow
1. **Data Loading & Cleaning**
   - Load CSV using `pandas`
   - Handle missing values (if any)
2. **Exploratory Data Analysis (EDA)**
   - Statistical summaries (mean, median, std)
   - Distribution plots for each score
   - Correlation heatmap between math, reading, writing scores
   - Grouped analysis (gender, parental education, lunch type)
3. **Feature Engineering**
   - Create overall average score per student
   - Encode categorical variables if needed
4. **Visualization**
   - Bar plots, boxplots, histograms, heatmaps
   - Insights on score distribution by demographic factors
5. **Insights & Recommendations**
   - Identify key factors affecting performance
   - Provide suggestions for improving scores

---

## 🖥️ How to Run
1. **Clone the repository**
```bash
git clone https://github.com/your-username/student-performance-analysis.git
cd student-performance-analysis
