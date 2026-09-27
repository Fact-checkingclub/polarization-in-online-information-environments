# Polarization Dynamics in Science and Conspiratorial Forums on Reddit

## About this project

This repository contains weekly aggregated data and analysis code accompanying the study **"Polarization Dynamics in Science and Conspiratorial Forums on Reddit: Cognitive, Emotional, and Identity Narratives."**

The study examines differences in narrative structures and the temporal dynamics of within-community polarization in r/Askscience and r/Conspiracy, using Reddit posts and comments from 2009 to 2022. It investigates how cognitive, identity, and emotional narrative features are associated with polarization over time.

## Data

The data include weekly values for both communities:

- **Polar:** the signed composite index combining evaluative dominance and interaction homogeneity.
- **Homo_dis:** the balance of positive and negative evaluations.
- **Homo_link:** the proportion of same-valence interactions.
- **Narrative features:** cognitive measures, social identity indicators, and emotional expression measures used in the time-series analyses.

## Code

The code implements ARIMA and ARIMAX analyses of Polar, Homo_dis, and Homo_link, including model estimation, diagnostics, and predictive performance evaluation. These analyses correspond to the main polarization results and the additional analyses of opinion dominance and interaction homogeneity reported in the manuscript.
