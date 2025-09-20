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

## Insights

- Crimes against women have **increased over the years**, indicating the need for stronger preventive measures and awareness programs.
- **Cruelty by Husband or Relatives** and **Assault on Women** are the most frequent crimes nationwide.
- Uttar Pradesh consistently shows **high numbers across multiple crime categories**, highlighting regional disparities.
- Certain crimes like **Dowry Deaths** and **Kidnapping/Abduction** show fluctuating trends, suggesting varying levels of enforcement and reporting over the years.
- Pie charts and bar plots reveal that **a few categories dominate the crime statistics**, emphasizing areas where policy interventions could have the greatest impact.

---

## Future Work

- Extend the analysis to include **post-2014 data** to study more recent trends.
- Perform **correlation analysis** between crime rates and socio-economic factors such as literacy, poverty, and urbanization.
- Develop **interactive dashboards** using Plotly, Power BI, or Tableau to allow dynamic exploration of crime trends by year, state, and category.
- Incorporate **predictive modeling** to forecast potential crime trends based on historical data.
- Compare **regional trends across different states and union territories** to identify high-risk areas and evaluate the effectiveness of interventions.


## How to Run

1. Clone the repository:  
```bash
git clone https://github.com/aryamandhindsa010/Women-Safety-Analysis.git
