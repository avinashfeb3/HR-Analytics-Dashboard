# 📊 HR Analytics Dashboard — Power BI

## 🔍 Overview

This Power BI project provides a comprehensive **HR Analytics Dashboard** designed to help HR teams and business leaders monitor workforce health, analyze employee attrition, and make data-driven decisions. The dashboard consolidates key HR metrics into a single, interactive view with dynamic filtering by age group and department.

---

## 🎯 Key Metrics Tracked

| Metric | Value |
|---|---|
| Total Employees | 1,417 |
| Active Employees | 1,186 |
| Attrition Count | 231 |
| Attrition Rate | 16.3% |
| Average Age | 36.94 years |
| Average Experience | 7.04 years |

---

## 📌 Dashboard Features

### 1. 🏢 Attrition by Department
Donut chart breaking down employee attrition across departments:
- **Sales** — 84 (36%)
- **Operations** — 52 (23%)
- **Human Resources** — 43 (19%)
- **Administration** — 30 (13%)
- **IT**, **Marketing**, **Finance** — remaining share

### 2. 💰 Attrition by Salary Slab
Horizontal bar chart comparing employees who stayed vs. left across salary brackets:
- **6–10 LPA** — Highest headcount (399 employees)
- **0–3 LPA** — 299 employees
- **3–6 LPA** — 293 employees
- **10+ LPA** — 195 employees

### 3. 👔 Attrition by Job Role & Job Satisfaction
Matrix table cross-referencing job roles against satisfaction scores (1–4):
- Roles tracked: Healthcare Representative, Human Resources, Laboratory Technician, Manager, Manufacturing Director, Research Director, Research Scientist, Sales Executive
- Total attrition per role visible at a glance

### 4. 📅 Age Group Distribution
Bar chart showing employee count across age groups:
- **26–35** — 588 (largest group)
- **36–45** — 446
- **46–55** — 222
- **18–25** — 117
- **55+** — 44

### 5. ⚧ Attrition by Gender
Pie chart showing gender split in attrition:
- **Female** — 146 (63%)
- **Male** — 85 (36.8%)

### 6. 📈 Attrition Trend by Experience
Line chart displaying attrition patterns across total years of experience (0–40 years), helping identify high-risk experience bands.

### 7. 🏭 Department-wise Employee Count
Horizontal bar chart showing workforce distribution:
- Operations: 512 | Administration: 406 | Sales: 207 | IT: 166 | Marketing: 64 | Human Resources: 39 | Finance: 23

---

## 🔧 Filters & Slicers

- **Age Group Filter** — Toggle between: `18–25`, `26–35`, `36–45`, `46–55`, `55+`
- **Department Slicer** — Filter all visuals by department

---
![HR Analytics Dashboard](https://github.com/avinashfeb3/HR-Analytics-Dashboard/blob/main/HR%20Analytics%20Dashboard.png)

## 📁 Project Structure

```
HR-Analytics-Dashboard/
│
├── HR_Analytics_Dashboard.pbix     # Main Power BI file
├── HR_Analytics_Dashboard.png      # Dashboard screenshot
├── data/
│   └── hr_data.csv                 # Source dataset
├── README.md                       # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
- Windows OS (required for Power BI Desktop)

### Steps to Run
1. Clone or download this repository
2. Open `HR_Analytics_Dashboard.pbix` in Power BI Desktop
3. If prompted, update the data source path to your local `data/hr_data.csv.`
4. Click **Refresh** to load the latest data
5. Use the slicers and filters to explore the dashboard

---

## 📊 Data Source

The dataset used is a standard HR Analytics dataset containing employee-level information including:
- Demographics (age, gender)
- Job details (role, department, salary)
- Experience and tenure
- Attrition status
- Job satisfaction scores

> ⚠️ The data used in this project is for demonstration purposes only and does not represent real employee information.

---

## 💡 Insights & Takeaways

- The overall **attrition rate of 16.3%** is a critical metric to monitor — industry benchmarks typically sit between 10–15%.
- **Sales department** accounts for the highest attrition (36%), signaling potential issues with workload, compensation, or culture.
- Employees in the **6–10 LPA salary band** form the largest group — retention strategies here could have outsized impact.
- The **26–35 age group** is the largest workforce segment and also a high-attrition risk group — engagement programs targeting this cohort are recommended.
- **Low job satisfaction scores (1–2)** correlate with higher attrition in roles like Laboratory Technician and Sales Executive.

---

## 🛠️ Tools Used

- **Power BI Desktop** — Data modeling, DAX measures, and visualization
- **Microsoft Excel / CSV** — Data preparation
- **DAX** — Custom measures for attrition rate, averages, and conditional formatting

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

> ⭐ If you found this project helpful, please consider giving it a star on GitHub!
