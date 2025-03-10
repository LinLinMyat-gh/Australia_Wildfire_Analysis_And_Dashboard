# Australia Wildfire Analysis & Dashboard

## Overview

This project analyzes historical wildfire data in Australia and presents insights through an interactive dashboard. The analysis covers trends, patterns, and key factors contributing to wildfires, helping in better understanding and mitigation strategies.

## Dataset Variables

- **Region**: The 7 regions in Australia.
- **Date**: UTC timestamp providing the data for 24 hours ahead.
- **Estimated_fire_area**: Daily sum of estimated fire area for presumed vegetation fires with a confidence > 75%, measured in km² for each region.
- **Mean_estimated_fire_brightness**: Daily mean of estimated fire brightness for presumed vegetation fires with a confidence > 75%, measured in Kelvin.
- **Mean_estimated_fire_radiative_power**: Daily mean of estimated radiative power for presumed vegetation fires with a confidence > 75%, measured in megawatts for each region.
- **Mean_confidence**: Daily mean of confidence for presumed vegetation fires with a confidence > 75%.
- **Std_confidence**: Standard deviation of estimated fire radiative power, measured in megawatts.
- **Var_confidence**: Variance of estimated fire radiative power, measured in megawatts.
- **Count**: Daily number of pixels for presumed vegetation fires with a confidence > 75% for each region.
- **Replaced**: Indicates whether the data has been replaced with standard quality data when available (typically with a 2-3 month lag). Replaced data has slightly higher quality in terms of locations.


---

## Files in This Repository

- **`Australia_Wildfire_Analysis.ipynb`**  
  A Jupyter Notebook that performs data cleaning, exploratory data analysis (EDA), and visualization of wildfire trends.

- **`Australia_Wildfire_Dashboard.ipynb`**  
  A Jupyter Notebook that creates an interactive dashboard to visualize wildfire data and trends.

---

## Key Features

- **Exploratory Data Analysis (EDA)**  
  Visualizing wildfire occurrences, severity, and geographical distribution.

- **Interactive Dashboard**  
  A user-friendly dashboard for stakeholders to interact with wildfire data.

---

## Technologies Used

- **Python**
- **Pandas**
- **Matplotlib & Seaborn**
- **Plotly & Dash**
- **Jupyter Notebook**

---

