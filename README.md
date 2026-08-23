# 📊 AI Impact on Students - Exploratory Data Analysis & Tableau Dashboard

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-orange)
![Tableau](https://img.shields.io/badge/BI-Tableau-e97627)
![Status](https://img.shields.io/badge/Project-Completed-success)

This repository contains a comprehensive Exploratory Data Analysis (EDA) of the **AI Impact on Students** dataset, extended into a 12-sheet interactive Tableau dashboard. The analysis explores how Generative AI tools affect university students' academic performance, study habits, burnout risk, and exam anxiety — first through Python/statistical analysis, then through a business-facing BI dashboard.

---

## 📂 Project Structure

```text
AI-Impact-on-Students-EDA/
│
├── data/
│   ├── ai_impact_students.csv          # Raw dataset
│   └── cleaned_ai_impact_students.csv  # Standardized and processed dataset
│
├── notebooks/
│   └── AI_Impact_on_Students_EDA.ipynb # Detailed step-by-step notebook
│
├── images/                             # Saved visualizations for the portfolio
│   ├── distribution_genai_usage.png
│   ├── ai_usage_vs_gpa.png
│   ├── burnout_dependency.png
│   ├── paid_subscription_boxplot.png
│   ├── skill_retention_bar.png
│   ├── anxiety_violinplot.png
│   └── correlation_heatmap.png
│
├── tableau/                             # Interactive Tableau dashboard
│   ├── AI_Student_Impact_Dashboard.twbx # Full packaged workbook (12 sheets, 3 dashboards)
│   └── images/                          # Dashboard screenshots
│       ├── dashboard_1_overview.png
│       ├── dashboard_2_usage_burnout.png
│       └── dashboard_3_policy_institutional.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## 🎯 Project Objectives

1. **Understand AI Usage Patterns:** Analyze weekly hours spent on Generative AI across different student profiles.
2. **Evaluate Academic Performance (GPA):** Examine correlations between AI usage hours and semester GPAs.
3. **Assess Burnout Risk & AI Dependency:** Observe if higher self-reported AI dependency triggers increased academic burnout risk.
4. **Compare Free vs. Paid Subscriptions:** Contrast academic performance between free users and premium AI tool subscribers.
5. **Explore Skill Retention:** Identify which AI use cases (e.g. coding, ideation, copywriting) retain skills best.
6. **Examine Exam Anxiety:** Investigate the relationship between traditional study hours and exam anxiety.
7. **Translate Findings into BI:** Turn the statistical analysis into a stakeholder-facing, filterable Tableau dashboard.

---

## 📈 Python EDA — Visualizations & Insights

### 1. Distribution of Weekly Generative AI Usage Hours
This chart displays how many hours per week students spend on Generative AI tools.
![Weekly GenAI Usage](images/distribution_genai_usage.png)

### 2. Weekly GenAI Usage vs. Post-Semester GPA
A scatterplot investigating whether extensive AI tool usage correlates positively or negatively with final GPAs.
![AI Usage vs GPA](images/ai_usage_vs_gpa.png)

### 3. Burnout Risk vs. AI Dependency Levels
A countplot showing how academic burnout risk corresponds to self-reported AI dependency scores.
![Burnout Risk](images/burnout_dependency.png)

### 4. Post-Semester GPA by Paid AI Subscription
A boxplot comparing the GPA distributions of students using free tools versus those paying for premium subscriptions.
![Paid Subscription Boxplot](images/paid_subscription_boxplot.png)

### 5. Average Skill Retention Score by AI Use Case
This horizontal bar chart ranks different AI use cases (summarization, debugging, copywriting, ideation) by their associated average skill retention score.
![Skill Retention](images/skill_retention_bar.png)

### 6. Traditional Study Hours by Exam Anxiety Level
A violinplot illustrating the relationship between non-AI study habits and reported anxiety levels during exams.
![Anxiety Violin Plot](images/anxiety_violinplot.png)

### 7. Correlation Heatmap of Numerical Variables
A heatmap demonstrating relationships between numerical features such as traditional study hours, AI usage, GPA, anxiety, and skill retention.
![Correlation Heatmap](images/correlation_heatmap.png)

---

## 📊 Interactive Tableau Dashboard

The EDA findings above were extended into a **12-sheet interactive Tableau dashboard** across 3 stakeholder-facing views, letting non-technical viewers filter and explore the data themselves rather than reading static charts.

📁 [View the full dashboard folder](tableau/) — includes the packaged workbook (`.twbx`) and screenshots below.

### Dashboard 1 — Overview, GPA by Major, GenAI Usage & Performance, Burnout
![Dashboard 1](tableau/images/dashboard_1_overview.png)

- KPI scorecards: 50,000 students, avg. 8 weekly GenAI hours, avg. 3.0 post-semester GPA, 24.97% high burnout rate
- GPA comparison (pre vs. post-semester) broken down by major category
- AI dependency vs. skill retention, colored by major
- Burnout rate by major category (STEM highest at 30%, Humanities lowest at 20.74%)

### Dashboard 2 — AI Dependency, Tool Diversity, Skill Retention, Use Case
![Dashboard 2](tableau/images/dashboard_2_usage_burnout.png)

- AI dependency vs. traditional study hours
- Tool diversity vs. weekly GenAI hours
- Skill retention score vs. AI dependency
- AI dependency broken down by primary use case (copywriting, debugging, ideation, etc.)

### Dashboard 3 — Usage by Year of Study, Institutional Policy, Academic Performance
![Dashboard 3](tableau/images/dashboard_3_policy_institutional.png)

- Weekly GenAI usage by major category and year of study (freshman → senior)
- AI dependency across institutional policy types (actively encouraged, allowed with citation, strict ban)
- Academic performance (GPA) vs. AI dependency
- Traditional study hours vs. AI usage

> **Note:** A live Tableau Public link will be added here once publishing is unblocked on my network. The full workbook file is available in `tableau/AI_Student_Impact_Dashboard.twbx` for anyone with Tableau Desktop who wants to open it directly.

---

## 🛠️ Installation & Usage

To run the analysis locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/piyushayy/AI-impact-on-student-analysis.git
   cd AI-impact-on-student-analysis
   ```

2. **Install Dependencies:**
   Make sure Python is installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Notebook:**
   Start Jupyter Notebook to explore the code:
   ```bash
   jupyter notebook notebooks/AI_Impact_on_Students_EDA.ipynb
   ```

4. **Open the Tableau Dashboard:**
   Open `tableau/AI_Student_Impact_Dashboard.twbx` in Tableau Desktop or Tableau Public to interact with it directly.

---

## 📄 License
This project is licensed under the terms of the MIT License.
