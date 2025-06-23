# 👩‍💼 HR Dashboard in Power BI

This project is a fully interactive **Human Resources Dashboard** created in **Power BI**. It provides dynamic insights into employee data using **buttons**, **filters**, and **navigation features** to enhance user experience and decision-making.

## 🗂️ File

- `Zarin_Shirinli_hr_Dashboard.pbix` (Power BI Dashboard File)

## 🎯 Purpose

To visualize key HR metrics in an intuitive and interactive format, enabling HR teams and decision-makers to:
- Monitor workforce distribution
- Track employee demographics
- Analyze attrition and retention
- Identify trends and anomalies

## 🧩 Key Features

### 🔘 Buttons & Navigation
- **Page Navigation Buttons**: Jump between report pages (e.g., Overview → Attrition → Demographics).
- **Reset Filters Button**: Quickly clear all filters to default state.
- **Drill-Through Links**: Contextual deep-dives into employee-specific data.

### 🧮 Filters & Slicers
- Filter by:
  - Department
  - Gender
  - Age Group
  - Job Role
  - Employment Type
  - Hire Date / Year
- Date hierarchy slicers and dynamic dropdowns for flexible exploration

### 📊 Visuals Included
- **KPI Cards** for:
  - Total Employees
  - Active Employees
  - Attrition Rate
- **Bar/Column Charts** for:
  - Employee distribution by department & job role
  - Gender & age demographics
- **Line Chart** for attrition trends over time
- **Pie/Donut Charts** for visual proportion breakdowns
- **Table with Conditional Formatting** for detailed employee info

## Preview
![image](https://github.com/user-attachments/assets/a9e663ab-82a5-4791-b8b1-7c2b1822cbed)
![image](https://github.com/user-attachments/assets/4bedf814-a10f-4b4a-be45-8785fffa9cca)
![image](https://github.com/user-attachments/assets/97dadef1-acee-45dc-a3f2-c3044c3e5892)



Attrition Rate = 
DIVIDE(
    CALCULATE(COUNTROWS(Employee), Employee[Status] = "Exited"),
    CALCULATE(COUNTROWS(Employee))
)
