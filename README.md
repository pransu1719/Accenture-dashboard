https://drive.google.com/file/d/1niRGJNxfJAEb2rNDPJcy8luxrXdZCHCk/view?usp=drive_link<div align="center">

# -- ! Accenture India HR Analytics Dashboard ! --
### *Interactive 5-Page Power BI Report for Workforce, Attrition, Compensation & Performance Insights*

[![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Measures-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/dax/)
[![Data Model](https://img.shields.io/badge/Data%20Model-Star%20Schema-4CAF50?style=for-the-badge&logo=databricks&logoColor=white)](https://powerbi.microsoft.com/)
[![HR Analytics](https://img.shields.io/badge/HR-Analytics-9C27B0?style=for-the-badge&logo=googleanalytics&logoColor=white)](https://powerbi.microsoft.com/)

<br/>

> *"People are the most valuable asset of any company — data helps us understand them."*

</div>

---

## 📋 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Problem Statement](#-problem-statement)
- [✨ Key Features](#-key-features)
- [🏗️ Project Structure](#️-project-structure)
- [🗄️ Data Model](#️-data-model)
- [📊 Dashboard Pages](#-dashboard-pages)
- [📐 Key DAX Measures](#-key-dax-measures)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 How to Use](#-how-to-use)
- [📈 Results & Insights](#-results--insights)
- [🏆 Advantages](#-advantages)
- [📄 License](#-license)
- [👤 Author](#-author)
- [🙏 Acknowledgements](#-acknowledgements)

---

## 📌 Overview

The **Accenture India HR Analytics Dashboard** is an interactive **5-page Power BI report** that turns raw HR data into clear, decision-ready insights. It covers the complete employee lifecycle: **headcount, attrition, compensation, performance, promotion and training**.

This project is designed to:
- Give HR leaders a **single view** of workforce health
- Track **attrition and retention** across departments, job levels and locations
- Analyze **salary and payroll** patterns by department and grade
- Measure **performance, promotions and training completion**
- Demonstrate end-to-end **Power BI skills**: data modeling, DAX and dashboard design

---

## 🎯 Problem Statement

> **Objective:** Build an interactive HR dashboard that helps management understand workforce size, why employees leave, how they are paid and how they perform.

HR teams often work with data spread across many tables and sheets. This makes it difficult to answer simple questions quickly. This dashboard answers questions such as:

| ❓ Business Question | 📄 Answered On Page |
|---------------------|--------------------|
| How many employees do we have and where? | Workforce Overview |
| Which departments lose the most people? | Attrition & Retention |
| How much do we pay, and who earns the most? | Compensation Analysis |
| Who are our high performers and who gets promoted? | Performance & Promotion |
| What is the overall HR health at a glance? | Executive Summary |

---

## ✨ Key Features

| Feature | Description |
|--------|-------------|
| 📄 **5 Interactive Pages** | Executive Summary, Workforce, Attrition, Compensation, Performance |
| 🎛️ **Dynamic Slicers** | Filter by Year, Department, Business Unit, Job Level, Gender and Location |
| 🔢 **KPI Cards** | Total Employees, Attrition Rate, Retention Rate, Average Salary, Total Payroll and more |
| 💡 **Dynamic Insight Cards** | Auto-updating "Key Insights" text powered by DAX measures |
| 📊 **Rich Visuals** | Donut, bar, column, line, area, scatter, treemap, gauge, table and matrix |
| 🗄️ **Star Schema Model** | 11 tables: Dimension tables linked to Fact tables |
| 🎨 **Custom Design** | Consistent Accenture-style theme, icons and navigation across pages |

---

## 🏗️ Project Structure

```
📦 Accenture-dashboard/
│
├── 📄 Accenture dashboard.pbix   ← Power BI report file
│
├── 📁 screenshots/               ← Dashboard page screenshots (optional)
│
└── 📄 README.md                  ← Project documentation
```

---

## 🗄️ Data Model

The report is built on a **star schema** with **5 dimension tables** and **6 fact tables**.

| Type | Table | Purpose |
|------|-------|---------|
| 📘 Dimension | `DimEmployee` | Employee details such as gender, grade and performance |
| 📘 Dimension | `DimDepartment` | Departments and business units |
| 📘 Dimension | `DimJobLevel` | Job levels / grades |
| 📘 Dimension | `DimLocation` | Cities and locations |
| 📘 Dimension | `DimDate` | Calendar and fiscal periods |
| 📗 Fact | `FactWorkforce` | Headcount and workforce records |
| 📗 Fact | `FactAttrition` | Employee exits |
| 📗 Fact | `FactCompensation` | Salary and payroll |
| 📗 Fact | `FactPerformance` | Ratings and reviews |
| 📗 Fact | `FactRecruitment` | New hires |
| 📗 Fact | `FactTraining` | Training completion |

---

## 📊 Dashboard Pages

### 🏠 1. Executive Summary
> A one-page snapshot of overall HR health for leadership.

- KPI cards: **Total Employees, Attrition Rate, Average Salary, High Performer Review %, Promotion Rate**
- Dynamic insight cards for headcount, rating and top-paying department
- Charts: Avg Exit Tenure by department, Female % by city, gender donut, performance vs gender ratio

---

### 👥 2. Workforce Overview
> Understand headcount, hiring and diversity.

- KPI cards: **Active Employees, Total Employees, Attrition Rate, Average Tenure, Gender Ratio (M : F)**
- Charts: Employees by department, **New Hires by Fiscal Quarter**, gender donut
- Matrix: Business Unit vs Attrition Rate, Headcount and Average Salary
- Slicers: Year, Department, Business Unit, Job Level, Gender, Location

---

### 🚪 3. Attrition & Retention
> Find out who is leaving and from where.

- KPI cards: **Total Attritions, Attrition Rate, Retention Rate, Avg Exit Tenure**
- Charts: Attrition by department (bar + treemap), by job level, by gender
- Table: Department-wise Attrition Rate, Attritions and Exit Tenure
- Dynamic **Attrition insight** card

---

### 💰 4. Compensation Analysis
> Analyze salary, payroll and pay fairness.

- KPI cards: **Average Salary (LPA), Median Salary (LPA), Highest Salary (LPA), Total Payroll (Cr)**
- Charts: Average salary by department, highest salary by department, **scatter: Job Level vs Salary vs Exit Tenure**
- Matrix: Department × Job Level with Median Salary, Headcount and High Performer %
- Dynamic **Payroll insight** card

---

### ⭐ 5. Performance & Promotion
> Measure performance, promotions and learning.

- KPI cards: **Avg Performance Rating, High Performer Review %, Retention Rate, Training Completion %**
- Charts: High performers by department, High Performer % by gender, Business Unit donut, gauge, treemap
- Table: Department, Gender, Grade and **Promotion Rate**
- Dynamic insight cards for **Rating** and **Training**

---

## 📐 Key DAX Measures

| Measure | Purpose |
|---------|---------|
| `Total Employees` | Total headcount |
| `Active Employees` | Employees currently working |
| `Total Attritions` | Number of employees who left |
| `Attrition Rate` | Attritions as a % of headcount |
| `Retention Rate` | Share of employees retained |
| `New Hires` | Hires per fiscal quarter |
| `Average Tenure (Years)` | Average time spent in the company |
| `Avg Exit Tenure (Years)` | Average tenure of leavers |
| `Average / Median / Highest Salary (LPA)` | Salary statistics |
| `Total Payroll (Cr)` | Total salary cost |
| `Avg Performance Rating` | Average rating score |
| `High Performer Review %` | Share of employees rated high |
| `Training Completion %` | Training completion rate |
| `Gender Ratio (M : F)` / `Female %` | Diversity metrics |
| `Insight ...` measures | Dynamic text cards that update with filters |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 📊 **Power BI Desktop** | Report building and visualization |
| 🧮 **DAX** | Measures, KPIs and dynamic insight text |
| 🗄️ **Data Modeling** | Star schema with relationships between Dim and Fact tables |
| 🎨 **Power BI Formatting** | Custom theme, icons, shapes and navigation |

---

## 🚀 How to Use

1. **Download** the file `Accenture dashboard.pbix` from this repository
   *(If it is not visible, check the **Releases** section or the download link provided)*
2. Install **Power BI Desktop** (free) from [powerbi.microsoft.com](https://powerbi.microsoft.com/desktop/)
3. **Open** the `.pbix` file in Power BI Desktop
4. Use the **slicers** to filter the data and **click the visuals** to cross-filter
5. Use the page tabs to move between the **5 dashboard pages**

---

## 📈 Results & Insights

After exploring the dashboard, you can quickly find:

- ✅ **Workforce size and mix** by department, business unit, gender and location
- 🚪 **Attrition hot-spots** by department and job level
- 💰 **Pay patterns**: average, median and highest salary with total payroll
- ⭐ **High performers** and promotion rates across departments
- 🎓 **Training completion** and its link to performance
- 💡 **Auto-updating insights** that change with every filter

---

## 🏆 Advantages

| Advantage | Detail |
|-----------|--------|
| 🎯 **Decision Ready** | Leaders get answers in seconds, not hours |
| 🔄 **Fully Interactive** | Every slicer and visual filters the whole page |
| 🗄️ **Clean Data Model** | Star schema keeps the report fast and easy to extend |
| 📚 **Complete Coverage** | Workforce, attrition, pay, performance and training in one file |
| 🧩 **Reusable** | Measures and layout can be reused for other HR projects |
| 🎨 **Professional Design** | Consistent theme and layout across all 5 pages |

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for full details.

```
MIT License — Free to use, modify, and distribute with attribution.
```

---

## 👤 Author

<div align="center">

### Your Name

[![GitHub](https://img.shields.io/badge/GitHub-pransu1719-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pransu1719)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)

> *"Data tells a story — the dashboard helps everyone hear it."*

**🎓 Role:** Data Analyst | Power BI Enthusiast\
**📍 Location:** India\
**🛠️ Skills:** Power BI · DAX · Data Modeling · HR Analytics · Dashboard Design

</div>

---

## 🙏 Acknowledgements

- 📚 [Microsoft Power BI Docs](https://learn.microsoft.com/en-us/power-bi/) — Official Power BI documentation
- 🧮 [DAX Guide](https://dax.guide/) — DAX function reference
- 🎓 [Microsoft Learn](https://learn.microsoft.com/en-us/training/powerplatform/power-bi) — Power BI learning paths
- 💬 [Power BI Community](https://community.fabric.microsoft.com/) — Problem-solving support

---

<div align="center">

---

*Made with ❤️ and ☕ using Power BI*

</div>
