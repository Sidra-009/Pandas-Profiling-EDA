# 🌟 EDA with YData Profiling

*Exploratory Data Analysis (EDA) made simple and interactive using **YData Profiling** (pandas-profiling).*

---

## 📌 About 

This repository demonstrates a detailed **Exploratory Data Analysis (EDA)** using the **YData Profiling Report**.  
It provides **automatic insights** into datasets and helps data scientists quickly understand the data structure, statistics, correlations, and potential issues.

> *Recommended font for viewing documentation: Times New Roman (italic for emphasis where needed).*

---

## 🛠 Why Use This Library?

- Automates the EDA process, saving time on manual analysis.
- Provides **interactive HTML reports** with a complete overview of datasets.
- Highlights **missing values, correlations, and variable interactions**.
- Useful for **data cleaning, feature selection, and initial dataset understanding**.

---

## 📊 About the Report

The **YData Profiling Report** consists of several sections:

### **1. Overview**
- **Alerts:** Shows potential issues in the dataset.  
- **Reproduction:** Steps to reproduce the analysis.  
- **Dataset statistics:** Summarizes the dataset structure.

### **2. Variables**
- Summary statistics for each variable.
- Includes type, unique values, mean, min, max, and more.

### **3. Interactions**
- Shows pairwise interactions between variables.
- Helps identify potential relationships and patterns.

### **4. Correlations**
- Displays correlations between numeric variables.
- Detects redundant or highly correlated features.

### **5. Missing Values**
- Counts and visualizes missing data.
- Provides percentage of missing values per variable.

### **6. Sample**
- Displays a few sample rows from the dataset.
- Useful for quick data inspection.

---

## 📈 Dataset Statistics

| Metric | Value |
|--------|-------|
| Number of variables | 5 |
| Number of observations | 400 |
| Missing cells | 0 |
| Missing cells (%) | 0.0% |
| Duplicate rows | 0 |
| Duplicate rows (%) | 0.0% |
| Total size in memory | 15.8 KiB |
| Average record size | 40.3 B |

**Variable Types:** Mixed (numeric, categorical as per dataset)

---

## 🚀 How to Use

1. Install the required library:

```bash
pip install pandas-profiling
Load your dataset and generate the report:

python
Copy code
import pandas as pd
from pandas_profiling import ProfileReport


# Load dataset
df = pd.read_csv("your_dataset.csv")

# Generate report
profile = ProfileReport(df, title="Auraa - YData Profiling Report", explorative=True)

# Save as HTML
profile.to_file("Auraa_Report.html")
Open Auraa_Report.html in your browser to explore all sections interactively.
```

💡 Conclusion
The EDA repo helps data scientists quickly understand datasets, identify issues, and make informed decisions for preprocessing and modeling.
Using YData Profiling, you can save hours of manual analysis and get ready-to-use insights.

🔗 References
YData Profiling Documentation

Pandas Library
