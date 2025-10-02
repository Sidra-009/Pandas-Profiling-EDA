# ✨ Interactive EDA with YData Profiling

*💻 Exploratory Data Analysis (EDA) made simple and interactive using **YData Profiling**.*

---

## 🌟 About This Project

This repository demonstrates a **complete Exploratory Data Analysis (EDA)** using the **YData Profiling Report**.  
It helps data scientists quickly understand the dataset structure, statistics, correlations, and potential issues—all in **interactive HTML reports**.  

> *Recommended font for viewing: Times New Roman, with italics for emphasis.*

---

## 🔧 Why Use This Library?

- ⏱️ Automates the EDA process and saves hours of manual work.  
- 📊 Provides **interactive HTML reports** with a full dataset overview.  
- ⚠️ Highlights **missing values, correlations, and variable interactions**.  
- 🛠️ Useful for **data cleaning, feature selection, and dataset understanding**.

---

## 📄 About the Report

The **YData Profiling Report** includes:

### 📝 1. Overview
- ⚠️ **Alerts:** Potential issues in the dataset.  
- 🔁 **Reproduction:** Steps to reproduce analysis.  
- 📈 **Dataset statistics:** Quick summary of dataset size and structure.  

### 📊 2. Variables
- Summary statistics for each variable.  
- Type, unique values, min, max, mean, and more.  

### 🔄 3. Interactions
- Pairwise interactions between variables.  
- Helps identify patterns and relationships.  

### 📌 4. Correlations
- Displays numeric correlations.  
- Detects redundant or highly correlated features.  

### ❓ 5. Missing Values
- Counts and visualizes missing data.  
- Shows percentage of missing values per variable.  

### 🖼️ 6. Sample
- Displays a few sample rows.  
- Quick look at dataset content.  

---

## 📊 Dataset Statistics

| Metric | Value |
|--------|-------|
| 🧮 Number of variables | 5 |
| 📋 Number of observations | 400 |
| ❌ Missing cells | 0 |
| ❌ Missing cells (%) | 0.0% |
| 🔁 Duplicate rows | 0 |
| 🔁 Duplicate rows (%) | 0.0% |
| 💾 Total size in memory | 15.8 KiB |
| 📝 Average record size | 40.3 B |

**Variable Types:** Mixed (numeric & categorical)

---

## 🚀 How to Use

1️⃣ Install the library:

```bash
pip install pandas-profiling
2️⃣ Load your dataset and generate the report:

python
Copy code
import pandas as pd
from pandas_profiling import ProfileReport

# Load dataset
df = pd.read_csv("your_dataset.csv")

# Generate report
profile = ProfileReport(df, title="✨ Auraa - YData Profiling Report", explorative=True)

# Save as HTML
profile.to_file("Auraa_Report.html")
3️⃣ Open Report.html in your browser to explore interactively.
```

💡 Conclusion
The EDA repo helps data scientists:

⚡ Quickly understand datasets

🛡️ Detect issues and anomalies

🧩 Make informed preprocessing and modeling decisions

Using YData Profiling, you can save hours of manual analysis and get ready-to-use insights in seconds.

🔗 References
📚 YData Profiling Documentation

🐼 Pandas Library
