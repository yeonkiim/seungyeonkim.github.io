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

<p class="project-subtitle">🚲 City Exploration – Bike Safety & Infrastructure</p>

<h1 class="project-main-title">
Why Is Bike Riding Still Dangerous? An Analysis of Infrastructure and Risk Areas</h1>

---

## Problem / Research Question

Road safety is particularly important for cyclists, much like it is for pedestrians, as they lack the protection afforded by a vehicle. Moreover, many bicycle-related accidents involve motorcycles, highlighting the need for safer infrastructure.

Building on these observations, I aim to examine the characteristics of Bluebike stations with the highest and lowest accident rates and explore the surrounding infrastructure and environmental factors that may contribute to variations in cyclist safety.

---

## Data & Methods

The analysis integrates traffic safety data with bikeshare station locations to examine spatial patterns of cyclist risk.

- **Data sources:**  
  Vision Zero Boston crash data (2015, 2024), Bluebike station data, and Boston bike network data  

- **Approach:**  
  Spatial linkage of crash incidents to nearby Bluebike stations and comparison of high-risk vs. low-risk locations  

- **Methods:**  
  GIS spatial analysis in R (including `st_is_within_distance`), mapping with `tmap`, and qualitative site review using Google Maps  

---

## Key Findings

<div class="figure-card">
  <img src="Picture2.png" alt="High-risk intersection near Bluebike station with shared lane and heavy vehicle interaction">
  <p class="figure-caption">
    Example of a high-risk Bluebike station location, showing shared bike lanes and proximity to major vehicle traffic (Author’s observation via Google Maps)
  </p>
</div>

Bicycle-related injuries declined from 502 in 2015 to 366 in 2024, indicating overall improvements in cyclist safety.

High-risk bikeshare stations are consistently located near major traffic corridors where protective infrastructure is limited.

In addition, the bike networks in both years primarily consisted of conventional or shared lanes, indicating limited improvement in physical protection for cyclists.

---

## Policy Implications

By examining the infrastructure, it became clear that the absence of separated or protected bike lanes, and the need for cyclists to share roads with vehicles, was a critical and common contributor to the high number of traffic accidents in these areas.

Additionally, I found that the City of Boston is actively gathering public feedback on transportation infrastructure through the Vision Zero Safety Concerns platform.

From this map, it was evident that I am not the only one who noticed these issues. Boston residents have already submitted concerns regarding the identified roads, often marking them with comments such as:

- "It needs physical separation, including hard vertical elements, to prevent cars from parking in the bike lane."
- "Cars are in the bike lane every time."

From this city exploration, it is evident that improving the bike network requires not only expansion in terms of distance and coverage, but also significant enhancements in quality to better protect cyclists.

Urban planners should carefully consider both public feedback and data on high-risk areas to more effectively improve the city's bike infrastructure.

---

## Files & Links

- [Project Report (PDF)](city-exploration.pdf)
