# Project Documentation

## 1. Title
Student Academic Performance Analysis using R

## 2. Problem statement
Analyse student academic information to understand marks, attendance, result distribution and the relationship between attendance and marks.

## 3. Dataset
The project uses a small CSV dataset of 12 students and 7 variables.

## 4. Methodology
1. Import CSV using `read.csv()`.
2. Inspect data using `str()` and `summary()`.
3. Check missing values with `is.na()` and `colSums()`.
4. Check duplicates using `duplicated()`.
5. Validate numeric ranges and categories.
6. Clean text fields using `trimws()`.
7. Calculate mean, median, variance and standard deviation.
8. Analyse categorical distributions.
9. Create pie charts and bar charts.
10. Calculate Pearson correlation between attendance and marks.
11. Create a scatter plot and interpret the pattern.
12. Report findings, limitations and conclusion.

## 5. Important results
- Observations: 12
- Variables: 7
- Male: 6
- Female: 6
- Pass: 10
- Fail: 2
- Mean marks: 69.50
- Median marks: 70
- Marks standard deviation: approximately 18.15
- Mean attendance: approximately 79.92%
- Attendance–marks correlation: approximately 0.993

## 6. Interpretation
The sample shows a very strong positive association between attendance and marks. Because the sample is small and observational, the result should not be interpreted as proof of causality.

## 7. Limitations
The dataset is small and synthetic/sample-like. It does not contain enough variables or observations for broad conclusions.

## 8. Reproducibility
The report uses relative file paths, so the project can be moved to another computer without changing a hard-coded Windows path.
