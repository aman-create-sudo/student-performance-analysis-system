# student-performance-analysis-system
An object-oriented Python application for student performance assessment, CPI calculation, performance classification, risk diagnosis, and automated CSV reporting.
# 🎓 Student Performance Analytics System

**An Intelligent Academic & Sports Performance Evaluation Platform Built with Python**

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Project](https://img.shields.io/badge/Project-Data%20Analytics-purple)
![Architecture](https://img.shields.io/badge/Architecture-OOP-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Overview

The Student Performance Analytics System is a Python-based application designed to evaluate students' academic and sports performance using statistical computation and diagnostic analysis.

The system calculates academic percentages, evaluates sports performance, generates a Composite Performance Index (CPI), classifies student performance, identifies areas requiring support, and exports reports in CSV format.

## ✨ Key Features

- **Data Validation:** Checks student records, duplicate IDs, and score ranges.
- **Academic Analysis:** Calculates academic percentages and assigns grades.
- **Sports Evaluation:** Evaluates fitness, participation, and event performance.
- **CPI Calculation:** Combines academic and sports performance.
- **Performance Classification:** Categorizes students into performance tiers.
- **Diagnostic Analysis:** Identifies academic and sports-related support requirements.
- **Statistical Analysis:** Calculates cohort average CPI and standard deviation.
- **CSV Export:** Automatically generates student performance reports.

## 🧮 Performance Calculation

### Academic Percentage

Average of all academic subject scores.

### Sports Score

Sports Score = (0.40 × Fitness) + (0.35 × Participation) + (0.25 × Event Points)

### Composite Performance Index

CPI = (0.70 × Academic Percentage) + (0.30 × Sports Score)

## 🏆 Performance Categories

| Condition | Classification |
|---|---|
| Academic ≥ 85 and Sports ≥ 80 | Elite All-Rounder |
| Academic ≥ 85 | Academic Scholar |
| Sports ≥ 85 | Athletic Prodigy |
| CPI ≥ 60 | Consistent Performer |
| Otherwise | Development Required |

## 🛠️ Technologies Used

- Python 3
- Object-Oriented Programming (OOP)
- CSV Module
- Math Module
- Statistical Computation
- Data Validation

## 📂 Project Structure

```text
student-performance-analytics-system/
│
├── main.py
├── README.md
├── .gitignore
└── student_report.csv
```

## ⚙️ Installation & Execution

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/student-performance-analytics-system.git
```

**2. Navigate to the project directory**

```bash
cd student-performance-analytics-system
```

**3. Run the application**

```bash
python main.py
```

No external Python packages are required.

## 📊 Generated Output

The application displays:

- Student ID and name
- Academic percentage and grade
- Sports performance score
- Composite Performance Index
- Performance classification
- Diagnostic flags and interventions
- Overall cohort statistics

The system also exports a CSV file:

`student_report.csv`

## 🧠 Core Modules

| Class | Responsibility |
|---|---|
| DataManager | Data validation |
| StatisticalComputationEngine | Grades, scores and CPI |
| DiagnosticEngine | Risk identification and interventions |
| ReportExporter | Display and CSV export |
| PerformanceApp | Main application execution |

## 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Python classes and static methods
- Data structures and dictionaries
- Exception handling
- Mathematical computations
- Statistical analysis
- File handling and CSV generation
- Modular programming

## 👨‍💻 Author

**Aman Ranjan**

B.Tech Computer Science & Engineering Student

Interested in Python Development, Software Engineering, and Data Analytics.

---

⭐ If you find this project interesting, consider giving the repository a star!

**Built with Python | Learning Through Building**
