 Machine Failure Analysis
##  Overview
This repository contains the coursework for **Week 2 Lab 23**, focusing on analyzing machine performance data to detect and understand failure patterns.  
The project applies Python-based data analysis to evaluate operating hours, temperature, vibration levels, pressure, humidity, and error history, with the goal of identifying key indicators of machine failure and supporting predictive maintenance.

---

##  Objectives
- Inspect and summarize the machine dataset  
- Compare average temperature, vibration levels, and pressure by failure status  
- Visualize machine performance trends with clear plots and charts  
- Apply analytical thinking to predictive maintenance scenarios  

---

##  Tools & Libraries Used
- **Python 3**  
- **Pandas** – for data handling and grouped statistical analysis  
- **Matplotlib** – for visualizations (bar charts, plots)  

---

##  Repository Structure

week2-lab23/ │ ├── lab23.py # Python script with analysis code ├── README.md # Documentation for the lab └── data/ # (Optional) Folder for datasets if needed

---

##  How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/week2-lab23.git

Navigate into the project folder:
 cd week2-lab23


Run the Python script:
 python lab23.py



Sample Insights
Temperature by Failure Status:


Machines with failure → ~90.75 °C average
Machines without failure → ~67.50 °C average
Vibration Level by Failure Status:


Machines with failure → ~4.89 average
Machines without failure → ~2.25 average
Pressure by Failure Status:


Machines with failure → ~134.6 psi average
Machines without failure → ~96.0 psi average

 Learning Outcomes
Practical application of Python data analysis tools
Understanding how machine parameters affect failure likelihood
Building informative visualizations for predictive maintenance decision-making

 Future Improvements
Add larger and more diverse datasets for deeper analysis
Incorporate machine learning models to predict failure probability
Explore optimization techniques for maintenance scheduling
Enhance visualizations with interactive dashboards (e.g., Plotly, Dash)

 Author
Harshita
