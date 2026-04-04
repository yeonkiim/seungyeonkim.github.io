---
layout: default
title: Bikeshare Equity Analysis – Boston
---
<div class="nav-links">
  <a href="../../">Home</a>
  <a href="../city-exploration/">City Exploration</a>
  <a href="../bikeshare-equity/">Bikeshare Equity</a>
  <a href="../homelessness/">Homelessness</a>
</div>

# 🚴 Bikeshare Equity Analysis – Boston

<p align="center">
  <img src="images/Picture3.png" width="100%">
</p>

<p align="center">
  <em>
  Comparison of median income, station count, and bike usage across Boston census tracts in 2015 and 2019 (Author’s analysis)
  </em>
</p>

## Research Question
Is bikeshare equally accessible and affordable across neighborhoods in Boston following the launch of the **SNAP Card to Ride** low-income membership program (2018)?

## Background
Boston’s Bluebikes introduced a discounted membership initiative (“SNAP Card to Ride”) to improve access for residents eligible for public benefit programs.  
This project explores demographic and socioeconomic patterns in Bluebikes usage **before and after** the program launch, focusing on **2015 (pre)** and **2019 (post)**.

## Data & Methods
- **Bluebikes trip / usage data:** 2015 and 2019  
- **Neighborhood socioeconomic data:** ACS (census tract level)  
- **Cost / accessibility context:** Housing + Transportation (H+T) Index  
- **Methods:** Regression analysis (R), GIS mapping, spatial comparison of station distribution and ridership patterns

<p align="center">
  <img src="images/Picture4.png" width="100%">
</p>

<p align="center">
  <em>
  Bike usage and station distribution by income quantile in 2019, showing increased access but persistent disparities in usage (Author’s analysis)
  </em>
</p>

## Key Findings
- Bikeshare usage increased in low-income census tracts between 2015 and 2019.
- Boston’s 2018 launch of discounted bikeshare memberships and the addition of 250+ new stations improved access, especially in underserved areas.
- Stronger effects were expected, but not fully observed, likely due to the short-term scope of the study.
- However, the lowest income quantile still had the lowest average usage.
- Regression results suggest that **income-based disparities persisted**, and relationships were not uniformly significant across all measures, reflecting the exploratory and short-term nature of the evaluation.

## Policy Implications
- Discounted memberships may support inclusion, but **affordability alone is not sufficient** to ensure equitable access.
- **Station density and proximity** appear to be as influential as pricing in shaping usage patterns.

## Files & Links
- 📄 [Data Analysis Document (PDF)](bikeshare-equity.pdf)
