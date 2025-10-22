---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 6
---

My ongoing research focuses on **advancing the representation of groundwater processes in land surface models (LSMs)** through the development of novel numerical frameworks that balance physical realism with computational efficiency. Traditional fully distributed models provide a detailed spatial representation of subsurface hydrology, but their computational demands limit their applicability at regional to global scales, especially when coupled with high-resolution atmospheric and land datasets. To address this challenge, my work explores the feasibility of **implementing multiscale processes** within novel **tiling schemes** as an alternative modeling paradigm.

In this framework, the land surface is partitioned into representative tiles that capture heterogeneity in soil, vegetation, and topography without requiring the full computational burden of a distributed grid. By embedding groundwater dynamics within these tiles, I aim to improve the simulation of critical processes such as water table fluctuations, lateral subsurface flow, and groundwater–surface water interactions. **This approach leverages high-resolution data products** (e.g., remote sensing of soil moisture, evapotranspiration, and groundwater storage anomalies) while maintaining scalability for Earth system modeling applications.

A central component of this research is the design of numerical coupling strategies that allow groundwater processes to interact dynamically with surface energy and water fluxes. I am investigating how tile-based parameterizations can reproduce emergent hydrological behavior observed in distributed models, while also testing the sensitivity of model outputs to tile resolution and aggregation strategies. Early results suggest that tiling schemes can capture key groundwater–land surface feedbacks, such as the modulation of evapotranspiration by shallow water tables, at a fraction of the computational cost.

The broader goal of this research is to **enable next-generation land surface models** that are both physically robust and computationally tractable, thereby improving predictions of water availability, drought persistence, and land–atmosphere coupling under climate variability and change. By bridging the gap between high-resolution data availability and model scalability, this work contributes to the development of modeling tools that can inform water resource management and climate adaptation strategies at regional to global scales.
