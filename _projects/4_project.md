---
layout: page
title: A foodie's map
description: Average restaurant reviews of cities around the world
img: assets/img/restaurants.png
importance: 3
category: fun
---

I am absolutely a foodie. I spent a semester in culinary school before starting my PhD and I love trying new restaurants when I travel. Recently, my partner and I have been researching food spots to try for an upcoming trip, and it made me wonder what cities have the best-reviewed food, but also, are people in some parts of the world a little more circumspect with their reviews? Is it posisble reviewers in Chicago (Where I live) are just more generous in their reviews than in New York? or London?

I decided to take a look at the average restaurant reviews on Yelp for different cities. To do this, I scraped data from Yelp and then took the average review across the top 100 most reviewed restaurants in each city and added them to a map using ArcGIS.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/restaurants.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Average restaurant reviews by city. Darker blues represent higher ratings and the paler yellows are lower ratings. 
</div>

Zooming in a little on Europe you might expect Paris, a city that is definitely known for its food, to have one of the highest average reviews in this region. Instead, I found that Barcelona actually seems to be home to some of the most well-reviewed restaurants in Europe.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/europe.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A closer look at Europe and the incredibly high-ranking restaurants in Barcelona. 
</div>

Maybe Parisians are just that much more reserved in their reviews? Or maybe we should all be booking a trip to Barcelona!

<em> Skills: ArcGIS, BeautifulSoup </em>
