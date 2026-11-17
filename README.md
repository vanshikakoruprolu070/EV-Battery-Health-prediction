# EV Battery Health Prediction Using Machine Learning

A machine learning regression project that predicts the State of Health (SoH) of a lithium-ion battery using recorded battery measurements.

## Dataset

**EV Lithium Ion Battery State of Health Dataset**

- Source: Mendeley Data
- Dataset link: [https://data.mendeley.com/datasets/7ctkcfnsdw/2]
- Number of labelled cycles: 168
- Battery type: Lithium-ion

## Project Status

work in progress

## Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Flask (planned for backend development)

## Limitations

- Uses recorded battery data rather than live EV data.
- Does not directly connect to an EV, scooter, or Battery Management System (BMS).
- The dataset contains measurements recorded at a constant ambient temperature of 24°C.
- The dataset represents a particular lithium-ion battery experiment, so predictions may not generalize to other batteries.
- Prediction accuracy depends on the quality and limitations of the dataset.

## Project Objective

To develop a machine learning system that analyses battery measurements and predicts the State of Health (SoH) of a lithium-ion battery.
