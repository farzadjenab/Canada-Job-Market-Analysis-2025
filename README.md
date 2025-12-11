# 📊 Canada Job Market Analysis 2025

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)](https://pandas.pydata.org)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?style=flat)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()

> **A comprehensive exploratory data analysis (EDA) of the Canadian job market, featuring salary insights, industry trends, regional comparisons, and a deep-dive into Toronto's employment landscape.**

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Dataset](#-dataset)
- [Features](#-features)
- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Analysis Highlights](#-analysis-highlights)
- [Visualizations](#-visualizations)
- [Toronto Deep Dive](#-toronto-deep-dive)
- [Key Findings](#-key-findings)
- [Technologies Used](#-technologies-used)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 Overview

This project provides a **step-by-step exploratory data analysis** of the Canadian job market using real-world data. Designed for **junior data analysts**, the analysis avoids complex techniques while delivering actionable insights through:

- 📈 **Descriptive Statistics**
- 🎨 **Data Visualizations**
- 🏙️ **Regional Comparisons**
- 💰 **Salary Analysis**
- 📊 **Interactive Dashboards**

---

## 📁 Dataset

| Attribute | Details |
|-----------|---------|
| **File Name** | `Job Market Canada.csv` |
| **Total Records** | 30,000+ job postings |
| **Time Period** | 2025 |
| **Geographic Coverage** | All Canadian provinces |
| **Key Variables** | 40+ columns |

### 📌 Key Columns

| Column | Description |
|--------|-------------|
| `job_title` | Position name (15 unique roles) |
| `industry` | Business sector (10+ industries) |
| `salary_median_cad` | Median salary in CAD |
| `experience_level` | Entry / Mid / Senior |
| `city` | Job location city |
| `region` | Canadian province |
| `remote_availability` | Yes / No |
| `hiring_trend` | Up / Stable / Down |
| `number_of_openings` | Available positions |
| `demand_index` | Market demand score (0-100) |

---

## ✨ Features

### 🔍 Data Exploration
- [x] Data loading and initial inspection
- [x] Missing values analysis
- [x] Duplicate detection
- [x] Data type verification

### 📊 Statistical Analysis
- [x] Descriptive statistics for numerical columns
- [x] Categorical variable distribution
- [x] Correlation analysis with heatmaps

### 💰 Salary Analysis
- [x] Salary distribution by job title
- [x] Salary comparison by experience level
- [x] Regional salary variations
- [x] Industry-wise salary breakdown

### 📈 Trend Analysis
- [x] Hiring trend visualization
- [x] Seasonal job posting patterns
- [x] Remote work availability rates

### 🏙️ Toronto Analysis
- [x] Toronto vs Canada comparison
- [x] City-specific salary insights
- [x] Industry distribution in Toronto
- [x] Experience level breakdown

### 🎨 Dashboards
- [x] Multi-panel overview dashboard
- [x] Salary-focused dashboard
- [x] Comparative analysis charts

---

## 🚀 Installation

### Prerequisites
bash
Python 3.8+
Jupyter Notebook / JupyterLab

### Setup Instructions

1. **Clone the repository**
bash
git clone https://github.com/yourusername/canada-job-market-analysis.git
cd canada-job-market-analysis

2. **Create virtual environment**
bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install dependencies**
bash
pip install -r requirements.txt

4. **Launch Jupyter Notebook**
bash
jupyter notebook

### 📦 Requirements

text
pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
seaborn>=0.12.0
jupyter>=1.0.0

---

## 📂 Project Structure


canada-job-market-analysis/
│
├── 📁 data/
│   └── Job Market Canada.csv
│
├── 📁 notebooks/
│   └── Canada_Job_Market_Analysis.ipynb
│
├── 📁 images/
│   ├── dashboard_overview.png
│   ├── salary_distribution.png
│   └── toronto_comparison.png
│
├── 📁 reports/
│   └── analysis_summary.pdf
│
├── 📄 README.md
├── 📄 requirements.txt
└── 📄 LICENSE

---

## 📊 Analysis Highlights

### 1️⃣ Data Overview

python
# Dataset dimensions
Total Records: 30,000+
Total Columns: 43
Missing Values: Minimal
Duplicates: None detected

### 2️⃣ Salary Statistics

| Metric | Value (CAD) |
|--------|-------------|
| **Mean Salary** | ~$85,000 |
| **Median Salary** | ~$80,000 |
| **Min Salary** | $27,000 |
| **Max Salary** | $270,000+ |

### 3️⃣ Top Paying Jobs

| Rank | Job Title | Avg Salary (CAD) |
|------|-----------|------------------|
| 🥇 | DevOps Engineer | $130,000+ |
| 🥈 | Product Manager | $120,000+ |
| 🥉 | Marketing Manager | $110,000+ |

### 4️⃣ Experience Impact


Entry Level  →  ~$65,000
Mid Level    →  ~$85,000
Senior Level →  ~$115,000

---

## 🎨 Visualizations

### 📊 Overview Dashboard


┌─────────────────────────────────────────────────────────┐
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐     │
│  │ Top Jobs    │  │ Exp Salary  │  │ Hire Trend  │     │
│  │ Bar Chart   │  │ Line Chart  │  │ Pie Chart   │     │
│  └─────────────┘  └─────────────┘  └─────────────┘     │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐     │
│  │ Industry $  │  │ Remote %    │  │ Seasonal    │     │
│  │ Horizontal  │  │ Pie Chart   │  │ Bar Chart   │     │
│  └─────────────┘  └─────────────┘  └─────────────┘     │
└─────────────────────────────────────────────────────────┘

### 📈 Visualization Types Used

| Chart Type | Purpose |
|------------|---------|
| 📊 Bar Charts | Job & industry distribution |
| 🥧 Pie Charts | Hiring trends, remote availability |
| 📈 Line Charts | Salary by experience progression |
| 📦 Box Plots | Salary range & outliers |
| 🔥 Heatmaps | Correlation matrix |
| 📉 Histograms | Salary distribution |

---

## 🏙️ Toronto Deep Dive

### 🔍 Toronto vs Canada Comparison

| Metric | Toronto | Canada | Difference |
|--------|---------|--------|------------|
| **Avg Salary** | $89,000+ | $85,000 | +$4,000 |
| **Remote Jobs** | ~51% | ~49% | +2% |
| **"Up" Hiring** | ~48% | ~45% | +3% |
| **Market Share** | ~7% | 100% | - |

### 🏆 Toronto Advantages

- ✅ **Higher salaries** across most job titles
- ✅ **More remote opportunities** in tech sector
- ✅ **Stronger hiring momentum** in IT & Services
- ✅ **Diverse industry mix** with tech dominance

### 📊 Toronto Industry Focus


IT & Technology    ████████████  35%
Business Services  ████████      22%
Finance            ██████        18%
Marketing          █████         15%
Others             ███           10%

---

## 🔑 Key Findings

### 💡 Major Insights

> 1. **Salary Growth**: Senior roles earn **75%+ more** than entry-level positions

> 2. **Remote Work**: Nearly **50% of jobs** offer remote flexibility

> 3. **Hiring Trends**: **45%+ jobs** show upward hiring momentum

> 4. **Top Industries**: IT, Healthcare, and Finance lead in job openings

> 5. **Geographic Premium**: Major cities (Toronto, Vancouver) pay **5-10% more**

### 📌 Recommendations

| For Job Seekers | For Employers |
|-----------------|---------------|
| 🎯 Target Senior DevOps roles | 📊 Competitive salaries needed |
| 🏙️ Consider Toronto/Vancouver | 🖥️ Remote options attract talent |
| 💻 Build IT/Tech skills | 📈 IT sector shows highest demand |
| 📚 Higher education = higher pay | 🎓 Education requirements flexible |

---

## 🛠️ Technologies Used

### Languages & Libraries

| Technology | Version | Purpose |
|------------|---------|---------|
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) | 3.8+ | Core programming |
| ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white) | 2.0+ | Data manipulation |
| ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white) | 1.24+ | Numerical operations |
| ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557c?style=flat) | 3.7+ | Static visualizations |
| ![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?style=flat) | 0.12+ | Statistical graphics |
| ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) | 1.0+ | Interactive notebooks |

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch
   
bash
   git checkout -b feature/AmazingFeature
3. Commit your changes

bash
   git commit -m 'Add AmazingFeature'
4. Push to branch

bash
   git push origin feature/AmazingFeature
5. Open a Pull Request
### 📝 Guidelines
- Follow PEP 8 style guide
- Add comments to code blocks
- Update README for new features
- Include sample outputs

## 📄 License
This project is licensed under the MIT License.

MIT License

Copyright © 2025

Permission is hereby granted, free of charge, to any person obtaining a copy

of this software and associated documentation files (the “Software”), to deal

in the Software without restriction…

## 📬 Contact
|Platform |	Link |
|📧 Email |	jenabfarzad@yahoo.com |
|💼 LinkedIn |	farzadjenab |
|🐙 GitHub	| @farzadjenab |
## ⭐ Acknowledgments
- 📊 Dataset sourced from Canadian job market aggregators
- 🎨 Visualization inspiration from data science community
- 📚 Analysis methodology based on EDA best practices

--- 

<div align="center">

**⭐ If you found this project helpful, please give it a star! ⭐**

[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)]()
[![Python](https://img.shields.io/badge/Powered%20by-Python-blue.svg)]()

</div>
