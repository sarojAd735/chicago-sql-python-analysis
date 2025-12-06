# Chicago Data Analysis Using Python & SQL

This project explores three real-world datasets from the City of Chicago using **Python, Pandas, SQLite, and SQL**.  
The goal is to load, clean, and analyze public data to answer meaningful questions about schools, crime, and socioeconomic conditions across Chicago’s community areas.

---

## 🔍 Project Overview

Using Jupyter Notebook, this project:

- Loads **three datasets** (Census, Public Schools, Crime)
- Creates and populates a **SQLite database** (`FinalDB.db`)
- Performs data analysis using **SQL queries**
- Answers key analytical questions such as:
  - Total number of crimes reported
  - Crimes involving minors
  - Crime types occurring at schools
  - Average school safety scores by school type (ES/MS/HS)
  - Top 5 community areas with highest poverty levels
  - Most crime-prone community area
  - Community area with the highest hardship index (subquery)
  - Community area with the most crimes (subquery)

This project demonstrates skills in **data engineering, SQL querying, and exploratory data analysis**.

---

## 📂 Datasets Used

The notebook loads three publicly available CSV datasets from IBM’s Skills Network cloud:

- **Chicago Census Data**  
  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCensusData.csv

- **Chicago Public Schools Data**  
  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoPublicSchools.csv

- **Chicago Crime Data**  
  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCrimeData.csv

These datasets are subsets of Chicago’s open data portal and include:
- Socioeconomic indicators and hardship index  
- School performance and safety scores  
- Crime incident records across Chicago  

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **SQLite / sqlite3**
- **ipython-sql**
- **Jupyter Notebook**

---

## 🗄️ Database Structure

The notebook creates and populates three SQLite tables:

| Table Name                     | Description |
|-------------------------------|-------------|
| `CHICAGO_PUBLIC_SCHOOLS`      | School performance and safety data |
| `CHICAGO_CRIME_DATA`          | Crime incident reports |
| `CENSUS_DATA`                 | Socioeconomic and hardship indicators |

---

## 📊 Key SQL Analyses Performed

- Number of crimes recorded
- Crimes involving minors
- Crime types occurring at school locations
- Average safety score by school type (ES / MS / HS)
- Top 5 community areas with highest poverty %
- Most crime-prone community area
- Community area with highest hardship index (subquery)
- Community area with the most crimes (subquery)

---

## ▶️ How to Run the Project

1. **Clone the repository**

```bash
git clone https://github.com/<your-username>/chicago-sql-python-analysis.git
cd chicago-sql-python-analysis
