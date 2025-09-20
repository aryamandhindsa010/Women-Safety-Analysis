# Crime Analysis Against Women in India (2001–2014)

![Crime Analysis](https://img.shields.io/badge/Status-Completed-green) ![Python](https://img.shields.io/badge/Python-3.12-blue) ![Libraries](https://img.shields.io/badge/Libraries-Pandas%2C%20Matplotlib%2C%20Seaborn-orange)

## Project Overview

This project provides an **analytical exploration of crimes against women in India** from **2001 to 2014**, using publicly available crime datasets. The focus is on:  

- Total number of crimes across India  
- Year-wise trends  
- State-wise analysis, particularly highlighting **Uttar Pradesh**  
- Breakdown of crime categories such as Rape, Dowry Deaths, Kidnapping, and more  

The analysis uses **Python (Pandas, Matplotlib, Seaborn)** for data cleaning, aggregation, and visualization.

---

## Dataset

The project uses the following dataset:  

- **Source:** Government of India Crime Records / Publicly available CSV files  
- **Columns include:**  
  - `STATE/UT` – State or Union Territory  
  - `Year` – Year of the crime record  
  - `Rape`, `Dowry Deaths`, `Assault on Women`, etc. – Counts of each crime category  
  - `total_crimes` – Total number of crimes recorded  

---

## Key Features & Analysis

1. **Year-wise Crime Trends**  
   - Visualized total crimes per year using bar plots  
   - Observed increasing trends in certain crime categories

2. **Category-wise Crime Distribution**  
   - Top crimes across India visualized with pie charts  
   - Highlights most prevalent crimes such as `Cruelty by Husband or Relatives`

3. **State-wise Analysis**  
   - Aggregated data by state using `groupby`  
   - Visualizations show which states have the highest occurrences of specific crimes

4. **Uttar Pradesh Focus**  
   - Total count of each crime in Uttar Pradesh  
   - Top crime categories highlighted using bar and pie charts  

---

## Tools & Libraries

- **Python 3.12**  
- **Pandas** – Data cleaning, aggregation  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive analysis  

---

## How to Run

1. Clone the repository:  
```bash
git clone https://github.com/aryamandhindsa010/Women-Safety-Analysis.git
