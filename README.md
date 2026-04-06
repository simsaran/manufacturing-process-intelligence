# 🏭 Manufacturing Process Intelligence Platform

> **Interactive DMAIC continuous improvement platform for food packaging operations**

🔗 **[Live Demo](YOUR_STACKBLITZ_URL_HERE)** | 📊 **Power BI Dashboard** (screenshots below) | 📓 **[Python Notebook](YOUR_COLAB_LINK_HERE)**

---

## 🎯 Executive Summary

A food packaging plant is experiencing rising defect rates (4.2% vs 2.0% target) and declining OEE (64% vs 85% world class). Night shift performance lags day shift by 18 percentage points. Annual cost of poor quality: **$312K**.

This project applies the **DMAIC methodology** (Lean Six Sigma) to identify root causes, design experiments, implement solutions, and establish control plans — projecting **$312K annual savings** through 57% defect reduction and 18-point OEE improvement.

---

## 📊 Key Results

| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| OEE | 64.2% | 82.4% | +18.2 pts |
| Defect Rate | 4.2% | 1.8% | -57% |
| Downtime | 22 min/shift | 13 min/shift | -41% |
| COPQ | $312K/year | $125K/year | -$187K |

---

## 🔧 Technical Skills Demonstrated

| Skill | Where It Appears |
|-------|-----------------|
| Statistical Process Control (SPC) | Tab 2 — X̄ and R control charts with UCL/LCL |
| Process Capability (Cp/Cpk) | Tab 2 — Distribution analysis with spec limits |
| OEE Calculation | Tab 2 — Interactive calculator (Availability × Performance × Quality) |
| Pareto Analysis | Tab 3 — 80/20 defect prioritization by count and cost |
| Ishikawa (Fishbone) Diagram | Tab 3 — 6M root cause categories (Man, Machine, Method, Material, Measurement, Environment) |
| 5 Whys Analysis | Tab 3 — Interactive drill-down to root cause |
| Correlation Analysis | Tab 3 — Variable relationship heatmap |
| Design of Experiments (DOE) | Tab 4 — 2³ factorial design with main effects plot |
| FMEA (Risk Analysis) | Tab 5 — Failure modes with Severity, Occurrence, Detection, RPN scoring |
| Control Plans | Tab 5 — Parameter monitoring specifications with reaction plans |
| Standard Operating Procedures | Tab 5 — Interactive SOP viewer |
| Value Stream Mapping | Tab 1 — VA/NVA time analysis across 7 process stages |
| DMAIC Framework | Entire project follows Define → Measure → Analyze → Improve → Control |
| Data Visualization (Power BI) | Companion dashboard with KPI cards, trend charts, and breakdowns |
| Python (Pandas, NumPy, Matplotlib) | Data generation and statistical analysis notebook |
| React / JavaScript | Interactive web platform with 6 tabs |

---

## 🏗️ DMAIC Methodology

### Phase 1: Define
- **Problem Charter** with clear problem statement, goal, scope, and projected savings
- **Value Stream Map** showing 7 process stages with value-add vs non-value-add time analysis
- Identified packaging & sealing stage as source of 56% of defects

### Phase 2: Measure
- **SPC Control Charts** (X̄ and R) for fill weight, seal strength, and line speed
- **Process Capability Analysis** with Cp and Cpk calculations against spec limits
- **OEE Baseline**: 64.2% overall, with Night shift at 58.1% (18pts below Day shift)
- **KPI Dashboard** tracking defect rate (4.2%), average downtime (22 min/shift), COPQ ($312K/yr)

### Phase 3: Analyze
- **Pareto Analysis** revealed top 2 defects (Seal Failure + Underfill) account for 56% of all defects
- **Ishikawa Diagram** with 24 potential causes across 6 categories
- **5 Whys** drill-down traced seal failures to lack of condition-based preventive maintenance
- **Correlation Analysis** identified relationships between temperature, humidity, and defect rates

### Phase 4: Improve
- **2³ Factorial DOE** testing seal temperature, line speed, and film thickness
- Optimal settings identified: 190°C seal temp, 110 u/min speed, 0.12mm film (Run #6: 18 defects, 98.2% yield)
- **Impact vs Effort Matrix** prioritizing 6 solutions by feasibility
- **Savings Calculator** projecting $312K annual savings at 57% defect reduction and 40% downtime reduction

### Phase 5: Control
- **FMEA Table** with RPN scoring — seal bar temperature drift identified as highest risk (RPN: 280)
- **Control Plan** for 5 critical parameters with specs, measurement methods, frequency, and reaction plans
- **Standard Operating Procedures** for seal bar calibration and mid-shift weight checks
- **Before/After Validation** confirming OEE improvement from 64.2% → 82.4%

---

## 📸 Screenshots

### Interactive DMAIC Platform
*(Add screenshots of each tab here)*

### Power BI Dashboard
*(Add Power BI dashboard screenshot here)*

---

## 🛠️ Tech Stack

- **Frontend:** React, Recharts, D3.js
- **Data Analysis:** Python, Pandas, NumPy, Matplotlib, Seaborn
- **Business Intelligence:** Microsoft Power BI
- **Statistical Methods:** SPC, DOE, FMEA, Process Capability
- **Methodologies:** DMAIC, Lean Six Sigma, Value Stream Mapping
- **Hosting:** StackBlitz
- **Version Control:** Git / GitHub

---

## 📁 Repository Structure

```
manufacturing-process-intelligence/
├── src/
│   └── App.js                     # Interactive DMAIC platform (React)
├── notebooks/
│   └── data_generator.ipynb       # Python data generation & analysis
├── data/
│   └── production_data.csv        # Simulated production dataset
├── docs/
│   ├── screenshots/               # Dashboard screenshots
│   └── powerbi_dashboard.pdf      # Power BI export
├── public/
│   └── index.html                 # Entry point
├── package.json
└── README.md                      # This file
```

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```
   git clone https://github.com/YOUR_USERNAME/manufacturing-process-intelligence.git
   ```
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm start
   ```
4. Open http://localhost:3000 in your browser

---

## 👤 About

Built by **Simran** as a process improvement portfolio project demonstrating end-to-end DMAIC methodology with technical implementation.

**Bachelor of Science** | University of Waterloo | 2026

**Contact:** [LinkedIn](YOUR_LINKEDIN_URL) | [GitHub](https://github.com/YOUR_USERNAME)

---

*This project demonstrates proficiency in Lean Six Sigma methodology, statistical process control, data analysis, and dashboard development — core competencies for Process Improvement, Business Analyst, and Operations Analyst roles.*
