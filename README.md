# McKinsey Solve Global Analytics Report (2018–2025)

![McKinsey Dashboard Dark](https://github.com/user-attachments/assets/4b0b1a31-890a-48ba-a846-de07e2735ae9)

[![Kaggle Dataset](https://img.shields.io/badge/View%20on-Kaggle-blue?logo=kaggle)](https://www.kaggle.com/datasets/oluwademiladeadeniyi/mckinsey-solve-global-assessment-data)  
[Connect on LinkedIn](https://linkedin.com/in/demibolt/) • [Follow on X (Twitter)](https://twitter.com/demibolt_)

---

## 🧭 Overview

This report explores global test-taker data from the **McKinsey Solve Assessment** between 2018 and 2025. Using Excel-powered dashboards, charts, and performance gauges, we uncover what influences assessment success — from demographics and education to regional engagement and resume strength.

📊 **Explore the Dataset on Kaggle:**  
➡ [Kaggle: McKinsey Solve Global Assessment Data (2018–2025)](https://www.kaggle.com/datasets/oluwademiladeadeniyi/mckinsey-solve-global-assessment-data)

---

## 📌 Table of Contents

- [1. Introduction](#1-introduction)
- [2. Story of Data](#2-story-of-data)
- [3. Data Preprocessing & Splitting](#3-data-preprocessing--splitting)
- [4. Pre-Analysis Observations](#4-pre-analysis-observations)
- [5. In-Analysis](#5-in-analysis)
- [6. Post-Analysis & Key Insights](#6-post-analysis--key-insights)
- [7. Data Visualizations](#7-data-visualizations)
- [8. Recommendations](#8-recommendations)
- [9. Conclusion](#9-conclusion)
- [10. References & Appendices](#10-references--appendices)

---

## 1. Introduction

This report investigates the drivers of success in the McKinsey Solve gamified assessments. It identifies patterns by region, education, employment, gender, and game behaviour — offering insights for recruiters and educators.

---

## 2. Story of Data

- **Source**: This dataset was self-generated using a combination of synthetic data modelling and real-world structure. Department names, office locations, and assessment components were referenced from McKinsey’s Solve website and recruitment resources. All test scores, participant demographics, and game engagement metrics were created to simulate realistic candidate performance across global regions.
- **Volume**: 4,000+ global records  
- **Structure**: Rows = individual test takers; Columns = demographics, assessment scores, game engagement, resume score  
- **Key Fields**:  
  - Gender, Age, Country, Education Level  
  - Game Engagement (Ecosystem %, Redrock %, Seawolf %)  
  - Resume Score, Total Score, Pass/Fail Status

---

## 3. Data Preprocessing & Splitting

- **Cleaning**: Removed duplicates, completed missing resume data  
- **Derived Fields**: Created Pass Rate, Test Time Allocation, and Score Categories  
- **Split Variables**:  
  - **Dependent**: Assessment Score, Pass/Fail  
  - **Independent**: Age, Gender, Country, Resume Score, Game Scores

---

## 4. Pre-Analysis Observations

- Most test takers are aged 21–30  
- Resume Scores tend to be higher for graduate-level participants  
- Some countries with smaller participation had surprisingly high pass rates (e.g., Colombia, Italy)

---

## 5. In-Analysis

### 📈 Full Global Insights (2018–2025)

- **Average Assessment Score**: ~76.15% (visualized via a **Performance Gauge**)  
- **High Performers**: Italy (74%), Colombia (72%), Spain (70%)  
- **Low Performers**: Ghana (36%), Nigeria (38%), Tanzania (42%)  
- **Observation**: Education levels strongly influence both Resume and Test scores  
- **Trend**: Master's degree holders dominate high pass rates

---

### 🔍 Filtered Subgroup Insights (e.g., Age 21–25, Undergraduate Only)

- **Resume Scores**: Drop significantly for first-gen university students  
- **Gender Split**: Females slightly outperform in Redrock and Seawolf games  
- **Game Engagement**: Ecosystem scores correlate most with Total Assessment Scores  
- **Unemployed Segment**: Represents 38% of test takers — low Resume Score, high game engagement  

---

## 6. Post-Analysis & Key Insights

- Average global pass rate: **57.7%**  
- Game performance is **regionally balanced** — validates fairness of the assessment tool  
- Resume strength and education still heavily influence pass outcomes

---

## 7. Data Visualizations

Key visuals created in Microsoft Excel:

- 🌍 **Pass Rate by Country** — Color-coded map  
- 🎓 **Assessment Status by Education** — Bar chart (Pass vs. Fail)  
- 🎮 **Game Scores by Region** — Grouped bar chart  
- 🧑‍💼 **Resume Trends Across Education Levels** — Line graph  
- ⏱️ **Performance Gauge** — Speedometer showing average global score (76.15%)

![McKinsey Dashboard Light](https://github.com/user-attachments/assets/b50058f5-8810-4e58-9ed5-fbfc969927b5)

---

## 8. Recommendations

- 📍 **Targeted Preparation**: Invest in countries with <50% pass rate — provide practice tools.  
- 🎓 **Resume Uplift**: Develop CV support workshops for first-gen and unemployed test takers.
- 🧪 **A/B Test Support**: Pilot resume prep or game tutorials to boost underperforming segments.  
- 🧭 **Localise Resources**: Translate and adapt training for regional learning styles and access.

---

## 9. Conclusion

This dataset sheds light on the evolving nature of global hiring assessments. Demographics, education, and engagement behavior influence success, but fair testing design allows broad participation. Continuous support for underserved regions and groups will drive equitable talent identification.

---

## 10. References & Appendices

- 🧠 Inspired by McKinsey Solve’s game-based assessment structure.
- 📊 Built entirely in **Microsoft Excel** with Pivot Tables and Dynamic Charts.
- 📁 [Download the Dataset on Kaggle](https://www.kaggle.com/datasets/oluwademiladeadeniyi/mckinsey-solve-global-assessment-data)

---

## 🙌 Let’s Connect

📌 [LinkedIn](https://linkedin.com/in/demibolt/)  
🐦 [Twitter / X](https://twitter.com/demibolt_)  
📫 Open to feedback, questions, or collaborations!
