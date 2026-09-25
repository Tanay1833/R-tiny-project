# Tiny Project — Student Academic Performance Analysis

## Topic
Student Academic Performance Analysis using R.

## Project purpose
This project demonstrates a complete R Markdown data-analysis workflow:
- CSV/database-style data importing
- preprocessing and cleaning
- descriptive and statistical exploration
- graphs and plots
- interpretation
- findings and conclusion
- reproducible R Markdown source

## Files
- `student_performance_analysis.Rmd` — complete R Markdown source.
- `student_data.csv` — sample dataset used by the report.
- `student_performance_analysis.html` — rendered project report.
- `student_marks.png` — marks chart.
- `student_attendance.png` — attendance chart.
- `gender_distribution.png` — gender distribution chart.
- `result_distribution.png` — result distribution chart.
- `attendance_vs_marks.png` — attendance vs marks scatter plot.
- `PROJECT_DOCUMENTATION.md` — project documentation.
- `requirements.txt` — software/package requirements.
- `README.md` — this file.

## How to run
1. Install R and RStudio.
2. Install the required packages:
   `install.packages(c("rmarkdown", "knitr"))`
3. Keep the `.Rmd` and `.csv` files in the same folder.
4. Open `student_performance_analysis.Rmd` in RStudio.
5. Click **Knit** to generate the HTML report.

## Dataset
The dataset contains 12 student records with:
`Student_ID, Name, Gender, Age, Marks, Attendance, Result`.

## Main result
The sample shows a correlation of approximately 0.993 between attendance and marks. This indicates a very strong positive association in this small sample, but it does not establish causation.

## Source basis
The uploaded practical R Markdown/HTML material used the same student-performance dataset and demonstrated CSV import, structure/missing-value checks, descriptive statistics, gender/result counts, bar charts and attendance–marks correlation. The project reorganises and expands that material into a complete tiny-project report.
