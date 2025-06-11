# 📁 SAP HR Dataset Documentation

This dataset supports the HR dashboard analysis for the **SAP Bicycle Company**, focusing on data from the following entities:

- **Acme Western EU SE**
- **Acme LA Corp.**
- **Acme NA Corp.**

The dataset is composed of structured Excel files used to analyze employee metrics, headcount trends, and organizational structure.

---

## 📊 Dataset Files and Descriptions

| File Name                     | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| `Departments.csv`           | Contains department codes used across the organization.                     |
| `DepartmentTexts.csv`       | Display names and descriptions for department codes.                        |
| `Divisions.csv`             | Contains division codes mapped to departments.                             |
| `DivisionTexts.csv`         | Descriptive text and display values for division codes.                     |
| `EmployeeHeadcount.csv`     | Headcount and status data per employee, including start and end dates.      |
| `EmployeePerformance.csv`   | Performance scores, leadership flags, and impact indicators.                |
| `EmployeePersonalData.csv`  | Master data of employees (e.g., ID, name, gender, marital status, etc).     |
| `EmployeePosition.csv`      | Job position data with job title, job level, and position dates.            |
| `HRManager.csv`             | List of HR managers responsible for employees or departments.               |
| `Job.csv`                   | Job codes and role identifiers.                                             |
| `JobClassification.csv`     | Classification levels such as associate, manager, expert, etc.              |
| `JobClassificationTexts.csv`| Descriptions and display values for job classifications.                    |
| `JobTexts.csv`              | Job title texts and additional job descriptions.                            |
| `Location.csv`              | Location codes used across employee records.                                |
| `LocationHierarchy.csv`     | Hierarchical structure of office, country, and region data.                 |
| `LocationTexts.csv`         | Descriptive names for location codes.                                       |

---

## 📈 Usage in Dashboards

The data was transformed using **Power Query** and visualized using **Power Pivot** in Excel. Three dashboards were created:

### 1. Active Employee Dashboard
Focuses on:
- Headcount by department, gender, and job level
- Age group, tenure, and salary range distribution

### 2. Turnover Dashboard
Highlights:
- Exit trends over time
- Retention vs. voluntary/involuntary turnover
- Comparison by division and job level

### 3. Employee Personal Data Dashboard
Presents:
- Detailed individual employee records
- Personal and professional data (ID, gender, role, etc.)
- Performance and history

---

## 🗂 Source System

All data files are simulated and derived from SAP’s demo HR dataset under the **SAP Bicycle Company** structure. The sources were segmented per regional company unit (Acme Western EU SE, Acme LA Corp., Acme NA Corp.).

---

## 📷 Dashboard Preview

You can find screenshots and visual samples under the [`Dashboard Preview`](./Dashboard%20Preview) folder.
