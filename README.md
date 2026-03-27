# SPICE Solar Generation Dashboard

An interactive dashboard analyzing solar power generation at KKP1 kisikāw pīsim 
in Edmonton, Alberta — with a focus on the impact of wildfire smoke events.

## Pages

- **Map** — NASA GIBS satellite imagery of Edmonton during smoke events
- **Client Nulls** — Gap-fill analysis using KKP1 as a proxy for the client site (r=0.916)
- **Free Prediction** — Historical generation lookup using a Random Forest model (R²=0.86, blind tested on 2025)
- **The Paradox** — Wildfire smoke vs solar generation — the counterintuitive finding

## Data Sources

- AESO solar generation data (public)
- Edmonton Blatchford weather station (public)
- NASA POWER shortwave radiation (public)
- Edmonton PM2.5 monitoring stations (public)

## Model

Random Forest trained on 2022–2024, blind tested on 2025. R²=0.86.

## Live Dashboard

[View Dashboard](https://datasynergists-solargenproject-nx3thggv35tww9o9q9swfn.streamlit.app/)