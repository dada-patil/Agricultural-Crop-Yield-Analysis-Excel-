# 🌾 Agricultural Crop Yield Analysis – Excel Dashboard

##  Project Overview

This project analyzes Indian agricultural crop yield data using Microsoft Excel.

The objective is to identify crop performance patterns across different states and districts and understand how factors such as irrigation, fertilizer usage, rainfall, soil type, temperature, season, and cultivated area relate to agricultural yield.

The final output is an interactive Excel dashboard containing KPIs, PivotTables, charts, and slicers.

---

##  Business Objectives

- Understand crop yield trends across states and districts.
- Identify high- and low-performing crops.
- Analyze the effect of irrigation on crop yield.
- Analyze fertilizer usage and crop performance.
- Study rainfall and temperature patterns.
- Compare agricultural performance across seasons.
- Create an interactive dashboard for agricultural monitoring.

---

##  Dataset

The dataset contains agricultural crop records with the following fields:

| Column | Description |
|---|---|
| Crop ID | Unique identifier for each crop entry |
| State | Indian state where the crop was cultivated |
| District | District of the state |
| Year | Year of observation |
| Season | Crop season |
| Crop Name | Name of the crop |
| Area (Hectares) | Cultivated area |
| Production (Tonnes) | Total crop production |
| Yield (Kg/Ha) | Crop yield |
| Irrigation Type | Type of irrigation |
| Fertilizer Used (Kg) | Fertilizer quantity |
| Rainfall (mm) | Rainfall received |
| Soil Type | Soil category |
| Temperature (Celsius) | Average temperature |

---

##  Dataset Summary

- Records: **500**
- Years: **2010–2022**
- States: **7**
- Districts: **21**
- Crops: **6**
- Seasons: **Kharif, Rabi, Zaid**
- Irrigation types: **4**
- Fertilizer types: **5**
- Soil types: **5**

---

##  Data Cleaning

The following data-cleaning activities were performed:

- Checked for duplicate records.
- Checked missing/blank values.
- Verified numerical columns.
- Checked state and district values.
- Checked crop and season categories.
- Verified yield values.
- Formatted the dataset as an Excel table.

---

## 🔄 Data Transformation

The project uses existing agricultural metrics and performs aggregation through PivotTables.

Important analysis metrics include:

### Total Production

```text
SUM(Production)
