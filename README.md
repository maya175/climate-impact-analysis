# Climate Change Impact Analysis

**By Mya Thet Mon**

## Overview

This project analyzes the impact of climate change in Singapore using datasets on:

* CO₂ emissions
* Weather patterns (temperature, rainfall, humidity)
* Energy consumption

The goal is to identify trends, relationships, and key factors contributing to environmental changes.

---

## 📂 Datasets Used

1. **Fossil CO₂ Emissions of Singapore**
   Source: https://www.worldometers.info/co2-emissions/singapore-co2-emissions/

2. **Weather Data (Temperature, Humidity, Rainfall)**
   Source: https://data.gov.sg/datasets/d_19c6ce4509e0bddde2062298aa8ce9ab/view

3. **Energy Consumption by Sector and Type**
   Source: https://data.gov.sg/datasets/d_70d247965470ea125814eee0171c1dd1/view

---

## Technologies Used

* Python
* Pandas (data processing)
* NumPy (numerical analysis)
* Matplotlib (data visualization)

---

## Key Analysis Performed

### 1. CO₂ Emissions Trend

* CO₂ emissions have **increased over time**
* Per capita emissions:

  * Peaked around **1995**
  * Then **declined and stabilized**

### 2. Population vs CO₂ Emissions

* Positive correlation observed
* Higher population → higher emissions

### 3. Temperature vs Humidity

* Higher temperature → lower relative humidity
* Shows inverse relationship

### 4. Energy Consumption vs CO₂ Emissions

* Strong positive correlation
* More energy usage → more emissions

### 5. Sector Variability (Boxplot)

* **Industry sector** = highest variation
* Followed by transport
* Households = most stable

### 6. Energy Distribution (2021)

* Industry dominates energy usage
* Transport is second
* Households consume ~5%

### 7. Energy Type Analysis (2021)

* Petroleum = highest
* Electricity = second
* Natural gas = third
* Coal = minimal

---

## Visualizations Included

* Line charts (trends over time)
* Scatter plots (correlations)
* Box plots (variability)
* Pie charts (distribution)
* Bar charts (comparisons)

---

## How to Run

1. Install required libraries:

```bash
pip install pandas numpy matplotlib
```

2. Place datasets in the same folder as the script

3. Run the Python file:

```bash
python your_script_name.py
```

---

## 📁 File Structure

```
├── FossilCarbonDioxide(CO2)EmissionsOfSingapore.csv
├── AirTemperatureAndSunshineRelativeHumidityAndRainfallAnnual.csv
├── TotalFinalEnergyConsumptionByEnergyTypeAndSectorAnnual.csv
├── analysis.py / notebook.ipynb
└── README.md
```

---

## Insights & Conclusion

* Climate change in Singapore is closely linked to **energy consumption and population growth**
* **Industrial activities** are the main driver of energy use
* Reducing fossil fuel dependency is key to lowering emissions

---

## Future Improvements

* Add predictive models (machine learning)
* Include more recent datasets
* Build interactive dashboards (Power BI / Tableau)

---

## Contact

**Mya Thet Mon**
Singapore Polytechnic – Computer Engineering
