---
layout: page
title: The Chicago Food Deserts
description: Grocery stores in Chicago
img: assets/img/chicago_grocery_full.png
importance: 2
category: fun
---

<em> Skills: ArcGIS, Python: BeautifulSoup, Pandas </em>

I live within a 10-minute walk of 4 different grocery stores. But that's not the case for many Chicagoans. These regions are often referred to as food deserts, and the lack of access to grocery stores and healthy ingredients can have serious ramifications for the communities. 

This map shows the number of grocery stores per area in different neighborhoods in Chicago. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chicago_grocery_full.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Darker colors represent neighborhoods with a higher density of grocery stores. Quite quickly, we see the difference between the north side and the south and west sides of Chicago.
</div>

If you compare this to a map of Chicago's median household income (map available through 
 <a href=https://services3.arcgis.com/iuNbZYJOrAYBrPyC/arcgis/rest/services/Median_HH_Income_by_Census_Tract_Chicago_WFL1/FeatureServer> ArcGIS </a>) you can quite quickly see how less affluent neighborhoods in Chicago have far fewer grocery stores than those in wealthier ares.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/chicago_income.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Chicago's median household income by neighborhood.
</div>


