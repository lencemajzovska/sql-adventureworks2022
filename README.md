# SQL AdventureWorks2022 – Data Analysis & Visualization

A project that explores and analyzes the **AdventureWorks2022** SQL Server database.  
The analysis combines **SQL queries** for data extraction with **Python** for statistical calculations and visualizations.

---

## Functionality

- Connects to the AdventureWorks2022 database using **SQLAlchemy**
- Extracts sales data grouped by sales territories
- Calculates:
  - **Average order value**
  - **95% confidence intervals (CI)**
  - **Comparison between top- and bottom-performing territories**
- Creates visualizations with **Seaborn** and **Matplotlib**
- Presents results in **interactive styled tables** in Jupyter Notebook

---

## Features

- **SQL + Python integration** for flexible analysis  
- **Statistical summaries** using NumPy & SciPy  
- **Visual insights** with clear bar charts and data tables  
- **Well-documented notebook** with comments explaining each step  

---

## Example Output

### Visualization – Average Order Value per Sales Territory
*(Example from the project)*  
![Example Chart](docs/example_plot.png)

### Styled Comparison Table
| Territory      | Avg Order Value (USD) | 95% CI (USD)         | Orders |
|----------------|-----------------------|----------------------|--------|
| Northwest      | 8,540.12               | [8,100.50; 8,980.00] |  122   |
| Southeast      | 4,320.45               | [4,100.20; 4,540.70] |  154   |

---

## Installation & Usage

1. **Clone the repository**
```bash
git clone https://github.com/lencemajzovska/sql-adventureworks2022.git

Developer
Lence Majzovska
Data Science Student, EC Utbildning 2025
