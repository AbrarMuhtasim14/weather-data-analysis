# Weather Data Analysis with Python

**Project from:** *13 Python Data Analytics Real World Hands-on Projects* (Udemy)  
**Dataset:** `Project 1 - Weather Dataset.csv` – Hourly weather records for **2012**

---

## Project Overview
This project analyzes **time-series weather data** recorded hourly throughout **2012** using **Pandas**. The dataset includes key meteorological variables such as temperature, humidity, wind speed, visibility, pressure, and weather conditions.

---

## Dataset Columns
| Column               | Description |
|----------------------|-----------|
| `Date/Time`          | Timestamp (e.g., `1/1/2012 0:00`) |
| `Temp_C`             | Temperature in °C |
| `Dew Point Temp_C`   | Dew point temperature in °C |
| `Rel Hum_%`          | Relative humidity (%) |
| `Wind Speed_km/h`    | Wind speed in km/h |
| `Visibility_km`      | Visibility distance in km |
| `Press_kPa`          | Atmospheric pressure in kPa |
| `Weather Condition`  | Description (e.g., Clear, Fog, Snow) |

---

## Key Analysis Performed
- Loaded and explored hourly weather data
- Filtered records using **complex conditions**:
  > `(Clear weather AND humidity > 50%) OR (visibility > 40 km)`
- Found **2,921** instances meeting the criteria

---

## Tools & Libraries
```python
pandas

```

### Insights Gained

- **Clear skies with high visibility (>40 km)** often occur even with **moderate humidity (>50%)**  
- **Visibility is strongly influenced** by **fog, snow, and precipitation**  
- **Wind speed and temperature show seasonal patterns**  
- **Useful for weather forecasting, climate studies, and environmental monitoring**
