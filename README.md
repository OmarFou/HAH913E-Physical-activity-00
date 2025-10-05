# HAH913E-Physical-activity-00
This repository is used to do an assignment about Physical activity.

# HAH913E Physical Activity – ENMO Assignment
This repository contains my solution for the ENMO assignment.

## Project Description
The goal of this project is to compute and visualize **ENMO (Euclidean Norm Minus One)** values from raw accelerometer data collected by an **Axivity AX3** wrist-worn sensor.

The notebook:
- Calculates ENMO (`max(0, sqrt(x² + y² + z²) - 1)`).
- Integrates ENMO over epochs of **10 s**, **30 s**, and **60 s**.
- Produces plots comparing ENMO intensity at different epoch lengths.
- Discusses how epoch duration affects signal smoothing.

## Files
- `HAH913E_ENMO_Assignment.ipynb` → Jupyter notebook with code and explanations.
- `0_z.csv` → Raw accelerometer dataset (t, x, y, z).
- Output plots (PNG files) → Visualize integrated ENMO values.

