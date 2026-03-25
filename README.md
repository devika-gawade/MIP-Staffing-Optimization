# ☕ Coffee Shop Staffing Optimizer
**Applying Mixed-Integer Programming (MIP) to Minimize Labor Costs & Align with Peak Demand**

## 📌 Project Overview
For small service businesses like cafés, labor typically represents 30-40% of total expenses. Managers often schedule based on intuition, leading to overstaffing during slow periods and understaffing during rushes. This project utilizes **Mixed-Integer Linear Programming** to generate cost-effective, demand-aligned schedules that comply with complex labor constraints.

## 🛠️ Tech Stack
* **Language:** Python (Google Colab)
* **Mathematical Approach:** Mixed-Integer Programming (MIP)
* **Optimization Goal:** Minimize total weekly wage expenditure while meeting 100% of staffing demand.

## 🧠 The Logic: Constraints & Variables
The power of this model lies in the constraints it satisfies simultaneously:
* **Staffing Demand:** Ensuring a minimum number of baristas are present for every hour of operation (9 AM - 6 PM).
* **Labor Compliance:** Managing maximum allowed hours per employee per week.
* **Wage Optimization:** Calculating costs based on individualized hourly rates ($18/hr - $25/hr).
* **Weekend Peak Logic:** Specifically handling increased demand during Saturday and Sunday morning shifts.

## 📊 Results & Impact
* **Total Weekly Cost:** Optimized to **$5,443.00** for an 8-person team.
* **Efficiency:** Automated a scheduling process that usually takes managers hours, delivering a compliant schedule in seconds.
* **Coverage:** Identified and minimized "Penalty Hours" where staffing demand could not be met due to current employee availability.

## 📉 Visualizing the Schedule
The repository includes automated visualizations (Matplotlib) that track:
1. **Weekly Hours Worked vs. Maximum Allowed:** Ensuring no employee is overworked.
2. **Staffing Density:** A heatmap/grid showing exactly how many baristas are on the floor for every hour of the week.

## 📁 Project Documents
* [📄 Presentation (PDF)](Cafe%20Scheduling%20Presentation.pdf) - A deep dive into the business benefits and results.
* [📓 Jupyter Notebook (.ipynb)](Coffee_Scheduling_solver.ipynb) - The Python model and solver logic.
