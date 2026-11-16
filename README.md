# Statistical Analysis of GoFast Scooter Rental Service

## Project Description
Analysis of user and ride data for the GoFast scooter rental service. Goal — test hypotheses to help the business make decisions about developing the Ultra subscription.

## Data
- **Source:** GoFast (internal service data)
- **Coverage:** multiple cities in Russia, January — December 2021
- **Size:** 1,565 users, 18,068 rides
- **Data types:** user data + ride data + subscription plans

## Workflow
- Data preprocessing: duplicate removal, anomaly filtering, type conversion
- EDA: user age analysis, ride distance and duration
- Monthly revenue calculation by segment
- Statistical hypothesis testing (t-test):
  - subscribers spend more time per ride
  - average ride distance for subscribers does not exceed 3,130 m
  - revenue from subscribers is higher
- Binomial distribution and normal approximation

## Key Findings
- **Ride duration:** Ultra subscribers spend more time per ride
- **Distance:** average ride distance for subscribers does not exceed 3,130 m
- **Revenue:** monthly revenue from subscribers is higher than from non-subscribers
- **Recommendation:** incentivize users to switch to Ultra subscription as a more profitable segment

## Tech Stack
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-lightgrey)
![Matplotlib](https://img.shields.io/badge/Matplotlib-lightgrey)
![Scipy](https://img.shields.io/badge/Scipy-lightgrey)

## Repository Structure
```
├── gofast_statistical_analysis.ipynb  # main notebook
└── README.md
```
