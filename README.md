# Talent-Science-Recruitment-Analytics
This project is an end-to-end **People Analytics** study that combines **Psychological Assessment** with **Data Science**. It aims to evaluate the effectiveness of recruitment sources and the validity of psychometric testing in the hiring process.

## Project Overview
As a candidate with a background in Psychology, I designed this project to demonstrate how data can transform HR from a reactive function into a strategic, science-based department.

- **Problem:** Does our current psychometric testing actually predict interview success?
- **Goal:** Optimize recruitment spend by identifying high-quality candidate sources.

## Tech Stack & Methodology

### 1. Data Simulation (Python)
- Generated a synthetic dataset of **200 candidates** using `pandas` and `numpy`.
- Performed **Feature Importance** analysis using `RandomForestClassifier` to identify which variables (experience, test scores, etc.) truly drive hiring decisions.
- Conducted **Correlation Analysis** to measure the relationship between test scores and performance.

### 2. Strategic Querying (SQL)
- Used SQL to aggregate data by `recruitment_source`.
- Calculated average performance metrics and conversion rates (Hiring Rate) for each channel.

### 3. Executive Dashboard (Tableau)
<img width="1219" height="652" alt="Screenshot 2025-12-29 at 16 52 32" src="https://github.com/user-attachments/assets/f0f0f287-1fe2-4879-b8ac-4448888f130a" />


- Built an interactive dashboard featuring **3 KPIs**: Total Applicants, Hiring Rate, and Average Candidate Quality.
  <img width="275" height="51" alt="Screenshot 2025-12-29 at 16 50 16" src="https://github.com/user-attachments/assets/5587d951-4264-40cd-bf85-dc20e38d7ae8" />
- Visualized the **Recruitment Funnel** and candidate distribution. 
- Created a custom **"Candidate Quality Score"** using weighted calculated fields.

## Key Findings & Insights
- **Low Correlation (0.12):** The analysis revealed a very weak relationship between psychometric test scores and interview performance, suggesting the need for a **test validation study**.
- **Source Efficiency:** While *Indeed* brought the highest volume of candidates, *Employee Referrals* yielded the highest average **Candidate Quality Score**.
- **Decision Drivers:** Interview performance remains the primary driver of hiring, with psychometric data being underutilized.
