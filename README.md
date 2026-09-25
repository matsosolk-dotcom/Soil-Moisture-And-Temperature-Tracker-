# Soil Moisture and Temperature Tracker

## Purpose / Problem Solved
Monitors plot-level soil health metrics by processing automated soil moisture and temperature readings to support precision agricultural management and soil health tracking.

## Key Nodes & Configuration
* **Trigger:** Receives field sensor transmissions on a scheduled interval.
* **Data Transformation Nodes:** Parses temperature (°C) and moisture percentage values.
* **Database / Log Sync Nodes:** Integrates records into central field-plot database tables.
* **Alert / Display Node:** Flags environmental metrics outside optimal crop ranges.

## Impact & Results
Successfully automates plot data ingestion, ensuring reliable, continuous soil health tracking for agricultural planning.
