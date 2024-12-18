# NASA Battery Dataset Analysis

This project explores the NASA Battery Dataset, which contains data about Li-ion battery behavior under different operational conditions. The dataset includes information from charge, discharge, and impedance measurements taken at various temperatures over multiple cycles, providing insight into battery aging.

## Overview

The project performs the following tasks:
1. **Data Preprocessing:** Clean and format the raw dataset.
2. **Data Analysis:** Investigate how battery parameters (Battery Impedance, Re, Rct) change over time during charge/discharge cycles.
3. **Visualization:** Generate plots using Plotly to visualize battery parameter changes as the battery ages.

## Dataset Information

The dataset contains multiple columns, including:
- **start_time:** Timestamp of the measurement.
- **ambient_temperature:** The temperature during measurement.
- **Re:** Electrolyte resistance (Ohms).
- **Rct:** Charge transfer resistance (Ohms).
- **type:** Type of measurement (charge, discharge, impedance).
- **battery_id:** Unique identifier for the battery.

The experiment runs until the batteries reach end-of-life (EOL).


