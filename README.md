# 📊 Data Professional Survey Visualization (Power BI)

## Folder Chart

PowerBI_Projects/
└── 01_Data_Professional_Survey_Visualization/
    ├── DataProfessionalSurvey.pbix
    ├── Dataset.xlsx
    ├── README.md
    └── assets/
        └── dashboard_screenshots/



## Project Overview
This Power BI project analyzes survey data from data professionals to uncover trends related to job roles, salaries, programming languages, and job satisfaction.  
The focus of this project is to practice data cleaning, transformation, and dashboard creation using Power BI.

---

## Dataset
- **Source**: Data Professional Survey
- **Format**: Excel (`Dataset.xlsx`)
- **Description**: Survey responses from professionals working in data-related roles across different countries and experience levels.

---

## Data Preparation & Transformation
Data cleaning and transformation were performed using **Power Query**:
- Removed unnecessary and blank columns
- Split columns using delimiters to separate combined salary ranges
- Converted salary ranges (e.g. `100–200k`) into numeric values
- Created an **average salary metric** for analysis
- Standardized categorical fields such as job title, gender, and programming language

---

## Key Questions Answered
- What is the average salary by job title?
- How is the gender distribution across survey respondents?
- Which programming languages are most commonly used?
- What are the most popular programming languages among data professionals?
- How satisfied are professionals with their salary and current position?
- What is the average age of survey participants?

---

## Dashboard Features
- Average salary comparison by job role
- Gender distribution of survey takers
- Programming language usage analysis
- Total number of respondents and average age
- Happiness indicators for salary and job position
- Interactive visuals and filters for exploration

---

## Tools & Technologies Used
- Power BI Desktop
- Power Query (data cleaning & transformation)
- DAX (basic measures and calculations)
- Microsoft Excel

---

## How to Use
1. Open `DataProfessionalSurvey.pbix` using **Power BI Desktop**
2. Ensure `Dataset.xlsx` is available in the same folder if data refresh is required
3. Explore insights using interactive visuals and filters

---

## 📷 Dashboard Preview
*(Dashboard screenshots can be added here for better visualization.)*
