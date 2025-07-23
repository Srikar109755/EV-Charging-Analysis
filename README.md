# Electric Vehicle Charging Behavior Analysis

A data-driven analysis of electric vehicle (EV) charging patterns to uncover insights on cost, duration, station usage, energy consumption, and user behavior across various locations and vehicle models.

---

## Project Overview

This notebook explores and visualizes key behavioral trends in EV charging using a real-world dataset. By applying clustering techniques and insightful visualizations, the project aims to:

- Identify factors influencing charging cost and duration.
- Understand usage patterns by time of day and location.
- Evaluate energy consumption relative to vehicle distance driven.
- Compare behaviors across different vehicle models and charger types.

These insights can support smarter infrastructure planning, cost optimization, and personalized EV service offerings.

---

## Dataset Description

- **Filename:** `ev_charging_patterns.csv`
- **Attributes:**
  - Charging Duration (hours)
  - Charging Cost (USD)
  - Vehicle Model
  - Charger Type
  - Time of Day
  - Charging Station Location
  - Distance Driven (since last charge) (km)
  - Energy Consumed (kWh)

---

## Objectives

- Analyze the correlation between charging time and cost.
- Identify peak usage times across different station locations.
- Evaluate energy consumption efficiency by vehicle and distance.
- Explore user and charger-type influence on charging behaviors.

---

## Visualizations Summary

### 1. Charging Cost vs Charging Duration

Shows how cost scales with duration, grouped by vehicle and charger type.

![Charging Duration vs Cost](images/charging_cost_duration.png)

---

### 2. Time of Day Usage by Charging Station Location

Captures hourly usage patterns across different charging station locations.

![Station Usage](images/station_usage.png)

---

### 3. Energy Consumed vs Distance Driven

Highlights energy efficiency relative to distance driven since the last charge.

![Energy vs Distance](images/energy_vs_distance.png)

---

## Tools and Libraries

- **Python**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `sklearn.cluster.KMeans`
- Jupyter Notebook

---

## How to Run the Project

> Ensure Python and Jupyter Notebook are installed on your system.

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ev-charging-analysis.git
cd ev-charging-analysis
```
---
### 2. Install Required Libraries

```bash
pip install -r requirements.txt
```
---
### 3. Launch the Notebook

```bash
jupyter notebook EC22B1076_84.ipynb
```
---

## Author
Sai Srikar
B.Tech, Electronics & Communication Engineering


## Contact

LinkedIn: https://www.linkedin.com/in/sai-srikar-2b6a3624a/

Email: saisrikar109@gmail.com

