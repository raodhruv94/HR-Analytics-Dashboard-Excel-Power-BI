**# HR Analytics Dashboard – Power BI**

## 📋 Project Overview
This interactive Power BI dashboard provides comprehensive insights into employee attrition, demographics, satisfaction levels, and compensation patterns for an HR department. It helps identify key drivers of employee turnover, such as age groups, salary slabs, job roles, and education fields, enabling data-driven decisions to improve retention and workforce planning.

## 🎯 Objective
- Analyse factors contributing to employee attrition.
- Identify high-risk employee segments for targeted retention strategies.
- Monitor key HR KPIs like attrition rate, average salary, and satisfaction metrics.

## 🛠️ Tools Used
- Power BI Desktop
- Excel (data preparation)
- DAX for custom measures and calculations

## 📊 Dataset
- **Source**: HR Analytics dataset (likely Kaggle / internal HR data)
- **Size**: Standard employee records (multiple tables linked in the data model)
- **Key columns**: EmpID, Attrition (Yes/No), Age, Gender, Department, JobRole, EducationField, MonthlyIncome, YearsAtCompany, EnvironmentSatisfaction, AttritionCount (measure)

## 🔄 Process (Step-by-Step)
1. **Data Import & Cleaning**: Loaded data into Power BI, handled missing values, and created calculated columns (e.g., AgeGroup, SalarySlab).
2. **Data Modelling**: Established relationships between tables (employee facts and dimensions).
3. **DAX Measures**: Created key metrics like `Attrition Rate`, `Count of Employees`, `Average Salary`, `Attrition Count`.
4. **Dashboard Design**: Built an intuitive layout with KPI cards, charts (doughnut, column, bar, line), pivot table, slicers, and a background image for professional appeal.

## 📈 Key Insights
- **Attrition by Education Field**: Life Sciences shows notable attrition volume.
- **Attrition by Age/Salary**: Higher risk in certain age groups and lower salary slabs.
- **Job Role Impact**: Sales Executive and Research Scientist have higher attrition.
- **Satisfaction Analysis**: Environment Satisfaction and Job Role correlation with turnover.
- Overall attrition rate and demographic breakdowns provide clear retention priorities.

## 🚀 How to View
- Download the `.pbix` file above and open in Power BI Desktop.
- **Interactive version**: Publish to Power BI Service for sharing (or use Publish to Web if enabled).

## 📌 Skills Demonstrated
- Advanced DAX (measures, calculated columns)
- Data modelling and relationships
- Interactive visualisations and storytelling
- HR business analytics best practices
