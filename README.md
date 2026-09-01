# Power_BI_StudentPerformanceFactor
An interactive analytics dashboard visualizing key academic, social, and environmental factors influencing student performance, helping educators identify patterns and target intervention strategies.

Dataset from Kaggle: https://www.kaggle.com/datasets/fatihyavuzz/studentperformancefactors

**Learning Disabilities Slicer: **
Filters the entire dashboard to isolate performance trends for students with or without identified learning needs.

**Motivation Level Slicer: **
Filters all visuals by student motivation (High, Medium, Low) to evaluate its impact on attendance, study habits, and final scores.

**Top KPI Summary Cards:**
- Total Students (6.607K): Displays the total active student cohort analyzed in the live dataset.
- Avg Exam Score (67.24): Represents the overall mean score achieved across all current assessments.
- Avg Attendance Rate (79.98%): Tracks the average active class participation rate across the student body.
- Avg Hours Studied (19.98): Measures the average weekly study time spent by students.

**Upper Row Charts (Demographics & Baseline Factors):**
- Gender (Pie Chart): Outlines current gender distribution, with Male (57.73% / 3.81K) representing the larger group compared to Female (42.27% / 2.79K).
- School Type by Gender (Bar Chart): Compares total enrollment counts across Public and Private institutions, broken down by gender.
- Exam Score by Parental Education (Line Chart): Maps performance trends against parental education, showing higher mean scores for students whose parents hold Postgraduate qualifications compared to College or High School.
- Learning Disabilities (Pie Chart): Shows the actual student proportion with diagnosed learning needs (10.52% Yes vs. 89.48% No).
- Exam Score by Distance (Top Right Line Chart): Illustrates exam score variations based on school proximity, segmented by motivation levels (High, Medium, Low).

**Middle Row Charts (Performance Drivers & Correlations):**
- Exam Score by Hours Studied (Scatter Plot with Trendline): Highlights the positive linear correlation between weekly study hours and student exam performance.
- Attendance Impact (Dual-Line Chart): Tracks Average Exam Score (light blue line) alongside Average Previous Scores (dark blue line) across attendance percentages from 60% to 100%.
- Exam Score by Hours Studied / Tutoring Sessions (Stacked Bar Chart): Visualizes the distribution of student counts across Tutoring Sessions (0 through 8), segmented by Motivation Level (High, Low, Medium).
- Previous Score (Gauge Chart): Displays the historic performance benchmark score (75.07 out of 100).
- Exam Score (Gauge Chart): Shows current active exam performance (67.24 out of 101 target scale).

**Bottom-Left Chart:**
- Count of Exam_Score by School_Type and Teacher_Quality (Line Chart): Captures current distribution trends between Public and Private schools across distinct teacher quality categories (High, Medium, Low, Blank).

  
