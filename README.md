# Exploring-Factors-Affecting-Student-Performance-A-Data-Driven-Analysis
This project analyzes a dataset of students from two Portuguese schools to understand how gender, absences, and study time affect final grades. Using Python, Pandas, and Seaborn, I explored trends, created visualizations, and identified insights about student performance.
Dataset: UCI Student Performance Dataset (Math course)
#Columns include:

Student demographics (gender, family background)

Study habits (study time, absences)

Grades (G1, G2, G3)
#Key Questions Explored

(1) Do male or female students perform better on average?

(2) How do absences influence final grades?

(3)Does increased study time lead to higher grades?

(4) Are there exceptions to these trends?
#Methodology

Loaded and explored the dataset using Pandas

Performed visual analysis using Seaborn and Matplotlib

Barplot: Average grade by gender

Scatterplot: Absences vs final grade, highlighting exceptions

Boxplot: Study time vs final grade

Interpreted trends and anomalies to understand student performance factors

Key Findings

Gender: Male students scored slightly higher on average than female students, but the difference is minor (~1 point).

Absences: Students with fewer absences generally achieved higher grades. Exceptions exist (some students with 0 absences scored low; some with many absences scored high), highlighting the influence of other factors like study habits and prior knowledge.

Study Time: Students who dedicate more hours to studying tend to score higher, though a few outliers exist.

Overall: Attendance and study time are strong predictors of performance. Gender has a minor effect, and individual variation suggests personal circumstances, motivation, and prior knowledge also matter.

#Visual Dashboard

The dashboard below summarizes the findings:

Average Grade by Gender – compares male vs female student performance

Absences vs Final Grade – highlights exceptions to the general trend

Study Time vs Final Grade – shows how study time influences grades

(Insert your chart image here or link to notebook)

#Conclusion

This project demonstrates how data analytics can uncover insights in education. The trends observed align with general expectations: more study time and consistent attendance lead to better performance, but individual variation exists. This analysis could help educators identify students who may need extra support.

#Next Steps / Extensions

This project can be expanded in several ways to provide deeper insights and demonstrate advanced analytics skills:

Include Portuguese Course Data

Analyze the student-por.csv dataset alongside the Math dataset.

Compare student performance across subjects.

Optionally, merge both datasets to study students enrolled in both courses.

Explore Parental Education and Family Background

Investigate the influence of factors such as parental education (Medu, Fedu) and family relationships (famrel) on student performance.

Use barplots, boxplots, and correlation heatmaps to highlight trends.

Discuss how socio-economic background may shape academic outcomes.

Build Predictive Models

Develop models to estimate final grades (G3) based on multiple features (attendance, study time, family background, etc.).

Start with Linear Regression for interpretability and extend to Random Forests or other machine learning models.

Evaluate performance using metrics such as R² score and Mean Absolute Error (MAE).

Visualize predicted vs actual grades to illustrate model effectiveness.
