# Part 4 — Data Visualization & Machine Learning

**Theme:** Student Performance Analysis & Prediction | **Marks:** 25 (+2 bonus)

## Setup

```bash
pip install pandas matplotlib seaborn scikit-learn
jupyter notebook part4_visualization_ml.ipynb
```

## Dataset

`students.csv` — 15 students, 9 columns:

| Column | Type | Description |
|--------|------|-------------|
| name | str | Student name |
| math, science, english, history, pe | int | Subject scores (0–100) |
| attendance_pct | float | Attendance percentage |
| study_hours_per_day | float | Daily study hours |
| passed | int | Target label (1 = Pass, 0 = Fail) |

## Tasks Implemented

| Task | Description | Marks |
|------|-------------|-------|
| 1 | Pandas Exploration — head, shape, dtypes, describe, value_counts, pass/fail subject averages, top student | 5 |
| 2 | Matplotlib — 5 plots: bar chart, histogram, scatter, box plot, line plot (all saved as .png) | 8 |
| 3 | Seaborn — grouped bar chart + regression scatter (both saved as .png); Seaborn vs Matplotlib comparison | 4 |
| 4 | ML — Logistic Regression: prepare data, StandardScaler, train, evaluate, feature coefficients chart, new student prediction | 8 (+2) |

## Output Files

| File | Description |
|------|-------------|
| `plot1_bar_avg_subject.png` | Average score per subject (bar chart) |
| `plot2_hist_math.png` | Math score distribution (histogram) |
| `plot3_scatter_study_avg.png` | Study hours vs avg score (scatter) |
| `plot4_box_attendance.png` | Attendance % by pass/fail (box plot) |
| `plot5_line_math_science.png` | Math & science per student (line plot) |
| `plot6_seaborn_bar_math_science.png` | Seaborn grouped bar: math & science |
| `plot7_seaborn_regression.png` | Seaborn regression: attendance vs avg |
| `plot8_feature_importance.png` | Logistic Regression coefficients |

## Before Pushing

Run **Kernel → Restart & Run All**, save, then `git add . && git commit`.  
All plots must appear as inline outputs inside the notebook.
