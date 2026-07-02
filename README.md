# student-performance-analysis
# 📊 Student Performance Analysis

An Exploratory Data Analysis (EDA) project examining how demographic and 
background factors influence student exam performance, along with a basic 
predictive model to classify Pass/Fail outcomes.

## 👤 About
- **Author:** Ajay Koleti
- **College:** Sree Vahini Institute of Science and Technology
- **Course:** B.Tech CSE (Data Science), 3rd Year - Semester 3.1

## 📁 Dataset
The dataset contains 1000 student records with the following columns:
- `gender` - Male / Female
- `race/ethnicity` - Group A to Group E
- `parental level of education` - highest education level of parent
- `lunch` - standard or free/reduced
- `test preparation course` - none or completed
- `math score`, `reading score`, `writing score` - exam scores out of 100

## 🛠️ Tech Stack
- Python
- Pandas, NumPy - data handling
- Matplotlib, Seaborn - data visualization
- Scikit-learn - machine learning (Logistic Regression)
- Google Colab - development environment

## 🔍 Workflow
1. Data loading and cleaning (checked for missing values/duplicates)
2. Feature engineering (created `average_score` column)
3. Exploratory Data Analysis with visualizations
4. Built a Logistic Regression model to predict Pass/Fail

## 📈 Key Insights
- Students who completed the test preparation course scored **~7 points higher** on average
- **Parental education level** correlates positively with student scores
- **Lunch type** (proxy for socio-economic background) shows a performance gap
- Gender has minimal impact on overall scores
- Math, Reading, and Writing scores are positively correlated with each other

## 🤖 Model Performance
Logistic Regression model to predict Pass/Fail based on test preparation course completion:
- **Accuracy: 99.5%**

## 📂 Files in this Repository
| File | Description |
|------|-------------|
| `student_performance.ipynb` | Full Colab notebook with code |
| `StudentsPerformance.csv` | Dataset used for analysis |
| `Student_Performance_Report.pdf` | Detailed project report |
| `chart1_gender.png` | Gender vs Average Score |
| `chart2_dist.png` | Score Distribution |
| `chart3_parent.png` | Parental Education vs Score |
| `chart4_prep.png` | Test Preparation vs Score |
| `chart5_corr.png` | Correlation Heatmap |

## 🚀 Future Scope
- Add more features (attendance, study hours) for a stronger model
- Try Decision Trees / Random Forest for comparison
- Build an interactive dashboard for real-time tracking
