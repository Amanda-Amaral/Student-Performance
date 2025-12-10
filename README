# 🎓 Student Performance Analytics – Dimensional Modeling & Data Insights

Investigate which individual and contextual characteristics are associated with high student performance (score ≥ 85) using dimensional modeling, statistical analysis, and interactive visualizations to support data-driven educational decisions.

# 🧱 Project Architecture

Designed following a Lakehouse architecture with a multi-layer data pipeline:

Bronze – Raw data ingestion

Silver – Cleaning, preprocessing, and dimensional modeling (star schema)

Gold – Curated analytical datasets optimized for BI dashboards and exploratory analytics

# 🗃️ Dimensional Modeling (Star Schema)

Fact Table

fact_student_performance: stores student scores with keys linking to dimension tables.

Dimension Tables

dim_student (Gender, Financial Status, Parental Support, etc.)

dim_school (School Type, Previous Grades, Transportation Distance, etc.)

dim_study (Study Hours, Attendance, Tutoring, etc.)

dim_behavior (Motivation, Activities, Sleep, Social Influence, etc.)

📈 # Key Insights & Findings
🔹 High-Performance Students (Score ≥ 85)

School attendance (avg. 81%) and weekly study time (avg. 20 hours) show the strongest correlations with performance (0.58 and 0.45).

85% of top students do not report learning difficulties.

82% were influenced in a positive or neutral way by their environment.

Motivation alone was not a significant isolated predictor.

🔹# Categorical Variables

School type: 71% of high performers are from public schools.

Gender: Balanced (53% male, 47% female).

Financial condition: Performance is not concentrated in a single income group.

🔹# Numerical Variables Summary

| Variable           | Avg (High Performers) | Insight |
|-------------------|------------------------|--------|
| Study Hours       | 20h/week               | Strong correlation |
| Attendance Rate   | 81%                    | Highest impact factor |
| Tutoring Sessions | 1.4                    | Low influence |
| Sleep Hours       | 7h/day                 | Healthy but neutral |
| Previous Grades   | 75                     | Low predictable power |


📊# Visual Analytics

Implemented using SQL and Python (Pandas, Seaborn, Matplotlib):

Boxplots for numeric distribution by performance group

Stacked bar charts for categorical proportions

Correlation heatmaps for predictor evaluation

🧪 # Tools & Technologies

Databricks Notebooks

PySpark / Spark SQL

Pandas, Seaborn, Matplotlib

Delta Lake

Dimensional Modeling (Star Schema)

Bronze / Silver / Gold structured pipeline

🧠 # Conclusion

The analysis indicates that achieving high performance depends primarily on consistent school attendance, effective study time, and a supportive social context. Factors like motivation or income, while influential, were not decisive predictors on their own.
