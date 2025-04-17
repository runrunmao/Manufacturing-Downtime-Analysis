# Manufacturing Downtime Analysis
Improving Production Efficiency at Wolf Cola

## Table of Contents
1. [Project Overview](#project-overview)
2. [Business Objective](#business-objective)
3. [Approach & Methodology](#approach--methodology)
   - [1. Data Processing & Efficiency Analysis](#1-data-processing--efficiency-analysis)
   - [2. Downtime Root Cause Analysis (Pareto Chart)](#2-downtime-root-cause-analysis-pareto-chart)
   - [3. Operator-Specific Downtime Breakdown](#3-operator-specific-downtime-breakdown)
4. [Key Findings](#key-findings)
5. [Recommendations](#recommendations)
6. [Visual Highlights](#visual-highlights)
7. [Tools & Skills Used](#tools--skills-used)


## Project Overview  
This project analyzes manufacturing downtime and operator efficiency for **Wolf Cola**, a soft drink company based in Philadelphia. The goal was to identify major causes of inefficiency, evaluate operator performance, and recommend data-driven solutions to reduce downtime and enhance productivity.


## Business Objective  
> Improve overall production line efficiency by identifying and addressing key causes of downtime and low operator performance.


## Approach & Methodology  

### 1. Data Processing & Efficiency Analysis  
- Imported raw production data and created a **Batch Time** column to measure actual production durations.  
- Used `VLOOKUP` to fetch **Minimum Batch Time** per product to calculate efficiency.  
- Computed operator efficiency:  
  \[
  \text{Efficiency} = \frac{\text{Minimum Batch Time}}{\text{Actual Batch Time}} \times 100
  \]  
- Visualized operator performance using a bar chart:  
  - **Mac** had the lowest efficiency at **61%**, below the overall average of **64%**.

### 2. Downtime Root Cause Analysis (Pareto Chart)  
- Aggregated total downtime minutes by category and sorted in descending order.  
- Created a **Pareto Chart** to visualize the top contributors.  
- Found that **80% of total downtime** came from just **5 factors**:  
  - Machine Adjustment  
  - Machine Failure  
  - Inventory Shortage  
  - Batch Change  
  - Batch Coding Error  

### 3. Operator-Specific Downtime Breakdown  
- Built a matrix mapping downtime by operator and downtime reason.  
- Found that **3 of the top 5 downtime categories were due to operator error**.  
- Notably, **Mac** had **130 minutes of downtime** from Batch Change alone.

---

## Key Findings  
- **Mac** is the lowest-performing operator and needs targeted support.  
- **Machine adjustment** is the #1 downtime factor across all operators.  
- Operator errors contribute significantly to downtime and must be addressed.

---

## Recommendations  
1. **Machine Adjustment Training** for all operators (addresses top downtime driver).  
2. **Specialized Batch Change Training** for Mac.  
3. **Preventive Maintenance Plan** and inventory audits to reduce machine failure and shortage issues.

---

## 📊 Visual Highlights  

<img width="853" alt="Manufacturing Downtime Dashboard" src="https://github.com/user-attachments/assets/b76c7a56-acf4-4d3e-8c9a-741bfcea1cd4" />


---

## 🛠 Tools & Skills Used  
- **Excel**: VLOOKUP, PivotTables, Pareto Chart  
- **Data Analysis**: Efficiency calculations, root cause analysis  
- **Data Visualization**: Bar Charts, Pareto Chart  
- **Decision-Making**: Operational recommendations based on data insights
