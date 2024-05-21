---
layout: page
title: A Foodie's Map
description: Average restaurant reviews in cities around the world
img: assets/img/restaurants_full.png
importance: 2
category: fun
---

<em> Skills: ArcGIS, Python: BeautifulSoup, Pandas </em> <br>
<em> Code available <a href="https://github.com/mayamkay/portfolio/tree/main">here</a>. </em>

I am absolutely a foodie. I spent a semester in culinary school before starting my PhD, and I love trying new restaurants when I travel. Recently, my partner and I have been researching food spots to try for an upcoming trip, and it made me wonder what cities have the best-reviewed food. Also, are people in some parts of the world a little more circumspect with their reviews? Is it possible that reviewers in Chicago (Where I live) are more generous in their reviews than in New York? or London?

I decided to take a look at the average restaurant reviews on Yelp for different cities. To do this, I scraped data from Yelp, took the average review across the top 100 most reviewed restaurants in each city, and added them to a map using ArcGIS.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/restaurants_full.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Average restaurant reviews by city. The darker blue shade represents higher ratings, and the paler yellows are lower ratings. 
</div>

I started by looking at the US a little more closely, and you can pretty quickly notice that the East Coast definitely seems to be a little harsher in their reviews than elsewhere in the country. As a former New Yorker, I am absolutely obsessed with the food in NYC, and so this made me wonder if New Yorkers are just that much harsher in their reviews. My partner, who spent much of his childhood in Kansas City and swears that the BBQ in KC is hands down the best in the world, was pretty pleased to see the KC managed to inch out a win for the best-rated food in the US cities I looked at. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/restaurants_usa.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A closer look at restaurant reviews in the US. This map definitely suggests that I should finally make that trip to Kansas City to try some of their famous BBQ.
</div>

Zooming in a little on Europe, you might expect Paris, a city that is definitely known for its food, to have one of the highest average reviews in this region. Instead, I found that Barcelona is home to some of the most well-reviewed restaurants in Europe.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/restaurants_europe.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A closer look at Europe and the incredibly high-ranking restaurants in Barcelona. 
</div>

Maybe Parisians are just that much more reserved in their reviews? Or maybe we should all be booking a trip to Barcelona!


