# Internship Application Analysis Dashboard

## Overview 📊

This project visualizes and tracks my internship application journey from Fall 2024 through Spring 2025. The dashboard was created to analyze application patterns, company responses, and interview outcomes using real self-tracked data. It provides insights into response rates, interview progression, and application efficiency over time which will help me reflect on trends and improve future outreach strategies.

## Tools Used 🧰

- Microsoft Excel (data recording and formatting)
- Power Query (data cleaning and transformation)
- PowerBI (dashboard creation and data modeling)
- DAX (custom measures and calculations)

## Data Cleaning & Structuring 🛠️
[📥 Download Dataset (Excel)](https://github.com/kdrew714/2025-Sum.-Internship-App-Analysis/blob/main/Internship%20Application%20Dataset.xlsx)

Using Power Query in Excel and Power BI, I cleaned and transformed the data by:

- Removing duplicates and normalizing inconsistent status entries
- Using TRIM, PROPER, and conditional columns to standardize formatting
- Splitting the original flat file into multiple normalized tables:
    - Applications: 1 row per application, with company, role, semester, and source
    - StatusHistory: 1 row per status update per application, allowing multi-round tracking
- Linking tables via primary keys to follow third normal form (3NF), making the dataset scalable for querying and visualization

  

## Exploratory Data Analysis (EDA) 📄

I conducted EDA using DAX meausres and PowerBI visualizations to answer questions such as:

- How many of my applications resulted in a real response, not just an auto email?
- How long did it tkae on average to receive a response and how did that change over time?
- Are there companies where I consistently reached later rounds?
- Which months showed the most effort vs. most rejections?
- How often did I receive automated inrterviews versus direct outreach from recruiters?

## Preview 📌
[📎 Download Dashboard (PowerBI)](https://github.com/kdrew714/2025-Sum.-Internship-App-Analysis/blob/main/2025%20Sum.%20Internship%20App%20Analysis%20Dashboard.pbix)

![Dashboard Screenshot 1](https://github.com/kdrew714/2025-Sum.-Internship-App-Analysis/blob/main/Overview%20Dashboard.png)
![Dashboard Screenshot 1](https://github.com/kdrew714/2025-Sum.-Internship-App-Analysis/blob/main/Table%20Dashboard.png)

### Features 🗂️

- Total applications, response time, and screening metrics
- Interview and rejection rates (overall and monthly)
- Application outcomes breakdown (including auto interviews)
- Visuals for interview rounds and timelines
- Application sources and job category analysis
- Dedicated info page with KPI explanations and status definitions

## Findings 💡

- Out of over 400 applications submitted, only a small percentage of 3.18% passed resume screenings, highlighting the competitive and high-volume nature of early-career recruiting.
- Only 1.1% of total applications led to real-time interviews, though the interview rate jumped to 4.1% when considering only those that received a response.
- A large portion of applications were made through LinkedIn, which was my most-used platform but not necessarily the most effective in terms of interview conversion.
- Interview progression beyond the first round was rare, indicating drop-offs between early communication and deeper engagement.
- The timeline analysis revealed that the rejection rate closely follows the application rate displaying the amount of rejections given in a month is almost equal to the applications made in a month.
- Most companies that conducted multiple interview rounds tended to use structured processes, often including assessments, phone screens, and virtual interviews. However, multi-round progression remained rare overall.
- While a significant portion of applications were submitted to US Fortune 500 companies, the rate of response and interview progression was generally lower compared to other organizations.


## Limitations ⚠️

This project began as a simple Excel tracker intended to summarize high-level application metrics. However, as the number of applications increased, it became clear that I had not captured enough detail about each job opportunity such as role requirements, experience level, company size, or job description keywords.

As a result, the dashboard focuses more on application volume, responses, and outcomes rather than deeper analysis of job traits or matching qualifications. With more structured data on job listings themselves, future versions could explore correlations between specific job features and response quality or interview success.

## Future Plans 🔭

- Migrate data to a relational database (e.g., PostgreSQL) for scalability
- Track additional details like job requirements, experience level, company size
- Build comparative analysis across job sources and positions
- Automate weekly updates and trend summaries

## License 📋

This project is for educational and personal use.


