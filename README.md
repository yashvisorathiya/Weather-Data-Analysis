# Weather Data Visualisation

## Objective
Explore and visualise weather data to understand relationships between key meteorological variables such as temperature, humidity, wind speed, dew point, and air pollution index across different weather types.

## Dataset
- **File:** `Test.csv`
- **Columns include:** `date_time`, `temperature`, `humidity`, `wind_speed`, `wind_direction`, `dew_point`, `air_pollution_index`, `rain_p_h`, `snow_p_h`, `clouds_all`, `weather_type`, `weather_description`, `visibility_in_miles`, `is_holiday`

## Tools & Libraries
- `pandas` — data loading and exploration
- `seaborn` — data visualisation

## What the Notebook Covers

### Data Exploration
- Loaded and inspected the dataset using `.head()`, `.shape()`, `.info()`, and `.nunique()`

### Visualisations
- **Bar Plot** — average temperature across humidity levels, broken down by weather type
- **Histogram** — distribution of humidity and temperature (with KDE curve)
- **Joint Plot** — relationship between humidity and temperature (scatter, hex, and KDE versions)
- **Pair Plot** — pairwise relationships between temperature, humidity, and dew point
- **Strip Plot** — temperature spread across weather types
- **Swarm Plot** — dew point vs temperature coloured by weather type
- **Box Plot** — temperature distribution across humidity levels by weather type
- **Count Plot** — frequency of each weather type in the dataset
- **Point Plot** — average temperature across humidity levels by weather type
- **Violin Plot** — temperature distribution across wind speed levels
- **Heatmap** — correlation between temperature, humidity, and air pollution index

## Files
- `Weather Data Visualisation.ipynb` — main notebook with all code
- `Weather Data Visualisation.html` — exported HTML version of the notebook
- `Test.csv` — dataset used for analysis
