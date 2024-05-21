---
layout: page
title: The Chicago Food Deserts
description: Grocery stores in Chicago
img: assets/img/chicago_grocery_full.png
importance: 2
category: fun
---

<em> Skills: ArcGIS, Python: BeautifulSoup, Pandas </em> <br>
<em> Code available <a href="https://github.com/mayamkay/portfolio/tree/main">here</a>. </em>

I live within a 10-minute walk of 4 different grocery stores. But that's not the case for many Chicagoans. These regions are often referred to as food deserts, and the lack of access to grocery stores and healthy ingredients can have serious ramifications for the communities. 

To take a look at this a bit more closely I pulled data on the number of grocery stores in each area of the city and combined this with shape files to take a look at the density of grocery stores in Chicago. If you then compare this to a map of Chicago's median household income (map available through <a href="https://services3.arcgis.com/iuNbZYJOrAYBrPyC/arcgis/rest/services/Median_HH_Income_by_Census_Tract_Chicago_WFL1/FeatureServer">ArcGIS</a>) you can quite quickly see how less affluent neighborhoods in Chicago have far fewer grocery stores than those in wealthier areas.
<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/chicago_grocery_full.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            The density of grocery stores in Chicago by neighborhood.
        </div>
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/income.png" title="example image" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Chicago's median household income by neighborhood.
        </div>
    </div>
    <div class="caption">
        Darker blues represent higher densities of grocery stores as well as higher incomes. It's readily apparent that less affluent neighborhoods in Chicago also have far fewer grocery stores.
</div>


