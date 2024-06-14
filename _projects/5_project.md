---
layout: page
title: Ancona Air Pollution
description: Air pollution analysis
img: assets/img/ancona.png
importance: 2
category: fun
---

<em> Skills: Python: matplotlib, numpy, Pandas </em> <br>
<em> Jupyter notebooks available <a href="https://github.com/mayamkay/portfolio/tree/main/ancona_pollution">here</a>. </em>

I recently took a look at the Air Quality Monitoring in European Cities data set ([available here](https://www.kaggle.com/datasets/yekenot/air-quality-monitoring-in-european-cities/data)) from Kaggle. The data set presents time domain measurements of various properties related to air quality in three different European cities. I decided to take a look at the air quality over time in Ancona Italy. In particular, I'm interested in the parameter that describes the atmospheric aerosols concentration with a maximum particle diameter of 10 micrometers as these small particles can cause health risks when inhaled. Measuring the concentration of the particles is often used as a proxy to talk about how safe the air is.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/ancona.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            The region of Italy that this data is sourced from. The different points give you an idea of the different locations where the air quality was measured.
        </div>
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/pm10_zscore.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            The 7-day moving average of the PM10 data compared to the average. This comparison allows us to compute the z-score, which is the ratio of the difference between the moving average and the average divided by the standard deviation of the data. High z-scores suggest that the PM10 values are abnormally high. 
        </div>
</div>
</div>

The full EDA and analysis notebooks are available <a href="https://github.com/mayamkay/portfolio/tree/main/ancona_pollution">here</a>.


