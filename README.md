

***

## Deloitte Data Analytics Project

### Task 1: Factory Telemetry Data Analysis (Tableau)

**Objective:**  
Analyze factory machine telemetry data to identify which Daikibo factory and which types of machines experienced the most downtime in May 2021.

**Steps Taken:**  
- Imported a unified JSON file containing one month of telemetry data from 4 Daikibo factories, each with 9 machine types.
- Created a calculated field in Tableau called **“Unhealthy”** to quantify every instance of unhealthy machine status as 10 minutes of downtime.
- Built two key bar charts:
    - **Down Time per Factory**: Compared total downtime across all four factories.
    - **Down Time per Device Type**: Showed downtime for each machine type.
- Built an interactive dashboard where clicking on a factory bar filters device downtime to that location.
- Identified that Daikibo Factory Seiko (Osaka) had the highest overall downtime and LaserWelder machines were most problematic there.
- Provided actionable insights for targeted maintenance and operational improvement.

**Deliverables:**  
- Tableau workbook (.twbx) and dashboard screenshot for evidence of findings.
- Clear steps and methodology for reproducibility.

***

### Task 2: Gender Pay Equality Classification (Excel)

**Objective:**  
Investigate gender pay equality across Daikibo job roles and factories, classifying each role according to its Equality Score.

**Steps Taken:**  
- Used an Excel file listing job roles, factories, and an Equality Score (range: -100 to +100; where 0 is perfectly equal).
- Added a column **“Equality class”** that classified each job role as:
    - **Fair**: Score between -10 and 10
    - **Unfair**: Score between -20 and -11, or 11 and 20
    - **Highly Discriminative**: Score less than -20 or greater than 20
- Applied logical formulas to automate classification across all rows.
- Analyzed results by factory and job role to highlight locations and roles with the largest pay gaps.
- Summarized findings showing management roles consistently showed the biggest inequalities.

**Deliverables:**  
- Completed Excel file with “Equality class” column.
- Summary table and stats showing breakdown of Fair, Unfair, and Highly Discriminative roles.
- Insights to support further HR and forensics action.

___
