# social-media-impact-analysis-dashboard
Excel dashboard analyzing the impact of social media usage on student mental health, sleep quality, academic performance, and overall well-being using interactive charts, KPIs, and slicers.

# 📊 Social Media Impact on Student Wellbeing Dashboard

An interactive Excel dashboard analyzing the impact of social media on 1,000 students across academic levels, platforms, and usage patterns.

![Dashboard Preview](dashboard_preview.png)

---

## 📁 Project Structure

```
├── Social_media_impact_on_life.csv   # Raw dataset (1,000 students)
├── project_excel.xlsx                # Final Excel dashboard file
└── README.md
```

---

## 📌 Project Overview

This project explores how social media usage affects student wellbeing across three key dimensions — mental health, academic performance, and sleep quality. The dashboard was built entirely in Microsoft Excel using Power Query, PivotCharts, Slicers, and custom shapes.

---

## 🎯 Key Findings

| Metric | Value |
|---|---|
| Total Students Analyzed | 1,000 |
| Avg Daily Social Media Usage | 5.2 hrs |
| Avg Sleep Hours Per Night | 6.4 hrs |
| Avg Mental Health Score | 6.2 / 10 |
| Students Reporting Negative Impact | 47% (470 students) |
| Students Reporting Academic Impact | 55.8% (558 students) |

---

## 📊 Dashboard Features

### Charts Included
- **Overall Impact Distribution** — Donut chart showing Negative / Neutral / Positive breakdown
- **Avg Daily Usage by Platform** — Horizontal bar chart comparing platforms
- **Does Social Media Affect Academic Performance?** — Pie chart (Yes/No)
- **Avg Mental Health Score by Platform** — Column chart per platform
- **Impact Distribution by Usage Level** — Stacked bar (High / Low / Moderate usage)
- **Gender Distribution** — Bar chart by gender count
- **Student Distribution by Academic Level** — Column chart

### KPI Banner
| KPI | Value |
|---|---|
| Total Members | 1,000 |
| Avg Daily Usage | 5.2 hrs |
| Avg Sleep | 6.4 hrs |
| Avg Mental Health | 6.2 /10 |

### Interactive Filters (Slicers)
- Usage Category (High / Low / Moderate)
- Academic Level (Graduate / High School / Undergraduate)
- Overall Impact (Negative / Neutral / Positive)
- Gender (Female / Male)

All slicers are connected to all PivotCharts via Report Connections for synchronized filtering.

---

## 🧹 Data Cleaning (Power Query)

The raw CSV was cleaned using Power Query with the following steps:

1. Removed `Student_ID` column (irrelevant identifier)
2. Removed duplicate rows
3. Trimmed and cleaned all text columns
4. Standardized country values — grouped minor countries into "Other"
5. Rounded numeric columns to 1 decimal place
6. Set explicit data types for all columns
7. Added custom **Age Group** column (Late Teens / Early Twenties / Mid Twenties)
8. Added custom **Usage Category** column (Low ≤3hrs / Moderate 3–6hrs / High >6hrs)
9. Verified zero null/blank values across all columns

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel 2016 | Dashboard building, charting, slicers |
| Power Query | Data cleaning and transformation |
| PivotTables & PivotCharts | Dynamic chart data sources |
| Excel Shapes & Text Boxes | KPI cards, title banner, layout |

---

## 🎨 Design Specs

| Element | Specification |
|---|---|
| Color Palette | Monochromatic blue — `001D39` to `BDD8E9` |
| Title Font | Segoe UI Black, 20pt, White |
| Chart Title Font | Segoe UI Semibold, 12pt |
| KPI Number Font | Segoe UI Bold, 22pt, White |
| KPI Label Font | Segoe UI, 9pt, Light blue-white |
| Canvas Background | RGB 189, 216, 233 |
| KPI Box Fill | RGB 0, 29, 57 |
| Chart Card Fill | White with soft outer shadow |

---

## 📂 Dataset

**Source:** [Kaggle — Social Media Impact on Life](https://www.kaggle.com/)

**Columns:**
| Column | Description |
|---|---|
| Gender | Male / Female |
| Age | Student age (18–24) |
| Academic_Level | High School / Undergraduate / Graduate |
| Country | Student's country |
| Most_Used_Platform | Facebook / Instagram / LinkedIn / Snapchat / TikTok / Twitter / YouTube |
| Avg_Daily_Usage_Hours | Daily hours spent on social media |
| Sleep_Hours_Per_Night | Average sleep hours |
| Mental_Health_Score | Score out of 10 |
| Affects_Academic_Performance | Yes / No |
| Overall_Impact | Negative / Neutral / Positive |
| Age_Group | Derived column (Late Teens / Early Twenties / Mid Twenties) |
| Usage_Category | Derived column (Low / Moderate / High) |

---

## 🚀 How to Use

1. Download `project_excel.xlsx`
2. Open in **Microsoft Excel 2016 or later**
3. Navigate to the **Dashboard** sheet
4. Use the **slicers on the left** to filter all charts simultaneously
5. Hover over chart elements for data tooltips

---
