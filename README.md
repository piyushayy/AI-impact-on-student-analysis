# 📊 AI Impact on Students — Data Analysis & Tableau Dashboard

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

An end-to-end data analytics project exploring the impact of Generative AI on university students, including AI usage patterns, academic performance, study habits, AI dependency, burnout risk, exam anxiety, skill retention, and institutional AI policies.

The project combines **Python-based Exploratory Data Analysis (EDA)** with **interactive Tableau dashboards** to transform student-level data into meaningful visual insights.

---

## 🎯 Project Overview

Generative AI has rapidly become part of students' academic workflows. This project investigates how students use AI tools and explores relationships between AI usage, traditional study habits, academic performance, dependency, and other student-related factors.

The analysis focuses on identifying patterns rather than assuming that AI usage is inherently positive or negative.

### Key areas explored

- Generative AI usage patterns
- Weekly AI usage hours
- Academic performance and GPA
- AI dependency
- Traditional study habits
- Academic burnout risk
- Exam anxiety
- Skill retention
- Free vs. paid AI subscriptions
- AI use cases
- Year of study
- Institutional AI policies
- Relationship between AI usage and academic behavior

---

# 📂 Project Structure

```text
🎯 Project Objectives
Understand AI Usage Patterns: Analyze weekly hours spent on Generative AI across different student profiles.
Evaluate Academic Performance: Examine relationships between AI usage and post-semester GPA.
Assess Burnout Risk & AI Dependency: Analyze patterns between AI dependency and academic burnout risk.
Compare Free vs. Paid Subscriptions: Compare academic performance between free and premium AI tool users.
Explore Skill Retention: Identify differences in skill retention across AI use cases.
Examine Exam Anxiety: Investigate the relationship between traditional study hours and exam anxiety.
Analyze Institutional Policies: Explore relationships between AI policies and student AI dependency.
Analyze Usage by Year of Study: Compare GenAI usage patterns across different years of study.
🐍 Exploratory Data Analysis with Python

The Python analysis provides the exploratory foundation of the project.

📈 Visualizations & Insights
1. Distribution of Weekly Generative AI Usage Hours

This chart displays how many hours per week students spend on Generative AI tools.

2. Weekly GenAI Usage vs. Post-Semester GPA

A scatterplot investigating the relationship between weekly AI usage and post-semester GPA.

3. Burnout Risk vs. AI Dependency Levels

A countplot showing how academic burnout risk corresponds to self-reported AI dependency levels.

4. Post-Semester GPA by Paid AI Subscription

A boxplot comparing GPA distributions between students using free AI tools and those using paid subscriptions.

5. Average Skill Retention Score by AI Use Case

This horizontal bar chart ranks different AI use cases according to their associated average skill retention score.

6. Traditional Study Hours by Exam Anxiety Level

A violinplot illustrating the relationship between traditional study hours and reported exam anxiety.

7. Correlation Heatmap of Numerical Variables

A heatmap demonstrating relationships between numerical features such as traditional study hours, AI usage, GPA, anxiety, and skill retention.

📊 Tableau Dashboards

The exploratory analysis was further developed into three Tableau dashboards containing 12 analytical worksheets.

The complete Tableau workbook is available in:

tableau/AI_Student_Impact_Dashboard.twbx
Dashboard 1 — AI Impact Overview

The first dashboard provides an overview of major AI usage patterns and their relationship with student-related factors.

Dashboard 2 — AI Usage & Student Behavior

The second dashboard focuses on AI usage patterns, student behavior, and comparisons across different categories.

Dashboard 3 — AI Dependency & Academic Impact

The third dashboard explores AI dependency, academic performance, study behavior, and institutional AI policies.

📋 Tableau Worksheets

The Tableau workbook contains 12 analytical worksheets covering different aspects of the dataset.

Worksheet	Analysis
Sheet 1	AI Usage Analysis
Sheet 2	Student & AI Usage Overview
Sheet 3	Academic Performance Analysis
Sheet 4	AI Dependency Analysis
Sheet 5	Study Habits Analysis
Sheet 6	Burnout & Anxiety Analysis
Sheet 7	AI Use Case Analysis
Sheet 8	AI Usage Distribution
Sheet 9	GenAI Usage by Year of Study
Sheet 10	Institutional Policy & AI Dependency
Sheet 11	Academic Performance & AI Dependency
Sheet 12	Traditional Study vs AI Usage
🔎 Key Analysis Areas
🤖 GenAI Usage

Analysis of how frequently and for how many hours students use Generative AI tools.

🎓 Academic Performance

Exploration of relationships between AI usage, AI dependency, and post-semester GPA.

🧠 AI Dependency

Analysis of self-reported AI dependency across different student categories.

📚 Study Habits

Comparison between traditional study hours and weekly Generative AI usage.

🔥 Burnout Risk

Exploration of academic burnout risk in relation to AI dependency and student behavior.

😰 Exam Anxiety

Analysis of exam anxiety and its relationship with traditional study habits.

💡 Skill Retention

Comparison of skill retention across different AI use cases.

🏫 Institutional Policies

Analysis of institutional AI policies and their relationship with perceived AI dependency.

🛠️ Tools & Technologies
Category	Technologies
Programming	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Notebook	Jupyter Notebook
Dashboard	Tableau
Data Format	CSV
Version Control	Git & GitHub
🔄 Project Workflow
Raw Dataset
     ↓
Data Cleaning & Preparation
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Pattern & Relationship Analysis
     ↓
Tableau Worksheets
     ↓
Interactive Dashboards
     ↓
Insights & Interpretation
🛠️ Installation & Usage
1. Clone the Repository
git clone https://github.com/piyushayy/AI-impact-on-student-analysis.git
cd AI-impact-on-student-analysis
2. Install Dependencies

Make sure Python is installed, then run:

pip install -r requirements.txt
3. Open the Jupyter Notebook
jupyter notebook notebooks/AI_Impact_on_Students_EDA.ipynb
4. Open the Tableau Dashboard

Open the following workbook using Tableau Desktop:

tableau/AI_Student_Impact_Dashboard.twbx
📁 Dataset

The dataset contains student-level information related to:

Academic performance
Generative AI usage
AI dependency
Traditional study habits
Burnout risk
Exam anxiety
Skill retention
AI subscriptions
AI use cases
Institutional policies
Year of study
💼 Skills Demonstrated
Data Cleaning
Exploratory Data Analysis
Data Visualization
Python
Pandas
NumPy
Matplotlib
Seaborn
Tableau
Dashboard Development
Statistical Analysis
Data Interpretation
Analytical Storytelling
Git & GitHub
🚀 Future Improvements
Publish the Tableau dashboards on Tableau Public
Add additional interactive filters and parameters
Perform deeper statistical testing
Develop predictive models for academic outcomes
Explore additional demographic segments
Add automated data refresh workflows
Expand the analysis using machine learning
👨‍💻 Author

Piyush Kaushik

Data Analytics | Python | SQL | Tableau | Power BI

📜 License

This project is licensed under the terms of the MIT License.AI-impact-on-student-analysis/
│
├── data/
│   ├── ai_impact_students.csv
│   └── cleaned_ai_impact_students.csv
│
├── notebooks/
│   └── AI_Impact_on_Students_EDA.ipynb
│
├── images/
│   ├── dashboard-1.png
│   ├── dashboard-2.png
│   ├── dashboard-3.png
│   ├── distribution_genai_usage.png
│   ├── ai_usage_vs_gpa.png
│   ├── burnout_dependency.png
│   ├── paid_subscription_boxplot.png
│   ├── skill_retention_bar.png
│   ├── anxiety_violinplot.png
│   └── correlation_heatmap.png
│
├── tableau/
│   └── AI_Student_Impact_Dashboard.twbx
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
