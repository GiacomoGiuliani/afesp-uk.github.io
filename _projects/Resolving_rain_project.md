---
layout: page
title: "Resolving Rain"
description: 
img: assets/img/kscale_forecast_storm_alex.png
importance: 2
category: fellowships
---

**Fellow**: Julia Kukulies 

**Project Partners**: Alison Stirling, Richard Forbed, Tobias Becker, Andreas Prein

**Additional Collaborators**: Richard Keane, Benoît Vannière

Precipitation is one of the most societally impactful elements of the Earth system, yet it remains among the most challenging to simulate and predict across timescales. Recent advances in kilometer-scale (km-scale), convection-permitting models—combined with improved observations and the rise of data-driven approaches—offer new opportunities to improve precipitation forecasts from short-range weather to subseasonal-to-seasonal (S2S) timescales by better representing the physical processes governing the water cycle. However, key questions remain about the predictive value of these high-resolution models:

- What are the benefits of global km-scale models for forecasting impactful precipitation events?
- When and where does the better representation of convective precipitation potentially also deterioate forecasts?
- What are the emerging balances between forecast skill, spatial scales, and lead times in km-scale forecasts, more traditional global models and AI forecasts? 


In this project, we address these questions by systematically investigating the representation and sensitivity of precipitation processes in km-scale models. The focus is on developing frameworks to make better use of recent satellite missions such as [EarthCare](https://earth.esa.int/eogateway/missions/earthcare).

Through model intercomparisons, feature tracking, development of satellite-based diagnostics, and targeted perturbation experiments, the project will identify key sources of uncertainty in recipitation physics and evaluate their impact on forecast skill. A particular focus lies on **precipitation efficiency** as one potential factor that could make the simulated precipitation outcome more realistic in simulations with explicitly resolved convection. Ultimately, the project aims to determine when and why explicitly resolving convection leads to better forecasts—and whether km-scale simulations provide the physical realism needed to support next-generation AI forecasting systems.


**Recent experiments in global km-scale forecasting will be included:**

- ECMWF’s [Weather-Induced Extremes Digital Twin](https://destine.ecmwf.int/weather-induced-extremes-digital-twin/) with the [IFS model](https://www.ecmwf.int/en/forecasts/documentation-and-support/changes-ecmwf-model)
- Global 5km and 10km forecasts conducted by the UK Met Office
- Global MPAS forecasts at 3.75 km 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/kscale_forecast_storm_alex.png" title="Resolving Rain" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Global 5-km precipitation forecast conducted with the Unified Model. The forecast features Storm Alex (October 2-3, 2020) which brought a year's worth of rainfall over some parts in Europe. Extratropical cyclones are synoptically driven which make them easier to predict but would a traditional global forecast capture the mesoscale processes that drive the most intense precipitation inside the storm?**
    
</div>

