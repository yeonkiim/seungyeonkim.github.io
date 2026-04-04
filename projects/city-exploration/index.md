---
layout: default
title: City Exploration – Bike Safety & Infrastructure Risk Analysis
---
<div class="nav-links">
  <a href="../../">Home</a>
  <a href="../city-exploration/">City Exploration</a>
  <a href="../bikeshare-equity/">Bikeshare Equity</a>
  <a href="../homelessness/">Homelessness</a>
  <a href="../climate-gentrification/">Climate Gentrification</a>
</div>

# 🚲 City Exploration – Bike Safety & Infrastructure Risk Analysis (Boston)

<p align="center">
<img src="Picture2.png" width="100%"></p>

<p align="center">
  <em>
  Left: High-risk intersection with shared bike lanes and heavy vehicle interaction (Source: Google Maps)  
  <br>
  Right: Spatial distribution of bicycle crash hotspots and nearby infrastructure types (Author’s analysis)
  </em>
</p>

## Research Question
Why do certain Bluebikes stations in Boston consistently experience higher bicycle accident rates despite overall improvements in bike infrastructure?

## Data & Methods
- Vision Zero crash data (2015, 2024)
- Bluebikes station location data
- Distance-based spatial proximity analysis (`st_is_within_distance`)
- GIS mapping and infrastructure classification

## Key Findings
- Persistent high-risk stations across both years
- Strong association with shared or unprotected bike lanes
- High exposure along major vehicular corridors
- Improving bike safety requires qualitative upgrades to infrastructure,
particularly physical separation in high-risk areas.

## Files
- 📄 [Project Report (PDF)](city-exploration.pdf)
